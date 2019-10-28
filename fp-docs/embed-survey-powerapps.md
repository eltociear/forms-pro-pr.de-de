---
title: Einbetten einer Umfrage in PowerApps | MicrosoftDocs
description: Anleitungen zum Einbetten von Umfragen in PowerApps
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 08/19/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: F5543364-ADB8-465D-96A6-81B2C840299F
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 8a39b5afcb22ea0e344e15ef5f9a7666b9ef9177
ms.sourcegitcommit: fcdae207b37e42a145f95afa07ea26e99842aacd
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/19/2019
ms.locfileid: "1887326"
---
# <a name="embed-a-survey-in-powerapps"></a>Einbetten einer Umfrage in PowerApps

[!include[cc-beta-prerelease-disclaimer](includes/cc-beta-prerelease-disclaimer.md)]

Sie können Ihre Umfragen in den Canvas-Apps einbetten, die mithilfe von PowerApps erstellt sind. Dies ermöglicht es Benutzern, auf die Umfragen direkt von den Apps aus zu reagieren.

> [!NOTE]
> Sie müssen PowerApps Plan 1 haben, um Ihre Umfragen in einer Canvas-App einzubetten. Weitere Informationen zum Erwerben von PowerApps finden Sie unter [Kaufen von PowerApps für Ihre Organisation](https://docs.microsoft.com/en-us/power-platform/admin/signup-for-powerapps-admin).

1.  Melden Sie sich bei [PowerApps](https://web.powerapps.com/) an.

2.  Erstellen Sie eine leere Canvas-App oder verwenden Sie eine der verfügbaren Vorlagen. Weitere Informationen zum Erstellen einer Canvas-App finden Sie unter [Erstellen einer Canvas-App von Grund auf mithilfe von Common Data Service](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/data-platform-create-app-scratch).

3.  Öffnen Sie auf der Registerkarte **Einfügen** das Menü **Steuerelemente**, und fügen Sie dann das Steuerelement **Forms Pro-Umfrage (Vorschau)** hinzu.

    > [!div class=mx-imgBorder]
    > ![Das Steuerelement „Forms Pro-Umfrage (Vorschau)” hinzufügen](media/insert-control.png "Das Steuerelement „Forms Pro-Umfrage (Vorschau)” hinzufügen")  

4.  Wählen Sie im Optionsbereich **Keine Daten** aus.

    > [!div class=mx-imgBorder]
    > ![Optionsbereich](media/options-pane.png "Optionsbereich")  

5.  Wählen Sie im Bereich **Daten** die Umfrage aus, die Sie aus der Liste **Umfrage auswählen** einbetten möchten.

    > [!div class=mx-imgBorder]
    > ![Wählen Sie im Datenbereich Umfrage aus](media/data-pane.png "Wählen Sie im Datenbereich Umfrage aus") 

    Die ausgewählte Umfrage wird im Steuerelement gerendert.

    > [!div class=mx-imgBorder]
    > ![Im Steuerelement gerenderte Umfrage](media/survey-render.png "Im Steuerelement gerenderte Umfrage") 

6.  Um die Kontextparameter zu definieren, gehen Sie zur Registerkarte **Erweitert** im Optionsbereich.

7.  Im Feld **ContextParameters** geben Sie Kontextparameter als durch Komma getrennte Schlüssel-/Wert-Paare ein. Zum Beispiel: `{Name:TextInput1.Text,Email:TextInput2.Text, PageTitle:Label1.Text}`. 
    Kontextparameter ermöglichen es Ihnen, die Informationen Ihrer antwortenden Seite und den Kontext, in dem die Antwort gegeben wurde, zu erfassen und diese Daten in der Umfrageantwort zu speichern. 

    > [!div class=mx-imgBorder]
    > ![Kontextparameter hinzufügen](media/context-param.png "Kontextparameter hinzufügen")

    Wenn eine Antwort Kontextparameter enthält, werden diese auf der Registerkarte **Personalisierte Daten** angezeigt. 

    > [!div class=mx-imgBorder]
    > ![Kontextparameter in einer Umfrageantwort](media/context-param-powerapps.png "Kontextparameter in einer Umfrageantwort") 

## <a name="see-also"></a>Siehe auch

[Definieren Sie, wer an einer Umfrage teilnehmen darf](invite-settings.md)<br>
[Senden Sie eine Umfrage per E-Mail](send-survey-email.md)<br>
[Senden Sie eine Umfrage mit Microsoft Flow](send-survey-microsoft-flow.md)<br>
[Eingebettete Umfrage in eine Webseite](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Erstellen Sie eine Umfrageeinladung](create-survey-invite.md)
