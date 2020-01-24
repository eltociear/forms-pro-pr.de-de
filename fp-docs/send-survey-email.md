---
title: Senden einer Umfrage per E-Mail | MicrosoftDocs
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 12/23/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 69eff193e16e1d4c0624162d9b72ca8ef2245189
ms.sourcegitcommit: 12abf1856081a5f60a025c0ca305161eb0d0978a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/23/2019
ms.locfileid: "2922575"
---
# <a name="send-a-survey-by-using-email"></a>Senden Sie eine Umfrage per E-Mail.

Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden mit den folgenden Schritten:

1.  Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie **Senden** aus der Symbolleiste oben auf der Seite. 

2. Wählen Sie **E-Mail**. Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext. Sie können den Text an Ihre Anforderungen anpassen und formatieren.

3.  Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein. Sie können das Feld **An** auf eine der folgenden Methoden ausfüllen:

    - Manuelle Eingabe einer E-Mail-Adresse.
    - Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.
    - Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Service für Apps. Die Kontakte werden aus der ausgewählten Umgebung gefüllt. Weitere Informationen: [Arbeiten mit Umgebungen](choose-environment.md)
    - Hochladen einer csv-Datei durch Auswahl von **Empfänger importieren**. Die CSV-Datei unterstützt den Import von maximal 10000 Empfängern.

4.  Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [eiUmfrage-Link einfügen](#insert-survey-link).  

5.  Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einem Link](#unsubscribe-from-a-survey).  

6.  Informationen zum Personalisieren der E-Mail mithilfe von Umfragevariablen finden Sie unter [Personalisieren Sie die Umfrage-E-Mail](#personalize-an-email).

7. Informationen zum Einbetten der ersten Frage der Umfrage in Ihre E-Mail-Nachricht finden Sie unter [Betten Sie eine Umfrage in eine E-Mail ein](#embed-survey-in-an-email).

8.  Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**. Standardmäßig ist **Standardvorlage** ausgewählt. Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)

8.  Informationen zum Anpassen des Absenders der Umfrage-E-Mail finden Sie unter [Passen Sie die E-Mail-Adresse des Absenders an](#customize-sender-email-address).

9.  Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.

> [!NOTE]
> Sie können eine Umfrageeinladung an maximal 10000 Empfänger senden.

<a name="insert-survey-link"></a>

## <a name="insert-a-survey-link"></a>Einen Befragungslink einfügen

Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt. Um den Umfrage-Link an einer anderen Stelle in Ihrer E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Umfrage-Link**. Sie können auch Text auswählen und dann **Einfügen** > **Umfrage-Link** wählen, um diesen Text als Umfrage-Link anzuzeigen.

<a name="unsubscribe-from-a-survey"></a>

## <a name="insert-an-unsubscribe-link"></a>Link für eine Abonnementkündigung einfügen

Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden. Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Link**Abmelden. Sie können auch Text auswählen und dann **Einfügen** > **Abmelde-Link** wählen, um diesen Text als Abmeldelink anzuzeigen. Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.

<a name="personalize-an-email"></a>

## <a name="personalize-the-survey-email"></a>Personalisieren der Umfrage-E-Mail

Verwenden Sie Umfragevariablen, um Ihre Umfrage-E-Mail zu personalisieren&mdash;Sie können beispielsweise den Vornamen des Befragten hinzufügen. Platzieren Sie den Cursor an der Stelle, an der der Name angezeigt werden soll, und wählen Sie **Variablen** und dann **Vorname** von der Liste. Der Vorname des Befragten wird automatisch eingefügt. Alle in einer Umfrage erstellten Umfragevariablen werden in der Liste **Variablen** angezeigt.

Um eine neue Variable zu erstellen, wählen Sie **Neue Variable** aus der Liste **Variablen**. Wenn für Umfragevariablen keine Standardwerte definiert wurden, wird oben auf der Seite eine Warnmeldung angezeigt. Weitere Informationen zum Erstellen von Variablen und zum Bereitstellen von Werten finden Sie unter [Personalisieren Sie eine Umfrage](personalize-survey.md).

<a name="embed-survey-in-an-email"></a>

## <a name="embed-a-survey-in-an-email"></a>Betten Sie eine Umfrage in eine E-Mail ein

Wenn Sie eine Frage zur Bewertung oder zum Netto-Promoter-Score als erste Frage in Ihrer Umfrage hinzugefügt haben, können Sie sie in Ihre E-Mail-Nachricht einbetten. Um die Frage einzubetten, wählen Sie **Einbetten erste Frage**. Wenn Sie eine Frage einbetten, wird der Text in der E-Mail-Nachricht durch die Frage ersetzt. Wenn ein Befragter eine Option in der E-Mail auswählt, wird die gesamte Umfrage im Webbrowser geöffnet und der Befragte kann die Umfrage fortsetzen.

> [!div class=mx-imgBorder]
> ![Betten Sie eine Umfrage in eine E-Mail ein](media/embed-ques-email.png "Betten Sie eine Umfrage in eine E-Mail ein")

> [!NOTE]
> Sie können die Frage nicht in eine E-Mail einbetten, wenn Sie das Mischen von Fragen in einer Umfrage aktiviert haben.

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

<a name="customize-sender-email-address"></a>

## <a name="customize-the-senders-email-address"></a>Passen Sie die E-Mail-Adresse des Senders an

Mithilfe der Anpassungsfunktion können Sie eine E-Mail-Adresse auswählen, die der Marke Ihres Unternehmens entspricht. Sie können sich an den Microsoft-Support wenden, um den von Forms Pro bereitgestellten Speicherort zu erfahren, um anschließend CNAME-Datensätze manuell zu erstellen. Die CNAME-Datensätze werden für die DKIM-Authentifizierung verwendet. Sie müssen zwei CNAME-Einträge pro benutzerdefinierter Domäne erstellen. Anschließend können Sie die E-Mail-Adresse anpassen, mit der die Umfrageeinladung an Ihre Befragten gesendet wird.

1. Melden Sie sich mit Ihren Administrator-Anmeldeinformationen beim [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/support) an.

2. Wählen Sie **Hilfe + Support** > **Neue Supportanfragen** aus. Das Support-Anfrageformular wird im rechten Bereich angezeigt.

3. Geben Sie die Produktdetails wie folgt an:

    - **Produkt**: Dynamics 365 Customer Engagement
    - **Problemtyp**: Forms Pro
    - **Umgebung**: Geben Sie die Common Data Service-Umgebung ein, oder wählen Sie sie aus

4. Wählen Sie **Lösungen anzeigen** aus.

5. Wählen Sie **Erstellen Sie eine Supportanfrage** aus, und geben Sie dann Details wie folgt an:

    - **Problemtitel**: Passen Sie die Absender-E-Mail-Adresse an, um Umfrageeinladungen zu senden
    - **Fehlerbeschreibung** : Geben Sie Ihre Problembeschreibung ein und fragen Sie nach dem von Forms Pro bereitgestellten Speicherort.
    - **Wie schwer ist dieses Problem?**: Wählen Sie den Schweregrad des Problems.

6. Wählen Sie **Weiter**.

7. Geben Sie Ihre Kontaktinformationen ein, und wählen Sie dann **Senden** aus. Mit dem Microsoft-Support Team wird ein Ticket erstellt, das Sie über den bereitgestellten Speicherort informiert.

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
    > - Für Nordamerika (NAM) lautet die Auswahl "fpnamkey1" oder "fpnamkey2".
    > - Für Europa (EUR) lautet die Auswahl "fpeurkey1" oder "fpeurkey2".

    Nehmen wir an, Ihr von Forms Pro bereitgestellter Speicherort ist Nordamerika (NAM), und Sie haben zwei benutzerdefinierte Domänen: `contoso.com` und `contososuites.com`. Sie müssen wie folgt zwei CNAME-Einträge pro Domain einrichten (insgesamt vier CNAME-Einträge):

    ``` text
    Host name:                    fpnamkey1._domainkey
    Points to address or value:   fpnamkey1contosocom.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    fpnamkey2._domainkey
    Points to address or value:   fpnamkey1contosocom.marketing.dynamics.com
    TTL:                          3600
    Host name:                    fpnamkey1._domainkey
    Points to address or value:   fpnamkey1contososuitescom.marketing.dynamics.com
    TTL:                          3600
    Host name:                    fpnamkey2._domainkey
    Points to address or value:   fpnamkey1contososuitescom.marketing.dynamics.com
    TTL:                          3600
    ```

9.  Wenden Sie sich an den Microsoft-Support, und geben Sie die folgenden Informationen an:

    - Eine Liste der E-Mail-Adressen, die Sie erstellen möchten, z. B. support@contoso.com und noreply@contososuites.com.
    - Eine Liste der Benutzer, die die Umfrageeinladungen mithilfe der benutzerdefinierten E-Mail senden.

    Basierend auf den bereitgestellten Informationen überprüft der Microsoft-Support die Datensätze und erstellt die DKIM-Schlüssel zum Signieren der E-Mails. Sie erhalten vom Microsoft-Support eine Bestätigung, dass die Datensatzüberprüfung abgeschlossen ist.

    > [!NOTE]
    > Das SLA für die Erstellung von DKIM-Schlüsseln beträgt mindestens 3 bis 4 Wochen.

10. Melden Sie sich bei Forms Pro an und öffnen Sie die den Bereich **Einstellungen**. Wählen Sie die benutzerdefinierte E-Mail-Adresse an, die Sie verwenden möchten.  

    > [!div class=mx-imgBorder]
    > ![Benutzerdefinierte E-Mail-Einstellung](media/custom-email-setting.png "Benutzerdefinierte E-Mail-Einstellung")

    Verwenden Sie die benutzerdefinierte E-Mail, während Sie die Umfrageeinladung senden.

    > [!div class=mx-imgBorder]
    > ![Benutzerdefinierte Absender-E-Mail](media/custom-from-email.png "Benutzerdefinierte Absender-E-Mail")

    > [!NOTE]
    > Im Power Automate wird die benutzerdefinierte E-Mail-Adresse aus den Umfrageeinstellungen ausgewählt.

### <a name="frequently-asked-questions"></a>Häufig gestellte Fragen

#### <a name="should-the-email-account-be-a-functioning-account-or-can-it-be-a-dummy-account"></a>Sollte das E-Mail-Konto ein funktionierendes Konto sein oder kann es ein Dummy-Konto sein?

Das E-Mail-Konto muss nicht funktionsfähig sein, um E-Mails zu senden. Es muss jedoch ein Postfach konfiguriert werden, wenn für das Konto Antworten erwartet werden. In den meisten Fällen ist die E-Mail-Adresse, von der Umfrage-E-Mails gesendet werden, ein nicht überwachtes E-Mail-Konto und muss keine E-Mails empfangen.

#### <a name="how-long-does-it-take-for-setup-to-be-completed"></a>Wie lange dauert es, bis das Setup abgeschlossen ist?

Es dauert mindestens 3 bis 4 Wochen, bis die Einrichtung abgeschlossen ist. Nachdem der Microsoft-Support bestätigt hat, dass die Domain aktiv ist, können Sie mithilfe der benutzerdefinierten E-Mail mit dem Senden von Umfrageeinladungen beginnen.

### <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage mit Power Automate](send-survey-microsoft-flow.md)<br>
[Eine Umfrage in einer Webseite einbetten](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in Power Apps](embed-survey-powerapps.md)
