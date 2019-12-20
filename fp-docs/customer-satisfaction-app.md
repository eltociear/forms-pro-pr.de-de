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
ms.openlocfilehash: 2a943e1a50acaf7e2a934d52522466fb7e0d9975
ms.sourcegitcommit: 0612d18dc0591d4854e0452aacaeeaa68a9afc8f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/25/2019
ms.locfileid: "2831235"
---
# <a name="monitor-customer-satisfaction"></a>Kundenzufriedenheit überwachen

Verwenden Sie die Forms Pro-Kundenzufriedenheits-App, um ein Erkenntnisbericht zu erhalten, der Kundenfeedback mit den Anfragen verknüpft, wenn Sie Microsoft Forms Pro verwenden, um eine Umfrage nach einem Anfrageabschluss in Dynamics 365 Customer Service zu senden. Sie können den durchschnittlichen Net Promoter Score (NPS) sowie die einzelnen NPS Ihrer Agenten und Kunden anzeigen. Diese App bietet Ihnen die Funktionalität, den Bericht nach Anfragepriorität, Standort, Produkt und weiteren Anfrageparametern zu filtern. Eine Umfragemetrik, wie Anzahl gesendeter Umfrageeinladungen, Anzahl erhaltener Umfrageantworten, NPS, Stimmung und Schlüsselbegriffe werden auch im Bericht angezeigt. Sie können auch die Berichte bearbeiten und benutzerdefinierte Berichte gemäß Ihren Anforderungen erstellen.

## <a name="install-the-forms-pro-customer-satisfaction-app"></a>Die Forms Pro-Kundenzufriedenheits-App installieren

Die Forms Pro-Kundenzufriedenheits-App ist eine Vorlagen-App, die mithilfe von Power BI erstellt wurde. Diese App unterstützt Sie dabei, die Zufriedenheit Ihrer Kunden und die Leistung Ihrer Agenten zu erfahren. Sie können eine Verbindung zu Ihrer Dynamics 365 Customer Service-Instanz herstellen, um Erkenntnisse anhand Ihrer Geschäftsdaten anzuzeigen. Diese App umfasst Beispieldaten, mit denen Sie in der App navigieren und sie erkunden können. Sie gibt Ihnen auch die Möglichkeit, den Arbeitsbereich gemäß Ihren Anforderungen zu bearbeiten und anzupassen.

Weitere Informationen zu Vorlagen-Apps finden Sie unter [Was sind Power BI-Vorlagen-Apps?](https://docs.microsoft.com/power-bi/service-template-apps-overview)

Schritte zum Installieren einer Vorlagen-App und erste Schritte finden Sie unter [Installieren und Verteilen von Vorlagen-Apps](https://docs.microsoft.com/power-bi/service-template-apps-install-distribute).

### <a name="connect-to-dynamics-365-customer-service-data"></a>Eine Verbindung zu Dynamics 365 Customer Service-Daten herstellen

Wenn Sie sich entschließen, eine Verbindung zu Dynamics 365 Customer Service-Daten herzustellen, geben sie die URL ein, die Ihrer Dynamics 365 Customer Service-Instanz zugeordnet ist, und wählen Sie **Weiter** aus. Wenn Sie dazu aufgefordert werden, wählen Sie **oAuth2** als die Authentifizierungsmethode aus, wählen Sie **Anmelden** aus, und geben Sie dann die Anmeldeinformationen ein.

> [!NOTE]
> Es wird empfohlen, dass die aktuelle Version von Dynamics 365 Customer Service haben.

## <a name="report"></a>(Bericht)

Die Forms Pro-Kundenzufriedenheits-App zeigt Erkenntnisse in einem Bericht mit den folgenden Seiten an:

- [Übersicht](#overview)
- [Agentenleistung](#agent-performance)
- [Kundenzufriedenheit](#customer-satisfaction)

Sie können die Daten mithilfe des Filters **Datum** oben im Bericht filtern. Die Daten werden anhand der Umfrage-Einladungen gefiltert, die während der ausgewählten Zeitperiode gesendet werden. Wir nehmen einmal an, Sie haben 100 Umfrage-Einladungen während der ausgewählten Zeitperiode gesendet. Sie haben 60 Antworten innerhalb der Zeitperiode und 20 Antworten 20 nach der Zeitperiode erhalten. Die 20 Antworten werden ebenfalls in den Bericht einbezogen.

Wenn Sie eine andere Umfrage auswählen möchten, um Erkenntnisse anzuzeigen, ist dies vom Bereich **Filter** auf der rechten Seite des Berichts aus möglich. Öffnen Sie den Bereich, und wählen Sie eine Umfrage vom Filter **Umfragename** unter **Filter auf allen Seiten** aus. 

Weitere Informationen zum Arbeiten mit Filtern in Power BI-Berichten finden Sie unter [Die neue Filterfunktionalität in Power BI-Berichten](https://docs.microsoft.com/power-bi/power-bi-report-filter).

Weitere Informationen zum Arbeiten mit Berichten finden Sie unter [Berichte in Power BI](https://docs.microsoft.com/power-bi/consumer/end-user-reports).

### <a name="overview"></a>Übersicht

Die Seite „Übersicht“ bietet eine Übersicht über Kundenzufriedenheitsdaten. Die folgenden Umfragemetriken werden im gesamten oberen Bereich des Berichts angezeigt:

- **Umfrageeinladungen**: Gesamtzahl der gesendeten Umfrageeinladungen.
- **Umfrageantworten**: Anzahl der empfangenen, nicht anonymen Umfrageantworten.
- **NPS**: Durchschnittlicher NPS der Umfrage.
- **Stimmung**: Stimmung von Antwortenden basierend auf den Umfrageantworten.

Die folgenden Informationen werden unter der Umfragemetrik angezeigt:

- **Net Promoter Score**: Der Trend des durchschnittlichen NPS über eine Zeitperiode. Die x-Achse zeigt die Zeitperiode und die y-Achse zeigt den durchschnittlichen NPS an. Sie können das NPS-Diagramm anhand der folgenden Filter filtern, um NPS-Abweichungen anzuzeigen und auf dieser Grundlage wirksame Entscheidungen zu treffen:

  - **Trend**: Zeigt standardmäßig den durchschnittlichen NPS-Trend über einen Zeitraum an. 
  - **Standort**: Zeigt den NPS-Trend nach Standort an. Hierdurch können Sie die Standorte anzeigen, von denen die höchste Anzahl von Antworten kommt, und Sie können dementsprechend Entscheidungen treffen. Beispielsweise haben Sie NPS von drei Standorten erhalten: Loc1, Loc2 und Loc3. Erkenntnisse haben angezeigt, dass Loc3 einen besseren NPS als die anderen beiden Standorte hat. Sie entscheiden sich möglicherweise, sich auf Loc1 und Loc2 zu konzentrieren und Wege zu finden, den NPS zu steigern. 
  - **Anfragepriorität**: Zeigt den NPS-Trend nach Anfragepriorität an, wie z. B. hoch, niedrig oder mittelmäßig.
  - **Anfrageursprung**: Zeigt den NPS-Trend nach Ursprung der Anfrage an, z. B. Facebook, Telefon und Twitter.
  - **Anfragetyp**: Zeigt den NPS-Trend nach Typ der Anfrage an, z. B. Problem, Anforderung und Frage.
  - **Produkt**: Zeigt den NPS-Trend nach Produkten an, die den Anfragen zugeordnet sind.

- **Schlüsselbegriffe**: Zeigt eine Wort-Cloud der in der Standpunktanalyse verwendeten Schlüsselbegriffe an. Sie können filtern, damit Sie nur positive oder negative Schlüsselbegriffe oder alle Schlüsselbegriffe sehen.

  > [!div class=mx-imgBorder]
  > ![Übersichtsseite](media/overview-page.png "Übersichtsseite") 

### <a name="agent-performance"></a>Agentenleistung

Die Seite Agentenleistung bietet eine agentenzentrierte Ansicht der Zufriedenheitsdaten. Diese Seite unterstützt Kundenservicemanager bei der Analyse der Leistung eines Agenten auf Grundlage der Umfrageantworten. Die folgenden Informationen werden angezeigt:

- **NPS**: Durchschnittlicher NPS der Umfrage.
- Ein Blasendiagramm oben im Bericht, das die NPS-Verteilung gemäß der Anzahl von Agenten anzeigt.
- Ein Balkendiagramm, das den Trend des durchschnittlichen NPS über eine Zeitperiode anzeigt.
- Ein Raster, das die Namen von Agenten und ihre entsprechenden NPS enthält, sortiert nach NPS-Wert in absteigender Reihenfolge. Sie können den Namen eines Agenten auswählen, um die für den Agenten spezifischen Daten in allen anderen Diagrammen anzuzeigen.
- **Schlüsselbegriffe**: Zeigt eine Wort-Cloud der in der Standpunktanalyse verwendeten Schlüsselbegriffe an. Sie können filtern, damit Sie nur positive oder negative Schlüsselbegriffe oder alle Schlüsselbegriffe sehen.

  > [!div class=mx-imgBorder]
  > ![Agentleistungsseite](media/agent-performance-page.png "Agentleistungsseite")

### <a name="customer-satisfaction"></a>Kundenzufriedenheit

Die Seite „Kundenzufriedenheit“ bietet die kundenzentrierte Ansicht der Zufriedenheitsdaten. Diese Seite unterstützt Kundenservicemanager bei der Analyse der Zufriedenheit eines Kunden auf Grundlage der Umfrageantworten. Die folgenden Informationen werden angezeigt:

- **NPS**: Durchschnittlicher NPS der Umfrage.
- Ein Blasendiagramm oben im Bericht, das die NPS-Verteilung gemäß der Anzahl von Kunden anzeigt.
- Ein Balkendiagramm, das den Trend des durchschnittlichen NPS über eine Zeitperiode anzeigt.
- Ein Raster, das die zufriedenen Kunden und ihre entsprechenden NPS enthält, sortiert nach NPS-Wert in absteigender Reihenfolge. Sie können den Namen eines Kunden auswählen, um die für den Kunden spezifischen Daten in allen anderen Diagrammen anzuzeigen.
- **Schlüsselbegriffe**: Zeigt eine Wort-Cloud der in der Standpunktanalyse verwendeten Schlüsselbegriffe an. Sie können filtern, damit Sie nur positive oder negative Schlüsselbegriffe oder alle Schlüsselbegriffe sehen.

  > [!div class=mx-imgBorder]
  > ![Kundenzufriedenheitsseite](media/customer-satisfaction-page.png "Kundenzufriedenheitsseite")
