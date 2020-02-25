---
title: Senden einer Umfrage mit Power Automate | MicrosoftDocs
description: Anleitung zum Versenden einer Umfrage mit Power Automate.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 01/16/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: 11ac9528-c0a6-4fe6-9886-d2a4bfaa72f4
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: e9e9c6d3dfa98d50dd617ae073844b9284e70b25
ms.sourcegitcommit: f99b529d74a96beb8121df5344f40479619875ea
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/16/2020
ms.locfileid: "2966838"
---
# <a name="send-a-survey-by-using-power-automate"></a>Senden einer Umfrage mit Power Automate.

Nachdem Sie eine Umfrage erstellt haben, können Sie sie an die Befragten senden, z.B. aufgrund einer Business Trigger-Resolution eines Falles oder der Erfüllung einer Bestellung. Sie können entweder eine eingebaute Vorlage auswählen oder mit Power Automate einen Flow von Grund auf neu erstellen. Die folgenden Ablaufvorlagen sind in Forms Pro standardmäßig verfügbar:

- **Senden Sie eine Umfrage, wenn ein Fall in Dynamics 365 gelöst ist**: Diese Vorlage sendet eine Umfrage, wenn ein Fall in Dynamics 365 gelöst ist.
- **Senden Sie eine Umfrage, wenn ein Lead in Dynamics 365** qualifiziert ist: Diese Vorlage sendet eine Umfrage, wenn ein Lead in Dynamics 365 qualifiziert ist.
- **Senden Sie eine Umfrage, wenn eine Bestellung in Dynamics 365 erfüllt ist**: Diese Vorlage sendet eine Umfrage, wenn eine Bestellung in Dynamics 365 erfüllt ist.
- **Senden Sie eine Umfrage, wenn eine Schaltfläche angeglickt wird unter Power Apps**: Diese Vorlage sendet eine Umfrage an die angegebene Liste der Empfänger, wenn eine Schaltfläche unter Power Apps angeklickt wird.
- **Senden Sie eine Umfrage, wenn ein Fall in Salesforce geschlossen ist**: Diese Vorlage sendet eine Umfrage, wenn ein Fall in Salesforce geschlossen ist.

So senden Sie eine Umfrage mit Power Automate:

1.  Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie dann **Senden** aus der Symbolleiste oben auf der Seite aus.

2. Wählen Sie **Power Automate** und wählen Sie dann E-Mail erstellen aus.

3.  Wählen Sie **Flow konfigurieren**.

4.  Um einen integrierten Flow zu konfigurieren, wählen Sie eine Vorlage aus. Informationen zum Erstellen eines Flows aus einer Vorlage finden Sie unter [Anlegen eines Flows aus einer Vorlage in Power Automate](https://docs.microsoft.com/flow/get-started-logic-template).

5.  Um einen Flow von Grund auf neu zu erstellen, wählen Sie **Erstellen von Grund auf**. Informationen über das Erstellen eines neuen Flows finden Sie unter [Erstellen eines Flows in Power Automate](https://docs.microsoft.com/flow/get-started-logic-flow).

> [!NOTE]
> - Während der Konfiguration eines Flows zeigt die Vorlagenseite möglicherweise doppelte Vorlagen an. Um dieses Problem zu beheben, navigieren Sie aus der Registerkarte heraus und kehren Sie dann zurück, um den Flow erneut zu erstellen.
> - Wenn Sie in Ihrer Umfrage personalisierte Daten hinzugefügt haben, müssen Sie deren Werte im Flow angeben. Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)

5.  Wählen Sie **Flow erstellen**.

Wenn Sie eine Umfrage mit Power Automate senden, wird ein Umfrageeinladungssatz erstellt. Sie können Ihre Umfrageeinladung und -antwort mit Common Data Service verknüpfen.

## <a name="send-a-survey-action"></a>Senden einer Umfrageaktion

Diese Aktion sendet eine Umfrage an eine bestimmte Liste von Empfängern und erstellt für jeden Empfänger eine Umfrageeinladung. Sie können Ihre Umfrageeinladung und -antwort auch mit Common Data Service verknüpfen. Wenn Sie einen Flow von Grund auf neu anlegen, kann dies durch die Felder **Betreff** und **Empfängerdetails** in einem Flow erreicht werden. Wenn Sie eine Bewegung aus einer Vorlage anlegen, werden die Felder **Betreff** und **Empfängerdetails** entsprechend ausgefüllt.

Angenommen, Sie müssen eine Umfrage zu jedem Fallabschluß schicken. Über das Feld **Betreff** können Sie den Falldatensatz so festlegen, dass beim Anlegen einer Einladung und Antwort auf eine bestimmte Fallauflösung diese dann dem jeweiligen Fall zugeordnet werden. Der Fallmanager kann dann Berichte einrichten, um die Ergebnisse der Kundenzufriedenheit (CSAT) von Fall zu Fall anzuzeigen oder einen Fall wieder öffnen, wenn der CSAT sehr niedrig ist.

Im Feld **Empfängerdetails** können Sie die Umfrageeinladungs- und Antwortdatensätze dem entsprechenden Kontakt (dem Empfänger) zuordnen. Auf diese Weise können Vertriebsmitarbeiter oder andere Personen den Kontaktdatensatz einsehen und die Reaktion des Kunden sehen. Dies kann ihnen helfen, das Gespräch mit dem Kunden entsprechend zu gestalten.

> [!div class=mx-imgBorder]
> ![Felder Betreff und Empfängerdetails in einem Flow füllen](media/associate-survey.png "Füllen der Felder Betreffend und Empfängerdetails in einem Flow")  

### <a name="attributes"></a>Attribute

|Name|Beschreibung|
|---|----|
|Bis|E-Mail-Adresse zum Versenden der Einladung zur Umfrage. Wenn Sie mehreren E-Mail-Adressen eingeben, teilen Sie diese durch ein Semikolon.<br>**Hinweis**: Die E-Mail-Adresse sollte gültig sein und nicht Null zurückgeben.|
|Umfrage|Die Umfrage soll gesendet werden.<br>**Hinweis**: Sie müssen eine Umfrage aus der Liste auswählen und dürfen keinen benutzerdefinierten Wert eingeben.|
|E-Mail-Vorlage|E-Mail-Vorlage, die beim Senden der Einladung verwendet werden soll.<br>**Hinweis**: Sie müssen eine E-Mail-Vorlage aus der Liste auswählen und dürfen keinen benutzerdefinierten Wert eingeben.|
|Bezug|Aufzeichnen, um die Einladung und Beantwortung einer Umfrage zu verknüpfen. Dieser Wert wird in der Umfrageeinladung im Feld **Betreff** gespeichert.|
|Angaben zum Empfänger|Kontakt, um Ihre Umfrageeinladung und Ihre Antwortdatensätze damit zu verknüpfen. Dieser Wert wird im Feld **An** der Umfrageeinladung gespeichert.<br>**Hinweis**: Nur der Kontaktdatensatz wird unterstützt.|
|||

> [!NOTE]
> Wenn Sie in Ihrer Umfrage personalisierte Datenplatzhalter verwendet haben, sind diese Felder in dieser Aktion sichtbar und Sie können die Werte entsprechend angeben. Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)

Die Werte aus den Feldern **Betreff** und **Empfängerdetails** werden in der Umfrageeinladung gespeichert, so wie im folgenden Bild dargestellt.

> [!div class=mx-imgBorder]
> ![Umfrage Einladungsdatensatz](media/survey-invite.png "Befragungseinladungsdatensatz")  

> [!NOTE]
> Das Feld **An** wird auf dem Formular nicht standardmäßig angezeigt. Sie müssen zu **Erweiterte Suche** gehen und nach der Einladung suchen und die erforderlichen Spalten hinzufügen, um ihre Werte anzuzeigen.
>
> [!div class=mx-imgBorder]
> ![Umfrage Einladung mit Advanced Find](media/survey-invite-adv-find.png "Suchen Sie Umfrageeinladung mithilfe der erweiterten Suche") 

## <a name="view-flow-history"></a>Anzeige der Flow-Historie

Die Flow-Historie ist die Information, die dann für jede Umfrage gespeichert wird, während Sie die Flows zum Senden einer Umfrage konfigurieren. Bevor Sie einen neuen Flow konfigurieren, möchten Sie vielleicht mehr über die bereits für die Umfrage konfigurierten Flows erfahren. Die Flow-Historie liefert Ihnen die erforderlichen Informationen über die konfigurierten Flows, wie z.B. die Gesamtzahl der Flows, Ausfälle usw.

Die Flow-Historie wird in einem Raster mit den folgenden Informationen angezeigt:

- **Änderungsdatum**: Datum, an dem der Flow geändert wurde.

- **Flow**: Name des Flows.

- **Nachrichtenvorlage**: E-Mail-Nachrichtenvorlage(n), die vom Flow verwendet wird (werden).

- **Ausführungen**: Gesamtanzahl der Durchläufe eines Flows. Es werden Werte von bis zu 200 angezeigt. Wenn ein Flow mehr als 200 Mal ausgeführt wurde, wird 200+ als Zähler angezeigt. Sie können den Zählwert auswählen, um weitere Details zur Ausführung anzuzeigen.

- **Fehler (letzte 200 Durchläufe)**: Anzahl der Ausfälle eines Flows von den letzten 200 Durchläufen.

- **Status**: Status des Flows: ein oder aus. Sie können den Status eines Flows über Power Automate aktualisieren. Weitere Informationen finden Sie unter [Management einer Flows](https://docs.microsoft.com/flow/get-started-logic-flow#manage-a-flow).  

Bei Bedarf können Sie einen Flow auch bearbeiten, indem Sie das Symbol **Bearbeiten** auswählen. Der Flow-Editor öffnet sich in Power Automate, von wo aus Sie Ihre Änderungen vornehmen können.

> [!div class=mx-imgBorder]
> ![Einen Flow bearbeiten](media/edit-flow.png "Bearbeiten eines Flows")  

Zur Anzeige der Flow-Historie:

1.  Öffnen Sie die Umfrage, die Sie einbetten möchten und wählen Sie dann **Senden** aus der Symbolleiste oben auf der Seite aus.

2.  Wählen Sie auf der Kachel **Power Automate** **Konfigurierte Flows**.

    > [!div class=mx-imgBorder]
    > ![Konfigurierte Flows Schaltfläche](media/flows-configured.png "Schaltfläche für konfigurierte Flows")  

    Es wird ein Raster mit den konfigurierten Flows angezeigt.

    > [!div class=mx-imgBorder]
    > ![Flow-Historie Details](media/flow-history-details.png "Details zum Flow-Verlauf")  

### <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage per E-Mail](send-survey-email.md)<br>
[Eine Umfrage in einer Webseite einbetten](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in Power Apps](embed-survey-powerapps.md)
