---
title: Unfrageeinstellungen
description: Anweisungen zum Aktualisieren von Umfrageeinstellungen in Microsoft Forms Pro, um zu steuern, wer auf Ihre Umfrage und andere Umfrageantwortoptionen antworten kann
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 02/21/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: 1f6ec6f5-b3d2-4305-8dca-3a0b67a1083c
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: f7f46613778928fd665ec002848ef94e2930a971
ms.sourcegitcommit: 38563d8ed7de1c1d1d54c2b5cbd2d46c52c2478a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2020
ms.locfileid: "3161386"
---
# <a name="work-with-survey-settings"></a>Arbeiten mit Umfrage-Einstellungen

Nachdem Sie eine Umfrage erstellt haben, können Sie Einstellungen auswählen, um dann die Antworten auf Ihre Umfrage zu steuern. Sie können wählen, ob alle an der Umfrage teilnehmen können oder nur die Personen in Ihrem Unternehmen. Die erste Option erfordert keine Anmeldung eines Befragten, während aber die zweite Option eine Anmeldung eines Befragten erfordert. Sie können auch verschiedene Antwort- und Benachrichtigungsoptionen festlegen.

## <a name="define-who-can-respond-to-a-survey"></a>Definieren Sie, wer an einer Umfrage teilnehmen darf.

Betrachten Sie ein Szenario, in dem Sie eine Umfrage erstellt haben, um das Kundenfeedback zu sammeln, wenn ein Supportfall gelöst wurde. In diesem Szenario benötigen Sie den Feedback von den Personen außerhalb Ihres Unternehmens. Um dies zu erreichen, wählen Sie in den Umfrageeinstellungen die Option **Jeder mit einem Link kann antworten**. Mehr Informationen: [Jeder mit dem Link kann antworten](#anyone-with-the-link-can-respond)

Betrachten wir ein weiteres Szenario, in dem Sie eine Umfrage erstellt haben, um Feedback zu einer internen Veranstaltung zu sammeln und Sie möchten, dass nur die Personen in Ihrer Organisation an der Umfrage teilnehmen. Um dies zu erreichen, wählen Sie die Option **Nur Personen aus meiner Organisation können in den Umfrageeinstellungen antworten**. Mehr Informationen: [Nur Personen in meiner Organisation können antworten](#only-people-in-my-organization-can-respond)

Lassen Sie uns nun die Optionen sehen, die Sie auswählen können, um festzulegen, wer an einer Umfrage teilnehmen darf, und die Optionen auswählen, ob der Name des Befragten erfasst werden soll und der Befragte nur eine Antwort senden darf.

### <a name="anyone-with-the-link-can-respond"></a>Jeder mit dem Link kann antworten.

1. Öffnen Sie die Umfrage, für die Sie die Umfrage-Einstellungen ändern möchten.

2. Wählen Sie die Schaltfläche mit den Auslassungspunkten **(...)** aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Einstellungen** aus.

    > [!div class=mx-imgBorder]
    > ![Einstellungen](media/settings-icon.png "Einstellungen")

3. Wählen Sie **Jeder mit dem Link kann antworten**. Wenn Sie diese Option auswählen, müssen sich die Befragten nicht mit den Anmeldeinformationen anmelden.

4. Optional können Sie eine oder beide der folgenden Optionen auswählen:

    - **Datensatzname**: Der Name des Befragten wird aufgezeichnet. Diese Option funktioniert nur, wenn ein [personalisierter Umfrage-Link](#work-with-personalized-links) generiert wird.

    - **Eine Antwort pro Person**: Ein Befragter kann nur eine Antwort abgeben. Diese Option ist nur aktiviert, wenn **Name aufzeichen** ausgewählt ist und funktioniert nur, wenn ein [personalisierter Umfrage-Link](#work-with-personalized-links) generiert wird.

    > [!div class=mx-imgBorder]
    > ![Einladungseinstellungen für externe Umfragen](media/invite-settings-external.png "Einladungseinstellungen für externe Umfragen")

### <a name="only-people-in-my-organization-can-respond"></a>Nur Personen in meinem Unternehmen können antworten.

1. Öffnen Sie die Umfrage, für die Sie die Umfrage-Einstellungen ändern möchten.

2. Wählen Sie die Schaltfläche mit den Auslassungspunkten **(...)** aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Einstellungen** aus.

    > [!div class=mx-imgBorder]
    > ![Einstellungen](media/settings-icon.png "Einstellungen")

3. Wählen Sie **Nur Personen in meiner Organisation können antworten**. Wenn Sie diese Option auswählen, müssen sich die Befragten mit ihren Anmeldeinformationen anmelden.

4. Optional können Sie eine oder beide der folgenden Optionen auswählen:

    - **Datensatzname**: Der Name des Befragten wird aufgezeichnet.

    - **Eine Antwort pro Person**: Ein Befragter kann nur eine Antwort abgeben.

    > [!div class=mx-imgBorder]
    > ![Einladungseinstellungen für interne Umfragen](media/invite-settings-internal.png "Einladungseinstellungen für interne Umfragen")

## <a name="survey-response-options"></a>Antwortmöglichkeiten für Umfragen

Wenn Sie definiert haben, wer an Ihrer Umfrage teilnehmen darf, können Sie die folgenden Optionen auswählen oder löschen:

- **Antworten akzeptieren**: Geben Sie an, ob die Umfrage offen ist und ob Antworten akzeptiert werden sollen. Diese Option ist standardmäßig ausgewählt. Wenn Sie Ihre Umfrage stoppen möchten, deaktivieren Sie die Option und geben eine Nachricht für die Empfänger an.
- **Fragen mischen**: Geben Sie an, ob die Fragen in der Umfrage gemischt werden sollen.
- **Fragezahlen anzeigen**: Geben Sie an, ob die Fragenzahlen in der Umfrage angezeigt werden sollen. Diese Option ist standardmäßig ausgewählt.
- **Nachricht anpassen**: Geben Sie eine benutzerdefinierte Dankesnachricht für Ihre Teilnehmer an. Sie können die Dankesnachricht auch formatieren, um den Schriftstil, die Schriftart, den Schriftnamen und die Schriftgröße zu ändern. Sie können der Nachricht auch einen **Link** hinzufügen, indem Sie die Schaltfläche Verknüpfen auf der Formatierungssymbolleiste auswählen und den Link dann über den Link-Editor hinzufügen.
- **Passen Sie den Fußzeilentext an**: Geben Sie einen benutzerdefinierten Fußzeilentext ein, der für Ihre Umfrage angezeigt werden soll. Sie können den Fußnotentext auch formatieren, um den Schriftstil, die Schriftart, den Schriftnamen und die Schriftgröße zu ändern. Sie können der Nachricht auch einen **Link** hinzufügen, indem Sie die Schaltfläche Verknüpfen auf der Formatierungssymbolleiste auswählen und den Link dann über den Link-Editor hinzufügen.
- **Teilnehmer hinzufügen als**: Geben Sie an, ob der Befragte als Kontakt in hinzugefügt werden soll Common Data Service. Diese Option ist standardmäßig ausgewählt. Es funktioniert nur mit Umfragen, die per E-Mail gesendet werden.
- **Startdatum**: Geben Sie ein Datum an, an dem die Umfrage für Teilnehmer geöffnet wird.

### <a name="stop-survey"></a>Umfrage beenden

Sie können ein Datum, eine Anzahl von Antworten oder einen Zeitraum angeben, nach dem die Umfrage gestoppt wird und Ihre Befragten nicht in der Lage sind, die Umfrage abzuschließen. Wenn eine der folgenden Bedingungen zutrifft, wird die Umfrage gestoppt:

- **Enddatum**: Geben Sie das Datum an, an dem die Umfrage abgeschlossen wird.
- **Maximale Antworten**: Geben Sie die maximale Anzahl der zu empfangenden Antworten an, danach werden die Antworten nicht mehr gezählt und die Umfrage wird gestoppt.
- **Anzahl der Tage**: Geben Sie an, nach wie vielen Tagen Ihre Umfrage geöffnet sein soll, nachdem Sie die Umfrageeinladung gesendet haben. Der maximale Wert, der eingegeben werden kann, ist 1.095. Die Befragten können die Befragung über den personalisierten Link ab dem Tag des Empfangs der Befragungseinladung bis zur angegebenen Anzahl von Tagen nutzen.

### <a name="notification"></a>Benachrichtigung

- **Senden Sie eine E-Mail-Quittung an die Befragten**: Geben Sie an, ob die Befragten eine E-Mail-Bestätigung ihrer Antworten erhalten sollen. Diese Option ist aktiviert, wenn **Name aufzeichnen** unter **Nur Personen in meiner Organisation können antworten** ausgewählt ist. Nachdem Ihr Befragter Ihre Umfrage ausgefüllt hat, wird die Option **Senden Sie mir eine E-Mail-Bestätigung meiner Antworten** angezeigt. Nachdem Antworten eingereicht wurden, erhalten Teilnehmer dann eine E-Mail mit einer Dankesnachricht und einem Link zum Anzeigen ihrer Antworten.

- **E-Mail-Benachrichtigung jeder Antwort**: Geben Sie an, ob eine E-Mail-Benachrichtigung erforderlich ist, wenn eine Antwort gesendet wird.

> [!div class=mx-imgBorder]
> ![Antwortoptionen für Umfragen](media/invite-settings-options.png "Antwortoptionen für Umfragen")

Sie können die Authentifizierungseinstellungen jederzeit ändern, auch nach der Verteilung der Umfrage per E-Mail oder über andere Kanäle.

## <a name="add-a-progress-bar"></a>Einen Fortschrittsbalken hinzufügen

Ein Fortschrittsbalken zeigt Ihren Befragten den Prozentsatz der Seiten an, zu denen sie bisher navigiert oder die sie sich angesehen haben. Sie gibt ihnen eine Vorstellung davon, wie weit sie gekommen sind und wie weit sie noch gehen müssen. Der Fortschrittsbalken berücksichtigt alle Seiten in der Umfrage. Wenn Seiten aufgrund einer Verzweigungsregel übersprungen wurden, zeigt der Fortschrittsbalken den angepassten Abschlussprozentsatz an. Der Fortschrittsbalken wird nur angezeigt, wenn es zwei oder mehr Seiten in der Umfrage gibt.

Sie können die Anzeige des Fortschrittsbalkens steuern, indem Sie in den Umfrageeinstellungen das Kontrollkästchen **Fortschrittsbalken anzeigen** markieren oder deaktivieren. Bei Umfragen, die nach der Version Februar 2020 erstellt wurden, ist dieses Kontrollkästchen standardmäßig aktiviert. Bei Umfragen, die vor der Version Februar 2020 erstellt wurden, müssen Sie das Kontrollkästchen **Fortschrittsbalken anzeigen** aktivieren.

> [!div class=mx-imgBorder]
> ![Fortschrittsbalken-Einstellung](media/progress-bar-setting.png "Fortschrittsbalken-Einstellung")

Der Fortschrittsbalken wird auf der rechten Seite der Schaltflächen auf der Umfrage angezeigt.

> [!div class=mx-imgBorder]
> ![Fortschrittsleiste einer Umfrage](media/progress-bar.png "Fortschrittsbalken bei einer Umfrage")


## <a name="work-with-personalized-links"></a>Arbeit mit personalisierten Links

Personalisierte Umfragelinks oder verfolgbare Links werden generiert, wenn eine Umfrage mit dem integrierten E-Mail-Komponisten und Power Automate gesendet wird. Ein Umfrage-Link ist eindeutig für den Empfänger und hilft bei der Erfassung des Namens des Befragten und/oder der Frage, ob der Befragte nur eine Antwort geben muss.

Wenn Sie dann eine Umfrage senden, indem Sie einen Link oder einen QR-Code generieren, sind die Umfrage-Links nicht personalisiert. In diesen Fällen können Sie den Namen des Befragten nicht erfassen und auch nicht, ob der Befragte nur eine Antwort übermittelt hat, wenn Sie **Jeder mit dem Link kann antworten** ausgewählt haben.

### <a name="see-also"></a>Siehe auch

[Senden Sie eine Umfrage per E-Mail](send-survey-email.md)<br>
[Senden Sie eine Umfrage mit Power Automate](send-survey-flow.md)<br>
[Eine Umfrage in einer Webseite einbetten](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in Power Apps](embed-survey-powerapps.md)
