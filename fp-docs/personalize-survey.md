---
title: Eine Umfrage personalisieren | MicrosoftDocs
description: Anleitung zur Personalisierung einer Umfrage mit Microsoft Forms Pro.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 08/06/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 1AECC69F-B68A-4776-884A-C59770FC5C96
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 8f1982a942ef975346c1523b21a8e038c6339b46
ms.sourcegitcommit: e3e7192edb3753060a20a4dec47eb98faf1b87a3
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/06/2019
ms.locfileid: "1864100"
---
# <a name="personalize-a-survey"></a>Personalisieren einer Umfrage

Mit Platzhaltern können Sie Kundeninformationen mithilfe personalisierter Daten automatisch in Ihre Umfrage einfügen. Beispielsweise können Sie personalisierte Daten verwenden, um den Vornamen eines Kunden automatisch in eine Frage einzufügen, um ihn zu personalisieren.

Standardmäßig sind die folgenden personalisierten Datenoptionen verfügbar:

- Vorname
- Nachname

Zum Auswählen oder Hinzufügen neuer personalisierter Daten:

1.  Öffnen Sie die Umfrage, in der Sie personalisierte Daten verwenden möchten.

2.  Wählen Sie auf der Registerkarte **Fragen erstellen** die Schaltfläche Ellipsis (...) in der Symbolleiste oben auf der Seite und dann **Personalisieren**.

    > [!div class=mx-imgBorder]
    > ![Personalisieren](media/custom-data-button.png "Personalisieren")

3.  Wählen Sie aus der Liste der verfügbaren personalisierten Daten die personalisierten Daten aus, die Sie in Ihrer Umfrage verwenden möchten.

4.  Um neue personalisierte Daten hinzuzufügen, wählen Sie **Personalisierte Daten hinzufügen**.

5.  Geben Sie einen Namen für die personalisierten Daten ein.

6.  Wählen Sie **Hinzufügen** aus.

> [!NOTE]
> - Sie können auch Einladungen zu Umfragen personalisieren. Mehr Informationen: [Personalisieren Sie eine E-Mail](send-survey-email.md#personalize-an-email).
> - Verwenden Sie keine personenbezogenen Daten, wenn Sie planen, eine Umfrage anonym zu versenden. Bei einer anonymen Umfrage werden Platzhalter nicht durch aktuelle Daten ersetzt.
> - Platzhalter für personalisierte Daten werden durch die in einer Umfrage-E-Mail in den entsprechenden Feldern angegebenen Werte ersetzt.
> - Sie können maximal 15 personalisierte Datenenplatzhalter in einer Umfrage definieren.

## <a name="add-personalized-data-placeholders-to-a-question"></a>Hinzufügen von personalisierten Datenplatzhaltern zu einer Frage

Nachdem Sie die erforderlichen personalisierten Daten ausgewählt oder hinzugefügt haben, müssen Sie diese Daten den Platzhaltern in der Frage zuordnen. So fügen Sie einer Frage personalisierte Datenplatzhalter hinzu:

1.  Öffnen Sie die Umfrage, in der Sie personalisierte Datenplatzhalter hinzufügen möchten.

2.  Wählen Sie auf der Registerkarte **Fragen erstellen** den Fragentext aus, dem Sie personalisierte Daten hinzufügen möchten. Die Formatsymbolleiste wird angezeigt.

3.  Positionieren Sie den Cursor an der Stelle, an der Sie den Platzhalter für personalisierte Daten hinzufügen möchten.

4.  Wählen Sie aus der Liste **Personalisieren** in der Formatierungssymbolleiste die personalisierten Daten aus, die Sie hinzufügen möchten. 

    > [!div class=mx-imgBorder]
    > ![Personalisierte Daten hinzufügen](media/add-pipe-data.png "Personalisierte Daten hinzufügen")

Angenommen, Sie haben personalisierte Daten mit dem Namen **Produktname** angelegt und möchten in einer Frage den Vornamen des Kunden und den Produktnamen anzeigen. Wählen Sie aus der Liste **Personalisieren** **Vorname** und **Produktname** als personalisierte Daten. Die Platzhalter *{{Vorname}}* und *{{Produktname}}* werden an der Cursorposition eingefügt.

Nehmen wir an, die Frage ist: *{{Vorname}}*, wie beurteilen Sie insgesamt Ihre Erfahrungen mit dem Kundenservice für *{{Produktname}}*?

Diese Frage wird so aussehen, wenn ein Kunde namens Bert Hair die Umfrage zu einem Produkt namens Contoso Sales durchführt:

Bert, insgesamt, wie würden Sie Ihre Erfahrungen mit dem Kundenservice für Contoso Sales bewerten?

## <a name="specify-values-for-personalized-data-placeholders"></a>Geben Sie Werte für personalisierte Datenplatzhalter an.

Nachdem Sie in einer Frage personalisierte Datenplatzhalter hinzugefügt und verwendet haben, geben Sie Werte für diese an. Wenn Sie für sie keine Werte angeben, werden die Platzhalter nicht durch die Werte ersetzt und werden unverändert angezeigt. Sie können die Werte für personalisierte Datenplatzhalter angeben: 

- Beim Senden einer E-Mail.
- Bei der Konfiguration eines Flows.

### <a name="specify-values-in-an-email"></a>Werte in einer E-Mail angeben

Wenn Sie in einer E-Mail personalisierte Datenplatzhalter hinzugefügt haben, wird unterhalb des E-Mail-Editors ein Abschnitt angezeigt. Wählen Sie **Personalisierte Daten definieren**, um den Abschnitt zu erweitern und die Werte beim Senden von E-Mail-Einladungen anzugeben.

> [!div class=mx-imgBorder]
> ![Werte für personalisierte Daten in einer E-Mail angeben](media/custom-data-values.png "Werte für personalisierte Daten in einer E-Mail angeben")

### <a name="specify-values-in-a-flow"></a>Werte in einem Flow angeben

Um Werte für personalisierte Datenplatzhalter in einem Flow anzugeben:

1.  Wählen Sie während der Konfiguration eines Flows **Bearbeiten im erweiterten Modus**.

    > [!div class=mx-imgBorder]
    > ![Ein Flow im erweiterten Modus bearbeiten](media/flow-advanced-mode.png "Ein Flow im erweiterten Modus bearbeiten")

2.  Gehen Sie zu dem Schritt, der die Umfrage sendet, und erweitern Sie sie.

3.  Wählen Sie **Erweiterte Optionen anzeigen**.

    ![Erweiterte Optionen für einen Schritt in einem Flow anzeigen](media/flow-step-advanced-options-button.png "Erweiterte Optionen für einen Schritt in einem Flow anzeigen")

4.  Geben Sie die Werte für personalisierte Datenplatzhalter an.

    ![Werte für personalisierte Datenplatzhalter festlegen](media/flow-step-advanced-options.png "Werte für personalisierte Datenplatzhalter festlegen")

5.  Speichern Sie die Änderungen. 

## <a name="see-also"></a>Siehe auch

[Eine neue Umfrage erstellen](create-new-survey.md)<br>
[Thema auf eine Umfrage anwenden](apply-theme.md)<br>
[Vorschau und Test einer Umfrage](preview-test-survey.md)<br>
[Erstellen einer Verzweigungsregel](create-branching-rule.md)<br>
[Text in einer Umfrage formatieren](survey-text-format.md)<br>
[Erstellen eins klassischen Formulars](create-classic-form.md)<br>
[Erstellen einer mehrsprachigen Umfrage](create-multilingual-survey.md)<br>
[Erstellen einet mehrseitigen Umfrage](create-multipage-survey.md)
