---
title: Eine Umfrage personalisieren | MicrosoftDocs
description: Anleitung zur Personalisierung einer Umfrage mit Microsoft Forms Pro.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/04/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 1AECC69F-B68A-4776-884A-C59770FC5C96
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: cd145f76cff2d302b92dcb1e7b40678004d414ab
ms.sourcegitcommit: 2b2ffca387514568ff95dd1e566ba1850a416744
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2019
ms.locfileid: "2901041"
---
# <a name="personalize-a-survey"></a>Personalisieren einer Umfrage

Sie können benutzerdefinierte Informationen automatisch in Ihre Umfrage einfügen, indem Sie Umfragevariablen verwenden. Beispielsweise können Sie mit einer Umfragevariablen den Vornamen und den Produktnamen eines Kunden automatisch in eine Frage einfügen, um sie zu personalisieren.

Standardmäßig sind die folgenden Umfragevariablen verfügbar:

- **Vorname**: Fügt den Vornamen des Empfängers ein.

- **Nachname**: Fügt den Nachnamen des Empfängers ein.

Um eine neue Umfragevariable zu erstellen:

1.  Öffnen Sie die Umfrage, in der Sie Umfragevariablen verwenden möchten.

2.  Wählen Sie die Schaltfläche **Auslassungspunkte** (...) in der Symbolleiste oben auf der Seite und dann **Variablen der Umfrage**.

    > [!div class=mx-imgBorder]
    > ![Schaltflächefür Umfragevariablen](media/custom-data-button.png "Schaltfläche Variablen der Umfrage")

3.  Wählen Sie **Neue Variable**.

5.  Geben Sie einen Namen und einen Standardwert für die Umfragevariable ein.

> [!NOTE]
> - Sie können Umfrageeinladungen auch personalisieren, indem Sie Umfragevariablen verwenden. Mehr Informationen: [Personalisieren Sie eine E-Mail](send-survey-email.md#personalize-an-email)
> - Verwenden Sie keine Umfragevariablen, wenn Sie planen, eine Umfrage anonym zu senden. Bei einer anonymen Umfrage werden Variablen nicht durch aktuelle Daten ersetzt.
> - Variablen der Umfrage werden beim Senden einer Umfrageeinladung durch die angegebenen Standardwerte ersetzt.
> - Sie können maximal 15 Variablen in einer Umfrage definieren.

## <a name="add-survey-variables-to-a-question"></a>Hinzufügen von Umfragevariablen zu einer Frage

Nachdem Sie die erforderlichen Umfragevariablen erstellt haben, müssen Sie sie der noch Frage hinzufügen. 

1.  Öffnen Sie die Umfrage, in der Sie Umfragevariablen hinzufügen möchten.

2.  Wählen Sie auf der Registerkarte **Fragen** den Fragetext aus, dem Sie eine Umfragevariable hinzufügen möchten. Die Formatsymbolleiste wird angezeigt.

3.  Positionieren Sie den Cursor an der Stelle, an der Sie die Umfragevariable hinzufügen möchten.

4.  Wählen Sie in der Liste **Variablen** in der Formatierungssymbolleiste die Umfragevariable aus, die Sie hinzufügen möchten.

    > [!div class=mx-imgBorder]
    > ![Umfragevariablen hinzufügen ](media/add-pipe-data.png "Hinzufügen von Umfragevariablen")

Nehmen wir zum Beispiel an, dass Sie eine Umfragevariable mit dem Namen **Produktname** erstellt haben und dass Sie den Vornamen des Kunden und den Produktnamen in einer Frage anzeigen möchten. Wählen Sie **Vorname** und **Produktname** aus der Liste **Variablen**. *{{Vorname}}* und *{{Produktname}}* werden an der Cursorposition eingefügt.

Nehmen wir an, die Frage ist: *{{Vorname}}*, wie beurteilen Sie insgesamt Ihre Erfahrungen mit dem Kundenservice für *{{Produktname}}*?

Diese Frage wird so aussehen, wenn ein Kunde namens Bert Hair die Umfrage zu einem Produkt namens Contoso Sales durchführt:

&nbsp;&nbsp;&nbsp;&nbsp;Bert, insgesamt, wie würden Sie Ihre Erfahrungen mit dem Kundenservice für Contoso Sales bewerten?

## <a name="specify-values-for-survey-variables"></a>Geben Sie Werte für Umfragevariablen an

Beim Erstellen muss für jede Umfragevariable der Standardwert angegeben werden, während Sie diese erstellen. Wenn Sie keine Standardwerte angeben, wird für die Umfragevariablen nichts angezeigt. Sie können auch die Werte für Umfragevariablen angeben:

- Beim Versenden von E-Mail-Einladungen.
- Bei der Konfiguration eines Flows.

### <a name="specify-values-when-sending-email-invitations"></a>Geben Sie Werte für den Versand von E-Mail-Einladungen an

Wenn Sie Umfragevariablen erstellt, aber keine Standardwerte angegeben haben, wird beim Senden der Umfrage oben auf der Seite eine Warnmeldung angezeigt. Wählen Sie **Umfragevariablen definieren** zum Öffnen der **Umfragevariablen** Bereich und geben Sie dann die Standardwerte an.

### <a name="specify-values-in-a-flow"></a>Werte in einem Flow angeben

Um Werte für Umfragevariablen in einem Flow anzugeben:

1.  Wählen Sie während der Konfiguration eines Flows **Bearbeiten im erweiterten Modus**.

    > [!div class=mx-imgBorder]
    > ![Bearbeiten Sie einen Flow im erweiterten Modus](media/flow-advanced-mode.png "Bearbeiten eines Flows im erweiterten Modus")

2.  Gehen Sie zu dem Schritt, der die Umfrage sendet, und erweitern Sie sie.

3.  Wählen Sie **Erweiterte Optionen anzeigen**.

    ![Erweiterte Optionen für einen Schritt in einem Flow anzeigen](media/flow-step-advanced-options-button.png "Zeigt erweiterte Optionen für einen Schritt in einem Flow an")

4.  Geben Sie die Werte für Umfragevariablen an.

    ![Werte für Umfragevariablen festlegen](media/flow-step-advanced-options.png "Geben Sie Werte für Umfragevariablen an")

5.  Speichern Sie die Änderungen.

### <a name="see-also"></a>Siehe auch

[Eine neue Umfrage erstellen](create-new-survey.md)<br>
[Ein Design auf eine Umfrage anwenden](apply-theme.md)<br>
[Vorschau und Test einer Umfrage](preview-test-survey.md)<br>
[Erstellen einer Verzweigungsregel](create-branching-rule.md)<br>
[Text in einer Umfrage formatieren](survey-text-format.md)<br>
[Erstellen eins klassischen Formulars](create-classic-form.md)<br>
[Erstellen einer mehrsprachigen Umfrage](create-multilingual-survey.md)<br>
[Erstellen einet mehrseitigen Umfrage](create-multipage-survey.md)
