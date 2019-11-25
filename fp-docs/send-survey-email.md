---
title: Senden einer Umfrage per E-Mail | MicrosoftDocs
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/04/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: d48c4d15cdf98ba0ced17a6c497a2800ebecb066
ms.sourcegitcommit: 3225337823216f21b569779b829f069f53aa3742
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/04/2019
ms.locfileid: "2750442"
---
# <a name="send-a-survey-by-using-email"></a>Senden Sie eine Umfrage per E-Mail.

Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden: 

1.  Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie **Senden** aus der Symbolleiste oben auf der Seite. 

2. Wählen Sie **E-Mail**. Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext. Sie können den Text an Ihre Anforderungen anpassen und formatieren.

3.  Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein. Sie können das Feld **Bis** auf eine der folgenden Arten füllen:
    - Manuelle Eingabe einer E-Mail-Adresse.
    - Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.
    - Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Services für Apps. Die Kontakte werden aus der ausgewählten Umgebung gefüllt. Weitere Informationen zum Arbeiten mit Umgebungen finden Sie unter [Arbeiten mit Umgebungen](choose-environment.md).
    - Hochladen einer csv-Datei durch Auswahl von **Empfänger importieren**. Die CSV-Datei unterstützt den Import von maximal 10000 Empfängern.

4.  Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [Umfrage-Link einfügen](#insert-survey-link).  

5.  Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einer Umfrage](#unsubscribe-from-a-survey).  

6.  Informationen zur Personalisierung der E-Mail mithilfe von Umfragevariablen finden Sie unter [Personalisierung einer E-Mail](#personalize-an-email).

7. Um die erste Frage der Umfrage in Ihre E-Mail-Nachricht einzubetten, siehe [Umfrage einbetten in eine E-Mail](#embed-survey-in-an-email).

8.  Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**. Standardmäßig ist **Standardvorlage** ausgewählt. Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)  

9.  Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.

> [!NOTE]
> Sie können eine Umfrageeinladung an maximal 10000 Empfänger senden.

## <a name="insert-survey-link"></a>Umfrage-Link einfügen

Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt. Um den Umfrage-Link an einer anderen Stelle in Ihrer E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie **Einfügen** > **Umfrage-Link**. Sie können auch Text auswählen und dann **Einfügen** > **Umfrage-Link** wählen, um diesen Text als Umfrage-Link anzuzeigen.

## <a name="unsubscribe-from-a-survey"></a>Abmeldung von einer Umfrage

Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden. Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Link**Abmelden. Sie können auch Text auswählen und dann **Einfügen** > **Link**Abmelden wählen, um diesen Text als Abmeldelink anzuzeigen. Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.

## <a name="personalize-an-email"></a>Eine E-Mail personalisieren

Personalisieren Sie Ihre Umfrage-E-Mail, indem Sie Umfrage-Variablen verwenden. Positionieren Sie den Cursor beispielsweise an der Stelle, an der ein Vorname erscheinen soll. Wählen Sie **Variablen**, und wählen Sie dann **Vorname** aus der Auswahlliste. Der Vorname des Befragten wird automatisch eingefügt. Alle in einer Umfrage erstellten Umfragevariablen werden in der Liste **Variablen** angezeigt.

Um eine neue Variable zu erstellen, wählen Sie **Neue Variable** aus der Liste **Variablen**. Informationen zum Erstellen und Bereitstellen von Werten für die Variablen finden Sie unter [Personalisieren einer Umfrage](personalize-survey.md)

Wenn die Standardwerte für Umfragevariablen nicht definiert sind, wird oben auf der Seite eine Warnmeldung angezeigt.

## <a name="embed-survey-in-an-email"></a>Einbetten der Umfrage in eine E-Mail

Wenn Sie eine Frage zur Bewertung oder zum Netto-Promoter-Score als erste Frage in Ihrer Umfrage hinzugefügt haben, können Sie sie in Ihre E-Mail-Nachricht einbetten. Um die Frage einzubetten, wählen Sie **Einbetten erste Frage**. Wenn Sie eine Frage einbetten, wird der Text in der E-Mail-Nachricht durch die Frage ersetzt. Wenn ein Befragter eine Option in der E-Mail auswählt, wird die gesamte Umfrage im Webbrowser geöffnet und der Befragte kann die Umfrage fortsetzen.

> [!div class=mx-imgBorder]
> ![Eingebettete Umfrage in eine E-Mail ](media/embed-ques-email.png "Einbetten der Umfrage in eine E-Mail")

> [!NOTE]
> Sie können die Frage nicht in eine E-Mail einbetten, wenn Sie Verzweigungsregeln hinzugefügt oder die Fragen in einer Umfrage neu gemischt haben.

## <a name="use-email-templates"></a>E-Mail-Vorlagen verwenden

Eine E-Mail-Vorlage ist eine vorformatierte E-Mail-Nachricht, mit der Sie schnell E-Mail-Nachrichten erstellen und senden können. Sie können den Text ändern und Ihre Änderungen dann in der aktuellen E-Mail-Vorlage speichern oder die Änderungen in einer neuen E-Mail-Vorlage speichern. Wenn Sie keine andere Auswahl treffen, wird **Standardvorlage** für die Verwendung in einer E-Mail-Nachricht ausgewählt. 

Sie können diese Aktionen auf einer E-Mail-Vorlage durchführen:

- **Speichern**: Speichern Sie Ihre Änderungen an der aktuellen E-Mail-Vorlage.

- **Speichern unter**: Speichern Sie Ihre Änderungen in einer neuen E-Mail-Vorlage.

- **Löschen**: Löschen Sie die aktuelle E-Mail-Vorlage.

- **Umbenennen**: Benennen Sie die aktuelle E-Mail-Vorlage um.

> [!NOTE]
> - Sie können maximal 10 E-Mail-Vorlagen speichern.
> - Wenn Sie Umfragevariablen in einer E-Mail-Vorlage verwendet haben, die nicht Teil der Umfrage sind, wird oben auf der Seite eine Fehlermeldung angezeigt und es ist Ihnen nicht gestattet, die Umfrage per E-Mail oder Flow zu senden. Die Variablen der Umfrage sind rot markiert. Sie müssen die hervorgehobenen Umfragevariablen aus der E-Mail-Nachricht entfernen, um die Umfrage zu senden.

## <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage mit Microsoft Flow](send-survey-microsoft-flow.md)<br>
[Eingebettete Umfrage in eine Webseite](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in PowerApps](embed-survey-powerapps.md)
