---
title: Senden einer Umfrage mit Power Automate | MicrosoftDocs
description: Anleitung zum Versenden einer Umfrage mit Power Automate.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 01/16/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: 11ac9528-c0a6-4fe6-9886-d2a4bfaa72f4
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: e9e9c6d3dfa98d50dd617ae073844b9284e70b25
ms.sourcegitcommit: f99b529d74a96beb8121df5344f40479619875ea
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/16/2020
ms.locfileid: "2966838"
---
# <a name="send-a-survey-by-using-power-automate"></a><span data-ttu-id="5d57d-103">Senden einer Umfrage mit Power Automate.</span><span class="sxs-lookup"><span data-stu-id="5d57d-103">Send a survey by using Power Automate</span></span>

<span data-ttu-id="5d57d-104">Nachdem Sie eine Umfrage erstellt haben, können Sie sie an die Befragten senden, z.B. aufgrund einer Business Trigger-Resolution eines Falles oder der Erfüllung einer Bestellung.</span><span class="sxs-lookup"><span data-stu-id="5d57d-104">After creating a survey, you can send it to respondents based on a business trigger—resolution of a case or fulfillment of an order, for example.</span></span> <span data-ttu-id="5d57d-105">Sie können entweder eine eingebaute Vorlage auswählen oder mit Power Automate einen Flow von Grund auf neu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-105">You can either select a built-in template or create a flow from scratch by using Power Automate.</span></span> <span data-ttu-id="5d57d-106">Die folgenden Ablaufvorlagen sind in Forms Pro standardmäßig verfügbar:</span><span class="sxs-lookup"><span data-stu-id="5d57d-106">The following flow templates are available out of the box in Forms Pro:</span></span>

- <span data-ttu-id="5d57d-107">**Senden Sie eine Umfrage, wenn ein Fall in Dynamics 365 gelöst ist**: Diese Vorlage sendet eine Umfrage, wenn ein Fall in Dynamics 365 gelöst ist.</span><span class="sxs-lookup"><span data-stu-id="5d57d-107">**Send a survey when a case is resolved in Dynamics 365**: This template sends a survey when a case is resolved in Dynamics 365.</span></span>
- <span data-ttu-id="5d57d-108">**Senden Sie eine Umfrage, wenn ein Lead in Dynamics 365** qualifiziert ist: Diese Vorlage sendet eine Umfrage, wenn ein Lead in Dynamics 365 qualifiziert ist.</span><span class="sxs-lookup"><span data-stu-id="5d57d-108">**Send a survey when a lead is qualified in Dynamics 365**: This template sends a survey when a lead is qualified in Dynamics 365.</span></span>
- <span data-ttu-id="5d57d-109">**Senden Sie eine Umfrage, wenn eine Bestellung in Dynamics 365 erfüllt ist**: Diese Vorlage sendet eine Umfrage, wenn eine Bestellung in Dynamics 365 erfüllt ist.</span><span class="sxs-lookup"><span data-stu-id="5d57d-109">**Send a survey when an order is fulfilled in Dynamics 365**: This template sends a survey when an order is fulfilled in Dynamics 365.</span></span>
- <span data-ttu-id="5d57d-110">**Senden Sie eine Umfrage, wenn eine Schaltfläche angeglickt wird unter Power Apps**: Diese Vorlage sendet eine Umfrage an die angegebene Liste der Empfänger, wenn eine Schaltfläche unter Power Apps angeklickt wird.</span><span class="sxs-lookup"><span data-stu-id="5d57d-110">**Send a survey when a button is clicked in Power Apps**: This template sends a survey to the specified list of recipients when a button is clicked in Power Apps.</span></span>
- <span data-ttu-id="5d57d-111">**Senden Sie eine Umfrage, wenn ein Fall in Salesforce geschlossen ist**: Diese Vorlage sendet eine Umfrage, wenn ein Fall in Salesforce geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d57d-111">**Send a survey when a case is closed in Salesforce**: This template sends a survey when a case is closed in Salesforce.</span></span>

<span data-ttu-id="5d57d-112">So senden Sie eine Umfrage mit Power Automate:</span><span class="sxs-lookup"><span data-stu-id="5d57d-112">To send a survey by using Power Automate:</span></span>

1.  <span data-ttu-id="5d57d-113">Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie dann **Senden** aus der Symbolleiste oben auf der Seite aus.</span><span class="sxs-lookup"><span data-stu-id="5d57d-113">Open the survey you want to send, and then select **Send** from the toolbar at the top of the page.</span></span>

2. <span data-ttu-id="5d57d-114">Wählen Sie **Power Automate** und wählen Sie dann E-Mail erstellen aus.</span><span class="sxs-lookup"><span data-stu-id="5d57d-114">Select **Power Automate**, and then compose the email.</span></span>

3.  <span data-ttu-id="5d57d-115">Wählen Sie **Flow konfigurieren**.</span><span class="sxs-lookup"><span data-stu-id="5d57d-115">Select **Configure Flow**.</span></span>

4.  <span data-ttu-id="5d57d-116">Um einen integrierten Flow zu konfigurieren, wählen Sie eine Vorlage aus.</span><span class="sxs-lookup"><span data-stu-id="5d57d-116">To configure a built-in flow, select a template.</span></span> <span data-ttu-id="5d57d-117">Informationen zum Erstellen eines Flows aus einer Vorlage finden Sie unter [Anlegen eines Flows aus einer Vorlage in Power Automate](https://docs.microsoft.com/flow/get-started-logic-template).</span><span class="sxs-lookup"><span data-stu-id="5d57d-117">For information about creating a flow from a template, see [Create a flow from a template in Power Automate](https://docs.microsoft.com/flow/get-started-logic-template).</span></span>

5.  <span data-ttu-id="5d57d-118">Um einen Flow von Grund auf neu zu erstellen, wählen Sie **Erstellen von Grund auf**.</span><span class="sxs-lookup"><span data-stu-id="5d57d-118">To create a flow from scratch, select **Create from blank**.</span></span> <span data-ttu-id="5d57d-119">Informationen über das Erstellen eines neuen Flows finden Sie unter [Erstellen eines Flows in Power Automate](https://docs.microsoft.com/flow/get-started-logic-flow).</span><span class="sxs-lookup"><span data-stu-id="5d57d-119">For information about creating a flow from scratch, see [Create a flow in Power Automate](https://docs.microsoft.com/flow/get-started-logic-flow).</span></span>

> [!NOTE]
> - <span data-ttu-id="5d57d-120">Während der Konfiguration eines Flows zeigt die Vorlagenseite möglicherweise doppelte Vorlagen an.</span><span class="sxs-lookup"><span data-stu-id="5d57d-120">While configuring a flow, the template page might display duplicate templates.</span></span> <span data-ttu-id="5d57d-121">Um dieses Problem zu beheben, navigieren Sie aus der Registerkarte heraus und kehren Sie dann zurück, um den Flow erneut zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-121">To resolve this issue, navigate out of the tab, and then come back to create the flow again.</span></span>
> - <span data-ttu-id="5d57d-122">Wenn Sie in Ihrer Umfrage personalisierte Daten hinzugefügt haben, müssen Sie deren Werte im Flow angeben.</span><span class="sxs-lookup"><span data-stu-id="5d57d-122">If you have added personalized data in your survey, you must specify their values in the flow.</span></span> <span data-ttu-id="5d57d-123">Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)</span><span class="sxs-lookup"><span data-stu-id="5d57d-123">More information: [Specify values in a flow](personalize-survey.md#specify-values-in-a-flow)</span></span>

5.  <span data-ttu-id="5d57d-124">Wählen Sie **Flow erstellen**.</span><span class="sxs-lookup"><span data-stu-id="5d57d-124">Select **Create Flow**.</span></span>

<span data-ttu-id="5d57d-125">Wenn Sie eine Umfrage mit Power Automate senden, wird ein Umfrageeinladungssatz erstellt.</span><span class="sxs-lookup"><span data-stu-id="5d57d-125">When you send a survey by using Power Automate, a survey invitation record is created.</span></span> <span data-ttu-id="5d57d-126">Sie können Ihre Umfrageeinladung und -antwort mit Common Data Service verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-126">You can associate your survey invitation and response with Common Data Service.</span></span>

## <a name="send-a-survey-action"></a><span data-ttu-id="5d57d-127">Senden einer Umfrageaktion</span><span class="sxs-lookup"><span data-stu-id="5d57d-127">Send a survey action</span></span>

<span data-ttu-id="5d57d-128">Diese Aktion sendet eine Umfrage an eine bestimmte Liste von Empfängern und erstellt für jeden Empfänger eine Umfrageeinladung.</span><span class="sxs-lookup"><span data-stu-id="5d57d-128">This action sends a survey to a specified list of recipients and creates a survey invitation for each recipient.</span></span> <span data-ttu-id="5d57d-129">Sie können Ihre Umfrageeinladung und -antwort auch mit Common Data Service verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-129">You can also associate your survey invitation and response with Common Data Service.</span></span> <span data-ttu-id="5d57d-130">Wenn Sie einen Flow von Grund auf neu anlegen, kann dies durch die Felder **Betreff** und **Empfängerdetails** in einem Flow erreicht werden.</span><span class="sxs-lookup"><span data-stu-id="5d57d-130">When you create a flow from scratch, this can be achieved through the **Regarding** and **Recipient details** fields in a flow.</span></span> <span data-ttu-id="5d57d-131">Wenn Sie eine Bewegung aus einer Vorlage anlegen, werden die Felder **Betreff** und **Empfängerdetails** entsprechend ausgefüllt.</span><span class="sxs-lookup"><span data-stu-id="5d57d-131">If you choose to create a flow from a template, the **Regarding** and **Recipient details** fields are populated accordingly.</span></span>

<span data-ttu-id="5d57d-132">Angenommen, Sie müssen eine Umfrage zu jedem Fallabschluß schicken.</span><span class="sxs-lookup"><span data-stu-id="5d57d-132">Let's say you need to send a survey on every case closure.</span></span> <span data-ttu-id="5d57d-133">Über das Feld **Betreff** können Sie den Falldatensatz so festlegen, dass beim Anlegen einer Einladung und Antwort auf eine bestimmte Fallauflösung diese dann dem jeweiligen Fall zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="5d57d-133">You can use the **Regarding** field to specify the case record so that when an invitation and response are created on a particular case resolution, they're attached to the specific case.</span></span> <span data-ttu-id="5d57d-134">Der Fallmanager kann dann Berichte einrichten, um die Ergebnisse der Kundenzufriedenheit (CSAT) von Fall zu Fall anzuzeigen oder einen Fall wieder öffnen, wenn der CSAT sehr niedrig ist.</span><span class="sxs-lookup"><span data-stu-id="5d57d-134">The case manager then can set up reports to show customer satisfaction (CSAT) scores by case, or reopen a case if the CSAT is very low.</span></span>

<span data-ttu-id="5d57d-135">Im Feld **Empfängerdetails** können Sie die Umfrageeinladungs- und Antwortdatensätze dem entsprechenden Kontakt (dem Empfänger) zuordnen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-135">Use the **Recipient details** field to associate your survey invitation and response records to the appropriate contact (the recipient).</span></span> <span data-ttu-id="5d57d-136">Auf diese Weise können Vertriebsmitarbeiter oder andere Personen den Kontaktdatensatz einsehen und die Reaktion des Kunden sehen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-136">This allows sales personnel or anyone to see the contact record and the response of the customer.</span></span> <span data-ttu-id="5d57d-137">Dies kann ihnen helfen, das Gespräch mit dem Kunden entsprechend zu gestalten.</span><span class="sxs-lookup"><span data-stu-id="5d57d-137">This can help them formulate their conversation with the customer accordingly.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="5d57d-138">![Felder Betreff und Empfängerdetails in einem Flow füllen](media/associate-survey.png "Füllen der Felder Betreffend und Empfängerdetails in einem Flow")</span><span class="sxs-lookup"><span data-stu-id="5d57d-138">![Populate Regarding and Recipient details fields in a flow](media/associate-survey.png "Populate Regarding and Recipient details fields in a flow")</span></span>  

### <a name="attributes"></a><span data-ttu-id="5d57d-139">Attribute</span><span class="sxs-lookup"><span data-stu-id="5d57d-139">Attributes</span></span>

|<span data-ttu-id="5d57d-140">Name</span><span class="sxs-lookup"><span data-stu-id="5d57d-140">Name</span></span>|<span data-ttu-id="5d57d-141">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="5d57d-141">Description</span></span>|
|---|----|
|<span data-ttu-id="5d57d-142">Bis</span><span class="sxs-lookup"><span data-stu-id="5d57d-142">To</span></span>|<span data-ttu-id="5d57d-143">E-Mail-Adresse zum Versenden der Einladung zur Umfrage.</span><span class="sxs-lookup"><span data-stu-id="5d57d-143">Email address to send the survey invitation.</span></span> <span data-ttu-id="5d57d-144">Wenn Sie mehreren E-Mail-Adressen eingeben, teilen Sie diese durch ein Semikolon.</span><span class="sxs-lookup"><span data-stu-id="5d57d-144">If you're entering multiple email addresses, separate them by a semicolon.</span></span><br><span data-ttu-id="5d57d-145">**Hinweis**: Die E-Mail-Adresse sollte gültig sein und nicht Null zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="5d57d-145">**Note**: The email address should be valid and should not return null.</span></span>|
|<span data-ttu-id="5d57d-146">Umfrage</span><span class="sxs-lookup"><span data-stu-id="5d57d-146">Survey</span></span>|<span data-ttu-id="5d57d-147">Die Umfrage soll gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="5d57d-147">Survey to be sent.</span></span><br><span data-ttu-id="5d57d-148">**Hinweis**: Sie müssen eine Umfrage aus der Liste auswählen und dürfen keinen benutzerdefinierten Wert eingeben.</span><span class="sxs-lookup"><span data-stu-id="5d57d-148">**Note**: You must select a survey from the list and not enter a custom value.</span></span>|
|<span data-ttu-id="5d57d-149">E-Mail-Vorlage</span><span class="sxs-lookup"><span data-stu-id="5d57d-149">Email template</span></span>|<span data-ttu-id="5d57d-150">E-Mail-Vorlage, die beim Senden der Einladung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d57d-150">Email template to be used while sending the invitation.</span></span><br><span data-ttu-id="5d57d-151">**Hinweis**: Sie müssen eine E-Mail-Vorlage aus der Liste auswählen und dürfen keinen benutzerdefinierten Wert eingeben.</span><span class="sxs-lookup"><span data-stu-id="5d57d-151">**Note**: You must select an email template from the list and not enter a custom value.</span></span>|
|<span data-ttu-id="5d57d-152">Bezug</span><span class="sxs-lookup"><span data-stu-id="5d57d-152">Regarding</span></span>|<span data-ttu-id="5d57d-153">Aufzeichnen, um die Einladung und Beantwortung einer Umfrage zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-153">Record to associate survey invitation and response.</span></span> <span data-ttu-id="5d57d-154">Dieser Wert wird in der Umfrageeinladung im Feld **Betreff** gespeichert.</span><span class="sxs-lookup"><span data-stu-id="5d57d-154">This value is stored in the survey invitation's **Regarding** field.</span></span>|
|<span data-ttu-id="5d57d-155">Angaben zum Empfänger</span><span class="sxs-lookup"><span data-stu-id="5d57d-155">Recipient details</span></span>|<span data-ttu-id="5d57d-156">Kontakt, um Ihre Umfrageeinladung und Ihre Antwortdatensätze damit zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-156">Contact to associate your survey invitation and response records with.</span></span> <span data-ttu-id="5d57d-157">Dieser Wert wird im Feld **An** der Umfrageeinladung gespeichert.</span><span class="sxs-lookup"><span data-stu-id="5d57d-157">This value is stored in the survey invitation's **To** field.</span></span><br><span data-ttu-id="5d57d-158">**Hinweis**: Nur der Kontaktdatensatz wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="5d57d-158">**Note**: Only the Contact record is supported.</span></span>|
|||

> [!NOTE]
> <span data-ttu-id="5d57d-159">Wenn Sie in Ihrer Umfrage personalisierte Datenplatzhalter verwendet haben, sind diese Felder in dieser Aktion sichtbar und Sie können die Werte entsprechend angeben.</span><span class="sxs-lookup"><span data-stu-id="5d57d-159">If you've used personalized data placeholders in your survey, those fields will be visible in this action and you can specify the values accordingly.</span></span> <span data-ttu-id="5d57d-160">Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)</span><span class="sxs-lookup"><span data-stu-id="5d57d-160">More information: [Specify values in a flow](personalize-survey.md#specify-values-in-a-flow)</span></span>

<span data-ttu-id="5d57d-161">Die Werte aus den Feldern **Betreff** und **Empfängerdetails** werden in der Umfrageeinladung gespeichert, so wie im folgenden Bild dargestellt.</span><span class="sxs-lookup"><span data-stu-id="5d57d-161">The values from the **Regarding** and **Recipient details** fields are stored in the survey invitation as shown in the following image.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="5d57d-162">![Umfrage Einladungsdatensatz](media/survey-invite.png "Befragungseinladungsdatensatz")</span><span class="sxs-lookup"><span data-stu-id="5d57d-162">![Survey invite record](media/survey-invite.png "Survey invitation record")</span></span>  

> [!NOTE]
> <span data-ttu-id="5d57d-163">Das Feld **An** wird auf dem Formular nicht standardmäßig angezeigt.</span><span class="sxs-lookup"><span data-stu-id="5d57d-163">The **To** field isn't displayed by default on the form.</span></span> <span data-ttu-id="5d57d-164">Sie müssen zu **Erweiterte Suche** gehen und nach der Einladung suchen und die erforderlichen Spalten hinzufügen, um ihre Werte anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-164">You must go to **Advanced Find**, search for the invitation, and add the required columns to see their values.</span></span>
>
> [!div class=mx-imgBorder]
> <span data-ttu-id="5d57d-165">![Umfrage Einladung mit Advanced Find](media/survey-invite-adv-find.png "Suchen Sie Umfrageeinladung mithilfe der erweiterten Suche")</span><span class="sxs-lookup"><span data-stu-id="5d57d-165">![Search survey invite using Advanced Find](media/survey-invite-adv-find.png "Search survey invitation using Advanced Find")</span></span> 

## <a name="view-flow-history"></a><span data-ttu-id="5d57d-166">Anzeige der Flow-Historie</span><span class="sxs-lookup"><span data-stu-id="5d57d-166">View flow history</span></span>

<span data-ttu-id="5d57d-167">Die Flow-Historie ist die Information, die dann für jede Umfrage gespeichert wird, während Sie die Flows zum Senden einer Umfrage konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="5d57d-167">Flow history is the information that's stored for each survey as you configure flows to send a survey.</span></span> <span data-ttu-id="5d57d-168">Bevor Sie einen neuen Flow konfigurieren, möchten Sie vielleicht mehr über die bereits für die Umfrage konfigurierten Flows erfahren.</span><span class="sxs-lookup"><span data-stu-id="5d57d-168">Before configuring a new flow, you might want to know more about the flows that are already configured for the survey.</span></span> <span data-ttu-id="5d57d-169">Die Flow-Historie liefert Ihnen die erforderlichen Informationen über die konfigurierten Flows, wie z.B. die Gesamtzahl der Flows, Ausfälle usw.</span><span class="sxs-lookup"><span data-stu-id="5d57d-169">Flow history gives you the required information about the configured flows, such as the total number of runs, failures, and so on.</span></span>

<span data-ttu-id="5d57d-170">Die Flow-Historie wird in einem Raster mit den folgenden Informationen angezeigt:</span><span class="sxs-lookup"><span data-stu-id="5d57d-170">Flow history is displayed in a grid with the following information:</span></span>

- <span data-ttu-id="5d57d-171">**Änderungsdatum**: Datum, an dem der Flow geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="5d57d-171">**Date modified**: Date when the flow was modified.</span></span>

- <span data-ttu-id="5d57d-172">**Flow**: Name des Flows.</span><span class="sxs-lookup"><span data-stu-id="5d57d-172">**Flow**: Name of the flow.</span></span>

- <span data-ttu-id="5d57d-173">**Nachrichtenvorlage**: E-Mail-Nachrichtenvorlage(n), die vom Flow verwendet wird (werden).</span><span class="sxs-lookup"><span data-stu-id="5d57d-173">**Message template**: Email message template(s) used by the flow.</span></span>

- <span data-ttu-id="5d57d-174">**Ausführungen**: Gesamtanzahl der Durchläufe eines Flows.</span><span class="sxs-lookup"><span data-stu-id="5d57d-174">**Runs**: Total number of times a flow has run.</span></span> <span data-ttu-id="5d57d-175">Es werden Werte von bis zu 200 angezeigt.</span><span class="sxs-lookup"><span data-stu-id="5d57d-175">Values of up to 200 are displayed.</span></span> <span data-ttu-id="5d57d-176">Wenn ein Flow mehr als 200 Mal ausgeführt wurde, wird 200+ als Zähler angezeigt.</span><span class="sxs-lookup"><span data-stu-id="5d57d-176">If a flow has run more than 200 times, 200+ is displayed as the count.</span></span> <span data-ttu-id="5d57d-177">Sie können den Zählwert auswählen, um weitere Details zur Ausführung anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-177">You can select the count value to view more details about the run.</span></span>

- <span data-ttu-id="5d57d-178">**Fehler (letzte 200 Durchläufe)**: Anzahl der Ausfälle eines Flows von den letzten 200 Durchläufen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-178">**Failures (last 200 runs)**: Number of times a flow has failed out of the last 200 runs.</span></span>

- <span data-ttu-id="5d57d-179">**Status**: Status des Flows: ein oder aus.</span><span class="sxs-lookup"><span data-stu-id="5d57d-179">**Status**: Status of the flow: on or off.</span></span> <span data-ttu-id="5d57d-180">Sie können den Status eines Flows über Power Automate aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5d57d-180">You can update a flow's status from Power Automate.</span></span> <span data-ttu-id="5d57d-181">Weitere Informationen finden Sie unter [Management einer Flows](https://docs.microsoft.com/flow/get-started-logic-flow#manage-a-flow).</span><span class="sxs-lookup"><span data-stu-id="5d57d-181">For more information, see [Manage a flow](https://docs.microsoft.com/flow/get-started-logic-flow#manage-a-flow).</span></span>  

<span data-ttu-id="5d57d-182">Bei Bedarf können Sie einen Flow auch bearbeiten, indem Sie das Symbol **Bearbeiten** auswählen.</span><span class="sxs-lookup"><span data-stu-id="5d57d-182">If required, you can also edit a flow by selecting the **Edit** symbol.</span></span> <span data-ttu-id="5d57d-183">Der Flow-Editor öffnet sich in Power Automate, von wo aus Sie Ihre Änderungen vornehmen können.</span><span class="sxs-lookup"><span data-stu-id="5d57d-183">The flow editor opens in Power Automate, from which you make your changes.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="5d57d-184">![Einen Flow bearbeiten](media/edit-flow.png "Bearbeiten eines Flows")</span><span class="sxs-lookup"><span data-stu-id="5d57d-184">![Edit a flow](media/edit-flow.png "Edit a flow")</span></span>  

<span data-ttu-id="5d57d-185">Zur Anzeige der Flow-Historie:</span><span class="sxs-lookup"><span data-stu-id="5d57d-185">To view flow history:</span></span>

1.  <span data-ttu-id="5d57d-186">Öffnen Sie die Umfrage, die Sie einbetten möchten und wählen Sie dann **Senden** aus der Symbolleiste oben auf der Seite aus.</span><span class="sxs-lookup"><span data-stu-id="5d57d-186">Open the survey for which you want to view flow history, and then select **Send** from the toolbar at the top of the page.</span></span>

2.  <span data-ttu-id="5d57d-187">Wählen Sie auf der Kachel **Power Automate** **Konfigurierte Flows**.</span><span class="sxs-lookup"><span data-stu-id="5d57d-187">On the **Power Automate** tile, select **Flows configured**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="5d57d-188">![Konfigurierte Flows Schaltfläche](media/flows-configured.png "Schaltfläche für konfigurierte Flows")</span><span class="sxs-lookup"><span data-stu-id="5d57d-188">![Flows configured button](media/flows-configured.png "Flows configured button")</span></span>  

    <span data-ttu-id="5d57d-189">Es wird ein Raster mit den konfigurierten Flows angezeigt.</span><span class="sxs-lookup"><span data-stu-id="5d57d-189">A grid with the configured flows is displayed.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="5d57d-190">![Flow-Historie Details](media/flow-history-details.png "Details zum Flow-Verlauf")</span><span class="sxs-lookup"><span data-stu-id="5d57d-190">![Flow history details](media/flow-history-details.png "Flow history details")</span></span>  

### <a name="see-also"></a><span data-ttu-id="5d57d-191">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="5d57d-191">See also</span></span>

[<span data-ttu-id="5d57d-192">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="5d57d-192">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="5d57d-193">Senden Sie eine Umfrage per E-Mail</span><span class="sxs-lookup"><span data-stu-id="5d57d-193">Send a survey by using email</span></span>](send-survey-email.md)<br>
[<span data-ttu-id="5d57d-194">Eine Umfrage in einer Webseite einbetten</span><span class="sxs-lookup"><span data-stu-id="5d57d-194">Embed a survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="5d57d-195">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="5d57d-195">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="5d57d-196">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="5d57d-196">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="5d57d-197">Einbetten einer Umfrage in Power Apps</span><span class="sxs-lookup"><span data-stu-id="5d57d-197">Embed a survey in Power Apps</span></span>](embed-survey-powerapps.md)
