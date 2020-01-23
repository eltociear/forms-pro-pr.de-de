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
# <a name="analyze-survey-invitations"></a>Umfrageeinladungen analysieren

Für jede versendete Umfrage-E-Mail wird ein Umfrage-Einladungsdatensatz erstellt, entweder manuell oder mit Power Automate. Um die Einladungen zu einer Umfrage anzuzeigen, die mit einer Umfrage verknüpft sind, gehen Sie zu **Antworten** &gt; **Übersicht**, und wählen Sie dann **Einladungen** aus den zusammengefassten Informationen.

> [!div class=mx-imgBorder]
> ![Umfrageeinladungen](media/survey-invites.png "Umfrageeinladungen")

Die folgenden Statistiken zu Umfrageeinladungen werden in einem Übersichtsfenster oben auf der Seite angezeigt und die Liste der für eine Umfrage gesendeten Umfrageeinladungen wird unterhalb der Statistiken im Rasterformat angezeigt.

- **Durchschnittliche Bearbeitungszeit**: Durchschnittliche Zeit zwischen dem Senden einer Umfrageeinladung und dem Empfangen einer Umfrageantwort. Die unbeantworteten Umfrageeinladungen werden dabei ignoriert.

- **Fehlgeschlagene Einladungen**: Anzahl der fehlgeschlagenen Einladungen in der letzten Woche.

- **Einladungsstatus**: Ein Kreisdiagramm, das die Verteilung der Einladungen zu Umfragen nach Status darstellt. Die folgenden Status werden angezeigt:

  - **In Warteschlange**: Die Umfrage-Einladungs-E-Mail wird für den Versand in eine Warteschlange gesetzt.
  - **Gesendet**: Die Umfrage-Einladungs-E-Mail wurde erfolgreich zum Empfänger übermittelt.
  - **Fehlgeschlagen**: Die E-Mail mit der Einladung zur Umfrage wurde aufgrund einer falschen E-Mail-Adresse oder eines anderen Fehlers nicht an den Empfänger gesendet.
  - **Hat geantwortet**: Der Empfänger hat auf die Umfrage geantwortet.
  - **Abbestellt**: Der Empfänger hat den Empfang der umfragebezogenen E-Mails abbestellt.

- **Einladungstrend**: Ein Liniendiagramm, das die Verteilung der Trends bei der Einladung zur Umfrage zeigt.

> [!div class=mx-imgBorder]
> ![Umfrageeinladungsdetails](media/survey-invites-details.png "Umfrageeinladungsdetails")

## <a name="filter-invitations"></a>Einladungen filtern

Sie können die Einladungen wie folgt filtern:

- **Vordefinierte Filter**: Verwenden Sie die Filter Gesendet, Beantwortet, In Bearbeitung, Fehlgeschlagen und Nicht angemeldet, um die Einladungen zu filtern.

- **Datumsbereich**: Wählen Sie 30 Tage, 90 Tage oder einen benutzerdefinierten Datumsbereich.

- **Name oder E-Mail-Adresse des Empfängers**: Geben Sie den Namen oder die E-Mail-Adresse des Empfängers in das Suchfeld ein.

## <a name="export-survey-invitations"></a>Einladungen zu Umfragen exportieren

Sie können eine einzelne Umfrageeinladung oder mehrere Umfrageeinladungen auf Microsoft Excel exportieren. Um Umfrageeinladungen zu exportieren, wählen Sie die gewünschte(n) Einladung(en) aus und wählen Sie dann **Export** im Abschnitt **Einladungsdetails**.

Jede Einladungseigenschaft ist eine Spalte, und jede Einladung wird zu einer Zeile in der Excel-Arbeitsmappe.

> [!div class=mx-imgBorder]
> ![Einladungen zu Umfragen exportieren](media/export-survey-invite.png "Einladungen zu Umfragen exportieren")

## <a name="delete-survey-invitations"></a>Umfrageeinladungen löschen

Sie können eine einzelne Umfrageeinladung oder mehrere Umfrageeinladungen aus Forms, Common Data Service und dem Erkenntnisspeicher löschen. Wenn eine Umfrageeinladung gelöscht wird, wird auch die zugehörige Umfrageantwort gelöscht.

Um Umfrageeinladungen zu löschen, markieren Sie die gewünschten Einladungen und wählen Sie dann **Löschen** im Abschnitt **Einladungsdetails** aus. Wählen Sie **Löschen** in der Bestätigungsmeldung.

> [!div class=mx-imgBorder]
> ![Umfrageeinladungen löschen](media/delete-survey-invite.png "Umfrageeinladungen löschen")

### <a name="see-also"></a>Siehe auch

[Zusammenfassende Informationen für Ihre Umfrage anzeigen](view-summary-information.md)<br>
[Details für jede Frage anzeigen](view-details-each-question.md)<br>
[Auswerten von Umfrageantworten](analyze-survey-responses.md)<br>
[Analysieren Sie die Erkenntnisse aus Umfragen](analyze-survey-insights.md)
