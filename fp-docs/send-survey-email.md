---
title: Senden einer Umfrage per E-Mail | MicrosoftDocs
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 12/02/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 218ab18e8448011bf4b8e914ae43d0854d02ef2f
ms.sourcegitcommit: 7f28e8040b2a3e56ba0caff0d48053974e3a1e80
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/02/2019
ms.locfileid: "2856185"
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

## <a name="customize-the-sender-email-address"></a>Anpassen der Absender-E-Mail-Adresse

Mithilfe der Anpassungsfunktion können Sie eine E-Mail-Adresse auswählen, die der Marke Ihres Unternehmens entspricht. Sie können sich an den Microsoft-Support wenden, um den von Forms Pro bereitgestellten Speicherort zu erfahren, um anschließend CNAME-Datensätze manuell zu erstellen. Die CNAME-Datensätze werden für die DKIM-Authentifizierung verwendet. Für jede benutzerdefinierte Domäne müssen zwei CNAME-Einträge erstellt werden. Anschließend kann die E-Mail-Adresse angepasst werden, über die die Umfrageeinladung an Ihre Befragten gesendet wird.

1. Melden Sie sich mit Ihren Administrator-Anmeldeinformationen beim [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/support) an.

2. Wählen Sie **Hilfe + Support** > **Neue Supportanfragen** aus. Das Support-Anfrageformular wird im rechten Bereich angezeigt.

3. Geben Sie die Produktdetails wie folgt an:

    - **Produkt**: Dynamics 365 Customer Engagement
    - **Problemtyp**: Forms Pro
    - **Umgebung**: Geben Sie die Common Data Service-Umgebung ein, oder wählen Sie sie aus

4. Wählen Sie **Lösungen anzeigen** aus.

5. Wählen Sie **Erstellen Sie eine Supportanfrage** aus, und geben Sie Details wie folgt an:

    - **Problemtitel**: Passen Sie die Absender-E-Mail-Adresse an, um Umfrageeinladungen zu senden
    - **Problembeschreibung**: Geben Sie Ihre Problembeschreibung ein, und fragen Sie nach dem von Forms Pro bereitgestellten Speicherort.
    - **Wie schwer ist dieses Problem?**: Wählen Sie den Schweregrad des Problems.

6. Wählen Sie **Weiter**. 

7. Geben Sie Ihre Kontaktinformationen ein, und wählen Sie dann **Senden** aus. Es wird ein Ticket beim Microsoft-Support erstellt, und das Support-Team teilt Ihnen den bereitgestellten Speicherort mit.

8.  Nachdem Sie den bereitgestellten Speicherort erhalten haben, erstellen Sie zwei CNAME-Datensätze in Ihrer Domäne im folgenden Format: 

    ``` text
    Host name:                    selector1._domainkey
    Points to address or value:   selector1<domainGUID>.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    selector2._domainkey
    Points to address or value:   selector2<domainGUID>.marketing.dynamics.com
    TTL:                          3600
    ```

    > [!IMPORTANT]
    > Wenn Ihre benutzerdefinierte Domäne `contoso.com` lautet, ist die domainGuid `contosocom`. Sie müssen Punkte, Unterstriche und Bindestriche entfernen.
    > Die Auswahlmöglichkeiten richten sich nach dem von Forms Pro bereitgestellten Speicherort:
    > - Für Nordamerika (NAM) lautet die Auswahl „fpnamkey1“ oder „fpnamkey2“.
    > - Für Europa (EUR) lautet die Auswahl „fpeurkey1“ oder „fpeurkey2“.

    Nehmen wir an, Ihr von Forms Pro bereitgestellter Speicherort ist Nordamerika (NAM), und Sie haben zwei benutzerdefinierte Domänen: `cohovineyard.com` und `cohowinery.com`. Sie müssten zwei CNAME-Einträge pro Domäne (insgesamt vier CNAME-Datensätze) wie folgt einrichten:

    ``` text
    Host name:                    fpnamkey1._domainkey
    Points to address or value:   fpnamkey1cohovineyardcom.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    fpnamkey2._domainkey
    Points to address or value:   fpnamkey1cohovineyardcom.marketing.dynamics.com
    TTL:                          3600
    Host name:                    fpnamkey1._domainkey
    Points to address or value:   fpnamkey1cohowinerycom.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    fpnamkey2._domainkey
    Points to address or value:   fpnamkey1cohowinerycom.marketing.dynamics.com
    TTL:                          3600
    ```

9.  Wenden Sie sich an den Microsoft-Support, und geben Sie die folgenden Informationen an:

    - Eine Liste der E-Mail-Adressen, die Sie erstellen möchten, z. B. support@cohovineyard.com und noreply@cohowinery.com.
    - Eine Liste der Benutzer, die die Umfrageeinladungen mithilfe der benutzerdefinierten E-Mail senden.

    Basierend auf den bereitgestellten Informationen überprüft der Microsoft-Support die Datensätze und erstellt die DKIM-Schlüssel zum Signieren der E-Mails. Sie erhalten vom Microsoft-Support eine Bestätigung, dass die Datensatzüberprüfung abgeschlossen ist.

10. Melden Sie sich bei Forms Pro an, und öffnen Sie die den Bereich **Einstellungen**. Wählen Sie die benutzerdefinierte E-Mail-Adresse aus, die zum Senden von E-Mails verwendet werden soll.  

    > [!div class=mx-imgBorder]
    > ![Benutzerdefinierte E-Mail-Einstellung](media/custom-email-setting.png "Benutzerdefinierte E-Mail-Einstellung")

    Verwenden Sie die benutzerdefinierte E-Mail, während Sie die Umfrageeinladung senden.

    > [!div class=mx-imgBorder]
    > ![Benutzerdefinierte Absender-E-Mail](media/custom-from-email.png "Benutzerdefinierte Absender-E-Mail")

    > [!NOTE]
    > In Power Automate wird eine benutzerdefinierte E-Mail-Adresse aus den Umfrageeinstellungen ausgewählt.

### <a name="frequently-asked-questions"></a>Häufig gestellte Fragen

#### <a name="should-the-email-account-be-a-functioning-account-or-can-it-be-a-dummy-account"></a>Sollte das E-Mail-Konto ein funktionierendes Konto sein oder kann es ein Dummy-Konto sein?

Das E-Mail-Konto muss nicht funktionsfähig sein, um E-Mails zu senden. Wenn über dieses E-Mail-Konto Antworten erwartet werden, muss ein Postfach konfiguriert werden. In den meisten Fällen handelt es sich bei der E-Mail-Adresse, von der ein Kunde Umfrage-E-Mails sendet, um nicht überwachte E-Mail-Konten, die keine E-Mails empfangen müssen.

#### <a name="how-long-does-it-take-for-the-setup-to-complete"></a>Wie lange dauert es, bis die Einrichtung abgeschlossen ist?

Es kann zwischen 24 und 72 Stunden dauern, bis das Setup abgeschlossen ist. Nachdem der Microsoft-Support bestätigt hat, dass die Domäne aktiv ist, können Sie mit dem Senden von Umfrageeinladungen mithilfe der benutzerdefinierten E-Mail beginnen.

## <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage mit Microsoft Flow](send-survey-microsoft-flow.md)<br>
[Eingebettete Umfrage in eine Webseite](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in PowerApps](embed-survey-powerapps.md)
