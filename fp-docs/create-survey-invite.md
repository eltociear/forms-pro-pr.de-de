---
title: Erstellen einer Umfrageeinladung mit Power Automate | MicrosoftDocs
description: Anleitung zur Erstellung einer Umfrageeinladung mit Power Automate.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 01/16/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: 8579EFA2-7734-4516-ACFA-F65999983379
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 748fba463625ebde2b8a72548b74424f82c1f340
ms.sourcegitcommit: f99b529d74a96beb8121df5344f40479619875ea
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/16/2020
ms.locfileid: "2966178"
---
# <a name="create-a-survey-invitation"></a>Erstellen einer Umfrageeinladung

Wenn Sie eine Umfrage über eine andere Plattform als Microsoft Forms Pro&mdash;senden möchten – z. B. Outlook, Gmail oder SMS&mdash;können Sie mit Power Automate eine Umfrageeinladung erstellen. Die Umfrageeinladung erstellt einen personalisierten Link, der über die Plattform Ihrer Wahl verteilt werden kann.

1. Melden Sie sich bei [flow.microsoft.com](https://flow.microsoft.com) an.

2. Beginnen Sie, einen Flow von Grund auf neu zu erstellen. Weitere Informationen: [Erstellen eines Flows in Power Automate](https://docs.microsoft.com/flow/get-started-logic-flow)

3. Fügen Sie im Flow-Editor einen Trigger hinzu, um Ihren Flow zu starten.

4. Nachdem Sie den Trigger hinzugefügt haben, fügen Sie einen neuen Schritt hinzu und suchen Sie nach dem Connector **Microsoft Forms Pro**.

5. Wählen Sie in den Suchergebnissen **Microsoft Forms Pro**.

    > [!div class=mx-imgBorder]
    > ![Auswählen von Microsoft Forms Pro-Connector](media/search-connector.png "Aktivieren Sie den Microsoft Forms Pro Konnektor")  

6. Wählen Sie die Aktion **Eine Einladung erstellen (Vorschau)**.

    > [!div class=mx-imgBorder]
    > ![Wählen Sie die Aktion „Eine Einladung erstellen (Vorschau)“ aus](media/select-flow-action.png "Wählen Sie die Aktion „Eine Einladung erstellen (Vorschau)“ aus")  

7. Geben Sie in der Aktion **Eine Einladung erstellen** die folgenden Informationen ein oder wählen Sie sie aus:

    - **Umfrage**: Wählen Sie die zu sendende Umfrage aus.
    - **E-Mail**: Geben Sie die E-Mail-Adresse des Empfängers ein.
    - **Betreff**: Geben Sie einen Datensatz an, um die Umfrageeinladung und -antwort einander zuzuordnen. Dieser Wert wird in der Umfrageeinladung im Feld **Betreff** gespeichert.
    - **Empfängerdetails**: Geben Sie einen Kontakt an, um Ihre Umfrageeinladungs- und Antwortdatensätze einander zuzuordnen. Dieser Wert wird im Feld **An** der Umfrageeinladung gespeichert. In diesem Feld wird nur der Kontaktdatensatz unterstützt.

    > [!NOTE]
    > - Wenn Sie Ihre Umfrageeinladung und -antwort mit Common Data Service verknüpfen möchten, müssen Sie in den Feldern **Betreff** und **Empfängerdetails** entsprechend Werte eingeben. Weitere Informationen zu den Feldern **Betreff** und **Empfängerdetails** und wie sie in der Umfrageeinladung gespeichert sind, finden Sie unter [Senden einer Umfrageaktion](send-survey-flow.md#send-a-survey-action).
    > - Wenn Sie in Ihrer Umfrage Umfragevariablen verwendet haben, sind sie in dieser Aktion sichtbar und Sie können die Werte entsprechend angeben. Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)

8. Fügen Sie einen neuen Schritt hinzu und wählen Sie dann die Aktion zum Senden der E-Mail aus. Sie können Anbieter wie Outlook, Gmail oder SMS verwenden; wir haben Outlook verwendet, um die Umfrage in dieser Prozedur zu senden.

9. In der Aktion **E-Mail senden** gehen Sie wie folgt vor:

    - **An**: Geben Sie die E-Mail-Adresse des Empfängers ein.
    - **Betreff**: Geben Sie den Betreff der E-Mail ein.
    - **Text**: Geben Sie den gewünschten Text für den Textkörper der E-Mail ein, und fügen Sie den dynamischen Inhalt des **Einladungslinks** hinzu.

    Nach Eingabe der erforderlichen Angaben sieht der Fluss wie in der folgenden Abbildung dargestellt aus:

    > [!div class=mx-imgBorder]
    > ![Umfrageeinladungsflow](media/survey-invite-flow.png "Umfrageeinladungsflow")

    Der Flow läuft gemäß dem konfigurierten Trigger ab und sendet dann die Umfrage.

### <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage per E-Mail](send-survey-email.md)<br>
[Senden Sie eine Umfrage mit Power Automate](send-survey-flow.md)<br>
[Eine Umfrage in einer Webseite einbetten](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in Power Apps](embed-survey-powerapps.md)


