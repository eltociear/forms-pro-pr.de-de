---
title: Senden einer Umfrage mit Microsoft Flow | MicrosoftDocs
description: Anleitung zum Versenden einer Umfrage mit Microsoft Flow.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 08/06/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 11ac9528-c0a6-4fe6-9886-d2a4bfaa72f4
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: e8e6ad218e690ece25b29b8ddd3c109a60e3e6e2
ms.sourcegitcommit: e3e7192edb3753060a20a4dec47eb98faf1b87a3
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/06/2019
ms.locfileid: "1863968"
---
# <a name="send-a-survey-by-using-microsoft-flow"></a><span data-ttu-id="cd4e9-103">Senden einer Umfrage mit Microsoft Flow.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-103">Send a survey by using Microsoft Flow</span></span>



<span data-ttu-id="cd4e9-104">Nachdem Sie eine Umfrage erstellt haben, können Sie sie an die Befragten senden, z.B. aufgrund einer Business Trigger-Resolution eines Falles oder der Erfüllung einer Bestellung.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-104">After creating a survey, you can send it to respondents based on a business trigger—resolution of a case or fulfillment of an order, for example.</span></span> <span data-ttu-id="cd4e9-105">Sie können entweder eine eingebaute Vorlage auswählen oder mit Microsoft Flow einen Flow von Grund auf neu erstellen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-105">You can either select a built-in template or create a flow from scratch by using Microsoft Flow.</span></span> <span data-ttu-id="cd4e9-106">Die folgenden Ablaufvorlagen sind in Forms Pro standardmäßig verfügbar:</span><span class="sxs-lookup"><span data-stu-id="cd4e9-106">The following flow templates are available out of the box in Forms Pro:</span></span>

- <span data-ttu-id="cd4e9-107">**Senden Sie eine Umfrage, wenn ein Fall in Dynamics 365 gelöst ist**: Diese Vorlage sendet eine Umfrage, wenn ein Fall in Dynamics 365 gelöst ist.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-107">**Send a survey when a case is resolved in Dynamics 365**: This template sends a survey when a case is resolved in Dynamics 365.</span></span>
- <span data-ttu-id="cd4e9-108">**Senden Sie eine Umfrage, wenn ein Lead in Dynamics 365** qualifiziert ist: Diese Vorlage sendet eine Umfrage, wenn ein Lead in Dynamics 365 qualifiziert ist.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-108">**Send a survey when a lead is qualified in Dynamics 365**: This template sends a survey when a lead is qualified in Dynamics 365.</span></span>
- <span data-ttu-id="cd4e9-109">**Senden Sie eine Umfrage, wenn eine Bestellung in Dynamics 365 erfüllt ist**: Diese Vorlage sendet eine Umfrage, wenn eine Bestellung in Dynamics 365 erfüllt ist.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-109">**Send a survey when an order is fulfilled in Dynamics 365**: This template sends a survey when an order is fulfilled in Dynamics 365.</span></span>
- <span data-ttu-id="cd4e9-110">**Senden Sie eine Umfrage, wenn eine Schaltfläche in PowerApps** angeklickt wird: Diese Vorlage sendet eine Umfrage an die angegebene Liste von Empfängern, wenn eine Schaltfläche in PowerApps angeklickt wird.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-110">**Send a survey when a button is clicked in PowerApps**: This template sends a survey to the specified list of recipients when a button is clicked in PowerApps.</span></span>
- <span data-ttu-id="cd4e9-111">**Senden Sie eine Umfrage, wenn ein Fall in Salesforce geschlossen ist**: Diese Vorlage sendet eine Umfrage, wenn ein Fall in Salesforce geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-111">**Send a survey when a case is closed in Salesforce**: This template sends a survey when a case is closed in Salesforce.</span></span>

<span data-ttu-id="cd4e9-112">So senden Sie eine Umfrage mit Microsoft Flow:</span><span class="sxs-lookup"><span data-stu-id="cd4e9-112">To send a survey by using Microsoft Flow:</span></span>

1.  <span data-ttu-id="cd4e9-113">Öffnen Sie die Umfrage, die Sie senden möchten, und gehen Sie zu **Umfrage senden** &gt; **Microsoft Flow**.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-113">Open the survey you want to send, and go to **Send Survey** &gt; **Microsoft Flow**.</span></span>

2.  <span data-ttu-id="cd4e9-114">Verfassen Sie die E-Mail.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-114">Compose the email.</span></span>

3.  <span data-ttu-id="cd4e9-115">Wählen Sie **Flow konfigurieren**.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-115">Select **Configure Flow**.</span></span>

4.  <span data-ttu-id="cd4e9-116">Um einen integrierten Flow zu konfigurieren, wählen Sie eine Vorlage aus.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-116">To configure a built-in flow, select a template.</span></span> <span data-ttu-id="cd4e9-117">Informationen zum Anlegen eines Flows aus einer Vorlage finden Sie unter [Anlegen eines Flows aus einer Vorlage in Microsoft Flow](https://docs.microsoft.com/en-us/flow/get-started-logic-template).</span><span class="sxs-lookup"><span data-stu-id="cd4e9-117">For information on creating a flow from a template, see [Create a flow from a template in Microsoft Flow](https://docs.microsoft.com/en-us/flow/get-started-logic-template).</span></span> 

5.  <span data-ttu-id="cd4e9-118">Um einen Flow von Grund auf neu zu erstellen, wählen Sie **Erstellen von Grund auf**.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-118">To create a flow from scratch, select **Create from blank**.</span></span> <span data-ttu-id="cd4e9-119">Informationen zum Erstellen eines neuen Flows finden Sie unter [Erstellen eines Flows in Microsoft Flow](https://docs.microsoft.com/en-us/flow/get-started-logic-flow).</span><span class="sxs-lookup"><span data-stu-id="cd4e9-119">For information on creating a flow from scratch, see [Create a flow in Microsoft Flow](https://docs.microsoft.com/en-us/flow/get-started-logic-flow).</span></span>

> [!NOTE]
> - <span data-ttu-id="cd4e9-120">Während der Konfiguration eines Flows zeigt die Vorlagenseite möglicherweise doppelte Vorlagen an.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-120">While configuring a flow, the template page might display duplicate templates.</span></span> <span data-ttu-id="cd4e9-121">Um dieses Problem zu beheben, navigieren Sie aus der Registerkarte **Umfrage senden** heraus und kehren Sie dann zurück, um den Flow erneut zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-121">To resolve this issue, navigate out of the **Send Survey** tab, and then come back to create the flow again.</span></span>
> - <span data-ttu-id="cd4e9-122">Wenn Sie in Ihrer Umfrage personalisierte Daten hinzugefügt haben, müssen Sie deren Werte im Flow angeben.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-122">If you have added personalized data in your survey, you must specify their values in the flow.</span></span> <span data-ttu-id="cd4e9-123">Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)</span><span class="sxs-lookup"><span data-stu-id="cd4e9-123">More information: [Specify values in a flow](personalize-survey.md#specify-values-in-a-flow)</span></span>

5.  <span data-ttu-id="cd4e9-124">Wählen Sie **Flow erstellen**.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-124">Select **Create Flow**.</span></span>

<span data-ttu-id="cd4e9-125">Wenn Sie eine Umfrage mit Flow senden, wird ein Umfrageeinladungssatz erstellt.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-125">When you send a survey by using Flow, a survey invitation record is created.</span></span> <span data-ttu-id="cd4e9-126">Sie können Ihre Umfrageeinladung und -antwort mit Common Data Service verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-126">You can associate your survey invitation and response with Common Data Service.</span></span> <span data-ttu-id="cd4e9-127">Mehr Informationen: [Senden Sie eine Umfrageaktion](#send-a-survey-action).</span><span class="sxs-lookup"><span data-stu-id="cd4e9-127">More information: [Send a survey action](#send-a-survey-action)</span></span>

## <a name="send-a-survey-action"></a><span data-ttu-id="cd4e9-128">Senden einer Umfrageaktion</span><span class="sxs-lookup"><span data-stu-id="cd4e9-128">Send a survey action</span></span>

<span data-ttu-id="cd4e9-129">Diese Aktion sendet eine Umfrage an eine bestimmte Liste von Empfängern und erstellt für jeden Empfänger eine Umfrageeinladung.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-129">This action sends a survey to a specified list of recipients and creates a survey invitation for each recipient.</span></span> <span data-ttu-id="cd4e9-130">Sie können Ihre Umfrageeinladung und -antwort auch mit Common Data Service verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-130">You can also associate your survey invitation and response with Common Data Service.</span></span> <span data-ttu-id="cd4e9-131">Wenn Sie einen Flow von Grund auf neu anlegen, kann dies durch die Felder **Betreff** und **Empfängerdetails** in einem Flow erreicht werden.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-131">When you create a flow from scratch, this can be achieved through the **Regarding** and **Recipient details** fields in a flow.</span></span> <span data-ttu-id="cd4e9-132">Wenn Sie eine Bewegung aus einer Vorlage anlegen, werden die Felder **Betreff** und **Empfängerdetails** entsprechend ausgefüllt.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-132">If you choose to create a flow from a template, the **Regarding** and **Recipient details** fields are populated accordingly.</span></span>

<span data-ttu-id="cd4e9-133">Angenommen, Sie müssen eine Umfrage zu jedem Fallabschluß schicken.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-133">Let's say you need to send a survey on every case closure.</span></span> <span data-ttu-id="cd4e9-134">Über das Feld **Betreff** können Sie den Falldatensatz so festlegen, dass beim Anlegen einer Einladung und Antwort auf eine bestimmte Fallauflösung diese dem jeweiligen Fall zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-134">You can use the **Regarding** field to specify the case record so that when an invitation and response are created on a particular case resolution, they are attached to the specific case.</span></span> <span data-ttu-id="cd4e9-135">Der Fallmanager kann dann Berichte einrichten, um die Ergebnisse der Kundenzufriedenheit (CSAT) von Fall zu Fall anzuzeigen, oder einen Fall wieder öffnen, wenn der CSAT sehr niedrig ist.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-135">The case manager then can set up reports to show customer satisfaction (CSAT) scores by case or reopen a case if the CSAT is very low.</span></span>

<span data-ttu-id="cd4e9-136">Im Feld **Empfängerdetails** können Sie Ihre Umfrageeinladungs- und Antwortdatensätze dem entsprechenden Kontakt (dem Empfänger) zuordnen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-136">The **Recipient details** field allows you to associate your survey invitation and response records to the appropriate contact (the recipient).</span></span> <span data-ttu-id="cd4e9-137">Auf diese Weise können Vertriebsmitarbeiter oder andere Personen den Kontaktdatensatz einsehen und die Reaktion des Kunden kennen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-137">This allows sales personnel or anyone to see the contact record and know the response of the customer.</span></span> <span data-ttu-id="cd4e9-138">Dies kann helfen, das Gespräch mit dem Kunden entsprechend zu gestalten.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-138">This can help formulate their conversation with the customer accordingly.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="cd4e9-139">![Felder Betreff und Empfängerdetails in einem Flow füllen](media/associate-survey.png "Felder Betreff und Empfängerdetails in einem Flow füllen")</span><span class="sxs-lookup"><span data-stu-id="cd4e9-139">![Populate Regarding and Recipient details fields in a flow](media/associate-survey.png "Populate Regarding and Recipient details fields in a flow")</span></span>  

### <a name="attributes"></a><span data-ttu-id="cd4e9-140">Attribute</span><span class="sxs-lookup"><span data-stu-id="cd4e9-140">Attributes</span></span>

|<span data-ttu-id="cd4e9-141">Name</span><span class="sxs-lookup"><span data-stu-id="cd4e9-141">Name</span></span>|<span data-ttu-id="cd4e9-142">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="cd4e9-142">Description</span></span>|
|---|----|
|<span data-ttu-id="cd4e9-143">Bis</span><span class="sxs-lookup"><span data-stu-id="cd4e9-143">To</span></span>|<span data-ttu-id="cd4e9-144">E-Mail-Adresse zum Versenden der Einladung zur Umfrage.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-144">Email address to send the survey invitation.</span></span> <span data-ttu-id="cd4e9-145">Wenn Sie mehreren E-Mail-Adressen eingeben, teilen Sie sie durch ein Semikolon.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-145">If you are entering multiple email addresses, separate them by a semicolon.</span></span><br><span data-ttu-id="cd4e9-146">**Hinweis**: Die E-Mail-Adresse sollte gültig sein und nicht Null zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-146">**Note**: The email address should be valid and should not return null.</span></span>|
|<span data-ttu-id="cd4e9-147">Umfrage</span><span class="sxs-lookup"><span data-stu-id="cd4e9-147">Survey</span></span>|<span data-ttu-id="cd4e9-148">Die Umfrage soll gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-148">Survey to be sent.</span></span><br><span data-ttu-id="cd4e9-149">**Hinweis**: Sie müssen eine Umfrage aus der Liste auswählen und dürfen keinen benutzerdefinierten Wert eingeben.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-149">**Note**: You must select a survey from the list and not enter a custom value.</span></span>|
|<span data-ttu-id="cd4e9-150">E-Mail-Vorlage</span><span class="sxs-lookup"><span data-stu-id="cd4e9-150">Email template</span></span>|<span data-ttu-id="cd4e9-151">E-Mail-Vorlage, die beim Senden der Einladung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-151">Email template to be used while sending the invitation.</span></span><br><span data-ttu-id="cd4e9-152">**Hinweis**: Sie müssen eine E-Mail-Vorlage aus der Liste auswählen und dürfen keinen benutzerdefinierten Wert eingeben.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-152">**Note**: You must select an email template from the list and not enter a custom value.</span></span>|
|<span data-ttu-id="cd4e9-153">Bezug</span><span class="sxs-lookup"><span data-stu-id="cd4e9-153">Regarding</span></span>|<span data-ttu-id="cd4e9-154">Aufzeichnen, um die Einladung und Beantwortung einer Umfrage zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-154">Record to associate survey invitation and response.</span></span> <span data-ttu-id="cd4e9-155">Dieser Wert wird in der Umfrageeinladung im Feld **Betreff** gespeichert.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-155">This value is stored in the survey invitation's **Regarding** field.</span></span>|
|<span data-ttu-id="cd4e9-156">Angaben zum Empfänger</span><span class="sxs-lookup"><span data-stu-id="cd4e9-156">Recipient details</span></span>|<span data-ttu-id="cd4e9-157">Kontakt, um Ihre Umfrageeinladung und Ihre Antwortdatensätze zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-157">Contact to associate your survey invitation and response records.</span></span> <span data-ttu-id="cd4e9-158">Dieser Wert wird im Feld **An** der Umfrageeinladung gespeichert.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-158">This value is stored in the survey invitation's **To** field.</span></span><br><span data-ttu-id="cd4e9-159">**Hinweis**: Es wird nur der Kontaktdatensatz unterstützt.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-159">**Note**: Only Contact record is supported.</span></span>|
|||

> [!NOTE]
> <span data-ttu-id="cd4e9-160">Wenn Sie in Ihrer Umfrage personalisierte Datenplatzhalter verwendet haben, sind diese Felder in dieser Aktion sichtbar und Sie können die Werte entsprechend angeben.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-160">If you've used personalized data placeholders in your survey, those fields will be visible in this action and you can specify the values accordingly.</span></span> <span data-ttu-id="cd4e9-161">Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)</span><span class="sxs-lookup"><span data-stu-id="cd4e9-161">More information: [Specify values in a flow](personalize-survey.md#specify-values-in-a-flow)</span></span>

<span data-ttu-id="cd4e9-162">Die Werte aus den Feldern **Betreff** und **Empfängerdetails** werden in der Umfrageeinladung gespeichert, wie im folgenden Bild dargestellt.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-162">The values from the **Regarding** and **Recipient details** fields are stored in the survey invitation as shown in the below image.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="cd4e9-163">![Umfrage Einladungsdatensatz](media/survey-invite.png "Umfrage Einladungsdatensatz")</span><span class="sxs-lookup"><span data-stu-id="cd4e9-163">![Survey invite record](media/survey-invite.png "Survey invite record")</span></span>  

> [!NOTE]
> <span data-ttu-id="cd4e9-164">Das Feld **An** wird auf dem Formular standardmäßig nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-164">The **To** field is not displayed by default on the form.</span></span> <span data-ttu-id="cd4e9-165">Sie müssen zu **Erweiterte Suche** gehen, nach der Einladung suchen und die erforderlichen Spalten hinzufügen, um ihre Werte anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-165">You must go to **Advanced Find**, search for the invite, and add the required columns to see their values.</span></span>
>
> [!div class=mx-imgBorder]
> <span data-ttu-id="cd4e9-166">![Suche von Umfrageeinladung mit Erweiterter Suche](media/survey-invite-adv-find.png "Suche von Umfrageeinladung mit Erweiterter Suche")</span><span class="sxs-lookup"><span data-stu-id="cd4e9-166">![Search survey invite using Advanced Find](media/survey-invite-adv-find.png "Search survey invite using Advanced Find")</span></span> 

## <a name="view-flow-history"></a><span data-ttu-id="cd4e9-167">Anzeige der Flow-Historie</span><span class="sxs-lookup"><span data-stu-id="cd4e9-167">View flow history</span></span>

<span data-ttu-id="cd4e9-168">Die Flow-Historie ist die Information, die für jede Umfrage gespeichert wird, während Sie die Flows zum Senden einer Umfrage konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-168">Flow history is the information that is stored for each survey as you configure flows to send a survey.</span></span> <span data-ttu-id="cd4e9-169">Bevor Sie einen neuen Flow konfigurieren, möchten Sie vielleicht mehr über die bereits für die Umfrage konfigurierten Flows erfahren.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-169">Before configuring a new flow, you might want to know more about the flows that are already configured for the survey.</span></span> <span data-ttu-id="cd4e9-170">Die Flow-Historie liefert Ihnen die erforderlichen Informationen über die konfigurierten Flows, wie z.B. die Gesamtzahl der Flows, Ausfälle usw.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-170">Flow history gives you the required information about the configured flows, such as the total number of runs, failures, and so on.</span></span>

<span data-ttu-id="cd4e9-171">Die Flow-Historie wird in einem Raster mit den folgenden Informationen angezeigt:</span><span class="sxs-lookup"><span data-stu-id="cd4e9-171">Flow history is displayed in a grid with the following information:</span></span>

- <span data-ttu-id="cd4e9-172">**Änderungsdatum**: Datum, an dem der Flow geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-172">**Date modified**: Date when the flow was modified.</span></span>

- <span data-ttu-id="cd4e9-173">**Flow**: Name des Flows.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-173">**Flow**: Name of the flow.</span></span>

- <span data-ttu-id="cd4e9-174">**Nachrichtenvorlage**: E-Mail-Nachrichtenvorlage(n), die vom Flow verwendet wird (werden).</span><span class="sxs-lookup"><span data-stu-id="cd4e9-174">**Message template**: Email message template(s) used by the flow.</span></span>

- <span data-ttu-id="cd4e9-175">**Ausführungen**: Gesamtanzahl der Durchläufe eines Flows.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-175">**Runs**: Total number of times a flow has run.</span></span> <span data-ttu-id="cd4e9-176">Es werden Werte von bis zu 200 angezeigt.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-176">Values of up to 200 are displayed.</span></span> <span data-ttu-id="cd4e9-177">Wenn ein Flow mehr als 200 Mal ausgeführt wurde, wird 200+ als Zähler angezeigt.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-177">If a flow has run more than 200 times, 200+ is displayed as the count.</span></span> <span data-ttu-id="cd4e9-178">Sie können den Zählwert auswählen, um weitere Details zur Ausführung anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-178">You can select the count value to view more details about the run.</span></span>

- <span data-ttu-id="cd4e9-179">**Fehler (letzte 200 Durchläufe)**: Anzahl der Ausfälle eines Flows von den letzten 200 Durchläufen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-179">**Failures (last 200 runs)**: Number of times a flow has failed out of the last 200 runs.</span></span>

- <span data-ttu-id="cd4e9-180">**Status**: Status des Flows: ein oder aus.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-180">**Status**: Status of the flow: on or off.</span></span> <span data-ttu-id="cd4e9-181">Sie können den Status eines Flows von Microsoft Flow aus aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-181">You can update a flow’s status from Microsoft Flow.</span></span> <span data-ttu-id="cd4e9-182">Weitere Informationen finden Sie unter [Management einer Flows](https://docs.microsoft.com/en-us/flow/get-started-logic-flow#manage-a-flow).</span><span class="sxs-lookup"><span data-stu-id="cd4e9-182">For more information, see [Manage a flow](https://docs.microsoft.com/en-us/flow/get-started-logic-flow#manage-a-flow).</span></span>  

<span data-ttu-id="cd4e9-183">Bei Bedarf können Sie einen Flow auch bearbeiten, indem Sie das Symbol **Bearbeiten** auswählen.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-183">If required, you can also edit a flow by selecting the **Edit** symbol.</span></span> <span data-ttu-id="cd4e9-184">Der Flow-Editor öffnet sich in Microsoft Flow, von wo aus Sie Ihre Änderungen vornehmen können.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-184">The flow editor opens in Microsoft Flow, from which you make your changes.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="cd4e9-185">![Einen Flow bearbeiten](media/edit-flow.png "Einen Flow bearbeiten")</span><span class="sxs-lookup"><span data-stu-id="cd4e9-185">![Edit a flow](media/edit-flow.png "Edit a flow")</span></span>  

<span data-ttu-id="cd4e9-186">Zur Anzeige der Flow-Historie:</span><span class="sxs-lookup"><span data-stu-id="cd4e9-186">To view flow history:</span></span>

1.  <span data-ttu-id="cd4e9-187">Öffnen Sie die Umfrage, für die Sie die Flow-Historie anzeigen möchten, und gehen Sie zu **Umfrage senden** &gt; **Start**.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-187">Open the survey for which you want to view flow history, and go to **Send Survey** &gt; **Home**.</span></span>

2.  <span data-ttu-id="cd4e9-188">Wählen Sie auf der Kachel **Microsoft Flow** **Konfigurierte Flows**.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-188">On the **Microsoft Flow** tile, select **Flows configured**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="cd4e9-189">![Schaltfläche Konfigurierte Flows](media/flows-configured.png "Schaltfläche Konfigurierte Flows")</span><span class="sxs-lookup"><span data-stu-id="cd4e9-189">![Flows configured button](media/flows-configured.png "Flows configured button")</span></span>  

    <span data-ttu-id="cd4e9-190">Es wird ein Raster mit den konfigurierten Flows angezeigt.</span><span class="sxs-lookup"><span data-stu-id="cd4e9-190">A grid with the configured flows is displayed.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="cd4e9-191">![Flow-Historie Details](media/flow-history-details.png "Flow-Historie Details")</span><span class="sxs-lookup"><span data-stu-id="cd4e9-191">![Flow history details](media/flow-history-details.png "Flow history details")</span></span>  

## <a name="see-also"></a><span data-ttu-id="cd4e9-192">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="cd4e9-192">See also</span></span>

[<span data-ttu-id="cd4e9-193">Definieren Sie, wer an einer Umfrage teilnehmen darf</span><span class="sxs-lookup"><span data-stu-id="cd4e9-193">Define who can respond to a survey</span></span>](invite-settings.md)<br>
[<span data-ttu-id="cd4e9-194">Senden Sie eine Umfrage per E-Mail</span><span class="sxs-lookup"><span data-stu-id="cd4e9-194">Send a survey by using email</span></span>](send-survey-email.md)<br>
[<span data-ttu-id="cd4e9-195">Eingebettete Umfrage in eine Webseite</span><span class="sxs-lookup"><span data-stu-id="cd4e9-195">Embed survey in a web page</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="cd4e9-196">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="cd4e9-196">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="cd4e9-197">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="cd4e9-197">Send a survey QR code</span></span>](send-survey-qrcode.md)
