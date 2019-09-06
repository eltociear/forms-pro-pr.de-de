---
title: Erstellen einer Verzweigungsregel für eine Umfrage | MicrosoftDocs
description: Anleitung zum Erstellen einer Verzweigungsregel für eine Umfrage mit Microsoft Forms Pro.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 04/26/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 72B81F9F-952B-4A58-83C7-9F68A5EF9B5C
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 5d8ebc963aa8081f2edb6c91e7f91101b43b6c59
ms.sourcegitcommit: 5661ec673caaeeba4c63158a98a0f6e083cb73cd
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2019
ms.locfileid: "1778931"
---
# <a name="create-a-branching-rule"></a>Erstellen einer Verzweigungsregel



Wenn Sie zusätzliche Fragen auf der Grundlage von Antworten in einer Umfrage stellen möchten, erstellen Sie eine oder mehrere Verzweigungsregeln für diese Antworten. Verzweigungsregeln machen Ihre Umfragen interaktiv und stellen sicher, dass den Befragten nur die relevanten Fragen angezeigt werden. 

Sie können auch zu einer anderen Frage oder Umfrage navigieren oder sogar eine Website öffnen, die auf der Antwort auf eine Frage basiert. Wenn Sie eine Frage mit der Option **Sichtbar** vor der Anzeige in einer Umfrage ausgeblendet haben, können Sie sie mit der Verzweigungsregel entsprechend der gewünschten Antwort anzeigen. Weitere Informationen zum Einstellen der Sichtbarkeit einer Frage finden Sie unter [Erstellen einer neuen Umfrage](create-new-survey.md).

Zum Beispiel für die Frage **Wie wahrscheinlich ist es, dass Sie uns einem Freund empfehlen würden?**, können Sie eine Verzweigungsregel erstellen, um den Grund zu fragen, wenn jemand antwortet **Nicht wahrscheinlich**.

Um eine Verzweigungsregel zu erstellen:

1.  Öffnen Sie die Umfrage, in der Sie eine Verzweigungsregel hinzufügen möchten.

2.  Wählen Sie auf der Registerkarte **Fragen erstellen** die Schaltfläche Ellipsis (...) in der Symbolleiste oben auf der Seite und wählen Sie dann **Verzweigungsregeln**. 

    > [!div class=mx-imgBorder]
    > ![Verzweigungsregeln-Schaltfläche](media/branching-rules-button.png "Verzweigungsregeln-Schaltfläche")
    
    Wenn Sie noch keine Regeln erstellt haben, wird die folgende Seite angezeigt. Wählen Sie **Regel erstellen**. 

    > [!div class=mx-imgBorder]
    > ![Neue Regel erstellen](media/create-rule-button.png "Neue Regel erstellen") 

    Wenn Sie mindestens eine Regel erstellt haben, wird eine Liste von Regeln in einem Raster angezeigt. Wählen Sie **Neue Regel**. 
 
    > [!div class=mx-imgBorder]
    > ![Neue Regel](media/branch-new-rule-button.png "Neue Regel")

3.  Geben Sie im Feld **Regelname** einen Namen für die Verzweigungsregel ein.

4.  Wählen Sie im Bereich **Bedingungen definieren** **Bedingung hinzufügen**, um eine Antwortbedingung hinzuzufügen.

5.  Wählen Sie in der Liste **Frage auswählen** die Frage aus, für die Sie eine Regel anlegen möchten.

    > [!div class=mx-imgBorder]
    > ![Verzweigungsregeln Bedingungsfrage](media/branch-condition-question.png "Verzweigungsregeln Bedingungsfrage")

6.  Wählen Sie Werte aus den Listen **Operator auswählen** und **Antwort auswählen** entsprechend.

    > [!div class=mx-imgBorder]
    > ![Verzweigungsregeln Abschlusszustand](media/branch-condition.png "Verzweigungsregeln Abschlusszustand")

    Sie können weitere Bedingungen mit der Kombination von **AND**/**OR** Operatoren hinzufügen, indem Sie **Bedingung hinzufügen** auswählen.

    > [!div class=mx-imgBorder]
    > ![Verzweigungsregeln mehrere Bedingungen](media/branch-multi-condition.png "Verzweigungsregeln mehrere Bedingungen")

7.  Wählen Sie **Add "If true"**, um die Aktion hinzuzufügen, die ausgelöst wird, wenn die definierte Bedingung die Kriterien erfüllt.

8.  Wählen Sie **Aktion hinzufügen**, um die Antwortaktion hinzuzufügen.

9.  Wählen Sie in der Liste **Aktion auswählen** eine der folgenden Aktionen aus:

    - **Anzeigen**: Ermöglicht es Ihnen, eine Frage auszuwählen, die anhand der Antwort auf eine Frage angezeigt wird.
    - **Verbergen**: Ermöglicht es Ihnen, eine Frage auszuwählen, die anhand der Antwort auf eine Frage ausgeblendet werden soll.
    - **Umschalten**: Ermöglicht es Ihnen, den Status der ausgewählten Frage anhand der Antwort auf eine Frage umzuschalten.
    - **Navigieren zu**: Ermöglicht es Ihnen, ein Ziel auszuwählen, zu dem ein Befragter navigiert werden soll.

    > [!div class=mx-imgBorder]
    > ![Aktion für wahre Bedingung auswählen](media/branch-true-select-action.png "Aktion für wahre Bedingung auswählen")

10. Wählen Sie in der Liste **Ziel auswählen** ein Ziel für die ausgewählte Aktion aus. Wenn Sie **Anzeigen**, **Ausblenden,** oder **Umschalten** als Aktion wählen, können Sie **Frage** als Ziel auswählen. Wenn Sie als Aktion **Navigieren zu** wählen, können Sie eines der folgenden Ziele auswählen:

    - **Frage**: Ermöglicht es Ihnen, zu einer Frage pro Antwort auf eine Frage zu springen. Die Fragen zwischen Quell- und Zielfrage sind für den Beantworter verborgen.
    - **Ende der Umfrage**: Ermöglicht es Ihnen, die Umfrage anhand der Antwort auf eine Frage zu beenden.
    - **Kettenumfrage**: Ermöglicht es Ihnen, eine andere, von Ihnen erstellte Umfrage pro Antwort auf eine Frage zu öffnen.
    - **URL**: Ermöglicht es Ihnen, eine Website anhand der Antwort auf eine Frage zu öffnen. Sie müssen der URL `http://` hinzufügen, damit sie ordnungsgemäß funktioniert.

    > [!div class=mx-imgBorder]
    > ![Auswahl eines Ziels für die wahre Bedingung](media/branch-true-select-target.png "Auswahl eines Ziels für die wahre Bedingung")

11. Geben Sie in der Liste **Wert auswählen** einen Wert für das Ziel ein oder wählen Sie ihn aus.

    > [!div class=mx-imgBorder]
    > ![Verzweigungsregeln wahre Aktion](media/branch-true-action.png "Verzweigungsregeln wahre Aktion")

12. Wählen Sie **Add "If false"**, um die Aktion hinzuzufügen, die ausgelöst wird, wenn die definierte Bedingung nicht den Kriterien entspricht. Führen Sie dann die Schritte 8 bis 11 aus. 

    > [!div class=mx-imgBorder]
    > ![Verzweigungsregeln falsche Aktion](media/branch-false-action.png "Verzweigungsregeln falsche Aktion")

13. Wählen Sie **Speichern** aus.

Nachdem Sie eine Verzweigungsregel erstellt haben, können Sie eine Vorschau der Umfrage anzeigen und sehen, ob die Regel wie erwartet funktioniert.

## <a name="manage-branching-rules"></a>Verwalten von Verzweigungsregeln

Nachdem Sie eine Verzweigungsregel oder einen Satz von Verzweigungsregeln erstellt haben, können Sie die Reihenfolge ihrer Ausführung bearbeiten, löschen oder ändern. Die Verzweigungsregeln werden in der Reihenfolge ihrer Erstellung ausgeführt. 

1. Öffnen Sie die Umfrage, in der Sie Verzweigungsregeln verwalten möchten.
 
2. Wählen Sie auf der Registerkarte **Fragen erstellen** die Schaltfläche Ellipsis (...) in der Symbolleiste oben auf der Seite und wählen Sie dann **Verzweigungsregeln**. 

    > [!div class=mx-imgBorder]
    > ![Verzweigungsregeln-Schaltfläche](media/branching-rules-button.png "Verzweigungsregeln-Schaltfläche")

3. Eine Liste von Regeln wird in einem Raster angezeigt.

    > [!div class=mx-imgBorder]
    > ![Existierende Verzweigungsregeln](media/existing-rules.png "Existierende Verzweigungsregeln")

4. Um eine Verzweigungsregel zu bearbeiten, wählen Sie **Bearbeiten** ![Verzweigungsregel bearbeiten](media/edit-rule.png "Verzweigungsregel bearbeiten") aus der entsprechenden Regelzeile.

5. Um eine Verzweigungsregel zu löschen, wählen Sie **Löschen** ![Verzweigungsregel löschen](media/delete-rule.png "Verzweigungsregel löschen") aus der entsprechenden Regelzeile.

6. Um die Reihenfolge der Ausführung einer Verzweigungsregel zu ändern, verschieben Sie eine Regel im Raster nach oben oder unten. Um eine Regel nach oben oder unten zu verschieben, wählen Sie **Nach oben verschieben** ![Nach oben verschieben](media/move-up-rule.png "Nach oben verschieben") oder **Nach unten verschieben** ![Nach unten verschieben](media/move-down-rule.png "Nach unten verschieben") aus der entsprechenden Regelreihe.

## <a name="see-also"></a>Siehe auch

[Eine neue Umfrage erstellen](create-new-survey.md)<br>
[Thema auf eine Umfrage anwenden](apply-theme.md)<br>
[Vorschau und Test einer Umfrage](preview-test-survey.md)<br>
[Personalisieren einer Umfrage](personalize-survey.md)<br>
[Text in einer Umfrage formatieren](survey-text-format.md)<br>
[Erstellen eins klassischen Formulars](create-classic-form.md)<br>
[Erstellen einer mehrsprachigen Umfrage](create-multilingual-survey.md)<br>
[Erstellen einet mehrseitigen Umfrage](create-multipage-survey.md)
