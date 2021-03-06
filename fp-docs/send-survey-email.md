---
title: Senden Sie eine Umfrage per E-Mail.
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 02/24/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 7bf609261c6808328031ef8afd35f3a91fa6ac68
ms.sourcegitcommit: b67bc5a218afc5d99d49aad2ea10dfd68c8dc338
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/02/2020
ms.locfileid: "3094354"
---
# <a name="send-a-survey-by-using-email"></a>Senden Sie eine Umfrage per E-Mail.

Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden mit den folgenden Schritten:

1.  Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie **Senden** aus der Symbolleiste oben auf der Seite. 

2. Wählen Sie **E-Mail**. Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext. Sie können den Text an Ihre Anforderungen anpassen und formatieren.

3.  Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein. Sie können das Feld **An** auf eine der folgenden Methoden ausfüllen:

    - Manuelle Eingabe einer E-Mail-Adresse.
    - Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.
    - Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Service für Apps. Die Kontakte werden aus der ausgewählten Umgebung gefüllt. Weitere Informationen: [Arbeiten mit Umgebungen](choose-environment.md)
    - Hochladen einer CSV-Datei durch Auswahl von **Empfänger importieren**. Die CSV-Datei unterstützt den Import von maximal 10000 Empfängern.

4.  Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [eiUmfrage-Link einfügen](#insert-survey-link).  

5.  Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einem Link](#unsubscribe-from-a-survey).  

6.  Informationen zum Personalisieren der E-Mail mithilfe von Umfragevariablen finden Sie unter [Personalisieren Sie die Umfrage-E-Mail](#personalize-an-email).

7. Informationen zum Einbetten der ersten Frage der Umfrage in Ihre E-Mail-Nachricht finden Sie unter [Betten Sie eine Umfrage in eine E-Mail ein](#embed-survey-in-an-email).

8.  Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**. Standardmäßig ist **Standardvorlage** ausgewählt. Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)

9.  Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.

> [!NOTE]
> Sie können eine Umfrageeinladung an maximal 10000 Empfänger senden.

<a name="insert-survey-link"></a>

## <a name="insert-a-survey-link"></a>Einen Befragungslink einfügen

Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt. Um den Umfragelink an einer anderen Stelle in Ihre E-Mail-Nachricht einzufügen, platzieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Umfragelink**. Sie können auch Text auswählen und dann **Einfügen** > **Umfrage-Link** wählen, um diesen Text als Umfrage-Link anzuzeigen.

<a name="unsubscribe-from-a-survey"></a>

## <a name="insert-an-unsubscribe-link"></a>Link für eine Abonnementkündigung einfügen

Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden. Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Link**Abmelden. Sie können auch Text auswählen und dann **Einfügen** > **Abmelde-Link** wählen, um diesen Text als Abmeldelink anzuzeigen. Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.

<a name="personalize-an-email"></a>

## <a name="personalize-the-survey-email"></a>Personalisieren der Umfrage-E-Mail

Verwenden Sie Umfragevariablen, um Ihre Umfrage-E-Mail zu personalisieren&mdash;Sie können beispielsweise den Vornamen des Befragten hinzufügen. Platzieren Sie den Cursor an der Stelle, an der der Name angezeigt werden soll, und wählen Sie **Variablen** und dann **Vorname** von der Liste. Der Vorname des Befragten wird automatisch eingefügt. Alle in einer Umfrage erstellten Umfragevariablen werden in der Liste **Variablen** angezeigt.

Um eine neue Variable zu erstellen, wählen Sie **Neue Variable** aus der Liste **Variablen**. Wenn für Umfragevariablen keine Standardwerte definiert wurden, wird oben auf der Seite eine Warnmeldung angezeigt. Weitere Informationen zum Erstellen von Variablen und zum Bereitstellen von Werten finden Sie unter [Personalisieren Sie eine Umfrage](personalize-survey.md).

<a name="embed-survey-in-an-email"></a>

## <a name="embed-a-survey-in-an-email"></a>Betten Sie eine Umfrage in eine E-Mail ein

Wenn Sie als erste Frage in Ihrer Umfrage eine Frage zur Auswahl (Einzelantwort), Bewertung (Stern- oder Smileysymbol) oder Net Promoter Score hinzugefügt haben, können Sie diese in Ihre E-Mail-Nachricht einbetten. Um die Frage einzubetten, wählen Sie **Einbetten erste Frage**. Wenn Sie eine Frage einbetten, wird der Text in der E-Mail-Nachricht durch die Frage ersetzt. Wenn ein Beantworter eine Option zur Beantwortung der Frage auswählt, wird die gesamte Umfrage in einem Webbrowser geöffnet und der Beantworter kann mit dem Ausfüllen der Umfrage fortfahren.

> [!div class=mx-imgBorder]
> ![Betten Sie eine Umfrage in eine E-Mail ein](media/embed-ques-email.png "Betten Sie eine Umfrage in eine E-Mail ein")

> [!NOTE]
> - Sie können eine Frage nicht in eine E-Mail einbetten, wenn Sie das Mischen von Fragen in der Umfrage aktiviert haben.
> - Wenn Sie eine eingebettete Umfrage in einer E-Mail über Power Automate senden möchten, müssen Sie die Frage in eine E-Mail einbetten und als neue E-Mail-Vorlage speichern. Während Sie einen Flow konfigurieren, müssen Sie die neue E-Mail-Vorlage auswählen. Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)

Wenn Sie eine mehrsprachige Umfrage erstellt haben, können Sie Umfragevariablen verwenden, um das Standardgebietsschema für die Anzeige der Umfrage festzulegen. Um das Standardgebietsschema festzulegen, öffnen Sie den Bereich **Umfragevariablen** und geben Sie dann einen Wert für die Variable **Lokalisierung** an. Der Wert muss ein Sprachcode sein, z. B. **en** oder **fr**.

<a name="use-email-templates"></a>

## <a name="use-email-templates"></a>E-Mail-Vorlagen verwenden

Sie können eine E-Mail-Vorlage,&mdash;eine vorformatierte E-Mail-Nachricht&mdash;nutzen, mit der Sie schnell E-Mail-Nachrichten erstellen und senden können. Sie können den Text ändern und Ihre Änderungen dann in der aktuellen E-Mail-Vorlage speichern oder die Änderungen in einer neuen E-Mail-Vorlage speichern. Wenn Sie keine andere Auswahl treffen, wird **Standardvorlage** für die Verwendung in einer E-Mail-Nachricht ausgewählt.

Sie können diese Aktionen auf einer E-Mail-Vorlage durchführen:

- **Speichern**: Speichern Sie Ihre Änderungen an der aktuellen E-Mail-Vorlage.

- **Speichern unter**: Speichern Sie Ihre Änderungen in einer neuen E-Mail-Vorlage.

- **Löschen**: Löschen Sie die aktuelle E-Mail-Vorlage.

- **Umbenennen**: Benennen Sie die aktuelle E-Mail-Vorlage um.


> [!NOTE]
> - Sie können maximal 10 E-Mail-Vorlagen speichern.
> - Wenn eine E-Mail-Vorlage Umfragevariablen enthält, die nicht Teil der Umfrage sind, wird oben auf der Seite eine Fehlermeldung angezeigt, und Sie können die Umfrage nicht per E-Mail oder Microsoft senden Power Automate. Die Umfragevariablen werden rot hervorgehoben. Sie müssen diese hervorgehobenen Variablen aus der E-Mail-Nachricht entfernen, bevor Sie die Umfrage senden können.

### <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage mit Power Automate](send-survey-flow.md)<br>
[Eine Umfrage in einer Webseite einbetten](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in Power Apps](embed-survey-powerapps.md)
