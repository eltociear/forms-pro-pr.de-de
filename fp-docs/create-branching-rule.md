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
ms.openlocfilehash: 45c658a42f72a04f8e4f9a7a27c8d1dd02fbc996
ms.sourcegitcommit: 3225337823216f21b569779b829f069f53aa3742
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/04/2019
ms.locfileid: "2750886"
---
# <a name="create-a-branching-rule"></a><span data-ttu-id="27161-103">Erstellen einer Verzweigungsregel</span><span class="sxs-lookup"><span data-stu-id="27161-103">Create a branching rule</span></span>

<span data-ttu-id="27161-104">Wenn Sie zusätzliche Fragen auf der Grundlage von Antworten in einer Umfrage stellen möchten, erstellen Sie eine oder mehrere Verzweigungsregeln für diese Antworten.</span><span class="sxs-lookup"><span data-stu-id="27161-104">When you want to ask additional questions based on responses in a survey, create one or more branching rules for those responses.</span></span> <span data-ttu-id="27161-105">Verzweigungsregeln machen Ihre Umfragen interaktiv und stellen sicher, dass den Befragten nur die relevanten Fragen angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="27161-105">Branching rules make your surveys interactive and ensure that only the relevant questions are displayed to the responders.</span></span> 

<span data-ttu-id="27161-106">Sie können auch zu einer anderen Frage oder Umfrage navigieren oder sogar eine Website öffnen, die auf der Antwort auf eine Frage basiert.</span><span class="sxs-lookup"><span data-stu-id="27161-106">You can also choose to navigate to another question or survey, or even open a website based on the response to a question.</span></span> <span data-ttu-id="27161-107">Wenn Sie eine Frage mit der Option **Sichtbar** vor der Anzeige in einer Umfrage ausgeblendet haben, können Sie sie mit der Verzweigungsregel entsprechend der gewünschten Antwort anzeigen.</span><span class="sxs-lookup"><span data-stu-id="27161-107">If you have hidden a question from being displayed in a survey by using the **Visible** option, you can use the branching rule to display it as per the required response.</span></span> <span data-ttu-id="27161-108">Weitere Informationen zum Einstellen der Sichtbarkeit einer Frage finden Sie unter [Erstellen einer neuen Umfrage](create-new-survey.md).</span><span class="sxs-lookup"><span data-stu-id="27161-108">For more information on setting the visibility of a question, see [Create a new survey](create-new-survey.md).</span></span>

<span data-ttu-id="27161-109">Zum Beispiel für die Frage **Wie wahrscheinlich ist es, dass Sie uns einem Freund empfehlen würden?**, können Sie eine Verzweigungsregel erstellen, um den Grund zu fragen, wenn jemand antwortet **Nicht wahrscheinlich**.</span><span class="sxs-lookup"><span data-stu-id="27161-109">For example, for the question **How likely is it that you would recommend us to a friend?**, you can create a branching rule to ask the reason if someone responds **Not likely**.</span></span>

<span data-ttu-id="27161-110">Um eine Verzweigungsregel zu erstellen:</span><span class="sxs-lookup"><span data-stu-id="27161-110">To create a branching rule:</span></span>

1.  <span data-ttu-id="27161-111">Öffnen Sie die Umfrage, in der Sie eine Verzweigungsregel hinzufügen möchten.</span><span class="sxs-lookup"><span data-stu-id="27161-111">Open the survey in which you want to add a branching rule.</span></span>

2.  <span data-ttu-id="27161-112">Wählen Sie die Schaltfläche **Auslassungspunkte** (...) aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Verzweigungsregeln** aus.</span><span class="sxs-lookup"><span data-stu-id="27161-112">Select the **ellipsis** button (…) from the toolbar at the top of the page, and then select **Branching rules**.</span></span> 

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-113">![Schaltfläche „Verzweigungsregeln“](media/branching-rules-button.png "Schaltfläche „Verzweigungsregeln“")</span><span class="sxs-lookup"><span data-stu-id="27161-113">![Branching rules button](media/branching-rules-button.png "Branching rules button")</span></span>
    
    <span data-ttu-id="27161-114">Wenn Sie noch keine Regeln erstellt haben, wird die folgende Seite angezeigt.</span><span class="sxs-lookup"><span data-stu-id="27161-114">If you don't have any rules created yet, the following page is displayed.</span></span> <span data-ttu-id="27161-115">Wählen Sie **Regel erstellen**.</span><span class="sxs-lookup"><span data-stu-id="27161-115">Select **Create rule**.</span></span> 

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-116">![Schaltfläche „Neue Regel erstellen“](media/create-rule-button.png "Schaltfläche „Neue Regel erstellen“")</span><span class="sxs-lookup"><span data-stu-id="27161-116">![Create new rule button](media/create-rule-button.png "Create new rule button")</span></span> 

    <span data-ttu-id="27161-117">Wenn Sie mindestens eine Regel erstellt haben, wird eine Liste von Regeln in einem Raster angezeigt.</span><span class="sxs-lookup"><span data-stu-id="27161-117">If you have at least one rule created, a list of rules is displayed in a grid.</span></span> <span data-ttu-id="27161-118">Wählen Sie **Neue Regel**.</span><span class="sxs-lookup"><span data-stu-id="27161-118">Select **New rule**.</span></span> 
 
    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-119">![Schaltfläche „Neue Regel“](media/branch-new-rule-button.png "Schaltfläche „Neue Regel“")</span><span class="sxs-lookup"><span data-stu-id="27161-119">![New rule button](media/branch-new-rule-button.png "New rule button")</span></span>

3.  <span data-ttu-id="27161-120">Geben Sie im Feld **Regelname** einen Namen für die Verzweigungsregel ein.</span><span class="sxs-lookup"><span data-stu-id="27161-120">In the **Rule name** field, enter a name for the branching rule.</span></span>

4.  <span data-ttu-id="27161-121">Wählen Sie im Bereich **Bedingungen definieren** **Bedingung hinzufügen**, um eine Antwortbedingung hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="27161-121">In the **Define conditions** area, select **Add condition** to add a response condition.</span></span>

5.  <span data-ttu-id="27161-122">Wählen Sie in der Liste **Frage auswählen** die Frage aus, für die Sie eine Regel anlegen möchten.</span><span class="sxs-lookup"><span data-stu-id="27161-122">In the **Select question** list, choose the question for which you want to create a rule.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-123">![Bedingungsfrage „Verzweigungsregeln“](media/branch-condition-question.png "Bedingungsfrage „Verzweigungsregeln“")</span><span class="sxs-lookup"><span data-stu-id="27161-123">![Branching rules condition question](media/branch-condition-question.png "Branching rules condition question")</span></span>

6.  <span data-ttu-id="27161-124">Wählen Sie Werte aus den Listen **Operator auswählen** und **Antwort auswählen** entsprechend.</span><span class="sxs-lookup"><span data-stu-id="27161-124">Select values from the **Select operator** and **Select response** lists accordingly.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-125">![Vollständige Bedingung für Verzweigungsregeln](media/branch-condition.png "Vollständige Bedingung für Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="27161-125">![Branching rules complete condition](media/branch-condition.png "Branching rules complete condition")</span></span>

    <span data-ttu-id="27161-126">Sie können weitere Bedingungen mit der Kombination von **AND**/**OR** Operatoren hinzufügen, indem Sie **Bedingung hinzufügen** auswählen.</span><span class="sxs-lookup"><span data-stu-id="27161-126">You can add more conditions with the combination of **AND**/**OR** operators by selecting **Add condition**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-127">![Mehrere Bedingungen für Verzweigungsregeln](media/branch-multi-condition.png "Mehrere Bedingungen für Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="27161-127">![Branching rules multiple conditions](media/branch-multi-condition.png "Branching rules multiple conditions")</span></span>

7.  <span data-ttu-id="27161-128">Wählen Sie **Add "If true"**, um die Aktion hinzuzufügen, die ausgelöst wird, wenn die definierte Bedingung die Kriterien erfüllt.</span><span class="sxs-lookup"><span data-stu-id="27161-128">Select **Add “If true”** to add the action that will trigger when the defined condition meets the criteria.</span></span>

8.  <span data-ttu-id="27161-129">Wählen Sie **Aktion hinzufügen**, um die Antwortaktion hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="27161-129">Select **Add action** to add the response action.</span></span>

9.  <span data-ttu-id="27161-130">Wählen Sie in der Liste **Aktion auswählen** eine der folgenden Aktionen aus:</span><span class="sxs-lookup"><span data-stu-id="27161-130">In the **Select action** list, choose one of the following actions:</span></span>

    - <span data-ttu-id="27161-131">**Anzeigen**: Ermöglicht es Ihnen, eine Frage auszuwählen, die anhand der Antwort auf eine Frage angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="27161-131">**Show**: Allows you to select a question to be displayed per the response to a question.</span></span>
    - <span data-ttu-id="27161-132">**Verbergen**: Ermöglicht es Ihnen, eine Frage auszuwählen, die anhand der Antwort auf eine Frage ausgeblendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="27161-132">**Hide**: Allows you to select a question to be hidden per the response to a question.</span></span>
    - <span data-ttu-id="27161-133">**Umschalten**: Ermöglicht es Ihnen, den Status der ausgewählten Frage anhand der Antwort auf eine Frage umzuschalten.</span><span class="sxs-lookup"><span data-stu-id="27161-133">**Toggle**: Allows you to toggle the state of the selected question per the response to a question.</span></span>
    - <span data-ttu-id="27161-134">**Navigieren zu**: Ermöglicht es Ihnen, ein Ziel auszuwählen, zu dem ein Befragter navigiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="27161-134">**Navigate to**: Allows you to select a target to which a responder should be navigated.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-135">![Eine Aktion für Bedingung „true“ auswählen](media/branch-true-select-action.png "Eine Aktion für Bedingung „true“ auswählen")</span><span class="sxs-lookup"><span data-stu-id="27161-135">![Select an action for true condition](media/branch-true-select-action.png "Select an action for true condition")</span></span>

10. <span data-ttu-id="27161-136">Wählen Sie in der Liste **Ziel auswählen** ein Ziel für die ausgewählte Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="27161-136">In the **Select target** list, choose a target for the selected action.</span></span> <span data-ttu-id="27161-137">Wenn Sie **Anzeigen**, **Ausblenden,** oder **Umschalten** als Aktion wählen, können Sie **Frage** als Ziel auswählen.</span><span class="sxs-lookup"><span data-stu-id="27161-137">If you select **Show**, **Hide,** or **Toggle** as the action, you can select **Question** as the target.</span></span> <span data-ttu-id="27161-138">Wenn Sie als Aktion **Navigieren zu** wählen, können Sie eines der folgenden Ziele auswählen:</span><span class="sxs-lookup"><span data-stu-id="27161-138">If you select **Navigate to** as the action, you can choose one of the following targets:</span></span>

    - <span data-ttu-id="27161-139">**Frage**: Ermöglicht es Ihnen, zu einer Frage pro Antwort auf eine Frage zu springen.</span><span class="sxs-lookup"><span data-stu-id="27161-139">**Question**: Allows you to skip to a question per the response to a question.</span></span> <span data-ttu-id="27161-140">Die Fragen zwischen Quell- und Zielfrage sind für den Beantworter verborgen.</span><span class="sxs-lookup"><span data-stu-id="27161-140">The questions in between the source and target questions are hidden from the responder.</span></span>
    - <span data-ttu-id="27161-141">**Ende der Umfrage**: Ermöglicht es Ihnen, die Umfrage anhand der Antwort auf eine Frage zu beenden.</span><span class="sxs-lookup"><span data-stu-id="27161-141">**End of survey**: Allows you to end the survey per the response to a question.</span></span>
    - <span data-ttu-id="27161-142">**Kettenumfrage**: Ermöglicht es Ihnen, eine andere, von Ihnen erstellte Umfrage pro Antwort auf eine Frage zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="27161-142">**Chain survey**: Allows you to open a different survey, created by you, per the response to a question.</span></span>
    - <span data-ttu-id="27161-143">**URL**: Ermöglicht es Ihnen, eine Website anhand der Antwort auf eine Frage zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="27161-143">**URL**: Allows you to open a website per the response to a question.</span></span> <span data-ttu-id="27161-144">Sie müssen der URL `http://` hinzufügen, damit sie ordnungsgemäß funktioniert.</span><span class="sxs-lookup"><span data-stu-id="27161-144">You must add `http://` to the URL for it to work properly.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-145">![Ein Ziel für Bedingung „true“ auswählen](media/branch-true-select-target.png "Ein Ziel für Bedingung „true“ auswählen")</span><span class="sxs-lookup"><span data-stu-id="27161-145">![Select a target for true condition](media/branch-true-select-target.png "Select a target for true condition")</span></span>

11. <span data-ttu-id="27161-146">Geben Sie in der Liste **Wert auswählen** einen Wert für das Ziel ein oder wählen Sie ihn aus.</span><span class="sxs-lookup"><span data-stu-id="27161-146">In the **Select value** list, enter or choose a value per the target.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-147">![Aktion „true“ für Verzweigungsregeln](media/branch-true-action.png "Aktion „true“ für Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="27161-147">![Branching rules true action](media/branch-true-action.png "Branching rules true action")</span></span>

12. <span data-ttu-id="27161-148">Wählen Sie **Add "If false"**, um die Aktion hinzuzufügen, die ausgelöst wird, wenn die definierte Bedingung nicht den Kriterien entspricht.</span><span class="sxs-lookup"><span data-stu-id="27161-148">Select **Add “If false”** to add the action that will trigger when the defined condition does not meet the criteria.</span></span> <span data-ttu-id="27161-149">Führen Sie dann die Schritte 8 bis 11 aus.</span><span class="sxs-lookup"><span data-stu-id="27161-149">Then follow Steps 8 through 11.</span></span> 

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-150">![Aktion „false“ für Verzweigungsregeln](media/branch-false-action.png "Aktion „false“ für Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="27161-150">![Branching rules false action](media/branch-false-action.png "Branching rules false action")</span></span>

13. <span data-ttu-id="27161-151">Wählen Sie **Speichern** aus.</span><span class="sxs-lookup"><span data-stu-id="27161-151">Select **Save**.</span></span>

<span data-ttu-id="27161-152">Nachdem Sie eine Verzweigungsregel erstellt haben, können Sie eine Vorschau der Umfrage anzeigen und sehen, ob die Regel wie erwartet funktioniert.</span><span class="sxs-lookup"><span data-stu-id="27161-152">After creating a branching rule, you can preview the survey and see if the rule is working as expected.</span></span>

## <a name="manage-branching-rules"></a><span data-ttu-id="27161-153">Verwalten von Verzweigungsregeln</span><span class="sxs-lookup"><span data-stu-id="27161-153">Manage branching rules</span></span>

<span data-ttu-id="27161-154">Nachdem Sie eine Verzweigungsregel oder einen Satz von Verzweigungsregeln erstellt haben, können Sie die Reihenfolge ihrer Ausführung bearbeiten, löschen oder ändern.</span><span class="sxs-lookup"><span data-stu-id="27161-154">Once you have created a branching rule or a set of branching rules, you can edit, delete, or change the order of their execution.</span></span> <span data-ttu-id="27161-155">Die Verzweigungsregeln werden in der Reihenfolge ihrer Erstellung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="27161-155">The branching rules are executed in the order they are created.</span></span> 

1. <span data-ttu-id="27161-156">Öffnen Sie die Umfrage, in der Sie Verzweigungsregeln verwalten möchten.</span><span class="sxs-lookup"><span data-stu-id="27161-156">Open the survey in which you want to manage branching rules.</span></span>
 
2. <span data-ttu-id="27161-157">Wählen Sie die Schaltfläche **Auslassungspunkte** (...) aus der Symbolleiste oben auf der Seite aus, und wählen Sie dann **Verzweigungsregeln** aus.</span><span class="sxs-lookup"><span data-stu-id="27161-157">Select the **ellipsis** button (…) from the toolbar at the top of the page, and then select **Branching rules**.</span></span> 

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-158">![Schaltfläche „Verzweigungsregeln“](media/branching-rules-button.png "Schaltfläche „Verzweigungsregeln“")</span><span class="sxs-lookup"><span data-stu-id="27161-158">![Branching rules button](media/branching-rules-button.png "Branching rules button")</span></span>

3. <span data-ttu-id="27161-159">Eine Liste von Regeln wird in einem Raster angezeigt.</span><span class="sxs-lookup"><span data-stu-id="27161-159">A list of rules is displayed in a grid.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="27161-160">![Vorhandene Verzweigungsregeln](media/existing-rules.png "Vorhandene Verzweigungsregeln")</span><span class="sxs-lookup"><span data-stu-id="27161-160">![Existing branching rules](media/existing-rules.png "Existing branching rules")</span></span>

4. <span data-ttu-id="27161-161">Um eine Verzweigungsregel zu bearbeiten, wählen Sie **Bearbeiten** ![Verzweigungsregel bearbeiten](media/edit-rule.png "Verzweigungsregel bearbeiten") aus der entsprechenden Regelzeile aus.</span><span class="sxs-lookup"><span data-stu-id="27161-161">To edit a branching rule, select **Edit** ![Edit branching rule](media/edit-rule.png "Edit branching rule") from the corresponding rule row.</span></span>

5. <span data-ttu-id="27161-162">Um eine Verzweigungsregel zu löschen, wählen Sie **Löschen** ![Verzweigungsregel löschen](media/delete-rule.png "Verzweigungsregel löschen") aus der entsprechenden Regelzeile aus.</span><span class="sxs-lookup"><span data-stu-id="27161-162">To delete a branching rule, select **Delete** ![Delete branching rule](media/delete-rule.png "Delete branching rule") from the corresponding rule row.</span></span>

6. <span data-ttu-id="27161-163">Um die Reihenfolge der Ausführung einer Verzweigungsregel zu ändern, verschieben Sie eine Regel im Raster nach oben oder unten.</span><span class="sxs-lookup"><span data-stu-id="27161-163">To change the order of execution of a branching rule, move a rule up or down in the grid.</span></span> <span data-ttu-id="27161-164">Um eine Regel nach oben oder unten zu verschieben, wählen Sie **Nach oben** ![Nach oben](media/move-up-rule.png "Nach oben") oder **Nach unten** ![Nach unten](media/move-down-rule.png "Nach unten") aus der entsprechenden Regelreihe aus.</span><span class="sxs-lookup"><span data-stu-id="27161-164">To move a rule up or down, select **Move up** ![Move up](media/move-up-rule.png "Move up") or **Move down** ![Move down](media/move-down-rule.png "Move down") from the corresponding rule row.</span></span>

## <a name="see-also"></a><span data-ttu-id="27161-165">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="27161-165">See also</span></span>

[<span data-ttu-id="27161-166">Eine neue Umfrage erstellen</span><span class="sxs-lookup"><span data-stu-id="27161-166">Create a new survey</span></span>](create-new-survey.md)<br>
[<span data-ttu-id="27161-167">Thema auf eine Umfrage anwenden</span><span class="sxs-lookup"><span data-stu-id="27161-167">Apply theme to a survey</span></span>](apply-theme.md)<br>
[<span data-ttu-id="27161-168">Vorschau und Test einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="27161-168">Preview and test a survey</span></span>](preview-test-survey.md)<br>
[<span data-ttu-id="27161-169">Personalisieren einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="27161-169">Personalize a survey</span></span>](personalize-survey.md)<br>
[<span data-ttu-id="27161-170">Text in einer Umfrage formatieren</span><span class="sxs-lookup"><span data-stu-id="27161-170">Format text in a survey</span></span>](survey-text-format.md)<br>
[<span data-ttu-id="27161-171">Erstellen eins klassischen Formulars</span><span class="sxs-lookup"><span data-stu-id="27161-171">Create a classic form</span></span>](create-classic-form.md)<br>
[<span data-ttu-id="27161-172">Erstellen einer mehrsprachigen Umfrage</span><span class="sxs-lookup"><span data-stu-id="27161-172">Create a multilingual survey</span></span>](create-multilingual-survey.md)<br>
[<span data-ttu-id="27161-173">Erstellen einet mehrseitigen Umfrage</span><span class="sxs-lookup"><span data-stu-id="27161-173">Create a multipage survey</span></span>](create-multipage-survey.md)
