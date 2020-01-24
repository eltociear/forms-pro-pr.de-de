---
title: Einbetten einer Umfrage in Power Apps | MicrosoftDocs
description: Anleitungen zum Einbetten von Umfragen in Power Apps
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
ms.openlocfilehash: 19c4dfc0548d3a2d673a4d43d383de40aaa7da90
ms.sourcegitcommit: 2b2ffca387514568ff95dd1e566ba1850a416744
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2019
ms.locfileid: "2900513"
---
# <a name="embed-a-survey-in-power-apps"></a>Einbetten einer Umfrage in Power Apps

[!include[cc-beta-prerelease-disclaimer](includes/cc-beta-prerelease-disclaimer.md)]

Sie können Ihre Umfragen in die Canvas-Apps einbetten, indem Sie Power Apps verwenden. Dies ermöglicht es Benutzern, auf die Umfragen direkt von den Apps aus zu reagieren.

> [!NOTE]
> Sie müssen Power Apps Plan 1 haben, um Ihre Umfragen in einer Canvas-App einzubetten. Weitere Informationen zum Erwerben von Power Apps finden Sie unter [Kaufen von Power Apps für Ihre Organisation](https://docs.microsoft.com/power-platform/admin/signup-for-powerapps-admin).

1.  Melden Sie sich bei [Power Apps](https://web.powerapps.com/) an.

2.  Erstellen Sie eine leere Canvas-App oder verwenden Sie eine der verfügbaren Vorlagen. Weitere Informationen über das Erstellen einer Canvas-App finden Sie unter [Erstellen einer Canvas-App von Grund auf mithilfe von Common Data Service](https://docs.microsoft.com/powerapps/maker/canvas-apps/data-platform-create-app-scratch).

3.  Öffnen Sie auf der Registerkarte **Einfügen** das Menü **Steuerelemente**, und fügen Sie dann das Steuerelement **Forms Pro-Umfrage (Vorschau)** hinzu.

    > [!div class=mx-imgBorder]
    > ![Das Forms Pro-Umfrage (Vorschau)-Steuerelement hinzufügen](media/insert-control.png "Das Forms Pro-Umfrage (Vorschau)-Steuerelement hinzufügen")  

4.  Wählen Sie im Optionsbereich **Keine Daten** aus.

    > [!div class=mx-imgBorder]
    > ![Optionsbereich](media/options-pane.png "Optionsbereich")  

5.  Wählen Sie im Bereich **Daten** die Umfrage aus, die Sie aus der Liste **Umfrage auswählen** einbetten möchten.

    > [!div class=mx-imgBorder]
    > ![Umfrage im Datenbereich auswählen](media/data-pane.png "Eine Umfrage im Bereich „Daten“ auswählen")

    Die ausgewählte Umfrage wird im Steuerelement gerendert.

    > [!div class=mx-imgBorder]
    > ![Umfrage im Steuerelement gerendert](media/survey-render.png "Umfrage im Steuerelement gerendert")

6.  Um die Kontextparameter zu definieren, gehen Sie zur Registerkarte **Erweitert** im Optionsbereich.

7.  Im Feld **ContextParameters** geben Sie Kontextparameter als durch Komma getrennte Schlüssel-/Wert-Paare ein. Zum Beispiel: `{Name:TextInput1.Text,Email:TextInput2.Text, PageTitle:Label1.Text}`.
    Sie verwenden Kontextparameter, um die Informationen Ihrer antwortenden Seite und den Kontext, in dem die Antwort gegeben wurde, zu erfassen und diese Daten in der Umfrageantwort zu speichern.

    > [!div class=mx-imgBorder]
    > ![Kontextparameter hinzufügen](media/context-param.png "Kontextparameter hinzufügen")

    Wenn eine Antwort Kontextparameter enthält, werden diese auf der Registerkarte **Personalisierte Daten** angezeigt.

    > [!div class=mx-imgBorder]
    > ![Kontextparameter in einer Umfrageantwort](media/context-param-powerapps.png "Kontextparameter in einer Umfrageantwort")

### <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage per E-Mail](send-survey-email.md)<br>
[Senden Sie eine Umfrage mit Power Automate](send-survey-microsoft-flow.md)<br>
[Eine Umfrage in einer Webseite einbetten](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Erstellen Sie eine Umfrageeinladung](create-survey-invite.md)
