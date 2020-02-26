---
title: Einbetten einer Umfrage in eine Webseite | MicrosoftDocs
description: Anleitung zum Einbetten einer Umfrage in eine Webseite
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/06/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 649b3390-c3a5-4166-a014-ae3cfd14cc71
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 17b2988a617338a14da4ff21c0825d2ea98a2145
ms.sourcegitcommit: f99b529d74a96beb8121df5344f40479619875ea
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/16/2020
ms.locfileid: "2966354"
---
# <a name="embed-a-survey-in-a-webpage"></a>Eine Umfrage in einer Webseite einbetten

Sie können Ihre Umfrage in eine Webseite einbetten, indem Sie den Einbettungscode der Umfrage in den Quellcode Ihrer Webseite einfügen. Sie können eine der folgenden Optionen eingebetteten Stile für die Umfrage auswählen:

- **Inline**: Zeigt die Umfrage statisch auf der Webseite an.

- **Popup**: Zeigt die Umfrage in einem Popupfenster an, das auf der Aktion der antwortenden Seite basiert.

- **Schaltfläche**: Zeigt die Umfrage an, wenn eine Schaltfläche ausgewählt ist. Standardmäßig lautet der Schaltflächenname **Feedback**.

Sie können auch eine Anzeigendichte für die Umfrage auswählen. Die Anzeigedichte steuert die Größe des Leerraums und die Größe der Elemente auf dem Bildschirm. Die folgenden Optionen stehen für die Anzeigedichte zur Verfügung:

- **Standard**: Zeigt die Umfrage mit dem Standardumfang an Leerraum und Elementen in Standardgröße auf dem Bildschirm an.

- **Kompakt**: Zeigt die Umfrage mit einem reduzierten Umfang an Leerraum und kleineren Elementen auf dem Bildschirm an. Standardmäßig ist **Kompakt** ausgewählt. Diese Anzeigedichte ist nützlich, um die Umfrage auf kleineren Bildschirmen wie Mobilgeräten oder Tablets anzuzeigen.

Wenn Sie Umfragevariablen erstellt haben, werden sie verwendet, um die Informationen Ihrer antwortenden Seite und den Kontext, in dem die Antwort gegeben wurde, zu erfassen und diese Daten in der Umfrageantwort zu speichern. Sie können bei Bedarf auch neue Umfragevariablen erstellen. Wenn die entsprechenden Werte nicht an die Umfragevariablen im Einbettungscode übergeben werden, werden die Standardwerte verwendet.

Die Werte von Umfragevariablen in einer Antwort werden auf der Registerkarte **Personalisierte Daten** angezeigt.

> [!div class=mx-imgBorder]
> ![Umfragevariablen in einer Umfrageantwort](media/survey-response-context-param.png "Umfragevariablen in einer Umfrageantwort")

Um Ihre Umfrage einzubetten:

1.  Öffnen Sie die Umfrage, die Sie einbetten möchten, und wählen Sie dann **Senden** aus der Symbolleiste oben auf der Seite aus.

2.  Wählen Sie **Einbetten** aus.

3. Wählen Sie unter **Anzeigendichte auswählen** eine der folgenden Optionen aus:

    - Standard

    - Kompakt

4.  Wählen Sie unter **Eingebetteten Stil auswählen** eine der folgenden Optionen aus:

    -   Inline

    -   Pop-up

    -   Schaltfläche

5.  Wählen Sie optional unter **Umfragevariablen** die Option **Neue Variablen** aus, um eine Variable zu erstellen.

6.  Wählen Sie **Code generieren**. Der Einbettungscode wird gemäß den von Ihnen ausgewählten Optionen generiert.

7.  Wählen Sie **Kopieren**, und fügen Sie dann den Einbettungscode in eine Webseite ein, um Ihre Umfrage einzubetten. Sie müssen dann den Quellcode der Webseite aktualisieren, um die Umfrage auf der Webseite anzuzeigen. Informationen darüber, wie der Quellcodes aktualisiert wird, finden Sie unter [Update des Quellcodes einer Webseite](#update-a-webpages-source-code).  

    > [!div class=mx-imgBorder]
    > ![Eine Umfrage in einer Webseite einbetten](media/survey-embed.png "Eine Umfrage in einer Webseite einbetten")  

## <a name="update-a-webpages-source-code"></a>Aktualisieren des Quellcodes einer Webseite

Nachdem Sie den Einbettungscode generiert haben, müssen Sie ihn dem Quellcode Ihrer Webseite hinzufügen. Dann erstellen Sie eine Methode, die die Funktion **renderSurvey** aufruft, um die Umfrage auf der Webseite anzuzeigen. Sie müssen sicherstellen, dass die Werte in der Funktion **renderSurvey** in der gleichen Reihenfolge übergeben werden wie die Umfragevariablen, die in der Funktion **renderSurvey** im Embed-Code definiert sind.

Für eine Inline-Umfrage muss ein übergeordneter **div** Container definiert werden, damit die Umfrage angezeigt wird.

### <a name="scenario-to-embed-an-inline-survey"></a>Szenario zur Einbindung einer Inline-Umfrage

Wir nehmen einmal an, Sie möchten eine Inline-Umfrage in Ihre Webseite einbetten und haben zwei Umfragevariablen erstellt (**E-Mail** und **PageTitle**). Der Embed-Code wird wie folgt generiert:

```JavaScript
<script src="https://www.contoso.com/Embed.js" type="text/javascript"></script><link rel="stylesheet" type="text/css" href="https://www.contoso.com/Embed.css" /><script type = "text/javascript" >function renderSurvey(parentElementId, FirstName, LastName, Email, PageTitle){var se = new SurveyEmbed("JtSG9ha000000000020pTSB1AovM_5u8bQH1UQjlNQjZRWV0000000000","https://www.contoso.com/");var context = {"FirstName": FirstName,"LastName": LastName,"Email": Email,"PageTitle": PageTitle,};se.renderInline(parentElementId, context);}</script>
```

Im vorhergehenden Einbettungscode enthält die Funktion `renderSurvey` neben dem ausgewählten `parentElementId`-Parameter auch die Umfragevariablen. Der Parameter `parentElementId` erhält beim Aufruf die Container-ID `div`.

Sie haben auf der Webseite, auf der Sie die Umfrage anzeigen möchten, einen `div`-Container mit der ID `surveyDiv` erstellt. Dieser `div`-Container zeigt die Umfrage statisch in einem bestimmten Bereich auf der Webseite an. Da Sie die Umfrage beim Laden der Seite laden möchten, erstellen Sie eine Methode wie folgt:

```JavaScript
<script>
     window.addEventListener('load', function () {
            renderSurvey("surveyDiv", "Bert", "Hair", "bert.hair@contoso.com", "Product Overview");
        }, false);
</script>

```

Die vorhergehende Methode ruft die Funktion `renderSurvey` auf und übergibt die erforderlichen Werte entsprechend. In dieser Methode werden statische Benutzerdetails übergeben, aber Sie können eine Funktion bereitstellen, die die angemeldeten Benutzerdetails abruft.

### <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage per E-Mail](send-survey-email.md)<br>
[Senden Sie eine Umfrage mit Power Automate](send-survey-flow.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in Power Apps](embed-survey-powerapps.md)
