---
title: Entitätsreferenz für Playbooks Microsoft Forms Pro  | MicrosoftDocs
description: Referenzdokumentation für die Entität von Microsoft Forms Pro.
keywords: ''
author: susikka
ms.author: susikka
manager: shujoshi
applies_to: ''
ms.date: 03/24/2020
ms.service: forms-pro
ms.topic: reference
ms.assetid: 0CCDE7D8-E6D8-4892-B293-A4F39DEE4B06
ms.custom: ''
search.audienceType:
- developer
search.app:
- PowerApps
- D365CE
search.appverid:
- FPR160
ms.openlocfilehash: 753fcc6029cdf0fc7c2e74d1240162580861d2b7
ms.sourcegitcommit: 38563d8ed7de1c1d1d54c2b5cbd2d46c52c2478a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2020
ms.locfileid: "3161248"
---
# <a name="entity-reference-for-microsoft-forms-pro"></a><span data-ttu-id="49793-103">Entitätsreferenz für Microsoft Forms Pro</span><span class="sxs-lookup"><span data-stu-id="49793-103">Entity Reference for Microsoft Forms Pro</span></span>

<span data-ttu-id="49793-104">Verwenden Sie diese Referenz, um die verfügbaren Vorgänge, die für bestimmte Entitäten, die Standardattributattribute jeder Entität und Beziehungen zwischen Entitäten ausgeführt werden können, zu verstehen.</span><span class="sxs-lookup"><span data-stu-id="49793-104">Use this reference to understand the available operations that can be performed on specific entities, the default attributes of each entity and the relationship between entities.</span></span>

<span data-ttu-id="49793-105">Im Folgenden finden Sie eine vereinfachte Version des Entitätsbeziehungsdiagramms von Forms Pro-Entitäten.</span><span class="sxs-lookup"><span data-stu-id="49793-105">Following is a simplified version of the entity relationship diagram of Forms Pro entities.</span></span> <span data-ttu-id="49793-106">Sie können ein detailliertes Entitätsbeziehungsdiagramm der Forms Pro Entitäten des ausgewählten Elements mit [Metadaten-Diagrammtool](https://code.msdn.microsoft.com/Sample-of-generating-a0ba0e47) erstellen.</span><span class="sxs-lookup"><span data-stu-id="49793-106">You can generate a detailed entity relationship diagram of Forms Pro entities using the [Metadata Diagram tool](https://code.msdn.microsoft.com/Sample-of-generating-a0ba0e47).</span></span> <span data-ttu-id="49793-107">Dazu brauchen Sie den logischen Entitätsnamen als Parameter, während das Beispiel ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="49793-107">To do this, you will just have to mention the entity logical names as parameters while executing the sample.</span></span> <span data-ttu-id="49793-108">Weitere Informationen: [Verwenden von Metadaten zum Generieren von Entitätsdiagrammen](https://docs.microsoft.com/dynamics365/customer-engagement/developer/use-metadata-generate-entity-diagrams).</span><span class="sxs-lookup"><span data-stu-id="49793-108">More information: [Use metadata to generate entity diagrams](https://docs.microsoft.com/dynamics365/customer-engagement/developer/use-metadata-generate-entity-diagrams).</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="49793-109">![Vereinfachtes Visualisierungsentitätsbeziehungsdiagramm](../media/er-diagram.png "Vereinfachtes Visualisierungsentitätsbeziehungsdiagramm")</span><span class="sxs-lookup"><span data-stu-id="49793-109">![Simplified entity relationship diagram](../media/er-diagram.png "Simplified entity relationship diagram")</span></span>

## <a name="entities"></a><span data-ttu-id="49793-110">Entitäten</span><span class="sxs-lookup"><span data-stu-id="49793-110">Entities</span></span>

|<span data-ttu-id="49793-111">Entitätsname</span><span class="sxs-lookup"><span data-stu-id="49793-111">Entity name</span></span>|<span data-ttu-id="49793-112">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="49793-112">Description</span></span>|
|------|------|
|[<span data-ttu-id="49793-113">msfp_emailtemplate</span><span class="sxs-lookup"><span data-stu-id="49793-113">msfp_emailtemplate</span></span>](reference/entities/msfp_emailtemplate.md)|<span data-ttu-id="49793-114">Vorlage für eine E-Mail-Nachricht mit dem Einladungslink für die Befragung</span><span class="sxs-lookup"><span data-stu-id="49793-114">Template for an email message that contains the survey invitation link.</span></span>|
|[<span data-ttu-id="49793-115">msfp_question</span><span class="sxs-lookup"><span data-stu-id="49793-115">msfp_question</span></span>](reference/entities/msfp_question.md)|<span data-ttu-id="49793-116">Frage in einer Befragung, um Feedback zu sammeln</span><span class="sxs-lookup"><span data-stu-id="49793-116">Question in a survey to collect feedback.</span></span>|
|[<span data-ttu-id="49793-117">msfp_questionresponse</span><span class="sxs-lookup"><span data-stu-id="49793-117">msfp_questionresponse</span></span>](reference/entities/msfp_questionresponse.md)|<span data-ttu-id="49793-118">Antwort auf eine Frage in einer Befragung</span><span class="sxs-lookup"><span data-stu-id="49793-118">Response to a question in a survey.</span></span>|
|[<span data-ttu-id="49793-119">msfp_survey</span><span class="sxs-lookup"><span data-stu-id="49793-119">msfp_survey</span></span>](reference/entities/msfp_survey.md)|<span data-ttu-id="49793-120">Fragensatz zum Sammeln von Feedback</span><span class="sxs-lookup"><span data-stu-id="49793-120">Set of questions to collect feedback.</span></span>|
|[<span data-ttu-id="49793-121">msfp_surveyinvite</span><span class="sxs-lookup"><span data-stu-id="49793-121">msfp_surveyinvite</span></span>](reference/entities/msfp_surveyinvite.md)|<span data-ttu-id="49793-122">Aktivität zur Nachverfolgung einer an eine Person gesendete Befragungseinladung</span><span class="sxs-lookup"><span data-stu-id="49793-122">Activity that tracks a survey invitation sent to a person.</span></span>|
|[<span data-ttu-id="49793-123">msfp_surveyresponse</span><span class="sxs-lookup"><span data-stu-id="49793-123">msfp_surveyresponse</span></span>](reference/entities/msfp_surveyresponse.md)|<span data-ttu-id="49793-124">Antwort auf eine Befragung</span><span class="sxs-lookup"><span data-stu-id="49793-124">Response to a survey.</span></span>|
|[<span data-ttu-id="49793-125">msfp_unsubscribedrecipient</span><span class="sxs-lookup"><span data-stu-id="49793-125">msfp_unsubscribedrecipient</span></span>](reference/entities/msfp_unsubscribedrecipient.md)|<span data-ttu-id="49793-126">E-Mail-Adresse des Befragten ohne Abonnement</span><span class="sxs-lookup"><span data-stu-id="49793-126">Email address of an unsubscribed respondent.</span></span>|

### <a name="see-also"></a><span data-ttu-id="49793-127">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="49793-127">See also</span></span>

[<span data-ttu-id="49793-128">Entwicklerhandbuch für Formulare Pro</span><span class="sxs-lookup"><span data-stu-id="49793-128">Developer guide for Forms Pro</span></span>](developer-guide.md)<br />
[<span data-ttu-id="49793-129">Entitätsreferenz für Microsoft Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="49793-129">Entity reference for Microsoft Dynamics 365</span></span>](/dynamics365/customer-engagement/developer/about-entity-reference)
