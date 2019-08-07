---
title: Arbeiten mit Umgebungen | MicrosoftDocs
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
ms.openlocfilehash: 3d6538d7dfc0c0c02ebdc5f69f9be09529d58d0c
ms.sourcegitcommit: 4f20bfe750e8d4eb2db4dca0479699eb365c8c9e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2019
ms.locfileid: "1723991"
---
# <a name="work-with-environments"></a>Arbeiten mit Umgebungen



Eine Umgebung ist ein Bereich zum Speichern, Verwalten und Freigeben der Geschäftsdaten, Anwendungen und Abläufe Ihres Unternehmens. Es dient auch als Container zur Trennung von Anwendungen, die unterschiedliche Rollen, Sicherheitsanforderungen oder Zielgruppen haben können. Mehr Informationen: [Umgebungsübersicht](https://docs.microsoft.com/en-us/power-platform/admin/environments-overview).

Sie können Umgebungen für verschiedene Zwecke erstellen, z.B. für die Entwicklung, das Testen und die Produktion von Umfragen. Nach der Entwicklung und dem Testen der Umfrage können Sie die Umfrage in die Produktionsumgebung kopieren.

Wenn Sie sich bei Microsoft Forms Pro anmelden, werden nur die Umfragen angezeigt, die in der ausgewählten Umgebung verfügbar sind. Wenn Sie eine Umfrage erstellen, ist die Umfrage mit der ausgewählten Umgebung verbunden und in anderen Umgebungen nicht verfügbar. Die Einladungen und Antworten werden in der gleichen Umgebung gespeichert, in der auch die Umfrage erstellt wird. 

Sie können die Umgebung jederzeit wechseln und mit der Arbeit in ihr beginnen. Sie können eine Umfrage auch aus einer Umgebung in eine andere kopieren. Wenn Sie eine Umfrage in eine andere Umgebung kopieren, werden nur die Umfragestruktur und ihre Verzweigungsregeln kopiert - Einladungen, Antworten und zugehörige Abläufe nicht.

Um mit Umfragen in einer Umgebung zu arbeiten, installieren Sie die App [Forms Pro von Microsoft AppSource](https://appsource.microsoft.com/en-us/product/dynamics-365/mscrm.shimla?tab=Overview) und weisen Sie den Benutzern die Rolle Umfragebesitzer zu. Wenn Sie in eine Umgebung wechseln, die nicht über Forms Pro verfügt, wird eine Fehlermeldung angezeigt.

> [!NOTE]
> Wenn Sie Organisationen für Dynamics 365 for Sales, Customer Service, Marketing und Talent haben, sind Forms Pro Einheiten bereits in diesen Organisationen installiert.

## <a name="privileges-required"></a>Erforderliche Berechtigungen

- Stellen Sie sicher, dass Sie den Benutzern die Rolle Umfrageeigentümer zugeordnet haben.
- Wenn Sie benutzerdefinierte Entitäten erstellt haben, mit denen Forms Pro interagieren soll, weisen Sie dem Benutzer das Privileg **Anhangen an** der Entitäten zu.

In diesem Abschnitt erfahren Sie Folgendes:

- [Eine Umgebung ändern](change-environment.md)
- [Kopieren einer Umfrage in eine andere Umgebung](copy-survey-environment.md)

