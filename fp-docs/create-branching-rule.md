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
# <a name="create-a-branching-rule"></a><span data-ttu-id="a2dcf-103">Erstellen einer Verzweigungsregel</span><span class="sxs-lookup"><span data-stu-id="a2dcf-103">Create a branching rule</span></span>

<span data-ttu-id="a2dcf-104">Wenn Sie zusätzliche Fragen auf der Grundlage von Antworten in einer Umfrage stellen möchten, erstellen Sie eine oder mehrere Verzweigungsregeln für diese Antworten.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-104">When you want to ask additional questions based on responses in a survey, create one or more branching rules for those responses.</span></span> <span data-ttu-id="a2dcf-105">Verzweigungsregeln machen Ihre Umfragen interaktiv und stellen sicher, dass Antwortdiensten nur relevante Fragen angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-105">Branching rules make your surveys interactive and ensure that only relevant questions are displayed to responders.</span></span>

<span data-ttu-id="a2dcf-106">Sie können auch zu einer anderen Frage oder Umfrage navigieren oder sogar eine Website öffnen, die auf der Antwort auf eine Frage basiert.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-106">You can also choose to navigate to another question or survey, or even open a website based on the response to a question.</span></span> <span data-ttu-id="a2dcf-107">Wenn Sie eine Frage mit der Option **Sichtbar** vor der Anzeige in einer Umfrage ausgeblendet haben, können Sie sie mit der Verzweigungsregel basierend auf der gewünschten Antwort anzeigen.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-107">If you have hidden a question from being displayed in a survey by using the **Visible** option, you can use the branching rule to display it based on the required response.</span></span> <span data-ttu-id="a2dcf-108">Weitere Informationen über das Einstellen der Sichtbarkeit einer Frage finden Sie unter [Erstellen einer neuen Umfrage](create-new-survey.md).</span><span class="sxs-lookup"><span data-stu-id="a2dcf-108">For more information about setting the visibility for a question, see [Create a new survey](create-new-survey.md).</span></span>

<span data-ttu-id="a2dcf-109">Zum Beispiel für die Frage **Wie wahrscheinlich ist es, dass Sie uns einem Freund empfehlen würden?**, können Sie eine Verzweigungsregel erstellen, um den Grund zu fragen, wenn jemand antwortet **Nicht wahrscheinlich**.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-109">For example, for the question **How likely is it that you would recommend us to a friend?**, you can create a branching rule to ask the reason if someone responds **Not likely**.</span></span>

<span data-ttu-id="a2dcf-110">**Um eine Verzweigungsregel zu erstellen**</span><span class="sxs-lookup"><span data-stu-id="a2dcf-110">**To create a branching rule**</span></span>

1.  <span data-ttu-id="a2dcf-111">Öffnen Sie die Umfrage, in der Sie eine Verzweigungsregel hinzufügen möchten.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-111">Open the survey in which you want to add a branching rule.</span></span>

2.  <span data-ttu-id="a2dcf-112">Wählen Sie die Schaltfläche Auslassungspunkte **(...)** aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Verzweigungsregeln**.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-112">Select the ellipsis button **(…)** from the toolbar at the top of the page, and then select **Branching rules**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-113">![Schaltfläche „Verzweigungsregeln“](media/branching-rules-button.png "Schaltfläche „Verzweigungsregeln“")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-113">![Branching rules button](media/branching-rules-button.png "Branching rules button")</span></span>

    <span data-ttu-id="a2dcf-114">Wenn Sie noch keine Regeln erstellt haben, wird die folgende Seite angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-114">If you don't have any rules created yet, the following page is displayed.</span></span> <span data-ttu-id="a2dcf-115">Wählen Sie **Regel erstellen**.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-115">Select **Create rule**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-116">![Schaltfläche „Neue Regel erstellen“](media/create-rule-button.png "Schaltfläche „Neue Regel erstellen“")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-116">![Create new rule button](media/create-rule-button.png "Create new rule button")</span></span> 

    <span data-ttu-id="a2dcf-117">Nachdem Sie mindestens eine Regel erstellt haben, wird eine Liste von Regeln in einem Raster angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-117">If you've created at least one rule, a list of rules is displayed in a grid.</span></span> <span data-ttu-id="a2dcf-118">Wählen Sie **Neue Regel**.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-118">Select **New rule**.</span></span>
 
    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-119">![Schaltfläche „Neue Regel“](media/branch-new-rule-button.png "Schaltfläche „Neue Regel“")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-119">![New rule button](media/branch-new-rule-button.png "New rule button")</span></span>

3.  <span data-ttu-id="a2dcf-120">Geben Sie im Feld **Regelname** einen Namen für die Verzweigungsregel ein.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-120">In the **Rule name** field, enter a name for the branching rule.</span></span>

4.  <span data-ttu-id="a2dcf-121">Wählen Sie im Bereich **Bedingungen definieren** **Bedingung hinzufügen**, um eine Antwortbedingung hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-121">In the **Define conditions** area, select **Add condition** to add a response condition.</span></span>

5.  <span data-ttu-id="a2dcf-122">Wählen Sie in der Liste **Frage auswählen** die Frage aus, für die Sie eine Regel anlegen möchten.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-122">In the **Select question** list, choose the question for which you want to create a rule.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-123">![Bedingungsfrage „Verzweigungsregeln“](media/branch-condition-question.png "Bedingungsfrage „Verzweigungsregeln“")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-123">![Branching rules condition question](media/branch-condition-question.png "Branching rules condition question")</span></span>

6.  <span data-ttu-id="a2dcf-124">Wählen Sie Werte aus den Listen **Operator auswählen** und **Antwort auswählen** entsprechend aus.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-124">Select values from the **Select operator** and **Select response** lists, respectively.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-125">![Vollständige Bedingung für Verzweigungsregeln](media/branch-condition.png "Vollständige Bedingung für Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-125">![Branching rules complete condition](media/branch-condition.png "Branching rules complete condition")</span></span>

    <span data-ttu-id="a2dcf-126">Sie können weitere Bedingungen mithilfe der Kombination von **AND**/**OR** Operatoren hinzufügen, indem Sie **Bedingung hinzufügen** auswählen.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-126">You can add more conditions by using the combination of **AND**/**OR** operators by selecting **Add condition**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-127">![Mehrere Bedingungen für Verzweigungsregeln](media/branch-multi-condition.png "Mehrere Bedingungen für Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-127">![Branching rules multiple conditions](media/branch-multi-condition.png "Branching rules multiple conditions")</span></span>

7.  <span data-ttu-id="a2dcf-128">Wählen Sie **„If true“ hinzufügen aus**, um die Aktion hinzuzufügen, die ausgelöst wird, wenn die definierte Bedingung die Kriterien erfüllt.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-128">Select **Add "If true"** to add the action that will be triggered when the defined condition meets the criteria.</span></span>

8.  <span data-ttu-id="a2dcf-129">Wählen Sie **Aktion hinzufügen**, um die Antwortaktion hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-129">Select **Add action** to add the response action.</span></span>

9.  <span data-ttu-id="a2dcf-130">Wählen Sie in der Liste **Aktion auswählen** eine der folgenden Aktionen aus:</span><span class="sxs-lookup"><span data-stu-id="a2dcf-130">In the **Select action** list, choose one of the following actions:</span></span>

    - <span data-ttu-id="a2dcf-131">**Anzeigen**: Wählen Sie eine Frage aus, die anhand der Antwort auf eine Frage angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-131">**Show**: Select a question to be displayed based on the response to a question.</span></span>
    - <span data-ttu-id="a2dcf-132">**Verbergen**: Wählen Sie eine Frage aus, die anhand der Antwort auf eine Frage verborgen wird.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-132">**Hide**: Select a question to be hidden based on the response to a question.</span></span>
    - <span data-ttu-id="a2dcf-133">**Umschalten**: Umschalten ermöglicht es Ihnen, den Status der ausgewählten Frage anhand der Antwort auf eine Frage umzuschalten.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-133">**Toggle**: Toggle the state of the selected question based on the response to a question.</span></span>
    - <span data-ttu-id="a2dcf-134">**Navigieren zu**: Wählen Sie das Ziel aus, zu dem ein Befragter navigiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-134">**Navigate to**: Select the target to which a responder should be navigated.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-135">![Eine Aktion für Bedingung „true“ auswählen](media/branch-true-select-action.png "Aktion für Bedingung „true“ auswählen")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-135">![Select an action for true condition](media/branch-true-select-action.png "Select an action for a true condition")</span></span>

10. <span data-ttu-id="a2dcf-136">Wählen Sie in der Liste **Ziel auswählen** ein Ziel für die ausgewählte Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-136">In the **Select target** list, choose a target for the selected action.</span></span> <span data-ttu-id="a2dcf-137">Wenn Sie **Anzeigen**, **Ausblenden** oder **Umschalten** als Aktion wählen, können Sie **Frage** als Ziel auswählen.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-137">If you select **Show**, **Hide**, or **Toggle** as the action, you can select **Question** as the target.</span></span> <span data-ttu-id="a2dcf-138">Wenn Sie als Aktion **Navigieren zu** wählen, können Sie eines der folgenden Ziele auswählen:</span><span class="sxs-lookup"><span data-stu-id="a2dcf-138">If you select **Navigate to** as the action, you can choose one of the following targets:</span></span>

    - <span data-ttu-id="a2dcf-139">**Frage**: Ermöglicht es Ihnen, zu einer Frage basierend auf der Antwort auf eine Frage zu springen.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-139">**Question**: Skip to a question based on the response to a question.</span></span> <span data-ttu-id="a2dcf-140">Die Fragen zwischen der Quell- und Zielfrage sind für den Beantworter verborgen.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-140">The questions between the source and target questions are hidden from the responder.</span></span>
    - <span data-ttu-id="a2dcf-141">**Ende der Umfrage**: Ermöglicht es Ihnen, die Umfrage anhand der Antwort auf eine bestimmte Frage zu beenden.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-141">**End of survey**: End the survey based on the response to a question.</span></span>
    - <span data-ttu-id="a2dcf-142">**Kettenumfrage**: Ermöglicht es Ihnen, eine andere, von Ihnen erstellte Umfrage basierend auf der Antwort auf eine Frage zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-142">**Chain survey**: Open a different survey, created by you, based on the response to a question.</span></span>
    - <span data-ttu-id="a2dcf-143">**URL**: Öffnen Sie eine Website basierend auf der Antwort auf eine Frage.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-143">**URL**: Open a website based on the response to a question.</span></span> <span data-ttu-id="a2dcf-144">Sie müssen der URL `http://` hinzufügen, damit sie ordnungsgemäß funktioniert.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-144">You must add `http://` to the URL for it to work properly.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-145">![Ein Ziel für Bedingung „true“ auswählen](media/branch-true-select-target.png "Ein Ziel für die Bedingung „true“ auswählen")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-145">![Select a target for true condition](media/branch-true-select-target.png "Select a target for a true condition")</span></span>

11. <span data-ttu-id="a2dcf-146">Geben Sie in der Liste **Wert auswählen** einen Wert für das Ziel ein oder wählen Sie ihn aus.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-146">In the **Select value** list, enter or choose a value per the target.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-147">![Aktion „true“ für Verzweigungsregeln](media/branch-true-action.png "Aktion „true“ für Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-147">![Branching rules true action](media/branch-true-action.png "Branching rules true action")</span></span>

12. <span data-ttu-id="a2dcf-148">Wählen Sie **Hinzufügen, wenn falsch**, um die Aktion hinzuzufügen, die ausgelöst wird, wenn die definierte Bedingung nicht den Kriterien entspricht.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-148">Select **Add "If false"** to add the action that's triggered when the defined condition doesn't meet the criteria.</span></span> <span data-ttu-id="a2dcf-149">Folgen Sie den Schritten 8 bis 11.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-149">Then follow steps 8 through 11.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-150">![Aktion „false“ für Verzweigungsregeln](media/branch-false-action.png "Aktion „false“ für Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-150">![Branching rules false action](media/branch-false-action.png "Branching rules false action")</span></span>

13. <span data-ttu-id="a2dcf-151">Wählen Sie **Speichern** aus.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-151">Select **Save**.</span></span>

<span data-ttu-id="a2dcf-152">Nachdem Sie eine Verzweigungsregel erstellt haben, können Sie eine Vorschau der Umfrage anzeigen und sehen, ob die Regel wie erwartet funktioniert.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-152">After creating a branching rule, you can preview the survey and see whether the rule is working as expected.</span></span>

## <a name="manage-branching-rules"></a><span data-ttu-id="a2dcf-153">Verwalten von Verzweigungsregeln</span><span class="sxs-lookup"><span data-stu-id="a2dcf-153">Manage branching rules</span></span>

<span data-ttu-id="a2dcf-154">Nachdem Sie eine Verzweigungsregel oder einen Satz von Verzweigungsregeln erstellt haben, können Sie die Reihenfolge ihrer Ausführung bearbeiten, löschen oder ändern.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-154">After you've created a branching rule or a set of branching rules, you can edit, delete, or change the order of their execution.</span></span> <span data-ttu-id="a2dcf-155">Die Verzweigungsregeln werden in der Reihenfolge ihrer Erstellung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-155">The branching rules are executed in the order they were created in.</span></span>

1. <span data-ttu-id="a2dcf-156">Öffnen Sie die Umfrage, in der Sie Verzweigungsregeln verwalten möchten.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-156">Open the survey in which you want to manage branching rules.</span></span>
 
2. <span data-ttu-id="a2dcf-157">Wählen Sie die Schaltfläche Auslassungspunkte **(...)** aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Verzweigungsregeln**.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-157">Select the ellipsis button **(...)** from the toolbar at the top of the page, and then select **Branching rules**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-158">![Schaltfläche „Verzweigungsregeln“](media/branching-rules-button.png "Schaltfläche „Verzweigungsregeln“")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-158">![Branching rules button](media/branching-rules-button.png "Branching rules button")</span></span>

3. <span data-ttu-id="a2dcf-159">Eine Liste von Regeln wird in einem Raster angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-159">A list of rules is displayed in a grid.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="a2dcf-160">![Vorhandene Verzweigungsregeln](media/existing-rules.png "Vorhandene Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="a2dcf-160">![Existing branching rules](media/existing-rules.png "Existing branching rules")</span></span>

4. <span data-ttu-id="a2dcf-161">Um eine Verzweigungsregel zu bearbeiten, wählen Sie **Bearbeiten** ![Verzweigungsregel bearbeiten](media/edit-rule.png "Verzweigungsregel bearbeiten") aus der entsprechenden Regelzeile aus.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-161">To edit a branching rule, select **Edit** ![Edit branching rule](media/edit-rule.png "Edit branching rule") from the corresponding rule row.</span></span>

5. <span data-ttu-id="a2dcf-162">Um eine Verzweigungsregel zu löschen, wählen Sie **Löschen** ![Verzweigungsregel löschen](media/delete-rule.png "Verzweigungsregel löschen") aus der entsprechenden Regelzeile aus.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-162">To delete a branching rule, select **Delete** ![Delete branching rule](media/delete-rule.png "Delete branching rule") from the corresponding rule row.</span></span>

6. <span data-ttu-id="a2dcf-163">Um die Reihenfolge der Ausführung einer Verzweigungsregel zu ändern, verschieben Sie eine Regel im Raster nach oben oder unten.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-163">To change the order of execution of a branching rule, move a rule up or down in the grid.</span></span> <span data-ttu-id="a2dcf-164">Um eine Regel nach oben oder unten zu verschieben, wählen Sie **Nach oben** ![Nach oben](media/move-up-rule.png "Nach oben") oder **Nach unten** ![Nach unten](media/move-down-rule.png "Nach unten") aus der entsprechenden Regelreihe aus.</span><span class="sxs-lookup"><span data-stu-id="a2dcf-164">To move a rule up or down, select **Move up** ![Move up](media/move-up-rule.png "Move up") or **Move down** ![Move down](media/move-down-rule.png "Move down") from the corresponding rule row.</span></span>

### <a name="see-also"></a><span data-ttu-id="a2dcf-165">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="a2dcf-165">See also</span></span>

[<span data-ttu-id="a2dcf-166">Eine neue Umfrage erstellen</span><span class="sxs-lookup"><span data-stu-id="a2dcf-166">Create a new survey</span></span>](create-new-survey.md)<br>
[<span data-ttu-id="a2dcf-167">Ein Design auf eine Umfrage anwenden</span><span class="sxs-lookup"><span data-stu-id="a2dcf-167">Apply a theme to a survey</span></span>](apply-theme.md)<br>
[<span data-ttu-id="a2dcf-168">Vorschau und Test einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="a2dcf-168">Preview and test a survey</span></span>](preview-test-survey.md)<br>
[<span data-ttu-id="a2dcf-169">Personalisieren einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="a2dcf-169">Personalize a survey</span></span>](personalize-survey.md)<br>
[<span data-ttu-id="a2dcf-170">Text in einer Umfrage formatieren</span><span class="sxs-lookup"><span data-stu-id="a2dcf-170">Format text in a survey</span></span>](survey-text-format.md)<br>
[<span data-ttu-id="a2dcf-171">Erstellen eins klassischen Formulars</span><span class="sxs-lookup"><span data-stu-id="a2dcf-171">Create a classic form</span></span>](create-classic-form.md)<br>
[<span data-ttu-id="a2dcf-172">Erstellen einer mehrsprachigen Umfrage</span><span class="sxs-lookup"><span data-stu-id="a2dcf-172">Create a multilingual survey</span></span>](create-multilingual-survey.md)<br>
[<span data-ttu-id="a2dcf-173">Erstellen Sie eine mehrseitige Umfrage</span><span class="sxs-lookup"><span data-stu-id="a2dcf-173">Create a multiple-page survey</span></span>](create-multipage-survey.md)
