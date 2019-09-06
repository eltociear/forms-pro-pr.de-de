---
title: Fehlerbehebung | MicrosoftDocs
description: Erfahren Sie, wie Sie Probleme in Microsoft Forms Pro beheben können.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 08/06/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 97526FE3-7523-48B0-A8F4-7C369AF78DB4
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 39d559a1255b59cd22a37816ec2b2402f92b3c2c
ms.sourcegitcommit: e3e7192edb3753060a20a4dec47eb98faf1b87a3
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/06/2019
ms.locfileid: "1864012"
---
# <a name="troubleshoot-issues-in-forms-pro"></a>Fehlerbehebung bei Problemen in Forms-Prozessen

Dieser Artikel enthält Informationen zur Fehlerbehebung in der Lösung Microsoft Forms Pro.

## <a name="environment-provisioning-failure"></a>Fehler bei der Umgebungsbereitstellung

Wenn Sie einen Fehler erhalten, der besagt, dass Ihre Umgebungsbereitstellung fehlgeschlagen ist, müssen Sie die von Ihnen verwendete Version von Common Data Service überprüfen. Forms Pro funktioniert nicht mit der Vorgängerversion von Common Data Service. Wenn Ihre Standardumgebung mit der vorherigen Version von Common Data Service erstellt wurde, wird Ihre Umgebung nicht bereitgestellt und es wird eine Fehlermeldung angezeigt.  Sie müssen die vorherige Version von Common Data Service auf die neuere Version von Common Data Service für Apps aktualisieren. Weitere Informationen zum Upgrade auf Common Data Service für Apps finden Sie unter [Upgrade auf Common Data Service für Apps](https://docs.microsoft.com/common-data-service/upgradecds/introduction-upgrade-cds).

Um Ihre Common Data Service von der Vorgängerversion auf die neuere Version zu löschen oder zu aktualisieren, wenden Sie sich an Ihren globalen Administrator. 

Wenn die Bereitstellung Ihrer Umgebung fehlgeschlagen ist, wird die Bereitstellung regelmäßig erneut getestet. Wenn Sie eine andere Anfrage priorisieren oder übermitteln möchten, wenden Sie sich bitte an den Microsoft Support.

Wenn Sie die Common Data Service aktualisiert haben und Ihre Umgebungserstellung immer noch Probleme aufweist, wenden Sie sich bitte an den Microsot Support.

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

## <a name="error-while-setting-up-a-user-in-default-environment"></a>Fehler beim Installieren eines Benutzers in der Standardumgebung

Wenn Sie sich in der Microsoft Forms Pro Standardumgebung anmelden, werden Sicherheitsrollen Ihnen zugewiesen. Wenn ein Fehler bei der Rollenzuweisung auftritt, kontrollieren Sie, ob sie unter eine der folgenden Kategorien fallen, um den Fehler zu beheben:

|Fehler|Auflösung|
|-----|----------|
|Benutzer hat keine Lizenz|Weisen Sie dem Benutzer in Active Directory einen entsprechenden Lizenz zu.|
|Benutzer ist Bestandteil der Sicherheitsgruppe|Fügen Sie den Benutzer auf der Instanz der Sicherheitsgruppe hinzu.|
|Benutzer wird in Active Directory erstellt|Erstellen Sie den Benutzer in Active Directory.|
|Benutzer wird in Active Directory nicht aktiviert|Benutzer in Active Directory aktivieren.|
|Die Instanz wurde nicht gefunden.|Instanzdetails sind ungültig oder Instanz ist elöscht.|
|Instanz ist nicht aktiv.|Instanz wird deaktiviert. Aktivieren Sie die Instanz und versuchen Sie es erneut.|
|||

> [!NOTE]
> Die obigen Fehler werden nur für die Standardumgebung angezeigt. Wenn Sie in einer anderen Umgebung als die Standardumgebung arbeiten, setzten Sie sich mit dem Administrator in Verbindung, um die Rollen entsprechend zuzuweisen. Weitere Informationen: [Arbeiten mit Umgebungen](choose-environment.md)

Wenn Sie den Fehler nicht beheben können, kontaktieren Sie bitte den Microsoft Support.

## <a name="azure-active-directory-disabled-error"></a>Azure Active Directory deaktivierte Fehler

Wenn Sie einen Fehler erhalten, der angibt, dass Azure Active Directory deaktiviert ist, müssen Sie sicherstellen, dass:

- Die Dynamics CRM Online App wird auf dem Mandanten deaktiviert.
- Eine neue App wird mit einer https://admin.service.crm4.dynamics.com Zielgruppe aktiviert, die deaktiviert ist und Azure Active Directory gibt die Präferenzen an die App, statt an die App der ersten Partei Microsoft.

Wenn eine neue App erstellt wird, müssen Sie die App  entfernen oder die Zielgruppe ändern. Wenn das nicht der Fall ist, müssen Sie sich an Ihren Mandantenadministrator wenden, um die nachfolgenden Skripts auszuführen, um die Dynamics CRM Online  App im Mandant zu erneuern. Damit sollte der Fehler behoben sein. 

1. Sie müssen das AzureAD-Modul herunterladen von: [Azure Active Directory PowerShell für Graph](https://docs.microsoft.com/en-us/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)

2. Führen Sie die folgenden Befehle in einem PowerShell Fenster aus (PowerShell als Administrator ausführen). Folgen Sie der Aufforderung, melden Sie sich mit den Mandantenadministrator-Anmeldeinformationen an.
    ```
    Install-Module AzureAD
    Connect-AzureAD
    $sp = Get-AzureADServicePrincipal -Filter "AppId eq '00000007-0000-0000-c000-000000000000'"
    Set-AzureADServicePrincipal -ObjectId $sp.ObjectId -AccountEnabled $True
    ```

3. Wenn Sie den Fehler nicht finden, wenn die oben Befehle durchgeführt wurden, oder die oben genannten Befehle eine Fehlermeldung auslösen, führen Sie die folgenden Befehle aus, um den Prinzipal des Mandanten zurückzusetzen, um sicherzustellen, dass er in einem entsprechenden Status ist.
    ```
    $appId = "00000007-0000-0000-c000-000000000000"
    Get-AzureADServicePrincipal -Filter "AppId eq '00000007-0000-0000-c000-000000000000'" | Remove-AzureADServicePrincipal
    New-AzureADServicePrincipal -AppId $appId
    ```


