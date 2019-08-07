---
title: Einbetten einer Umfrage in eine Webseite | MicrosoftDocs
description: Anleitung zum Einbetten einer Umfrage in eine Webseite
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 06/14/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 649b3390-c3a5-4166-a014-ae3cfd14cc71
ms.custom: ''
ms.openlocfilehash: f0a0691d88d0eb10821940d973bd731e3c4da838
ms.sourcegitcommit: 4f20bfe750e8d4eb2db4dca0479699eb365c8c9e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2019
ms.locfileid: "1724519"
---
# <a name="embed-survey-in-a-webpage"></a>Einbetten der Umfrage in eine Webseite



Sie können Ihre Umfrage in eine Webseite einbetten, indem Sie den Einbettungscode der Umfrage in den Quellcode Ihrer Webseite einfügen. Sie können wählen, wie die Umfrage angezeigt werden soll:

- **Inline**: Zeigt die Umfrage statisch auf der Webseite an.

- **Pop-up**: Zeigt die Umfrage in einem Popup-Fenster an, das auf der Aktion des Befragten basiert.

- **Schaltfläche**: Zeigt die Umfrage an, wenn eine Schaltfläche ausgewählt ist. Standardmäßig lautet der Schaltflächenname **Feedback**.

Sie können auch eigene Kontextparameter auswählen oder definieren. Kontextparameter ermöglichen es Ihnen, die Informationen Ihrer Befragten und den Kontext, in dem die Antwort gegeben wurde, zu erfassen und diese Daten in der Umfrageantwort zu speichern. Standardmäßig sind **Vorname**, **Nachname**, **E-Mail** und **URL** als Kontextparameter verfügbar. Zusätzlich können Sie 10 benutzerdefinierte Kontextparameter definieren.

Wenn eine Antwort Einbettungsparameter enthält, werden diese auf der Registerkarte **Personalisierte Daten** angezeigt.

> [!div class=mx-imgBorder]
> ![Kontextparameter in einer Umfrageantwort](media/survey-response-context-param.png "Kontextparameter in einer Umfrageantwort")

Um Ihre Umfrage einzubetten:

1.  Öffnen Sie die Umfrage, die Sie einbetten möchten, und gehen Sie zu **Umfrage senden** &gt;**Einbetten**.

2.  Wählen Sie unter **Auswählen des Einbettungstyps für Ihre Umfrage** eine der folgenden Optionen aus:

    -   Inline

    -   Pop-up

    -   Schaltfläche

3.  Optional können Sie unter **Auswählen von Parametern zum Hinzufügen von Einbettungscode** einen oder alle Out-of-the-box-Parameter auswählen oder **Benutzerdefinierten Parameter hinzufügen** wählen, um einen neuen Parameter zu erstellen.

4.  Wählen Sie **Code generieren**. Der Einbettungscode wird gemäß den ausgewählten Optionen generiert.

5.  Wählen Sie **Kopieren**, und fügen Sie dann den Einbettungscode in eine Webseite ein, um Ihre Umfrage einzubetten. Sie müssen dann den Quellcode der Webseite aktualisieren, um die Umfrage auf der Webseite anzuzeigen. Informationen zum Aktualisieren des Quellcodes finden Sie unter [Update des Quellcodes einer Webseite](#update-a-webpages-source-code).  

    > [!div class=mx-imgBorder]
    > ![Einbetten einer Umfrage in eine Webseite](media/survey-embed.png "Einbetten einer Umfrage in eine Webseite")  

## <a name="update-a-webpages-source-code"></a>Aktualisieren des Quellcodes einer Webseite

Nachdem Sie den Einbettungscode generiert haben, müssen Sie ihn in den Quellcode Ihrer Webseite einfügen. Erstellen Sie dann eine Methode, die die Funktion **renderSurvey** aufruft, um die Umfrage auf der Webseite anzuzeigen. Sie müssen sicherstellen, dass die Werte in der Funktion **renderSurvey** in der gleichen Reihenfolge übergeben werden wie die Parameter, die in der Funktion **renderSurvey** im Embed-Code definiert sind.

Für eine Inline-Umfrage muss ein übergeordneter **div** Container definiert werden, damit die Umfrage angezeigt wird.

### <a name="scenario-to-embed-an-inline-survey"></a>Szenario zur Einbindung einer Inline-Umfrage

Angenommen, Sie möchten eine Inline-Umfrage in Ihre Webseite einbetten und drei Kontextparameter auswählen (**Vorname**, **Nachname** und **E-Mail**) und einen benutzerdefinierten Kontextparameter erstellen (**PageTitle**). Der Embed-Code wird wie folgt generiert:

```JavaScript
<script src="https://www.contoso.com/Embed.js" type="text/javascript"></script><link rel="stylesheet" type="text/css" href="https://www.contoso.com/Embed.css" /><script type = "text/javascript" >function renderSurvey(parentElementId, Firstname, Lastname, Email, PageTitle){var se = new SurveyEmbed("JtSG9ha000000000020pTSB1AovM_5u8bQH1UQjlNQjZRWV0000000000","https://www.contoso.com/");var context = {"Firstname": Firstname,"Lastname": Lastname,"Email": Email,"PageTitle": PageTitle,};se.renderInline(parentElementId, context);}</script>
```

Im vorhergehenden Einbettungscode enthält die Funktion `renderSurvey` neben den ausgewählten Parametern auch den Parameter `parentElementId`. Der Parameter `parentElementId` erhält beim Aufruf die Container-ID `div`.

Sie haben auf der Webseite, auf der Sie die Umfrage anzeigen möchten, einen `div`-Container mit der ID `surveyDiv` erstellt. Dieser `div`-Container zeigt die Umfrage statisch in einem bestimmten Bereich auf der Webseite an. Da Sie die Umfrage beim Laden der Seite laden möchten, erstellen Sie eine Methode wie folgt:

```JavaScript
<script>
     window.addEventListener('load', function () {
            renderSurvey("surveyDiv", "Bert", "Hair", "bert.hair@contoso.com", "Product Overview");
        }, false);
</script>

```

Die vorhergehende Methode ruft die Funktion `renderSurvey` auf und übergibt die erforderlichen Werte entsprechend. In dieser Methode werden statische Benutzerdetails übergeben, aber Sie können eine Funktion bereitstellen, die die angemeldeten Benutzerdetails abruft.

## <a name="see-also"></a>Siehe auch

[Definieren Sie, wer an einer Umfrage teilnehmen darf](invite-settings.md)<br>
[Senden Sie eine Umfrage per E-Mail](send-survey-email.md)<br>
[Senden Sie eine Umfrage mit Microsoft Flow](send-survey-microsoft-flow.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)