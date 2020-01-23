---
title: Umfrageeinladungen analysieren | MicrosoftDocs
description: Anleitung zur Analyse von Umfrageeinladungen
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 12/07/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: efa240ce-9ef0-40e6-b634-143a347201e9
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 18d757f96fa436af4847438c94d3aa1c132b3253
ms.sourcegitcommit: 2b2ffca387514568ff95dd1e566ba1850a416744
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2019
ms.locfileid: "2899977"
---
# <a name="analyze-survey-invitations"></a><span data-ttu-id="a55fc-103">Umfrageeinladungen analysieren</span><span class="sxs-lookup"><span data-stu-id="a55fc-103">Analyze survey invitations</span></span>

<span data-ttu-id="a55fc-104">Für jede versendete Umfrage-E-Mail wird ein Umfrage-Einladungsdatensatz erstellt, entweder manuell oder mit Power Automate.</span><span class="sxs-lookup"><span data-stu-id="a55fc-104">A survey invitation record is created for each survey email that's sent, either manually or with Power Automate.</span></span> <span data-ttu-id="a55fc-105">Um die Einladungen zu einer Umfrage anzuzeigen, die mit einer Umfrage verknüpft sind, gehen Sie zu **Antworten** &gt; **Übersicht**, und wählen Sie dann **Einladungen** aus den zusammengefassten Informationen.</span><span class="sxs-lookup"><span data-stu-id="a55fc-105">To see the survey invitations associated with a survey, go to **Responses** &gt; **Overview**, and then select **Invitations** from the summary information.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="a55fc-106">![Umfrageeinladungen](media/survey-invites.png "Umfrageeinladungen")</span><span class="sxs-lookup"><span data-stu-id="a55fc-106">![Survey invitations](media/survey-invites.png "Survey invitations")</span></span>

<span data-ttu-id="a55fc-107">Die folgenden Statistiken zu Umfrageeinladungen werden in einem Übersichtsfenster oben auf der Seite angezeigt und die Liste der für eine Umfrage gesendeten Umfrageeinladungen wird unterhalb der Statistiken im Rasterformat angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a55fc-107">The following survey invitation statistics are displayed in a summary pane at the top of the page and the list of survey invitations sent for a survey is displayed below the statistics in the grid format.</span></span>

- <span data-ttu-id="a55fc-108">**Durchschnittliche Bearbeitungszeit**: Durchschnittliche Zeit zwischen dem Senden einer Umfrageeinladung und dem Empfangen einer Umfrageantwort.</span><span class="sxs-lookup"><span data-stu-id="a55fc-108">**Average turnaround time**: Average time between sending a survey invitation and receiving a survey response.</span></span> <span data-ttu-id="a55fc-109">Die unbeantworteten Umfrageeinladungen werden dabei ignoriert.</span><span class="sxs-lookup"><span data-stu-id="a55fc-109">The unanswered survey invitations are ignored for this.</span></span>

- <span data-ttu-id="a55fc-110">**Fehlgeschlagene Einladungen**: Anzahl der fehlgeschlagenen Einladungen in der letzten Woche.</span><span class="sxs-lookup"><span data-stu-id="a55fc-110">**Failed invitations**: Number of failed invitations in the last week.</span></span>

- <span data-ttu-id="a55fc-111">**Einladungsstatus**: Ein Kreisdiagramm, das die Verteilung der Einladungen zu Umfragen nach Status darstellt.</span><span class="sxs-lookup"><span data-stu-id="a55fc-111">**Invitation status**: A pie chart showing the distribution of survey invitations by status.</span></span> <span data-ttu-id="a55fc-112">Die folgenden Status werden angezeigt:</span><span class="sxs-lookup"><span data-stu-id="a55fc-112">The following statuses are displayed:</span></span>

  - <span data-ttu-id="a55fc-113">**In Warteschlange**: Die Umfrage-Einladungs-E-Mail wird für den Versand in eine Warteschlange gesetzt.</span><span class="sxs-lookup"><span data-stu-id="a55fc-113">**Queued**: The survey invitation email is queued to be sent.</span></span>
  - <span data-ttu-id="a55fc-114">**Gesendet**: Die Umfrage-Einladungs-E-Mail wurde erfolgreich zum Empfänger übermittelt.</span><span class="sxs-lookup"><span data-stu-id="a55fc-114">**Sent**: The survey invitation email has been successfully delivered to the recipient.</span></span>
  - <span data-ttu-id="a55fc-115">**Fehlgeschlagen**: Die E-Mail mit der Einladung zur Umfrage wurde aufgrund einer falschen E-Mail-Adresse oder eines anderen Fehlers nicht an den Empfänger gesendet.</span><span class="sxs-lookup"><span data-stu-id="a55fc-115">**Failed**: The survey invitation email wasn't delivered to the recipient due to an incorrect email address or any other error.</span></span>
  - <span data-ttu-id="a55fc-116">**Hat geantwortet**: Der Empfänger hat auf die Umfrage geantwortet.</span><span class="sxs-lookup"><span data-stu-id="a55fc-116">**Responded**: The recipient has responded to the survey.</span></span>
  - <span data-ttu-id="a55fc-117">**Abbestellt**: Der Empfänger hat den Empfang der umfragebezogenen E-Mails abbestellt.</span><span class="sxs-lookup"><span data-stu-id="a55fc-117">**Unsubscribed**: The recipient has unsubscribed from receiving the survey-related emails.</span></span>

- <span data-ttu-id="a55fc-118">**Einladungstrend**: Ein Liniendiagramm, das die Verteilung der Trends bei der Einladung zur Umfrage zeigt.</span><span class="sxs-lookup"><span data-stu-id="a55fc-118">**Invitation trend**: A line chart showing the distribution of survey invitation trends.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="a55fc-119">![Umfrageeinladungsdetails](media/survey-invites-details.png "Umfrageeinladungsdetails")</span><span class="sxs-lookup"><span data-stu-id="a55fc-119">![Survey invitation details](media/survey-invites-details.png "Survey invitation details")</span></span>

## <a name="filter-invitations"></a><span data-ttu-id="a55fc-120">Einladungen filtern</span><span class="sxs-lookup"><span data-stu-id="a55fc-120">Filter invitations</span></span>

<span data-ttu-id="a55fc-121">Sie können die Einladungen wie folgt filtern:</span><span class="sxs-lookup"><span data-stu-id="a55fc-121">You can filter the invitations by using the following:</span></span>

- <span data-ttu-id="a55fc-122">**Vordefinierte Filter**: Verwenden Sie die Filter Gesendet, Beantwortet, In Bearbeitung, Fehlgeschlagen und Nicht angemeldet, um die Einladungen zu filtern.</span><span class="sxs-lookup"><span data-stu-id="a55fc-122">**Pre-defined filters**: Use the Sent, Responded, In Progress, Failed, and Unsubscribed filters to filter the invitations.</span></span>

- <span data-ttu-id="a55fc-123">**Datumsbereich**: Wählen Sie 30 Tage, 90 Tage oder einen benutzerdefinierten Datumsbereich.</span><span class="sxs-lookup"><span data-stu-id="a55fc-123">**Date range**: Select 30 days, 90 days, or a custom date range.</span></span>

- <span data-ttu-id="a55fc-124">**Name oder E-Mail-Adresse des Empfängers**: Geben Sie den Namen oder die E-Mail-Adresse des Empfängers in das Suchfeld ein.</span><span class="sxs-lookup"><span data-stu-id="a55fc-124">**Recipient's name or email address**: Enter the recipient's name or email address in the search box.</span></span>

## <a name="export-survey-invitations"></a><span data-ttu-id="a55fc-125">Einladungen zu Umfragen exportieren</span><span class="sxs-lookup"><span data-stu-id="a55fc-125">Export survey invitations</span></span>

<span data-ttu-id="a55fc-126">Sie können eine einzelne Umfrageeinladung oder mehrere Umfrageeinladungen auf Microsoft Excel exportieren.</span><span class="sxs-lookup"><span data-stu-id="a55fc-126">You can export a single survey invitation or multiple survey invitations to Microsoft Excel.</span></span> <span data-ttu-id="a55fc-127">Um Umfrageeinladungen zu exportieren, wählen Sie die gewünschte(n) Einladung(en) aus und wählen Sie dann **Export** im Abschnitt **Einladungsdetails**.</span><span class="sxs-lookup"><span data-stu-id="a55fc-127">To export survey invitation(s), select the required invitation(s), and then select **Export** in the **Invitations details** section.</span></span>

<span data-ttu-id="a55fc-128">Jede Einladungseigenschaft ist eine Spalte, und jede Einladung wird zu einer Zeile in der Excel-Arbeitsmappe.</span><span class="sxs-lookup"><span data-stu-id="a55fc-128">Each invitation property is a column, and each invitation becomes a row in the Excel workbook.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="a55fc-129">![Einladungen zu Umfragen exportieren](media/export-survey-invite.png "Einladungen zu Umfragen exportieren")</span><span class="sxs-lookup"><span data-stu-id="a55fc-129">![Export survey invitations](media/export-survey-invite.png "Export survey invitations")</span></span>

## <a name="delete-survey-invitations"></a><span data-ttu-id="a55fc-130">Umfrageeinladungen löschen</span><span class="sxs-lookup"><span data-stu-id="a55fc-130">Delete survey invitations</span></span>

<span data-ttu-id="a55fc-131">Sie können eine einzelne Umfrageeinladung oder mehrere Umfrageeinladungen aus Forms, Common Data Service und dem Erkenntnisspeicher löschen.</span><span class="sxs-lookup"><span data-stu-id="a55fc-131">You can delete a single survey invitation or multiple survey invitations from Forms, Common Data Service, and the insights store.</span></span> <span data-ttu-id="a55fc-132">Wenn eine Umfrageeinladung gelöscht wird, wird auch die zugehörige Umfrageantwort gelöscht.</span><span class="sxs-lookup"><span data-stu-id="a55fc-132">When a survey invitation is deleted, the associated survey response is also deleted.</span></span>

<span data-ttu-id="a55fc-133">Um Umfrageeinladungen zu löschen, markieren Sie die gewünschten Einladungen und wählen Sie dann **Löschen** im Abschnitt **Einladungsdetails** aus.</span><span class="sxs-lookup"><span data-stu-id="a55fc-133">To delete survey invitations, select the required invitations, and then select **Delete** in the **Invitations details** section.</span></span> <span data-ttu-id="a55fc-134">Wählen Sie **Löschen** in der Bestätigungsmeldung.</span><span class="sxs-lookup"><span data-stu-id="a55fc-134">Select **Delete** in the confirmation message.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="a55fc-135">![Umfrageeinladungen löschen](media/delete-survey-invite.png "Umfrageeinladungen löschen")</span><span class="sxs-lookup"><span data-stu-id="a55fc-135">![Delete survey invitations](media/delete-survey-invite.png "Delete survey invitations")</span></span>

### <a name="see-also"></a><span data-ttu-id="a55fc-136">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="a55fc-136">See also</span></span>

[<span data-ttu-id="a55fc-137">Zusammenfassende Informationen für Ihre Umfrage anzeigen</span><span class="sxs-lookup"><span data-stu-id="a55fc-137">View summary information for your survey</span></span>](view-summary-information.md)<br>
[<span data-ttu-id="a55fc-138">Details für jede Frage anzeigen</span><span class="sxs-lookup"><span data-stu-id="a55fc-138">View details for each question</span></span>](view-details-each-question.md)<br>
[<span data-ttu-id="a55fc-139">Auswerten von Umfrageantworten</span><span class="sxs-lookup"><span data-stu-id="a55fc-139">Analyze survey responses</span></span>](analyze-survey-responses.md)<br>
[<span data-ttu-id="a55fc-140">Analysieren Sie die Erkenntnisse aus Umfragen</span><span class="sxs-lookup"><span data-stu-id="a55fc-140">Analyze survey insights</span></span>](analyze-survey-insights.md)
