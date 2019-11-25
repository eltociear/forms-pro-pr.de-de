---
title: Entitätsreferenz für Playbooks Microsoft Forms Pro  | MicrosoftDocs
description: Referenzdokumentation für die Entität von Microsoft Forms Pro.
keywords: ''
author: susikka
ms.author: susikka
manager: shujoshi
applies_to: ''
ms.date: 04/29/2019
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
ms.openlocfilehash: 3f3ec1673db98e18b990aed9d98647f6b105ddb6
ms.sourcegitcommit: 3225337823216f21b569779b829f069f53aa3742
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/04/2019
ms.locfileid: "2750692"
---
# <a name="entity-reference-for-microsoft-forms-pro"></a><span data-ttu-id="b7f92-103">Entitätsreferenz für Microsoft Forms Pro</span><span class="sxs-lookup"><span data-stu-id="b7f92-103">Entity Reference for Microsoft Forms Pro</span></span>

<span data-ttu-id="b7f92-104">Verwenden Sie diese Referenz, um die verfügbaren Vorgänge, die für bestimmte Entitäten, die Standardattributattribute jeder Entität und Beziehungen zwischen Entitäten ausgeführt werden können, zu verstehen.</span><span class="sxs-lookup"><span data-stu-id="b7f92-104">Use this reference to understand the available operations that can be performed on specific entities, the default attributes of each entity and the relationship between entities.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="b7f92-105">Sie können ein Entitätsbeziehungsdiagramm der Entitäten des ausgewählten Elements mit [Metadaten-Diagrammtool](https://code.msdn.microsoft.com/Sample-of-generating-a0ba0e47) erstellen.</span><span class="sxs-lookup"><span data-stu-id="b7f92-105">You can generate an entity relationship diagram of the entities of your choice using the [Metadata Diagram tool](https://code.msdn.microsoft.com/Sample-of-generating-a0ba0e47).</span></span> <span data-ttu-id="b7f92-106">Dazu brauchen Sie den logischen Entitätsnamen als Parameter, während das Beispiel ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b7f92-106">To do this, you will just have to mention the entity logical names as parameters while executing the sample.</span></span> <span data-ttu-id="b7f92-107">Weitere Informationen: [Verwenden von Metadaten zum Generieren von Entitätsdiagrammen](https://docs.microsoft.com/dynamics365/customer-engagement/developer/use-metadata-generate-entity-diagrams).</span><span class="sxs-lookup"><span data-stu-id="b7f92-107">More information: [Use metadata to generate entity diagrams](https://docs.microsoft.com/dynamics365/customer-engagement/developer/use-metadata-generate-entity-diagrams).</span></span>

## <a name="entities"></a><span data-ttu-id="b7f92-108">Entitäten</span><span class="sxs-lookup"><span data-stu-id="b7f92-108">Entities</span></span>

|<span data-ttu-id="b7f92-109">Entitätsname</span><span class="sxs-lookup"><span data-stu-id="b7f92-109">Entity name</span></span>|<span data-ttu-id="b7f92-110">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="b7f92-110">Description</span></span>|
|------|------|
|[<span data-ttu-id="b7f92-111">msfp_emailtemplate</span><span class="sxs-lookup"><span data-stu-id="b7f92-111">msfp_emailtemplate</span></span>](reference/entities/msfp_emailtemplate.md)|<span data-ttu-id="b7f92-112">Vorlage für eine E-Mail-Nachricht mit dem Einladungslink für die Befragung</span><span class="sxs-lookup"><span data-stu-id="b7f92-112">Template for an email message that contains the survey invitation link.</span></span>|
|[<span data-ttu-id="b7f92-113">msfp_question</span><span class="sxs-lookup"><span data-stu-id="b7f92-113">msfp_question</span></span>](reference/entities/msfp_question.md)|<span data-ttu-id="b7f92-114">Frage in einer Befragung, um Feedback zu sammeln</span><span class="sxs-lookup"><span data-stu-id="b7f92-114">Question in a survey to collect feedback.</span></span>|
|[<span data-ttu-id="b7f92-115">msfp_questionresponse</span><span class="sxs-lookup"><span data-stu-id="b7f92-115">msfp_questionresponse</span></span>](reference/entities/msfp_questionresponse.md)|<span data-ttu-id="b7f92-116">Antwort auf eine Frage in einer Befragung</span><span class="sxs-lookup"><span data-stu-id="b7f92-116">Response to a question in a survey.</span></span>|
|[<span data-ttu-id="b7f92-117">msfp_survey</span><span class="sxs-lookup"><span data-stu-id="b7f92-117">msfp_survey</span></span>](reference/entities/msfp_survey.md)|<span data-ttu-id="b7f92-118">Fragensatz zum Sammeln von Feedback</span><span class="sxs-lookup"><span data-stu-id="b7f92-118">Set of questions to collect feedback.</span></span>|
|[<span data-ttu-id="b7f92-119">msfp_surveyinvite</span><span class="sxs-lookup"><span data-stu-id="b7f92-119">msfp_surveyinvite</span></span>](reference/entities/msfp_surveyinvite.md)|<span data-ttu-id="b7f92-120">Aktivität zur Nachverfolgung einer an eine Person gesendete Befragungseinladung</span><span class="sxs-lookup"><span data-stu-id="b7f92-120">Activity that tracks a survey invitation sent to a person.</span></span>|
|[<span data-ttu-id="b7f92-121">msfp_surveyresponse</span><span class="sxs-lookup"><span data-stu-id="b7f92-121">msfp_surveyresponse</span></span>](reference/entities/msfp_surveyresponse.md)|<span data-ttu-id="b7f92-122">Antwort auf eine Befragung</span><span class="sxs-lookup"><span data-stu-id="b7f92-122">Response to a survey.</span></span>|
|[<span data-ttu-id="b7f92-123">msfp_unsubscribedrecipient</span><span class="sxs-lookup"><span data-stu-id="b7f92-123">msfp_unsubscribedrecipient</span></span>](reference/entities/msfp_unsubscribedrecipient.md)|<span data-ttu-id="b7f92-124">E-Mail-Adresse des Befragten ohne Abonnement</span><span class="sxs-lookup"><span data-stu-id="b7f92-124">Email address of an unsubscribed respondent.</span></span>|

## <a name="see-also"></a><span data-ttu-id="b7f92-125">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="b7f92-125">See also</span></span>

[<span data-ttu-id="b7f92-126">Entwicklerhandbuch für Formulare Pro</span><span class="sxs-lookup"><span data-stu-id="b7f92-126">Developer guide for Forms Pro</span></span>](developer-guide.md)<br />
[<span data-ttu-id="b7f92-127">Entitätsreferenz für Microsoft Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="b7f92-127">Entity reference for Microsoft Dynamics 365</span></span>](/dynamics365/customer-engagement/developer/about-entity-reference)
