---
title: Erstellen einer Umfrageeinladung mit Microsoft Flow | MicrosoftDocs
description: Anleitung zur Erstellung einer Umfrageeinladung mit Microsoft Flow.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 06/14/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 8579EFA2-7734-4516-ACFA-F65999983379
ms.custom: ''
ms.openlocfilehash: 4c678fce5c180647d17263fb4bfabf495420a5ce
ms.sourcegitcommit: 4f20bfe750e8d4eb2db4dca0479699eb365c8c9e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2019
ms.locfileid: "1723771"
---
# <a name="create-a-survey-invitation"></a><span data-ttu-id="c56f9-103">Erstellen einer Umfrageeinladung</span><span class="sxs-lookup"><span data-stu-id="c56f9-103">Create a survey invitation</span></span>



<span data-ttu-id="c56f9-104">Wenn Sie eine Umfrage über eine andere Plattform als Microsoft Forms Pro senden möchten, z. B. Outlook, Google Mail oder SMS, können Sie mit Microsoft Flow eine Umfrageeinladung erstellen.</span><span class="sxs-lookup"><span data-stu-id="c56f9-104">If you want to send a survey using a platform other than Microsoft Forms Pro, such as Outlook, Gmail, or SMS, you can create a survey invitation using Microsoft Flow.</span></span> <span data-ttu-id="c56f9-105">Die Umfrageeinladung erstellt einen personalisierten Link, der über eine Plattform Ihrer Wahl verteilt werden kann.</span><span class="sxs-lookup"><span data-stu-id="c56f9-105">The survey invitation creates a personalized link that can be distributed by using a platform of your choice.</span></span>

1. <span data-ttu-id="c56f9-106">Melden Sie sich bei [flow.microsoft.com](https://flow.microsoft.com) an.</span><span class="sxs-lookup"><span data-stu-id="c56f9-106">Sign in to [flow.microsoft.com](https://flow.microsoft.com).</span></span>

2. <span data-ttu-id="c56f9-107">Beginnen Sie, einen Flow von Grund auf neu zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="c56f9-107">Start to create a flow from scratch.</span></span> <span data-ttu-id="c56f9-108">Informationen zum Erstellen eines neuen Flows finden Sie unter [Erstellen eines Flows in Microsoft Flow](https://docs.microsoft.com/en-us/flow/get-started-logic-flow).</span><span class="sxs-lookup"><span data-stu-id="c56f9-108">For information on creating a flow from scratch, see [Create a flow in Microsoft Flow](https://docs.microsoft.com/en-us/flow/get-started-logic-flow).</span></span>

3. <span data-ttu-id="c56f9-109">Fügen Sie im Flow-Editor einen Trigger hinzu, um Ihren Flow zu starten.</span><span class="sxs-lookup"><span data-stu-id="c56f9-109">In the flow editor, add a trigger to start your flow.</span></span>

4. <span data-ttu-id="c56f9-110">Nachdem Sie den Trigger hinzugefügt haben, fügen Sie einen neuen Schritt hinzu und suchen Sie nach dem Connector **Microsoft Forms Pro**.</span><span class="sxs-lookup"><span data-stu-id="c56f9-110">After adding the trigger, add a new step and search for the **Microsoft Forms Pro** connector.</span></span>

5. <span data-ttu-id="c56f9-111">Wählen Sie in den Suchergebnissen **Microsoft Forms Pro**.</span><span class="sxs-lookup"><span data-stu-id="c56f9-111">In search results, select **Microsoft Forms Pro**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="c56f9-112">![Auswahl Microsoft Forms Pro Connector](media/search-connector.png "Auswahl Microsoft Forms Pro Connector")</span><span class="sxs-lookup"><span data-stu-id="c56f9-112">![Select Microsoft Forms Pro connector](media/search-connector.png "Select Microsoft Forms Pro connector")</span></span>  

6. <span data-ttu-id="c56f9-113">Wählen Sie die Aktion **Eine Einladung erstellen (Vorschau)**.</span><span class="sxs-lookup"><span data-stu-id="c56f9-113">Select the **Create an invitation (preview)** action.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="c56f9-114">![Eine Einladungs-(Vorschau)-Aktion erstellen](media/select-flow-action.png "Eine Einladungs-(Vorschau)-Aktion erstellen")</span><span class="sxs-lookup"><span data-stu-id="c56f9-114">![Select Create an invitation (preview) action](media/select-flow-action.png "Select Create an invitation (preview) action")</span></span>  

7. <span data-ttu-id="c56f9-115">Geben Sie in der Aktion **Eine Einladung erstellen** die folgenden Informationen ein oder wählen Sie sie aus:</span><span class="sxs-lookup"><span data-stu-id="c56f9-115">In the **Create an invitation** action, enter or select the following information:</span></span>

    - <span data-ttu-id="c56f9-116">**Umfrage**: Wählen Sie die zu sendende Umfrage aus.</span><span class="sxs-lookup"><span data-stu-id="c56f9-116">**Survey**: Select the survey to be sent.</span></span>
    - <span data-ttu-id="c56f9-117">**E-Mail**: Geben Sie die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="c56f9-117">**Email**: Enter the recipient's email address.</span></span>
    - <span data-ttu-id="c56f9-118">**Betreff**: Geben Sie einen Datensatz an, um Umfrageeinladung und -antwort zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="c56f9-118">**Regarding**: Specify a record to associate survey invitation and response.</span></span> <span data-ttu-id="c56f9-119">Dieser Wert wird in der Umfrageeinladung im Feld **Betreff** gespeichert.</span><span class="sxs-lookup"><span data-stu-id="c56f9-119">This value is stored in the survey invitation's **Regarding** field.</span></span>
    - <span data-ttu-id="c56f9-120">**Empfängerdetails**: Geben Sie einen Kontakt an, um Ihre Umfrageeinladungs- und Antwortdatensätze zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="c56f9-120">**Recipient details**: Specify a contact to associate your survey invitation and response records.</span></span> <span data-ttu-id="c56f9-121">Dieser Wert wird im Feld **An** der Umfrageeinladung gespeichert.</span><span class="sxs-lookup"><span data-stu-id="c56f9-121">This value is stored in the survey invitation's **To** field.</span></span> <span data-ttu-id="c56f9-122">In diesem Feld wird nur der Kontaktdatensatz unterstützt.</span><span class="sxs-lookup"><span data-stu-id="c56f9-122">Only Contact record is supported in this field.</span></span>

    > [!NOTE]
    > - <span data-ttu-id="c56f9-123">Wenn Sie Ihre Umfrageeinladung und -antwort mit Common Data Service verknüpfen möchten, müssen Sie in den Feldern **Betreff** und **Empfängerdetails** entsprechend Werte eingeben.</span><span class="sxs-lookup"><span data-stu-id="c56f9-123">If you want to associate your survey invitation and response with Common Data Service, you must enter values in **Regarding** and **Recipient details** fields accordingly.</span></span> <span data-ttu-id="c56f9-124">Weitere Informationen zu den Feldern **Betreff** und **Empfängerdetails** und wie sie in der Umfrageeinladung gespeichert sind, finden Sie unter [Senden einer Umfrageaktion](send-survey-microsoft-flow.md#send-a-survey-action).</span><span class="sxs-lookup"><span data-stu-id="c56f9-124">For more information on **Regarding** and **Recipient details** fields and how they are stored in the survey invitation, see [Send a survey action](send-survey-microsoft-flow.md#send-a-survey-action).</span></span>
    > - <span data-ttu-id="c56f9-125">Wenn Sie in Ihrer Umfrage personalisierte Datenplatzhalter verwendet haben, sind diese Felder in dieser Aktion sichtbar und Sie können die Werte entsprechend angeben.</span><span class="sxs-lookup"><span data-stu-id="c56f9-125">If you've used personalized data placeholders in your survey, those fields will be visible in this action and you can specify the values accordingly.</span></span> <span data-ttu-id="c56f9-126">Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)</span><span class="sxs-lookup"><span data-stu-id="c56f9-126">More information: [Specify values in a flow](personalize-survey.md#specify-values-in-a-flow)</span></span>

8. <span data-ttu-id="c56f9-127">Fügen Sie einen neuen Schritt hinzu und wählen Sie die Aktion zum Senden der E-Mail aus.</span><span class="sxs-lookup"><span data-stu-id="c56f9-127">Add a new step and select the action to send the email.</span></span> <span data-ttu-id="c56f9-128">Sie können Anbieter wie Outlook, Gmail oder SMS verwenden; wir haben Outlook verwendet, um die Umfrage in diesem Verfahren zu senden.</span><span class="sxs-lookup"><span data-stu-id="c56f9-128">You can use providers such as Outlook, Gmail, or SMS; we have used Outlook to send the survey in this procedure.</span></span>

9. <span data-ttu-id="c56f9-129">Geben Sie in der Aktion **Eine E-Mail senden** die folgenden Informationen ein:</span><span class="sxs-lookup"><span data-stu-id="c56f9-129">In the **Send an email** action, enter the following information:</span></span> 

    - <span data-ttu-id="c56f9-130">**An**: E-Mail-Adresse des Empfängers.</span><span class="sxs-lookup"><span data-stu-id="c56f9-130">**To**: Recipient's email address.</span></span>
    - <span data-ttu-id="c56f9-131">**Betreff**: Betreff der E-Mail.</span><span class="sxs-lookup"><span data-stu-id="c56f9-131">**Subject**: Subject of the email.</span></span>
    - <span data-ttu-id="c56f9-132">**Body**: Geben Sie den gewünschten Text ein und fügen Sie **Einladungslink** dynamische Inhalte hinzu.</span><span class="sxs-lookup"><span data-stu-id="c56f9-132">**Body**: Enter the required text and add **Invitation link** dynamic content.</span></span>

    <span data-ttu-id="c56f9-133">Nach Eingabe der erforderlichen Angaben sieht der Fluss wie in der folgenden Abbildung dargestellt aus:</span><span class="sxs-lookup"><span data-stu-id="c56f9-133">After entering the required details, the flow looks as shown in the following image:</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="c56f9-134">![Einladungs-Flow der Umfrage](media/survey-invite-flow.png "Einladungs-Flow der Umfrage")</span><span class="sxs-lookup"><span data-stu-id="c56f9-134">![Survey invitation flow](media/survey-invite-flow.png "Survey invitation flow")</span></span>

    <span data-ttu-id="c56f9-135">Der Flow läuft gemäß dem konfigurierten Trigger ab und sendet die Umfrage.</span><span class="sxs-lookup"><span data-stu-id="c56f9-135">The flow runs as per the configured trigger and the sends the survey.</span></span>


## <a name="see-also"></a><span data-ttu-id="c56f9-136">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="c56f9-136">See also</span></span>

[<span data-ttu-id="c56f9-137">Definieren Sie, wer an einer Umfrage teilnehmen darf</span><span class="sxs-lookup"><span data-stu-id="c56f9-137">Define who can respond to a survey</span></span>](invite-settings.md)<br>
[<span data-ttu-id="c56f9-138">Senden Sie eine Umfrage per E-Mail</span><span class="sxs-lookup"><span data-stu-id="c56f9-138">Send a survey by using email</span></span>](send-survey-email.md)<br>
[<span data-ttu-id="c56f9-139">Senden Sie eine Umfrage mit Microsoft Flow</span><span class="sxs-lookup"><span data-stu-id="c56f9-139">Send a survey by using Microsoft Flow</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="c56f9-140">Eingebettete Umfrage in eine Webseite</span><span class="sxs-lookup"><span data-stu-id="c56f9-140">Embed survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="c56f9-141">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="c56f9-141">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="c56f9-142">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="c56f9-142">Send a survey QR code</span></span>](send-survey-qrcode.md)


