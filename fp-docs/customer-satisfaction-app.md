---
title: Kundenzufriedenheits-App | MicrosoftDocs
description: Anweisungen zum Verwenden von Forms Pro-Kundenzufriedenheits-App
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/25/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 7771F115-DD60-4084-A8C3-A0DDBC2128A3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: a6656c154ab1a3a47df0edb73816772b18bd6917
ms.sourcegitcommit: 2b2ffca387514568ff95dd1e566ba1850a416744
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2019
ms.locfileid: "2900469"
---
# <a name="monitor-customer-satisfaction"></a>Kundenzufriedenheit überwachen

Verwenden Sie die Microsoft Forms Pro-Kundenzufriedenheits-App, um ein Erkenntnisbericht zu erhalten, der Kundenfeedback mit den Anfragen verknüpft, wenn Sie Forms Pro verwenden, um eine Umfrage nach dem Anfrageabschluss in Dynamics 365 Customer Service zu senden. Sie können den durchschnittlichen Net Promoter Score (NPS) zusätzlich zum individuellen NPS Ihrer Agenten und Kunden anzeigen. Mit dieser App können Sie den Bericht nach Anfrageparametern wie Priorität, Standort, Produkt usw. filtern. Eine Umfragemetrik – wie Anzahl gesendeter Umfrageeinladungen, Anzahl erhaltener Umfrageantworten, NPS, Stimmung und Schlüsselbegriffe – werden auch im Bericht angezeigt. Sie können diese Berichte bearbeiten und sie für Ihre Anforderungen anpassen.

## <a name="install-the-forms-pro-customer-satisfaction-app"></a>Die Forms Pro-Kundenzufriedenheits-App installieren

Die Forms Pro-Kundenzufriedenheits-App ist eine Vorlagen-App, die mithilfe von Power BI erstellt wurde. Mit dieser App können Sie die Zufriedenheit Ihrer Kunden und die Leistung Ihrer Agenten ermitteln. Sie können eine Verbindung zu Ihrer Dynamics 365 Customer Service-Instanz herstellen, um Erkenntnisse anhand Ihrer Geschäftsdaten anzuzeigen. Die App enthält Beispieldaten, durch die Sie navigieren können, während Sie die App erkunden. Außerdem erhalten Sie die Möglichkeit, den Arbeitsbereich entsprechend Ihren Bedürfnissen zu bearbeiten und anzupassen.

Weitere Informationen zu Vorlagen-Apps finden Sie unter [Was sind Power BI-Vorlagen-Apps?](https://docs.microsoft.com/power-bi/service-template-apps-overview).

Schritte zum Installieren einer Vorlagen-App und erste Schritte finden Sie unter [Installieren und Verteilen von Vorlagen-Apps](https://docs.microsoft.com/power-bi/service-template-apps-install-distribute).

### <a name="connect-to-dynamics-365-customer-service-data"></a>Eine Verbindung zu Dynamics 365 Customer Service-Daten herstellen

Wenn Sie eine Verbindung zu Dynamics 365 Customer Service-Daten herstellen möchten, geben Sie die URL ein, die Ihrer Dynamics 365 Customer Service-Instanz zugeordnet ist, und wählen Sie dann **Weiter** aus. Wenn Sie dazu aufgefordert werden, wählen Sie **oAuth2** als die Authentifizierungsmethode aus, wählen Sie **Anmelden** aus, und geben Sie dann Ihre Anmeldeinformationen ein.

> [!NOTE]
> Wir empfehlen, dass Sie die neueste Version von Dynamics 365 Customer Service verwenden.

## <a name="report"></a>(Bericht)

Die Forms Pro-Kundenzufriedenheits-App zeigt Erkenntnisse in einem Bericht mit den folgenden Seiten an:

- [Übersicht](#overview)
- [Agentenleistung](#agent-performance)
- [Kundenzufriedenheit](#customer-satisfaction)

Sie können die Daten mithilfe des Filters **Datum** oben im Bericht filtern. Die Daten werden anhand der Umfrage-Einladungen gefiltert, die während der ausgewählten Zeitperiode gesendet werden. Wir nehmen einmal an, Sie haben 100 Umfrage-Einladungen während der ausgewählten Zeitperiode gesendet. Sie haben 60 Antworten innerhalb der Zeitperiode und 20 Antworten 20 nach der Zeitperiode erhalten. Die 20 Antworten werden ebenfalls in den Bericht einbezogen.

Wenn Sie eine andere Umfrage zur Anzeige von Erkenntnissen auswählen möchten, können Sie dies über den Bereich **Filter** auf der rechten Seite des Berichts erledigen. Öffnen Sie den Bereich und wählen Sie dann eine Umfrage aus dem Filter **Umfragename** unter **Filter auf allen Seiten** aus. Weitere Informationen zum Arbeiten mit Filtern in Power BI-Berichten finden Sie unter [Die neue Filterfunktion in Power BI-Berichten](https://docs.microsoft.com/power-bi/power-bi-report-filter).

Weitere Informationen zur Arbeit mit Berichten finden Sie unter [Berichte in Power BI](https://docs.microsoft.com/power-bi/consumer/end-user-reports).

### <a name="overview"></a>Übersicht

Die Seite **Übersicht** bietet eine Übersicht über Kundenzufriedenheitsdaten. Die folgenden Umfragemetriken werden im gesamten oberen Bereich des Berichts angezeigt:

- **Umfrageeinladungen**: Gesamtzahl der gesendeten Umfrageeinladungen.
- **Umfrageantworten**: Anzahl der empfangenen, nicht anonymen Umfrageantworten.
- **NPS**: Durchschnittlicher NPS der Umfrage.
- **Stimmung**: Stimmung von Antwortenden basierend auf den Umfrageantworten.

Die folgenden Informationen werden unter der Umfragemetrik angezeigt:

- **Net Promoter Score**: Der Trend des durchschnittlichen NPS über eine Zeitperiode. Die x-Achse zeigt die Zeitperiode an, und die y-Achse zeigt den durchschnittlichen NPS an. Sie können das NPS-Diagramm mithilfe der folgenden Filter filtern, um NPS-Abweichungen anzuzeigen und effektive Entscheidungen entsprechend zu treffen:

  - **Trend**: Zeigt standardmäßig den durchschnittlichen NPS-Trend über einen Zeitraum an.
  - **Standort**: Zeigt den NPS-Trend nach Standort an. Auf diese Weise können Sie leichter die Standorte identifizieren, von denen positive oder negative Antworten eingehen, und entsprechende Entscheidungen treffen. Beispielsweise haben Sie NPS von drei Standorten erhalten: Loc1, Loc2 und Loc3. Erkenntnisse haben angezeigt, dass Loc3 einen besseren NPS als die anderen beiden Standorte hat. Sie könnten möglicherweise die Entscheidung treffen, sich auf Loc1 und Loc2 zu konzentrieren und Möglichkeiten zur Verbesserung des NPS dort zu finden.
  - **Anfragepriorität**: Zeigt den NPS-Trend nach Anfragepriorität an, wie z. B. hoch, niedrig oder mittelmäßig.
  - **Anfrageursprung** : Zeigt den NPS-Trend nach dem Ursprung der Anfrage an, z. B. Facebook, Telefon oder Twitter.
  - **Anfragetyp**: Zeigt den NPS-Trend nach Art der Anfrage an, z. B. Problem, Anforderung oder Frage.
  - **Produkt**: Zeigt den NPS-Trend nach Produkten an, die den Anfragen zugeordnet sind.

- **Schlüsselbegriffe**: Zeigt eine Wort-Cloud der in der Standpunktanalyse verwendeten Schlüsselbegriffe an. Sie können filtern, um nur die positiven oder negativen – oder alle – Schlüsselausdrücke zu sehen.

  > [!div class=mx-imgBorder]
  > ![Übersichtsseite](media/overview-page.png "Übersichtsseite")

### <a name="agent-performance"></a>Agentenleistung

Die Seite **Agentenleistung** bietet eine agentenzentrierte Ansicht der Zufriedenheitsdaten. Kundenservicemanager können diese Seite verwenden, um die Leistung eines Agenten basierend auf den Umfrageantworten zu analysieren. Die folgenden Informationen werden angezeigt:

- **NPS**: Durchschnittlicher NPS der Umfrage.
- Ein Blasendiagramm oben im Bericht, das die NPS-Verteilung gemäß der Anzahl von Agenten anzeigt.
- Ein Balkendiagramm, das den Trend des durchschnittlichen NPS über eine Zeitperiode anzeigt.
- Ein Raster, das die Namen von Agenten und ihre entsprechenden NPS enthält, sortiert nach NPS-Wert in absteigender Reihenfolge. Sie können den Namen eines Agenten auswählen, um die für den Agenten spezifischen Daten in allen anderen Diagrammen anzuzeigen.
- **Schlüsselbegriffe**: Zeigt eine Wort-Cloud der in der Standpunktanalyse verwendeten Schlüsselbegriffe an. Sie können filtern, um nur die positiven oder negativen – oder alle – Schlüsselausdrücke zu sehen.

  > [!div class=mx-imgBorder]
  > ![Agentleistungsseite](media/agent-performance-page.png "Agentleistungsseite")

### <a name="customer-satisfaction"></a>Kundenzufriedenheit

Die Seite **Kundenzufriedenheit** bietet die kundenzentrierte Ansicht der Zufriedenheitsdaten. Kundenservicemanager können diese Seite verwenden, um die Zufriedenheit eines Kunden basierend auf den Umfrageantworten zu analysieren. Die folgenden Informationen werden angezeigt:

- **NPS**: Durchschnittlicher NPS der Umfrage.
- Ein Blasendiagramm oben im Bericht, das die NPS-Verteilung gemäß der Anzahl von Kunden anzeigt.
- Ein Balkendiagramm, das den Trend des durchschnittlichen NPS über eine Zeitperiode anzeigt.
- Ein Raster, das die zufriedenen Kunden und ihre entsprechenden NPS enthält, sortiert nach NPS-Wert in absteigender Reihenfolge. Sie können den Namen eines Kunden auswählen, um die für den Kunden spezifischen Daten in allen anderen Diagrammen anzuzeigen.
- **Schlüsselbegriffe**: Zeigt eine Wort-Cloud der in der Standpunktanalyse verwendeten Schlüsselbegriffe an. Sie können filtern, um nur die positiven oder negativen – oder alle – Schlüsselausdrücke zu sehen.

  > [!div class=mx-imgBorder]
  > ![Kundenzufriedenheitsseite](media/customer-satisfaction-page.png "Kundenzufriedenheitsseite")
