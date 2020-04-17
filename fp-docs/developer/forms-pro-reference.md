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
# <a name="entity-reference-for-microsoft-forms-pro"></a>Entitätsreferenz für Microsoft Forms Pro

Verwenden Sie diese Referenz, um die verfügbaren Vorgänge, die für bestimmte Entitäten, die Standardattributattribute jeder Entität und Beziehungen zwischen Entitäten ausgeführt werden können, zu verstehen.

Im Folgenden finden Sie eine vereinfachte Version des Entitätsbeziehungsdiagramms von Forms Pro-Entitäten. Sie können ein detailliertes Entitätsbeziehungsdiagramm der Forms Pro Entitäten des ausgewählten Elements mit [Metadaten-Diagrammtool](https://code.msdn.microsoft.com/Sample-of-generating-a0ba0e47) erstellen. Dazu brauchen Sie den logischen Entitätsnamen als Parameter, während das Beispiel ausgeführt wird. Weitere Informationen: [Verwenden von Metadaten zum Generieren von Entitätsdiagrammen](https://docs.microsoft.com/dynamics365/customer-engagement/developer/use-metadata-generate-entity-diagrams).

> [!div class=mx-imgBorder]
> ![Vereinfachtes Visualisierungsentitätsbeziehungsdiagramm](../media/er-diagram.png "Vereinfachtes Visualisierungsentitätsbeziehungsdiagramm")

## <a name="entities"></a>Entitäten

|Entitätsname|Beschreibung|
|------|------|
|[msfp_emailtemplate](reference/entities/msfp_emailtemplate.md)|Vorlage für eine E-Mail-Nachricht mit dem Einladungslink für die Befragung|
|[msfp_question](reference/entities/msfp_question.md)|Frage in einer Befragung, um Feedback zu sammeln|
|[msfp_questionresponse](reference/entities/msfp_questionresponse.md)|Antwort auf eine Frage in einer Befragung|
|[msfp_survey](reference/entities/msfp_survey.md)|Fragensatz zum Sammeln von Feedback|
|[msfp_surveyinvite](reference/entities/msfp_surveyinvite.md)|Aktivität zur Nachverfolgung einer an eine Person gesendete Befragungseinladung|
|[msfp_surveyresponse](reference/entities/msfp_surveyresponse.md)|Antwort auf eine Befragung|
|[msfp_unsubscribedrecipient](reference/entities/msfp_unsubscribedrecipient.md)|E-Mail-Adresse des Befragten ohne Abonnement|

### <a name="see-also"></a>Siehe auch

[Entwicklerhandbuch für Formulare Pro](developer-guide.md)<br />
[Entitätsreferenz für Microsoft Dynamics 365](/dynamics365/customer-engagement/developer/about-entity-reference)
