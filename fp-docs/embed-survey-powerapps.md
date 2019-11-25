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
ms.openlocfilehash: 89269b799da8276a3f66d87774654e4fd0113e49
ms.sourcegitcommit: 3225337823216f21b569779b829f069f53aa3742
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/04/2019
ms.locfileid: "2751194"
---
# <a name="embed-a-survey-in-powerapps"></a><span data-ttu-id="40847-103">Einbetten einer Umfrage in PowerApps</span><span class="sxs-lookup"><span data-stu-id="40847-103">Embed a survey in PowerApps</span></span>

[!include[cc-beta-prerelease-disclaimer](includes/cc-beta-prerelease-disclaimer.md)]

<span data-ttu-id="40847-104">Sie können Ihre Umfragen in den Canvas-Apps einbetten, die mithilfe von PowerApps erstellt sind.</span><span class="sxs-lookup"><span data-stu-id="40847-104">You can embed your surveys in the canvas apps created using PowerApps.</span></span> <span data-ttu-id="40847-105">Dies ermöglicht es Benutzern, auf die Umfragen direkt von den Apps aus zu reagieren.</span><span class="sxs-lookup"><span data-stu-id="40847-105">This allows users to respond to the surveys directly from the apps.</span></span>

> [!NOTE]
> <span data-ttu-id="40847-106">Sie müssen PowerApps Plan 1 haben, um Ihre Umfragen in einer Canvas-App einzubetten.</span><span class="sxs-lookup"><span data-stu-id="40847-106">You must have PowerApps Plan 1 to embed your surveys in a canvas app.</span></span> <span data-ttu-id="40847-107">Weitere Informationen zum Erwerben von PowerApps finden Sie unter [Kaufen von PowerApps für Ihre Organisation](https://docs.microsoft.com/power-platform/admin/signup-for-powerapps-admin).</span><span class="sxs-lookup"><span data-stu-id="40847-107">For more information on purchasing PowerApps, see [Purchase PowerApps for your organization](https://docs.microsoft.com/power-platform/admin/signup-for-powerapps-admin).</span></span>

1.  <span data-ttu-id="40847-108">Melden Sie sich bei [PowerApps](https://web.powerapps.com/) an.</span><span class="sxs-lookup"><span data-stu-id="40847-108">Sign in to [PowerApps](https://web.powerapps.com/).</span></span>

2.  <span data-ttu-id="40847-109">Erstellen Sie eine leere Canvas-App oder verwenden Sie eine der verfügbaren Vorlagen.</span><span class="sxs-lookup"><span data-stu-id="40847-109">Create a blank canvas app or use one of the available templates.</span></span> <span data-ttu-id="40847-110">Weitere Informationen zum Erstellen einer Canvas-App finden Sie unter [Erstellen einer Canvas-App von Grund auf mithilfe von Common Data Service](https://docs.microsoft.com/powerapps/maker/canvas-apps/data-platform-create-app-scratch).</span><span class="sxs-lookup"><span data-stu-id="40847-110">For more information on creating a canvas app, see [Create a canvas app from scratch using Common Data Service](https://docs.microsoft.com/powerapps/maker/canvas-apps/data-platform-create-app-scratch).</span></span>

3.  <span data-ttu-id="40847-111">Öffnen Sie auf der Registerkarte **Einfügen** das Menü **Steuerelemente**, und fügen Sie dann das Steuerelement **Forms Pro-Umfrage (Vorschau)** hinzu.</span><span class="sxs-lookup"><span data-stu-id="40847-111">On the **Insert** tab, open the **Controls** menu and then add the **Forms Pro survey (Preview)** control.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="40847-112">![Das Forms Pro-Umfrage (Vorschau)-Steuerelement hinzufügen](media/insert-control.png "Das Forms Pro-Umfrage (Vorschau)-Steuerelement hinzufügen")</span><span class="sxs-lookup"><span data-stu-id="40847-112">![Add the Forms Pro survey (Preview) control](media/insert-control.png "Add the Forms Pro survey (Preview) control")</span></span>  

4.  <span data-ttu-id="40847-113">Wählen Sie im Optionsbereich **Keine Daten** aus.</span><span class="sxs-lookup"><span data-stu-id="40847-113">In the options pane, select **No data**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="40847-114">![Optionsbereich](media/options-pane.png "Optionsbereich")</span><span class="sxs-lookup"><span data-stu-id="40847-114">![Options pane](media/options-pane.png "Options pane")</span></span>  

5.  <span data-ttu-id="40847-115">Wählen Sie im Bereich **Daten** die Umfrage aus, die Sie aus der Liste **Umfrage auswählen** einbetten möchten.</span><span class="sxs-lookup"><span data-stu-id="40847-115">In the **Data** pane, select the survey you want to embed from the **Select survey** list.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="40847-116">![Umfrage im Datenbereich auswählen](media/data-pane.png "Umfrage im Datenbereich auswählen")</span><span class="sxs-lookup"><span data-stu-id="40847-116">![Select survey in the Data pane](media/data-pane.png "Select survey in the Data pane")</span></span> 

    <span data-ttu-id="40847-117">Die ausgewählte Umfrage wird im Steuerelement gerendert.</span><span class="sxs-lookup"><span data-stu-id="40847-117">The selected survey is rendered in the control.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="40847-118">![Umfrage im Steuerelement gerendert](media/survey-render.png "Umfrage im Steuerelement gerendert")</span><span class="sxs-lookup"><span data-stu-id="40847-118">![Survey rendered in the control](media/survey-render.png "Survey rendered in the control")</span></span> 

6.  <span data-ttu-id="40847-119">Um die Kontextparameter zu definieren, gehen Sie zur Registerkarte **Erweitert** im Optionsbereich.</span><span class="sxs-lookup"><span data-stu-id="40847-119">To define context parameters, go to the **Advanced** tab in the options pane.</span></span>

7.  <span data-ttu-id="40847-120">Im Feld **ContextParameters** geben Sie Kontextparameter als durch Komma getrennte Schlüssel-/Wert-Paare ein.</span><span class="sxs-lookup"><span data-stu-id="40847-120">In the **ContextParameters** field, enter context parameters as comma-separated key/value pairs.</span></span> <span data-ttu-id="40847-121">Zum Beispiel: `{Name:TextInput1.Text,Email:TextInput2.Text, PageTitle:Label1.Text}`.</span><span class="sxs-lookup"><span data-stu-id="40847-121">For example, `{Name:TextInput1.Text,Email:TextInput2.Text, PageTitle:Label1.Text}`.</span></span> 
    <span data-ttu-id="40847-122">Kontextparameter ermöglichen es Ihnen, die Informationen Ihrer antwortenden Seite und den Kontext, in dem die Antwort gegeben wurde, zu erfassen und diese Daten in der Umfrageantwort zu speichern.</span><span class="sxs-lookup"><span data-stu-id="40847-122">Context parameters allow you to capture your respondent's information and the context in which the response was provided and store that data in the survey response.</span></span> 

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="40847-123">![Kontextparameter hinzufügen](media/context-param.png "Kontextparameter hinzufügen")</span><span class="sxs-lookup"><span data-stu-id="40847-123">![Add context parameters](media/context-param.png "Add context parameters")</span></span>

    <span data-ttu-id="40847-124">Wenn eine Antwort Kontextparameter enthält, werden diese auf der Registerkarte **Personalisierte Daten** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="40847-124">If a response contains context parameters, they are displayed on the **Personalized data** tab.</span></span> 

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="40847-125">![Kontextparameter in einer Umfrageantwort](media/context-param-powerapps.png "Kontextparameter in einer Umfrageantwort")</span><span class="sxs-lookup"><span data-stu-id="40847-125">![Context parameters in a survey response](media/context-param-powerapps.png "Context parameters in a survey response")</span></span> 

## <a name="see-also"></a><span data-ttu-id="40847-126">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="40847-126">See also</span></span>

[<span data-ttu-id="40847-127">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="40847-127">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="40847-128">Senden Sie eine Umfrage per E-Mail</span><span class="sxs-lookup"><span data-stu-id="40847-128">Send a survey by using email</span></span>](send-survey-email.md)<br>
[<span data-ttu-id="40847-129">Senden Sie eine Umfrage mit Microsoft Flow</span><span class="sxs-lookup"><span data-stu-id="40847-129">Send a survey by using Microsoft Flow</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="40847-130">Eingebettete Umfrage in eine Webseite</span><span class="sxs-lookup"><span data-stu-id="40847-130">Embed survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="40847-131">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="40847-131">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="40847-132">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="40847-132">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="40847-133">Erstellen Sie eine Umfrageeinladung</span><span class="sxs-lookup"><span data-stu-id="40847-133">Create a survey invitation</span></span>](create-survey-invite.md)
