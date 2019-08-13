---
title: Fehlerbehebung | MicrosoftDocs
description: Erfahren Sie, wie Sie Probleme in Microsoft Forms Pro beheben können.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 06/14/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 97526FE3-7523-48B0-A8F4-7C369AF78DB4
ms.custom: ''
ms.openlocfilehash: 10f48d8ad3f8345892e02b6f4f58facaece99ae5
ms.sourcegitcommit: 4f20bfe750e8d4eb2db4dca0479699eb365c8c9e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2019
ms.locfileid: "1724607"
---
# <a name="troubleshoot-issues-in-forms-pro"></a>Fehlerbehebung bei Problemen in Forms-Prozessen

Dieser Artikel enthält Informationen zur Fehlerbehebung in der Lösung Microsoft Forms Pro.

## <a name="environment-provisioning-failure"></a>Fehler bei der Umgebungsbereitstellung

Wenn Sie einen Fehler erhalten, der besagt, dass Ihre Umgebungsbereitstellung fehlgeschlagen ist, müssen Sie die von Ihnen verwendete Version von Common Data Service überprüfen. Forms Pro funktioniert nicht mit der Vorgängerversion von Common Data Service. Wenn Ihre Standardumgebung mit der vorherigen Version von Common Data Service erstellt wurde, wird Ihre Umgebung nicht bereitgestellt und es wird eine Fehlermeldung angezeigt.  Sie müssen die vorherige Version von Common Data Service auf die neuere Version von Common Data Service für Apps aktualisieren. Weitere Informationen zum Upgrade auf Common Data Service für Apps finden Sie unter [Upgrade auf Common Data Service für Apps](https://docs.microsoft.com/en-us/common-data-service/upgradecds/introduction-upgrade-cds).

Um Ihre Common Data Service von der Vorgängerversion auf die neuere Version zu löschen oder zu aktualisieren, wenden Sie sich an Ihren globalen Administrator. 

Wenn die Bereitstellung Ihrer Umgebung fehlgeschlagen ist, wird die Bereitstellung regelmäßig erneut getestet. Wenn Sie eine andere Anfrage priorisieren oder übermitteln möchten, wenden Sie sich bitte an den Support.

 Wenn Sie die Common Data Service aktualisiert haben und Ihre Umgebungserstellung immer noch Probleme aufweist, wenden Sie sich bitte an den Support.

## <a name="environment-permission-failure"></a>Ausfall der Umgebungsberechtigung

Wenn Sie eine Fehlermeldung erhalten, dass Sie keine Berechtigung für den Zugriff auf die Umgebung haben, müssen Sie Ihren Administrator kontaktieren, um die folgenden Punkte zu überprüfen:

- Microsoft Forms Pro Lösung ist installiert.
- Ein Anwendungsbenutzer mit dem Namen Microsoft Forms Pro wird angelegt.
    - Dem Anwendungsbenutzer sind die Sicherheitsrollen Umfragedienste-Administrator und Systemadministrator zugewiesen.
    - Die Sicherheitsrolle Umfragedienste-Administrator hat die Berechtigungen Organisation für die Umfrageeinheiten, wie unter [Umfragedienste-Administrator Sicherheitsrollenberechtigungen](#survey-services-administrator-security-role-privileges) angegeben.
- Ihnen ist die Sicherheitsrolle Umfragebesitzer zugeordnet.
    - Die Sicherheitsrolle Umfragebesitzer hat die Benutzerprivilegien für die Umfrageeinheiten, wie unter [Umfragebesitzer Sicherheitsrollenprivilegien](#survey-owner-security-role-privileges) angegeben.

### <a name="survey-services-administrator-security-role-privileges"></a>Umfragedienste Administrator Sicherheitsrollenprivilegien

|Entität|Erstellen|Lesezugriff|Schreiben|Löschen|Anfügen|Anfügen an|Zuweisen|Freigeben|
|------|------|----|-----|------|------|---------|------|-----|
|Umfrage|x|x|x|x|x|x|x|x|
|Umfrage-E-Mail-Vorlage|x|x|x|x|x|x|x|x|
|Umfrage Frage|x|x|x|x|x|x|x|x|
|Beantwortung von Umfragefragen|x|x|x|x|x|x|x|x|
|Nicht abonnierter Empfänger|x|x|x|x|x|x|x|x|
||||||||||

### <a name="survey-owner-security-role-privileges"></a>Berechtigungen für die Sicherheitsrolle des Umfragebesitzers

|Entität|Erstellen|Lesezugriff|Schreiben|Löschen|Anfügen|Anfügen an|Zuweisen|Freigeben|
|------|------|----|-----|------|------|---------|------|-----|
|Umfrage|x|x|x|x|x|x|x|x|
|Umfrage-E-Mail-Vorlage|x|x|x|x|x|x|x|x|
|Umfrage Frage|x|x|x|x|x|x|x|x|
|Beantwortung von Umfragefragen|x|x|x|x|x|x|x|x|
||||||||||

## <a name="invalid-connection-error-in-flow"></a>Ungültiger Verbindungsfehler im Flow

Wenn Sie einen Fehler erhalten, der besagt, dass Ihre Verbindung ungültig ist oder es ein Problem mit dem Trigger des Flusses gibt, müssen Sie dies tun:

1. Öffnen Sie Microsoft Flow.

2. Wählen Sie im linken Bereich **Daten** > **Verbindungen**.

3. Suchen Sie nach der Verbindung **Microsoft Forms Pro** und löschen Sie sie.

    > [!NOTE]
    > Wenn Sie mehrere Verbindungen für Microsoft Forms Pro angelegt haben, müssen Sie diese alle löschen.

4. Wählen Sie **Neue Verbindung**, um eine neue Verbindung zu erstellen.

5. Suchen Sie in der Liste der Verbindungen nach **Microsoft Forms Pro** und wählen Sie sie aus.

6. Wählen Sie im Bestätigungsfenster **Erstellen**, und geben Sie dann Ihre Zugangsdaten ein.

7. Öffnen Sie den Fluss, in dem der Fehler aufgetreten ist.

8. Gehen Sie zu der Aktion, die den Fehler verursacht hat. Die von Ihnen erstellte Verbindung wird angezeigt.

9. Wählen Sie die Verbindung aus der Liste aus. Der Fehler wird nach der Auswahl der Verbindung behoben und der Durchfluss funktioniert einwandfrei.

