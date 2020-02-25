---
title: Erstellen einer Umfrageeinladung mit Power Automate | MicrosoftDocs
description: Anleitung zur Erstellung einer Umfrageeinladung mit Power Automate.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 01/16/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: 8579EFA2-7734-4516-ACFA-F65999983379
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 748fba463625ebde2b8a72548b74424f82c1f340
ms.sourcegitcommit: f99b529d74a96beb8121df5344f40479619875ea
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/16/2020
ms.locfileid: "2966178"
---
# <a name="create-a-survey-invitation"></a><span data-ttu-id="da2a4-103">Erstellen einer Umfrageeinladung</span><span class="sxs-lookup"><span data-stu-id="da2a4-103">Create a survey invitation</span></span>

<span data-ttu-id="da2a4-104">Wenn Sie eine Umfrage über eine andere Plattform als Microsoft Forms Pro&mdash;senden möchten – z. B. Outlook, Gmail oder SMS&mdash;können Sie mit Power Automate eine Umfrageeinladung erstellen.</span><span class="sxs-lookup"><span data-stu-id="da2a4-104">If you want to send a survey by using a platform other than Microsoft Forms Pro&mdash;such as Outlook, Gmail, or SMS&mdash;you can create a survey invitation by using Power Automate.</span></span> <span data-ttu-id="da2a4-105">Die Umfrageeinladung erstellt einen personalisierten Link, der über die Plattform Ihrer Wahl verteilt werden kann.</span><span class="sxs-lookup"><span data-stu-id="da2a4-105">The survey invitation creates a personalized link that can be distributed by using the platform of your choice.</span></span>

1. <span data-ttu-id="da2a4-106">Melden Sie sich bei [flow.microsoft.com](https://flow.microsoft.com) an.</span><span class="sxs-lookup"><span data-stu-id="da2a4-106">Sign in to [flow.microsoft.com](https://flow.microsoft.com).</span></span>

2. <span data-ttu-id="da2a4-107">Beginnen Sie, einen Flow von Grund auf neu zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="da2a4-107">Start to create a flow from scratch.</span></span> <span data-ttu-id="da2a4-108">Weitere Informationen: [Erstellen eines Flows in Power Automate](https://docs.microsoft.com/flow/get-started-logic-flow)</span><span class="sxs-lookup"><span data-stu-id="da2a4-108">More information: [Create a flow in Power Automate](https://docs.microsoft.com/flow/get-started-logic-flow)</span></span>

3. <span data-ttu-id="da2a4-109">Fügen Sie im Flow-Editor einen Trigger hinzu, um Ihren Flow zu starten.</span><span class="sxs-lookup"><span data-stu-id="da2a4-109">In the flow editor, add a trigger to start your flow.</span></span>

4. <span data-ttu-id="da2a4-110">Nachdem Sie den Trigger hinzugefügt haben, fügen Sie einen neuen Schritt hinzu und suchen Sie nach dem Connector **Microsoft Forms Pro**.</span><span class="sxs-lookup"><span data-stu-id="da2a4-110">After adding the trigger, add a new step and search for the **Microsoft Forms Pro** connector.</span></span>

5. <span data-ttu-id="da2a4-111">Wählen Sie in den Suchergebnissen **Microsoft Forms Pro**.</span><span class="sxs-lookup"><span data-stu-id="da2a4-111">In search results, select **Microsoft Forms Pro**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="da2a4-112">![Auswählen von Microsoft Forms Pro-Connector](media/search-connector.png "Aktivieren Sie den Microsoft Forms Pro Konnektor")</span><span class="sxs-lookup"><span data-stu-id="da2a4-112">![Select Microsoft Forms Pro connector](media/search-connector.png "Select the Microsoft Forms Pro connector")</span></span>  

6. <span data-ttu-id="da2a4-113">Wählen Sie die Aktion **Eine Einladung erstellen (Vorschau)**.</span><span class="sxs-lookup"><span data-stu-id="da2a4-113">Select the **Create an invitation (preview)** action.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="da2a4-114">![Wählen Sie die Aktion „Eine Einladung erstellen (Vorschau)“ aus](media/select-flow-action.png "Wählen Sie die Aktion „Eine Einladung erstellen (Vorschau)“ aus")</span><span class="sxs-lookup"><span data-stu-id="da2a4-114">![Select Create an invitation (preview) action](media/select-flow-action.png "Select Create an invitation (preview) action")</span></span>  

7. <span data-ttu-id="da2a4-115">Geben Sie in der Aktion **Eine Einladung erstellen** die folgenden Informationen ein oder wählen Sie sie aus:</span><span class="sxs-lookup"><span data-stu-id="da2a4-115">In the **Create an invitation** action, enter or select the following information:</span></span>

    - <span data-ttu-id="da2a4-116">**Umfrage**: Wählen Sie die zu sendende Umfrage aus.</span><span class="sxs-lookup"><span data-stu-id="da2a4-116">**Survey**: Select the survey to be sent.</span></span>
    - <span data-ttu-id="da2a4-117">**E-Mail**: Geben Sie die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="da2a4-117">**Email**: Enter the recipient's email address.</span></span>
    - <span data-ttu-id="da2a4-118">**Betreff**: Geben Sie einen Datensatz an, um die Umfrageeinladung und -antwort einander zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="da2a4-118">**Regarding**: Specify a record to associate the survey invitation and response.</span></span> <span data-ttu-id="da2a4-119">Dieser Wert wird in der Umfrageeinladung im Feld **Betreff** gespeichert.</span><span class="sxs-lookup"><span data-stu-id="da2a4-119">This value is stored in the survey invitation's **Regarding** field.</span></span>
    - <span data-ttu-id="da2a4-120">**Empfängerdetails**: Geben Sie einen Kontakt an, um Ihre Umfrageeinladungs- und Antwortdatensätze einander zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="da2a4-120">**Recipient details**: Specify a contact to associate your survey invitation and response records with.</span></span> <span data-ttu-id="da2a4-121">Dieser Wert wird im Feld **An** der Umfrageeinladung gespeichert.</span><span class="sxs-lookup"><span data-stu-id="da2a4-121">This value is stored in the survey invitation's **To** field.</span></span> <span data-ttu-id="da2a4-122">In diesem Feld wird nur der Kontaktdatensatz unterstützt.</span><span class="sxs-lookup"><span data-stu-id="da2a4-122">Only a Contact record is supported in this field.</span></span>

    > [!NOTE]
    > - <span data-ttu-id="da2a4-123">Wenn Sie Ihre Umfrageeinladung und -antwort mit Common Data Service verknüpfen möchten, müssen Sie in den Feldern **Betreff** und **Empfängerdetails** entsprechend Werte eingeben.</span><span class="sxs-lookup"><span data-stu-id="da2a4-123">If you want to associate your survey invitation and response with Common Data Service, you must enter values in **Regarding** and **Recipient details** fields, respectively.</span></span> <span data-ttu-id="da2a4-124">Weitere Informationen zu den Feldern **Betreff** und **Empfängerdetails** und wie sie in der Umfrageeinladung gespeichert sind, finden Sie unter [Senden einer Umfrageaktion](send-survey-flow.md#send-a-survey-action).</span><span class="sxs-lookup"><span data-stu-id="da2a4-124">For more information about **Regarding** and **Recipient details** fields and how they're stored in the survey invitation, see [Send a survey action](send-survey-flow.md#send-a-survey-action).</span></span>
    > - <span data-ttu-id="da2a4-125">Wenn Sie in Ihrer Umfrage Umfragevariablen verwendet haben, sind sie in dieser Aktion sichtbar und Sie können die Werte entsprechend angeben.</span><span class="sxs-lookup"><span data-stu-id="da2a4-125">If you've used survey variables in your survey, they'll be visible in this action and you can specify the values accordingly.</span></span> <span data-ttu-id="da2a4-126">Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)</span><span class="sxs-lookup"><span data-stu-id="da2a4-126">More information: [Specify values in a flow](personalize-survey.md#specify-values-in-a-flow)</span></span>

8. <span data-ttu-id="da2a4-127">Fügen Sie einen neuen Schritt hinzu und wählen Sie dann die Aktion zum Senden der E-Mail aus.</span><span class="sxs-lookup"><span data-stu-id="da2a4-127">Add a new step, and then select the action to send the email.</span></span> <span data-ttu-id="da2a4-128">Sie können Anbieter wie Outlook, Gmail oder SMS verwenden; wir haben Outlook verwendet, um die Umfrage in dieser Prozedur zu senden.</span><span class="sxs-lookup"><span data-stu-id="da2a4-128">You can use providers such as Outlook, Gmail, or SMS; we've used Outlook to send the survey in this procedure.</span></span>

9. <span data-ttu-id="da2a4-129">In der Aktion **E-Mail senden** gehen Sie wie folgt vor:</span><span class="sxs-lookup"><span data-stu-id="da2a4-129">In the **Send an email** action, do the following:</span></span>

    - <span data-ttu-id="da2a4-130">**An**: Geben Sie die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="da2a4-130">**To**: Enter the recipient's email address.</span></span>
    - <span data-ttu-id="da2a4-131">**Betreff**: Geben Sie den Betreff der E-Mail ein.</span><span class="sxs-lookup"><span data-stu-id="da2a4-131">**Subject**: Enter the subject of the email.</span></span>
    - <span data-ttu-id="da2a4-132">**Text**: Geben Sie den gewünschten Text für den Textkörper der E-Mail ein, und fügen Sie den dynamischen Inhalt des **Einladungslinks** hinzu.</span><span class="sxs-lookup"><span data-stu-id="da2a4-132">**Body**: Enter the text you want for the body of the email, and add the **Invitation link** dynamic content.</span></span>

    <span data-ttu-id="da2a4-133">Nach Eingabe der erforderlichen Angaben sieht der Fluss wie in der folgenden Abbildung dargestellt aus:</span><span class="sxs-lookup"><span data-stu-id="da2a4-133">After entering the required details, the flow looks as shown in the following image:</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="da2a4-134">![Umfrageeinladungsflow](media/survey-invite-flow.png "Umfrageeinladungsflow")</span><span class="sxs-lookup"><span data-stu-id="da2a4-134">![Survey invitation flow](media/survey-invite-flow.png "Survey invitation flow")</span></span>

    <span data-ttu-id="da2a4-135">Der Flow läuft gemäß dem konfigurierten Trigger ab und sendet dann die Umfrage.</span><span class="sxs-lookup"><span data-stu-id="da2a4-135">The flow runs in accordance with the configured trigger, and then sends the survey.</span></span>

### <a name="see-also"></a><span data-ttu-id="da2a4-136">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="da2a4-136">See also</span></span>

[<span data-ttu-id="da2a4-137">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="da2a4-137">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="da2a4-138">Senden Sie eine Umfrage per E-Mail</span><span class="sxs-lookup"><span data-stu-id="da2a4-138">Send a survey by using email</span></span>](send-survey-email.md)<br>
[<span data-ttu-id="da2a4-139">Senden Sie eine Umfrage mit Power Automate</span><span class="sxs-lookup"><span data-stu-id="da2a4-139">Send a survey by using Power Automate</span></span>](send-survey-flow.md)<br>
[<span data-ttu-id="da2a4-140">Eine Umfrage in einer Webseite einbetten</span><span class="sxs-lookup"><span data-stu-id="da2a4-140">Embed a survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="da2a4-141">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="da2a4-141">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="da2a4-142">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="da2a4-142">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="da2a4-143">Einbetten einer Umfrage in Power Apps</span><span class="sxs-lookup"><span data-stu-id="da2a4-143">Embed a survey in Power Apps</span></span>](embed-survey-powerapps.md)


