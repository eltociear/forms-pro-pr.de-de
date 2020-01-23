---
title: Erstellen einer Umfrageeinladung mit Power Automate | MicrosoftDocs
description: Anleitung zur Erstellung einer Umfrageeinladung mit Power Automate.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/04/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 8579EFA2-7734-4516-ACFA-F65999983379
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: d4d2b2fe06213418892f33dcb70add4a8df36433
ms.sourcegitcommit: 2b2ffca387514568ff95dd1e566ba1850a416744
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2019
ms.locfileid: "2900285"
---
# <a name="create-a-survey-invitation"></a><span data-ttu-id="d1228-103">Erstellen einer Umfrageeinladung</span><span class="sxs-lookup"><span data-stu-id="d1228-103">Create a survey invitation</span></span>

<span data-ttu-id="d1228-104">Wenn Sie eine Umfrage über eine andere Plattform als Microsoft Forms Pro senden möchten – z. B. Outlook, Gmail oder SMS – können Sie mit Power Automate eine Umfrageeinladung erstellen.</span><span class="sxs-lookup"><span data-stu-id="d1228-104">If you want to send a survey by using a platform other than Microsoft Forms Pro&mdash;such as Outlook, Gmail, or SMS&mdash;you can create a survey invitation by using Power Automate.</span></span> <span data-ttu-id="d1228-105">Die Umfrageeinladung erstellt einen personalisierten Link, der über die Plattform Ihrer Wahl verteilt werden kann.</span><span class="sxs-lookup"><span data-stu-id="d1228-105">The survey invitation creates a personalized link that can be distributed by using the platform of your choice.</span></span>

1. <span data-ttu-id="d1228-106">Melden Sie sich bei [flow.microsoft.com](https://flow.microsoft.com) an.</span><span class="sxs-lookup"><span data-stu-id="d1228-106">Sign in to [flow.microsoft.com](https://flow.microsoft.com).</span></span>

2. <span data-ttu-id="d1228-107">Beginnen Sie, einen Flow von Grund auf neu zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="d1228-107">Start to create a flow from scratch.</span></span> <span data-ttu-id="d1228-108">Weitere Informationen: [Erstellen eines Flows in Power Automate](https://docs.microsoft.com/flow/get-started-logic-flow)</span><span class="sxs-lookup"><span data-stu-id="d1228-108">More information: [Create a flow in Power Automate](https://docs.microsoft.com/flow/get-started-logic-flow)</span></span>

3. <span data-ttu-id="d1228-109">Fügen Sie im Flow-Editor einen Trigger hinzu, um Ihren Flow zu starten.</span><span class="sxs-lookup"><span data-stu-id="d1228-109">In the flow editor, add a trigger to start your flow.</span></span>

4. <span data-ttu-id="d1228-110">Nachdem Sie den Trigger hinzugefügt haben, fügen Sie einen neuen Schritt hinzu und suchen Sie nach dem Connector **Microsoft Forms Pro**.</span><span class="sxs-lookup"><span data-stu-id="d1228-110">After adding the trigger, add a new step and search for the **Microsoft Forms Pro** connector.</span></span>

5. <span data-ttu-id="d1228-111">Wählen Sie in den Suchergebnissen **Microsoft Forms Pro**.</span><span class="sxs-lookup"><span data-stu-id="d1228-111">In search results, select **Microsoft Forms Pro**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="d1228-112">![Auswählen von Microsoft Forms Pro-Connector](media/search-connector.png "Auswählen von Microsoft Forms Pro-Connector")</span><span class="sxs-lookup"><span data-stu-id="d1228-112">![Select Microsoft Forms Pro connector](media/search-connector.png "Select Microsoft Forms Pro connector")</span></span>  

6. <span data-ttu-id="d1228-113">Wählen Sie die Aktion **Eine Einladung erstellen (Vorschau)**.</span><span class="sxs-lookup"><span data-stu-id="d1228-113">Select the **Create an invitation (preview)** action.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="d1228-114">![Wählen Sie die Aktion „Eine Einladung erstellen (Vorschau)“ aus](media/select-flow-action.png "Wählen Sie die Aktion „Eine Einladung erstellen (Vorschau)“ aus")</span><span class="sxs-lookup"><span data-stu-id="d1228-114">![Select Create an invitation (preview) action](media/select-flow-action.png "Select Create an invitation (preview) action")</span></span>  

7. <span data-ttu-id="d1228-115">Geben Sie in der Aktion **Eine Einladung erstellen** die folgenden Informationen ein oder wählen Sie sie aus:</span><span class="sxs-lookup"><span data-stu-id="d1228-115">In the **Create an invitation** action, enter or select the following information:</span></span>

    - <span data-ttu-id="d1228-116">**Umfrage**: Wählen Sie die zu sendende Umfrage aus.</span><span class="sxs-lookup"><span data-stu-id="d1228-116">**Survey**: Select the survey to be sent.</span></span>
    - <span data-ttu-id="d1228-117">**E-Mail**: Geben Sie die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="d1228-117">**Email**: Enter the recipient's email address.</span></span>
    - <span data-ttu-id="d1228-118">**Betreff**: Geben Sie einen Datensatz an, um die Umfrageeinladung und -antwort einander zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="d1228-118">**Regarding**: Specify a record to associate the survey invitation and response.</span></span> <span data-ttu-id="d1228-119">Dieser Wert wird in der Umfrageeinladung im Feld **Betreff** gespeichert.</span><span class="sxs-lookup"><span data-stu-id="d1228-119">This value is stored in the survey invitation's **Regarding** field.</span></span>
    - <span data-ttu-id="d1228-120">**Empfängerdetails**: Geben Sie einen Kontakt an, um Ihre Umfrageeinladungs- und Antwortdatensätze einander zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="d1228-120">**Recipient details**: Specify a contact to associate your survey invitation and response records with.</span></span> <span data-ttu-id="d1228-121">Dieser Wert wird im Feld **An** der Umfrageeinladung gespeichert.</span><span class="sxs-lookup"><span data-stu-id="d1228-121">This value is stored in the survey invitation's **To** field.</span></span> <span data-ttu-id="d1228-122">In diesem Feld wird nur der Kontaktdatensatz unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d1228-122">Only a Contact record is supported in this field.</span></span>

    > [!NOTE]
    > - <span data-ttu-id="d1228-123">Wenn Sie Ihre Umfrageeinladung und -antwort mit Common Data Service verknüpfen möchten, müssen Sie in den Feldern **Betreff** und **Empfängerdetails** entsprechend Werte eingeben.</span><span class="sxs-lookup"><span data-stu-id="d1228-123">If you want to associate your survey invitation and response with Common Data Service, you must enter values in **Regarding** and **Recipient details** fields, respectively.</span></span> <span data-ttu-id="d1228-124">Weitere Informationen zu den Feldern **Betreff** und **Empfängerdetails** und wie sie in der Umfrageeinladung gespeichert sind, finden Sie unter [Senden einer Umfrageaktion](send-survey-microsoft-flow.md#send-a-survey-action).</span><span class="sxs-lookup"><span data-stu-id="d1228-124">For more information about **Regarding** and **Recipient details** fields and how they're stored in the survey invitation, see [Send a survey action](send-survey-microsoft-flow.md#send-a-survey-action).</span></span>
    > - <span data-ttu-id="d1228-125">Wenn Sie in Ihrer Umfrage Umfragevariablen verwendet haben, sind sie in dieser Aktion sichtbar und Sie können die Werte entsprechend angeben.</span><span class="sxs-lookup"><span data-stu-id="d1228-125">If you've used survey variables in your survey, they'll be visible in this action and you can specify the values accordingly.</span></span> <span data-ttu-id="d1228-126">Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)</span><span class="sxs-lookup"><span data-stu-id="d1228-126">More information: [Specify values in a flow](personalize-survey.md#specify-values-in-a-flow)</span></span>

8. <span data-ttu-id="d1228-127">Fügen Sie einen neuen Schritt hinzu und wählen Sie dann die Aktion zum Senden der E-Mail aus.</span><span class="sxs-lookup"><span data-stu-id="d1228-127">Add a new step, and then select the action to send the email.</span></span> <span data-ttu-id="d1228-128">Sie können Anbieter wie Outlook, Gmail oder SMS verwenden; wir haben Outlook verwendet, um die Umfrage in dieser Prozedur zu senden.</span><span class="sxs-lookup"><span data-stu-id="d1228-128">You can use providers such as Outlook, Gmail, or SMS; we've used Outlook to send the survey in this procedure.</span></span>

9. <span data-ttu-id="d1228-129">Geben Sie in der Aktion **Eine E-Mail senden** die folgenden Informationen ein:</span><span class="sxs-lookup"><span data-stu-id="d1228-129">In the **Send an email** action, enter the following information:</span></span>

    - <span data-ttu-id="d1228-130">**An**: E-Mail-Adresse des Empfängers.</span><span class="sxs-lookup"><span data-stu-id="d1228-130">**To**: Recipient's email address.</span></span>
    - <span data-ttu-id="d1228-131">**Betreff**: Betreff der E-Mail.</span><span class="sxs-lookup"><span data-stu-id="d1228-131">**Subject**: Subject of the email.</span></span>
    - <span data-ttu-id="d1228-132">**Body**: Geben Sie den gewünschten Text ein und fügen Sie **Einladungslink** dynamische Inhalte hinzu.</span><span class="sxs-lookup"><span data-stu-id="d1228-132">**Body**: Enter the required text and add **Invitation link** dynamic content.</span></span>

    <span data-ttu-id="d1228-133">Nach Eingabe der erforderlichen Angaben sieht der Fluss wie in der folgenden Abbildung dargestellt aus:</span><span class="sxs-lookup"><span data-stu-id="d1228-133">After entering the required details, the flow looks as shown in the following image:</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="d1228-134">![Umfrageeinladungsflow](media/survey-invite-flow.png "Umfrageeinladungsflow")</span><span class="sxs-lookup"><span data-stu-id="d1228-134">![Survey invitation flow](media/survey-invite-flow.png "Survey invitation flow")</span></span>

    <span data-ttu-id="d1228-135">Der Flow läuft gemäß dem konfigurierten Trigger ab und sendet dann die Umfrage.</span><span class="sxs-lookup"><span data-stu-id="d1228-135">The flow runs as per the configured trigger, and then sends the survey.</span></span>

### <a name="see-also"></a><span data-ttu-id="d1228-136">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="d1228-136">See also</span></span>

[<span data-ttu-id="d1228-137">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="d1228-137">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="d1228-138">Senden Sie eine Umfrage per E-Mail</span><span class="sxs-lookup"><span data-stu-id="d1228-138">Send a survey by using email</span></span>](send-survey-email.md)<br>
[<span data-ttu-id="d1228-139">Senden Sie eine Umfrage mit Power Automate</span><span class="sxs-lookup"><span data-stu-id="d1228-139">Send a survey by using Power Automate</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="d1228-140">Eine Umfrage in einer Webseite einbetten</span><span class="sxs-lookup"><span data-stu-id="d1228-140">Embed a survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="d1228-141">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="d1228-141">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="d1228-142">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="d1228-142">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="d1228-143">Einbetten einer Umfrage in Power Apps</span><span class="sxs-lookup"><span data-stu-id="d1228-143">Embed a survey in Power Apps</span></span>](embed-survey-powerapps.md)


