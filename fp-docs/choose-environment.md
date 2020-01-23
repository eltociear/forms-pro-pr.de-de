---
title: Arbeiten mit Umgebungen in Microsoft Forms Pro | Microsoft-Dokumentation
description: Erfahren Sie mehr über das Arbeiten mit Umgebungen in Microsoft Forms Pro.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 04/02/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 90EFF51F-36E3-4973-8768-82F12629B0B3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 9f021e43e7ac29a000a63ae5a7b3270db24d0b8e
ms.sourcegitcommit: 2b2ffca387514568ff95dd1e566ba1850a416744
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2019
ms.locfileid: "2899845"
---
# <a name="work-with-environments"></a><span data-ttu-id="e3365-103">Arbeiten mit Umgebungen</span><span class="sxs-lookup"><span data-stu-id="e3365-103">Work with environments</span></span>

<span data-ttu-id="e3365-104">Bei einer Umgebung handelt es sich um Speicherplatz zum Verwalten und Freigeben der Geschäftsdaten, Apps und Flows Ihres Unternehmens.</span><span class="sxs-lookup"><span data-stu-id="e3365-104">An environment is a space to store, manage, and share your organization's business data, apps, and flows.</span></span> <span data-ttu-id="e3365-105">Es dient auch als Container zur Trennung von Anwendungen, die unterschiedliche Rollen, Sicherheitsanforderungen oder Zielgruppen haben können.</span><span class="sxs-lookup"><span data-stu-id="e3365-105">It also serves as a container to separate apps that might have different roles, security requirements, or target audiences.</span></span> <span data-ttu-id="e3365-106">Weitere Informationen: [Umgebungsübersicht](https://docs.microsoft.com/power-platform/admin/environments-overview)</span><span class="sxs-lookup"><span data-stu-id="e3365-106">More information: [Environments overview](https://docs.microsoft.com/power-platform/admin/environments-overview)</span></span>

<span data-ttu-id="e3365-107">Sie können Umgebungen für verschiedene Zwecke erstellen, z.B. für die Entwicklung, das Testen und die Produktion von Umfragen.</span><span class="sxs-lookup"><span data-stu-id="e3365-107">You can create environments for different purposes such as survey development, testing, and production.</span></span> <span data-ttu-id="e3365-108">Nach der Entwicklung und dem Testen der Umfrage können Sie die Umfrage in die Produktionsumgebung kopieren.</span><span class="sxs-lookup"><span data-stu-id="e3365-108">After developing and testing the survey, you can copy the survey to the production environment.</span></span>

<span data-ttu-id="e3365-109">Wenn Sie sich bei Microsoft Forms Pro anmelden, werden nur die Umfragen angezeigt, die in der ausgewählten Umgebung verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="e3365-109">When you sign in to Microsoft Forms Pro, only the surveys that are available in the selected environment are displayed.</span></span> <span data-ttu-id="e3365-110">Wenn Sie eine Umfrage erstellen, ist die Umfrage mit der ausgewählten Umgebung verbunden und in anderen Umgebungen nicht verfügbar.</span><span class="sxs-lookup"><span data-stu-id="e3365-110">When you create a survey, the survey is connected to the selected environment and isn't available in other environments.</span></span> <span data-ttu-id="e3365-111">Die Einladungen und Antworten werden in der gleichen Umgebung gespeichert, in der auch die Umfrage erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="e3365-111">The invitations and responses are stored in the same environment in which the survey was created.</span></span>

<span data-ttu-id="e3365-112">Sie können die Umgebung jederzeit wechseln und mit der Arbeit in ihr beginnen.</span><span class="sxs-lookup"><span data-stu-id="e3365-112">You can switch the environment at any time and start working in it.</span></span> <span data-ttu-id="e3365-113">Sie können eine Umfrage auch aus einer Umgebung in eine andere kopieren.</span><span class="sxs-lookup"><span data-stu-id="e3365-113">You can also copy a survey from one environment to another.</span></span> <span data-ttu-id="e3365-114">Wenn Sie eine Umfrage in eine andere Umgebung kopieren, werden nur die Umfragestruktur und ihre Verzweigungsregeln kopiert – Einladungen, Antworten und zugehörige Abläufe nicht.</span><span class="sxs-lookup"><span data-stu-id="e3365-114">When you copy a survey to another environment, only the survey structure and its branching rules are copied&mdash;invitations, responses, and associated flows aren't copied.</span></span>

<span data-ttu-id="e3365-115">Um mit Umfragen in einer Umgebung zu arbeiten, installieren Sie die App [Forms Pro von Microsoft AppSource](https://appsource.microsoft.com/product/dynamics-365/mscrm.shimla?tab=Overview) und weisen Sie den Benutzern die Rolle Umfragebesitzer zu.</span><span class="sxs-lookup"><span data-stu-id="e3365-115">To work with surveys in an environment, install the [Forms Pro app from Microsoft AppSource](https://appsource.microsoft.com/product/dynamics-365/mscrm.shimla?tab=Overview), and assign the Survey Owner role to users.</span></span> <span data-ttu-id="e3365-116">Wenn Sie in eine Umgebung wechseln, die nicht über Forms Pro verfügt, wird eine Fehlermeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="e3365-116">If you switch to an environment that doesn't have Forms Pro, an error message is displayed.</span></span>

> [!NOTE]
> <span data-ttu-id="e3365-117">Wenn Sie Organisationen für Dynamics 365 Sales, Customer Service, Marketing und Talent haben, sind Forms Pro-Entitäten bereits in diesen Organisationen installiert.</span><span class="sxs-lookup"><span data-stu-id="e3365-117">If you have organizations for Dynamics 365 Sales, Customer Service, Marketing, and Talent, Forms Pro entities are already installed in these organizations.</span></span>

## <a name="privileges-required"></a><span data-ttu-id="e3365-118">Erforderliche Berechtigungen</span><span class="sxs-lookup"><span data-stu-id="e3365-118">Privileges required</span></span>

- <span data-ttu-id="e3365-119">Stellen Sie sicher, dass Sie den Benutzern die Rolle Umfragebesitzer zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="e3365-119">Ensure that you've assigned the Survey Owner role to users.</span></span>
- <span data-ttu-id="e3365-120">Wenn Sie irgendwelche benutzerdefinierte Entitäten erstellt haben, mit denen Forms Pro interagieren soll, weisen Sie dem Benutzer das Recht **Anhangen an** der Entitäten zu.</span><span class="sxs-lookup"><span data-stu-id="e3365-120">If you've created any custom entities that you want Forms Pro to interact with, assign the **Append To** privilege of the entities to the user.</span></span>

<span data-ttu-id="e3365-121">In diesem Abschnitt erfahren Sie Folgendes:</span><span class="sxs-lookup"><span data-stu-id="e3365-121">In this section, you'll learn how to:</span></span>

- [<span data-ttu-id="e3365-122">Eine Umgebung ändern</span><span class="sxs-lookup"><span data-stu-id="e3365-122">Change an environment</span></span>](change-environment.md)
- [<span data-ttu-id="e3365-123">Kopieren einer Umfrage in eine andere Umgebung</span><span class="sxs-lookup"><span data-stu-id="e3365-123">Copy a survey to another environment</span></span>](copy-survey-environment.md)

