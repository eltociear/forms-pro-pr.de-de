---
title: Senden einer Umfrage per E-Mail | MicrosoftDocs
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 07/01/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: c6f2c80afd0390c6398ffe7811a3b509732cbd3f
ms.sourcegitcommit: 5661ec673caaeeba4c63158a98a0f6e083cb73cd
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2019
ms.locfileid: "1778311"
---
# <a name="send-a-survey-by-using-email"></a>Senden Sie eine Umfrage per E-Mail.



Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden: 

1.  Öffnen Sie die Umfrage, die Sie senden möchten, und gehen Sie zu **Umfrage senden** &gt; **E-Mail**. Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext. Sie können den Text an Ihre Anforderungen anpassen und formatieren.

2.  Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein. Sie können das Feld **An** auf eine der folgenden Arten füllen:
    - Manuelle Eingabe einer E-Mail-Adresse.
    - Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.
    - Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Services für Apps. Die Kontakte werden aus der ausgewählten Umgebung gefüllt. Weitere Informationen zum Arbeiten mit Umgebungen finden Sie unter [Arbeiten Sie mit Umgebungen](choose-environment.md). 
    - Hochladen einer csv-Datei durch Auswahl von **Empfänger importieren**.

3.  Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [Umfrage-Link einfügen](#insert-survey-link).  

4.  Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einer Umfrage](#unsubscribe-from-a-survey).  

5.  Um die E-Mail unter Verwendung von Vor- und Nachnamen des Befragten zu personalisieren, siehe [Personalisieren einer E-Mail](#personalize-an-email).  

6.  Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**. Standardmäßig ist **Standardvorlage** ausgewählt. Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates).  

7.  Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.

> [!NOTE]
> In dieser Version können Sie eine Umfrageeinladung an maximal 100 Empfänger senden.

## <a name="insert-survey-link"></a>Umfrage-Link einfügen

Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt. Um den Umfrage-Link an einer anderen Stelle in Ihrer E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie **Umfrage-Link einfügen**. Sie können auch Text auswählen und dann **Umfrage-Link einfügen** wählen, um diesen Text als Umfrage-Link anzuzeigen.

## <a name="unsubscribe-from-a-survey"></a>Abmeldung von einer Umfrage

Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden. Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Abmeldelink einfügen**. Sie können auch Text auswählen und dann **Link zum Abmelden einfügen** wählen, um diesen Text als Abmeldelink anzuzeigen. Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.

## <a name="personalize-an-email"></a>Eine E-Mail personalisieren

Personalisieren Sie Ihre Umfrage-E-Mail, indem Sie Platzhalter verwenden. Positionieren Sie den Cursor beispielsweise an der Stelle, an der ein Vorname erscheinen soll. Wählen Sie **Personalisieren**, und wählen Sie dann **Vorname** aus der Auswahlliste. Der Vorname des Befragten wird automatisch eingefügt. 

Die folgenden Variablen stehen zur Verfügung:

- **Vorname**: Fügt den Vornamen des Empfängers ein.

- **Nachname**: Fügt den Nachnamen des Empfängers ein.


## <a name="use-email-templates"></a>E-Mail-Vorlagen verwenden

Eine E-Mail-Vorlage ist eine vorformatierte E-Mail-Nachricht, mit der Sie schnell E-Mail-Nachrichten erstellen und senden können. Sie können den Text ändern und Ihre Änderungen dann in der aktuellen E-Mail-Vorlage speichern oder die Änderungen in einer neuen E-Mail-Vorlage speichern. Wenn Sie keine andere Auswahl treffen, wird **Standardvorlage** für die Verwendung in einer E-Mail-Nachricht ausgewählt. 

Sie können diese Aktionen auf einer E-Mail-Vorlage durchführen:

- **Speichern**: Speichern Sie Ihre Änderungen an der aktuellen E-Mail-Vorlage.

- **Speichern unter**: Speichern Sie Ihre Änderungen in einer neuen E-Mail-Vorlage.

- **Löschen**: Löschen Sie die aktuelle E-Mail-Vorlage.

- **Umbenennen**: Benennen Sie die aktuelle E-Mail-Vorlage um.

> [!NOTE]
> Sie können maximal 10 E-Mail-Vorlagen speichern.

## <a name="see-also"></a>Siehe auch

[Definieren Sie, wer an einer Umfrage teilnehmen darf](invite-settings.md)<br>
[Senden Sie eine Umfrage mit Microsoft Flow](send-survey-microsoft-flow.md)<br>
[Eingebettete Umfrage in eine Webseite](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)
