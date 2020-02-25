---
title: Erstellen einer mehrsprachigen Umfrage | MicrosoftDocs
description: Anleitung zur Erstellung einer mehrsprachigen Umfrage mit Microsoft Forms Pro.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 01/16/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: 7BE3FAAC-79AC-4F8C-8C56-BF9BA3B52C67
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: ece212c928a289cad72da44370d466509f786a5d
ms.sourcegitcommit: f99b529d74a96beb8121df5344f40479619875ea
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/16/2020
ms.locfileid: "2966222"
---
# <a name="create-a-multilingual-survey"></a>Erstellen einer mehrsprachigen Umfrage

Sie können eine mehrsprachige Umfrage erstellen, indem Sie mehrere Sprachen zu einer einzigen Umfrage hinzufügen. Sie können dann Übersetzungen für jede Sprache hinzufügen. Dies hilft Ihnen, Ihren Kundenstamm zu erweitern und ermöglicht es den Befragten, die Umfrage in ihrer bevorzugten Sprache durchzuführen.

Wenn Sie eine mehrsprachige Umfrage erstellen, können die Befragten ihre bevorzugte Sprache über die Sprachauswahl in der oberen rechten Ecke der Umfrage auswählen.

> [!div class=mx-imgBorder]
> ![Eine Sprache für die Umfrage auswählen](media/lang-select.png "Eine Sprache für die Umfrage auswählen") 

**Um eine mehrsprachige Umfrage zu erstellen**

1.  [Umfragesprache hinzufügen](#step-1-add-survey-language)
2.  [Übersetzungen hinzufügen](#step-2-add-translations)

## <a name="step-1-add-survey-language"></a>Schritt 1: Hinzufügen der Sprache der Umfrage

1.  Öffnen Sie die Umfrage, in der Sie mehrere Sprachen aktivieren möchten.

2.  Wählen Sie die Schaltfläche Auslassungspunkte **(...)** aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Mehrsprachig** aus.

    > [!div class=mx-imgBorder]
    > ![Schaltfläche „Mehrsprachig“](media/multilingual-button.png "Schaltfläche „Mehrsprachig“") 

3.  Wählen Sie im Bereich **Mehrsprachig** **Zusätzliche Sprache hinzufügen**.

    > [!div class=mx-imgBorder]
    > ![Bereich „Mehrsprachig“](media/multilingual-pane.png "Bereich „Mehrsprachig“")

4.  Suchen Sie in der Liste der Sprachen nach der gewünschten Sprache und wählen Sie sie aus.

    > [!div class=mx-imgBorder]
    > ![Durchsuchen und die erforderliche Sprache auswählen](media/lang-list.png "Zur erforderlichen Sprache navigieren und sie auswählen") 

5.  Wählen Sie bei Bedarf **Zusätzliche Sprache hinzufügen**, um weitere Sprachen hinzuzufügen. Die hinzugefügten Sprachen werden im Fenster angezeigt.

    > [!div class=mx-imgBorder]
    > ![Sprachen, die für die Umfrage hinzugefügt wurden](media/lang-added.png "Sprachen, die für die Umfrage hinzugefügt wurden")

## <a name="step-2-add-translations"></a>Schritt 2: Übersetzungen hinzufügen

Sie können zwischen zwei Optionen zum Hinzufügen von Übersetzungen wählen:

1. [Übersetzen Sie alle Sprachen in großen Mengen](#option-1-translate-all-languages-in-bulk)
2. [Übersetzen einzelner Sprachen](#option-2-translate-individual-languages)

### <a name="option-1-translate-all-languages-in-bulk"></a>Option 1. Übersetzen Sie alle Sprachen in großen Mengen

1. Wählen Sie den Bereich **Mehrsprachig** und wählen **Alle bearbeiten**.

    > [!div class=mx-imgBorder]
    > ![Alle Sprachen bearbeiten](media/edit-all-lang.png "Alle Sprachen bearbeiten")

2. Wählen Sie **Dieses Excel herunterladen** aus, um eine Excel-Datei herunterzuladen, die Zeichenfolgen in der primären Sprache und Spalten für jede der ausgewählten Sprachen enthält. Zum Beispiel **ES** für Spanisch oder **FR** für Französisch.

    > [!div class=mx-imgBorder]
    > ![Excel-Datei herunterladen, um alle Sprachen zu bearbeiten](media/download-excel.png "Eine Excel-Datei herunterladen, um alle Sprachen zu bearbeiten")

3. Öffnen Sie die Excel-Datei, und fügen Sie Übersetzungen für jede Sprache in der jeweiligen Spalte hinzu.

4. Nachdem Sie Übersetzungen für alle Sprachen in der Excel-Datei hinzugefügt haben, gehen Sie zu **Mehrsprachig** > **alle bearbeiten** und wählen Sie dann **Excel-Datei hochladen** aus.

    > [!div class=mx-imgBorder]
    > ![Excel-Datei mit Übersetzungen für alle Sprachen hochladen](media/upload-excel.png "Die Excel-Datei mit Übersetzungen für alle Sprachen hochladen") 

5. Navigieren Sie zu der Excel-Datei, in der Sie Übersetzungen hinzugefügt haben, und wählen Sie sie aus.

Nach dem Hochladen der Excel-Datei können Sie eine Vorschau der Umfrage anzeigen, um zu sehen, ob alles wie erwartet funktioniert. Wählen Sie die Sprache aus dem Sprachwahlschalter in der oberen rechten Ecke der Umfrage.

> [!div class=mx-imgBorder]
> ![Übersetzte Umfrage](media/translated-survey.png "Übersetzte Umfrage")

> [!NOTE]
> - Die erste Spalte in der Excel-Datei enthält Zeichenfolgen in der primären Sprache und kann nicht bearbeitet werden.
> - Sie müssen sicherstellen, dass eine Übersetzung für jede Zeichenfolge in der Excel-Datei bereitgestellt wird.
> - Es wird empfohlen, dass Sie jedes Mal, wenn Sie die Übersetzungen hinzufügen oder bearbeiten, die neueste Excel-Datei herunterladen. Dadurch wird sichergestellt, dass die neuesten Zeichenfolgen und Sprachen verfügbar sind.
> - Es wird empfohlen, _keine_ Kopie der Excel-Datei zu erstellen und Zeichenfolgen hinzuzufügen oder die Dateinamenerweiterung zu ändern. Diese Aktionen können zu einem Uploadfehler führen.

### <a name="option-2-translate-individual-languages"></a>Option 2<. Übersetzen einzelner Sprachen

1.  Fahren Sie im Bereich **Mehrsprachig** mit der Maus über die Sprache, für die Sie Übersetzungen hinzufügen möchten, und wählen Sie dann das Symbol **Bearbeiten**.

    > [!div class=mx-imgBorder]
    > ![Die Sprache bearbeiten, die für die Umfrage hinzugefügt wurde](media/edit-lang.png "Die Sprache bearbeiten, die für die Umfrage hinzugefügt wurde")

2.  Wählen Sie den Titel der Umfrage, die Beschreibung und die Fragen und die entsprechenden Optionen in der Umfrage aus und geben Sie den übersetzten Text für alle Umfrageelemente ein.

    > [!div class=mx-imgBorder]
    > ![Übersetzter Text, der in der Umfrage hinzugefügt wurde](media/translation-added.png "Übersetzter Text, der in der Umfrage hinzugefügt wurde") 

3.  Nachdem Sie übersetzten Text für alle Elemente in der Umfrage hinzugefügt haben, wählen Sie **Zurück** in der oberen linken Ecke der Seite, um zum Umfrageeditor zurückzukehren.

4.  Wiederholen Sie die Schritte 2 bis 3, um Übersetzungen für andere Sprachen hinzuzufügen.

Nachdem Sie Übersetzungen für alle Sprachen hinzugefügt haben, können Sie eine Vorschau der Umfrage ansehen, um zu sehen, ob alles wie erwartet funktioniert. Wählen Sie die Sprache aus dem Sprachwahlschalter in der oberen rechten Ecke der Umfrage.

> [!div class=mx-imgBorder]
> ![Übersetzte Umfrage](media/translated-survey.png "Übersetzte Umfrage") 

## <a name="manage-translations"></a>Verwalten von Übersetzungen  

Nachdem Sie Übersetzungen für die gewünschten Sprachen in Ihrer Umfrage hinzugefügt haben, können Sie entweder die vorhandene Übersetzung bearbeiten oder eine Sprache löschen.

1.  Öffnen Sie die mehrsprachige Umfrage, in der Sie Übersetzungen verwalten möchten.

2.  Wählen Sie die Schaltfläche Auslassungspunkte **(...)** aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Mehrsprachig** aus.

    > [!div class=mx-imgBorder]
    > ![Schaltfläche „Mehrsprachig“](media/multilingual-button.png "Schaltfläche „Mehrsprachig“")

3.  Um die Übersetzungen zu bearbeiten, fahren Sie mit der Maus über die Sprache, für die Sie Übersetzungen bearbeiten möchten, und wählen Sie dann das Symbol **Bearbeiten**.

    > [!div class=mx-imgBorder]
    > ![Die Sprache bearbeiten, die für die Umfrage hinzugefügt wurde](media/edit-lang.png "Die Sprache bearbeiten, die für die Umfrage hinzugefügt wurde")

    > [!NOTE]
    > Um alle Sprachen zusammen zu bearbeiten, wählen Sie **alle bearbeiten** und folgen Sie den Schritten in [Option 1: Übersetzen aller Sprachen in großen Mengen](#option-1-translate-all-languages-in-bulk).

4.  Bearbeiten Sie die Übersetzungen nach Bedarf.

5.  Um eine Sprache zu löschen, fahren Sie mit der Maus über die zu löschende Sprache und wählen Sie dann das Symbol **Löschen**.

    > [!div class=mx-imgBorder]
    > ![Die Sprache löschen](media/delete-lang.png "Die Sprache löschen") 

### <a name="see-also"></a>Siehe auch

[Eine neue Umfrage erstellen](create-new-survey.md)<br>
[Ein Design auf eine Umfrage anwenden](apply-theme.md)<br>
[Vorschau und Test einer Umfrage](preview-test-survey.md)<br>
[Erstellen einer Verzweigungsregel](create-branching-rule.md)<br>
[Personalisieren einer Umfrage](personalize-survey.md)<br>
[Text in einer Umfrage formatieren](survey-text-format.md)<br>
[Erstellen eins klassischen Formulars](create-classic-form.md)<br>
[Erstellen Sie eine mehrseitige Umfrage](create-multipage-survey.md)
