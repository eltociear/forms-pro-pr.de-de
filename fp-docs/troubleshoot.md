---
title: Fehlerbehebung | MicrosoftDocs
description: Erfahren Sie, wie Sie Probleme in Microsoft Forms Pro beheben können.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 12/07/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 97526FE3-7523-48B0-A8F4-7C369AF78DB4
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 641b879f19fffaf993b53a3b938bdf06db980700
ms.sourcegitcommit: 2b2ffca387514568ff95dd1e566ba1850a416744
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2019
ms.locfileid: "2901217"
---
# <a name="troubleshoot-issues-in-forms-pro"></a>Beheben von Problemen in Forms Pro

Dieser Artikel enthält Informationen zur Problembehandlung in Microsoft Forms Pro.

## <a name="environment-provisioning-failure"></a>Fehler bei der Umgebungsbereitstellung

Sollten Sie einen Fehler erhalten, der besagt, dass Ihre Umgebungsbereitstellung fehlgeschlagen ist, müssen Sie die von Ihnen verwendete Version von Common Data Service überprüfen. Forms Pro funktioniert nicht mit der Vorgängerversion. Wenn Ihre Standardumgebung mit der vorherigen Version von Common Data Service erstellt wurde, wird Ihre Umgebung nicht bereitgestellt werden und es wird eine Fehlermeldung angezeigt. Sie müssen die vorherige Version von Common Data Service auf die neuere Version aktualisieren. Weitere Informationen zu Common Data Service finden Sie unter [Was ist Common Data Service](https://docs.microsoft.com/common-data-service/upgradecds/introduction-upgrade-cds).

Um Common Data Service von einer früheren Version auf die neuere Version zu löschen oder zu aktualisieren, wenden Sie sich an Ihren globalen Administrator.

Wenn die Bereitstellung Ihrer Umgebung fehlgeschlagen ist, wird die Bereitstellung regelmäßig erneut getestet. Wenn Sie Prioritäten setzen oder andere Anfragen stellen möchten, wenden Sie sich bitte an den Microsoft-Support.

Wenn Sie Common Data Service aktualisiert haben und Ihre Umgebungserstellung noch Probleme aufweist, wenden Sie sich bitte an den Microsoft Support.

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

## <a name="invalid-connection-error-in-a-flow"></a>Ungültiger Verbindungsfehler in einem Flow

Wenn Sie einen Fehler erhalten, der besagt, dass Ihre Verbindung ungültig ist oder es ein Problem mit dem Trigger des Flusses gibt, müssen Sie Folgendes tun:

1. Öffnen Sie Power Automate.

2. Wählen Sie im linken Bereich **Daten** > **Verbindungen**.

3. Suchen Sie nach der Verbindung **Microsoft Forms Pro** und löschen Sie sie.

    > [!NOTE]
    > Wenn Sie mehrere Verbindungen für Microsoft Forms Pro angelegt haben, müssen Sie diese alle löschen.

4. Wählen Sie **Neue Verbindung**, um eine neue Verbindung zu erstellen.

5. Suchen Sie in der Liste der Verbindungen nach **Microsoft Forms Pro** und wählen Sie sie aus.

6. Wählen Sie im Bestätigungsfenster **Erstellen**, und geben Sie dann Ihre Zugangsdaten ein.

7. Öffnen Sie den Fluss, in dem der Fehler aufgetreten ist.

8. Gehen Sie zu der Aktion, die den Fehler verursacht hat. Die von Ihnen erstellte Verbindung wird angezeigt.

9. Wählen Sie die Verbindung aus der Liste aus. Der Fehler wird nach der Auswahl der Verbindung behoben und der Flow funktioniert einwandfrei.

## <a name="error-while-setting-up-a-user-in-default-environment"></a>Fehler beim Installieren eines Benutzers in der Standardumgebung

Wenn Sie sich in der Microsoft Forms Pro Standardumgebung anmelden, werden Sicherheitsrollen Ihnen zugewiesen. Wenn ein Fehler bei der Rollenzuweisung auftritt, kontrollieren Sie, ob sie unter eine der folgenden Kategorien fallen, um den Fehler zu beheben.

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

Wenn Sie den Fehler nicht beheben können, wenden Sie sich bitte an den Microsoft-Support.

## <a name="azure-active-directory-disabled-error"></a>Azure Active Directory deaktivierte Fehler

Wenn Sie einen Fehler erhalten, der besagt, dass Azure Active Directory deaktiviert ist, müssen Sie überprüfen, ob:

- Die Dynamics CRM Online App wird auf dem Mandanten deaktiviert.
- Eine neue App wird mit einer „https://admin.service.crm4.dynamics.com” Zielgruppe erstellt, welche deaktiviert ist und Azure Active Directory bevorzugt diese App anstelle der First-Party-App von Microsoft.

Wenn eine neue App erstellt wird, müssen Sie die App entfernen oder die Zielgruppe ändern. Ist dies nicht der Fall, müssen Sie sich an Ihren Mandantenadministrator wenden, um das folgende Skript auszuführen, das die Dynamics CRM Online App im Mandanten wieder aktiviert und den Fehler beheben soll.

1. Laden Sie das AzureAD Module von [Azure Active Directory PowerShell für Graph](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0) herunter.

2. Führen Sie die folgenden Befehle in einem PowerShell Fenster aus (PowerShell als Administrator ausführen). Melden Sie sich bei Aufforderung mit den Anmeldedaten des Mandantenadministrators an.
    ```
    Install-Module AzureAD
    Connect-AzureAD
    $sp = Get-AzureADServicePrincipal -Filter "AppId eq '00000007-0000-0000-c000-000000000000'"
    Set-AzureADServicePrincipal -ObjectId $sp.ObjectId -AccountEnabled $True
    ```

3. Wenn Sie den Fehler nicht finden, wenn die oben Befehle durchgeführt wurden oder die oben genannten Befehle eine Fehlermeldung auslösen, führen Sie die folgenden Befehle aus, um den Prinzipal des Mandanten zurückzusetzen, um sicherzustellen, dass er in einem entsprechenden Status ist.
    ```
    $appId = "00000007-0000-0000-c000-000000000000"
    Get-AzureADServicePrincipal -Filter "AppId eq '00000007-0000-0000-c000-000000000000'" | Remove-AzureADServicePrincipal
    New-AzureADServicePrincipal -AppId $appId
    ```
