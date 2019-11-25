---
title: Erstellen einer Umfrageeinladung mit Microsoft Flow | MicrosoftDocs
description: Anleitung zur Erstellung einer Umfrageeinladung mit Microsoft Flow.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/04/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 8579EFA2-7734-4516-ACFA-F65999983379
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 089038e573fbbee4011ead629830f24a5e75d671
ms.sourcegitcommit: 3225337823216f21b569779b829f069f53aa3742
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/04/2019
ms.locfileid: "2750754"
---
# <a name="create-a-survey-invitation"></a>Erstellen einer Umfrageeinladung

Wenn Sie eine Umfrage über eine andere Plattform als Microsoft Forms Pro senden möchten, z. B. Outlook, Google Mail oder SMS, können Sie mit Microsoft Flow eine Umfrageeinladung erstellen. Die Umfrageeinladung erstellt einen personalisierten Link, der über eine Plattform Ihrer Wahl verteilt werden kann.

1. Melden Sie sich bei [flow.microsoft.com](https://flow.microsoft.com) an.

2. Beginnen Sie, einen Flow von Grund auf neu zu erstellen. Informationen zum Erstellen eines neuen Flows finden Sie unter [Erstellen eines Flows in Microsoft Flow](https://docs.microsoft.com/flow/get-started-logic-flow).

3. Fügen Sie im Flow-Editor einen Trigger hinzu, um Ihren Flow zu starten.

4. Nachdem Sie den Trigger hinzugefügt haben, fügen Sie einen neuen Schritt hinzu und suchen Sie nach dem Connector **Microsoft Forms Pro**.

5. Wählen Sie in den Suchergebnissen **Microsoft Forms Pro**.

    > [!div class=mx-imgBorder]
    > ![Auswählen von Microsoft Forms Pro-Connector](media/search-connector.png "Auswählen von Microsoft Forms Pro-Connector")  

6. Wählen Sie die Aktion **Eine Einladung erstellen (Vorschau)**.

    > [!div class=mx-imgBorder]
    > ![Wählen Sie die Aktion „Eine Einladung erstellen (Vorschau)“ aus](media/select-flow-action.png "Wählen Sie die Aktion „Eine Einladung erstellen (Vorschau)“ aus")  

7. Geben Sie in der Aktion **Eine Einladung erstellen** die folgenden Informationen ein oder wählen Sie sie aus:

    - **Umfrage**: Wählen Sie die zu sendende Umfrage aus.
    - **E-Mail**: Geben Sie die E-Mail-Adresse des Empfängers ein.
    - **Betreff**: Geben Sie einen Datensatz an, um Umfrageeinladung und -antwort zu verknüpfen. Dieser Wert wird in der Umfrageeinladung im Feld **Betreff** gespeichert.
    - **Empfängerdetails**: Geben Sie einen Kontakt an, um Ihre Umfrageeinladungs- und Antwortdatensätze zuzuordnen. Dieser Wert wird im Feld **An** der Umfrageeinladung gespeichert. In diesem Feld wird nur der Kontaktdatensatz unterstützt.

    > [!NOTE]
    > - Wenn Sie Ihre Umfrageeinladung und -antwort mit Common Data Service verknüpfen möchten, müssen Sie in den Feldern **Betreff** und **Empfängerdetails** entsprechend Werte eingeben. Weitere Informationen zu den Feldern **Betreff** und **Empfängerdetails** und wie sie in der Umfrageeinladung gespeichert sind, finden Sie unter [Senden einer Umfrageaktion](send-survey-microsoft-flow.md#send-a-survey-action).
    > - Wenn Sie in Ihrer Umfrage Umfragevariablen verwendet haben, sind diese Felder in dieser Aktion sichtbar, und Sie können die Werte entsprechend angeben. Mehr Informationen: [Werte in einem Flow angeben](personalize-survey.md#specify-values-in-a-flow)

8. Fügen Sie einen neuen Schritt hinzu und wählen Sie die Aktion zum Senden der E-Mail aus. Sie können Anbieter wie Outlook, Gmail oder SMS verwenden; wir haben Outlook verwendet, um die Umfrage in diesem Verfahren zu senden.

9. Geben Sie in der Aktion **Eine E-Mail senden** die folgenden Informationen ein: 

    - **An**: E-Mail-Adresse des Empfängers.
    - **Betreff**: Betreff der E-Mail.
    - **Body**: Geben Sie den gewünschten Text ein und fügen Sie **Einladungslink** dynamische Inhalte hinzu.

    Nach Eingabe der erforderlichen Angaben sieht der Fluss wie in der folgenden Abbildung dargestellt aus:

    > [!div class=mx-imgBorder]
    > ![Umfrageeinladungsflow](media/survey-invite-flow.png "Umfrageeinladungsflow")

    Der Flow läuft gemäß dem konfigurierten Trigger ab und sendet die Umfrage.


## <a name="see-also"></a>Siehe auch

[Arbeiten Sie mit den Umfrageeinstellungen](invite-settings.md)<br>
[Senden Sie eine Umfrage per E-Mail](send-survey-email.md)<br>
[Senden Sie eine Umfrage mit Microsoft Flow](send-survey-microsoft-flow.md)<br>
[Eingebettete Umfrage in eine Webseite](embed-web-page.md)<br>
[Senden Sie einen Umfrage-Link an andere](send-survey-link.md)<br>
[Senden Sie eine Umfrage QR-Code](send-survey-qrcode.md)<br>
[Einbetten einer Umfrage in PowerApps](embed-survey-powerapps.md)


