---
title: Erstellen einer Verzweigungsregel für eine Umfrage | MicrosoftDocs
description: Anleitung zum Erstellen einer Verzweigungsregel für eine Umfrage mit Microsoft Forms Pro.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/04/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 72B81F9F-952B-4A58-83C7-9F68A5EF9B5C
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 65f21164a01f59cae73cfe1cf5b2a2d3f279fa11
ms.sourcegitcommit: f99b529d74a96beb8121df5344f40479619875ea
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/16/2020
ms.locfileid: "2966266"
---
# <a name="create-a-branching-rule"></a>Erstellen einer Verzweigungsregel

Wenn Sie zusätzliche Fragen auf der Grundlage von Antworten in einer Umfrage stellen möchten, erstellen Sie eine oder mehrere Verzweigungsregeln für diese Antworten. Verzweigungsregeln machen Ihre Umfragen interaktiv und stellen sicher, dass Antwortdiensten nur relevante Fragen angezeigt werden.

Sie können auch zu einer anderen Frage oder Umfrage navigieren oder sogar eine Website öffnen, die auf der Antwort auf eine Frage basiert. Wenn Sie eine Frage mit der Option **Sichtbar** vor der Anzeige in einer Umfrage ausgeblendet haben, können Sie sie mit der Verzweigungsregel basierend auf der gewünschten Antwort anzeigen. Weitere Informationen über das Einstellen der Sichtbarkeit einer Frage finden Sie unter [Erstellen einer neuen Umfrage](create-new-survey.md).

Zum Beispiel für die Frage **Wie wahrscheinlich ist es, dass Sie uns einem Freund empfehlen würden?**, können Sie eine Verzweigungsregel erstellen, um den Grund zu fragen, wenn jemand antwortet **Nicht wahrscheinlich**.

**Um eine Verzweigungsregel zu erstellen**

1.  Öffnen Sie die Umfrage, in der Sie eine Verzweigungsregel hinzufügen möchten.

2.  Wählen Sie die Schaltfläche Auslassungspunkte **(...)** aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Verzweigungsregeln**.

    > [!div class=mx-imgBorder]
    > ![Schaltfläche „Verzweigungsregeln“](media/branching-rules-button.png "Schaltfläche „Verzweigungsregeln“")

    Wenn Sie noch keine Regeln erstellt haben, wird die folgende Seite angezeigt. Wählen Sie **Regel erstellen**.

    > [!div class=mx-imgBorder]
    > ![Schaltfläche „Neue Regel erstellen“](media/create-rule-button.png "Schaltfläche „Neue Regel erstellen“") 

    Nachdem Sie mindestens eine Regel erstellt haben, wird eine Liste von Regeln in einem Raster angezeigt. Wählen Sie **Neue Regel**.
 
    > [!div class=mx-imgBorder]
    > ![Schaltfläche „Neue Regel“](media/branch-new-rule-button.png "Schaltfläche „Neue Regel“")

3.  Geben Sie im Feld **Regelname** einen Namen für die Verzweigungsregel ein.

4.  Wählen Sie im Bereich **Bedingungen definieren** **Bedingung hinzufügen**, um eine Antwortbedingung hinzuzufügen.

5.  Wählen Sie in der Liste **Frage auswählen** die Frage aus, für die Sie eine Regel anlegen möchten.

    > [!div class=mx-imgBorder]
    > ![Bedingungsfrage „Verzweigungsregeln“](media/branch-condition-question.png "Bedingungsfrage „Verzweigungsregeln“")

6.  Wählen Sie Werte aus den Listen **Operator auswählen** und **Antwort auswählen** entsprechend aus.

    > [!div class=mx-imgBorder]
    > ![Vollständige Bedingung für Verzweigungsregeln](media/branch-condition.png "Vollständige Bedingung für Verzweigungsregeln")

    Sie können weitere Bedingungen mithilfe der Kombination von **AND**/**OR** Operatoren hinzufügen, indem Sie **Bedingung hinzufügen** auswählen.

    > [!div class=mx-imgBorder]
    > ![Mehrere Bedingungen für Verzweigungsregeln](media/branch-multi-condition.png "Mehrere Bedingungen für Verzweigungsregeln")

7.  Wählen Sie **„If true“ hinzufügen aus**, um die Aktion hinzuzufügen, die ausgelöst wird, wenn die definierte Bedingung die Kriterien erfüllt.

8.  Wählen Sie **Aktion hinzufügen**, um die Antwortaktion hinzuzufügen.

9.  Wählen Sie in der Liste **Aktion auswählen** eine der folgenden Aktionen aus:

    - **Anzeigen**: Wählen Sie eine Frage aus, die anhand der Antwort auf eine Frage angezeigt wird.
    - **Verbergen**: Wählen Sie eine Frage aus, die anhand der Antwort auf eine Frage verborgen wird.
    - **Umschalten**: Umschalten ermöglicht es Ihnen, den Status der ausgewählten Frage anhand der Antwort auf eine Frage umzuschalten.
    - **Navigieren zu**: Wählen Sie das Ziel aus, zu dem ein Befragter navigiert werden soll.

    > [!div class=mx-imgBorder]
    > ![Eine Aktion für Bedingung „true“ auswählen](media/branch-true-select-action.png "Aktion für Bedingung „true“ auswählen")

10. Wählen Sie in der Liste **Ziel auswählen** ein Ziel für die ausgewählte Aktion aus. Wenn Sie **Anzeigen**, **Ausblenden** oder **Umschalten** als Aktion wählen, können Sie **Frage** als Ziel auswählen. Wenn Sie als Aktion **Navigieren zu** wählen, können Sie eines der folgenden Ziele auswählen:

    - **Frage**: Ermöglicht es Ihnen, zu einer Frage basierend auf der Antwort auf eine Frage zu springen. Die Fragen zwischen der Quell- und Zielfrage sind für den Beantworter verborgen.
    - **Ende der Umfrage**: Ermöglicht es Ihnen, die Umfrage anhand der Antwort auf eine bestimmte Frage zu beenden.
    - **Kettenumfrage**: Ermöglicht es Ihnen, eine andere, von Ihnen erstellte Umfrage basierend auf der Antwort auf eine Frage zu öffnen.
    - **URL**: Öffnen Sie eine Website basierend auf der Antwort auf eine Frage. Sie müssen der URL `http://` hinzufügen, damit sie ordnungsgemäß funktioniert.

    > [!div class=mx-imgBorder]
    > ![Ein Ziel für Bedingung „true“ auswählen](media/branch-true-select-target.png "Ein Ziel für die Bedingung „true“ auswählen")

11. Geben Sie in der Liste **Wert auswählen** einen Wert für das Ziel ein oder wählen Sie ihn aus.

    > [!div class=mx-imgBorder]
    > ![Aktion „true“ für Verzweigungsregeln](media/branch-true-action.png "Aktion „true“ für Verzweigungsregeln")

12. Wählen Sie **Hinzufügen, wenn falsch**, um die Aktion hinzuzufügen, die ausgelöst wird, wenn die definierte Bedingung nicht den Kriterien entspricht. Folgen Sie den Schritten 8 bis 11.

    > [!div class=mx-imgBorder]
    > ![Aktion „false“ für Verzweigungsregeln](media/branch-false-action.png "Aktion „false“ für Verzweigungsregeln")

13. Wählen Sie **Speichern** aus.

Nachdem Sie eine Verzweigungsregel erstellt haben, können Sie eine Vorschau der Umfrage anzeigen und sehen, ob die Regel wie erwartet funktioniert.

## <a name="manage-branching-rules"></a>Verwalten von Verzweigungsregeln

Nachdem Sie eine Verzweigungsregel oder einen Satz von Verzweigungsregeln erstellt haben, können Sie die Reihenfolge ihrer Ausführung bearbeiten, löschen oder ändern. Die Verzweigungsregeln werden in der Reihenfolge ihrer Erstellung ausgeführt.

1. Öffnen Sie die Umfrage, in der Sie Verzweigungsregeln verwalten möchten.
 
2. Wählen Sie die Schaltfläche Auslassungspunkte **(...)** aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Verzweigungsregeln**.

    > [!div class=mx-imgBorder]
    > ![Schaltfläche „Verzweigungsregeln“](media/branching-rules-button.png "Schaltfläche „Verzweigungsregeln“")

3. Eine Liste von Regeln wird in einem Raster angezeigt.

    > [!div class=mx-imgBorder]
    > ![Vorhandene Verzweigungsregeln](media/existing-rules.png "Vorhandene Verzweigungsregeln")

4. Um eine Verzweigungsregel zu bearbeiten, wählen Sie **Bearbeiten** ![Verzweigungsregel bearbeiten](media/edit-rule.png "Verzweigungsregel bearbeiten") aus der entsprechenden Regelzeile aus.

5. Um eine Verzweigungsregel zu löschen, wählen Sie **Löschen** ![Verzweigungsregel löschen](media/delete-rule.png "Verzweigungsregel löschen") aus der entsprechenden Regelzeile aus.

6. Um die Reihenfolge der Ausführung einer Verzweigungsregel zu ändern, verschieben Sie eine Regel im Raster nach oben oder unten. Um eine Regel nach oben oder unten zu verschieben, wählen Sie **Nach oben** ![Nach oben](media/move-up-rule.png "Nach oben") oder **Nach unten** ![Nach unten](media/move-down-rule.png "Nach unten") aus der entsprechenden Regelreihe aus.

### <a name="see-also"></a>Siehe auch

[Eine neue Umfrage erstellen](create-new-survey.md)<br>
[Ein Design auf eine Umfrage anwenden](apply-theme.md)<br>
[Vorschau und Test einer Umfrage](preview-test-survey.md)<br>
[Personalisieren einer Umfrage](personalize-survey.md)<br>
[Text in einer Umfrage formatieren](survey-text-format.md)<br>
[Erstellen eins klassischen Formulars](create-classic-form.md)<br>
[Erstellen einer mehrsprachigen Umfrage](create-multilingual-survey.md)<br>
[Erstellen Sie eine mehrseitige Umfrage](create-multipage-survey.md)
