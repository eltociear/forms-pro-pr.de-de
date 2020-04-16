---
title: Eine Umfrage personalisieren | MicrosoftDocs
description: Anleitung zur Personalisierung einer Umfrage mit Microsoft Forms Pro.
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 01/16/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: 1AECC69F-B68A-4776-884A-C59770FC5C96
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 027fcb19c98c85a7da0819169abbf7bf31bbe383
ms.sourcegitcommit: 38563d8ed7de1c1d1d54c2b5cbd2d46c52c2478a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2020
ms.locfileid: "3161389"
---
# <a name="personalize-a-survey"></a><span data-ttu-id="b4bb7-103">Personalisieren einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="b4bb7-103">Personalize a survey</span></span>

<span data-ttu-id="b4bb7-104">Sie können benutzerdefinierte Informationen automatisch in Ihre Umfrage einfügen, indem Sie Umfragevariablen verwenden.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-104">You can automatically insert custom information into your survey by using survey variables.</span></span> <span data-ttu-id="b4bb7-105">Beispielsweise können Sie mit einer Umfragevariablen den Vornamen und den Produktnamen eines Kunden automatisch in eine Frage einfügen, um sie zu personalisieren.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-105">For example, you can use a survey variable to automatically insert a customer's first name and product name into a question to personalize it.</span></span>

<span data-ttu-id="b4bb7-106">Standardmäßig sind die folgenden Umfragevariablen verfügbar:</span><span class="sxs-lookup"><span data-stu-id="b4bb7-106">By default, the following survey variables are available:</span></span>

- <span data-ttu-id="b4bb7-107">**Vorname**: Fügt den Vornamen des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-107">**First Name**: Inserts the first name of the recipient.</span></span>

- <span data-ttu-id="b4bb7-108">**Nachname**: Fügt den Nachnamen des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-108">**Last Name**: Inserts the last name of the recipient.</span></span>

- <span data-ttu-id="b4bb7-109">**Gebietsschema**: Gibt das Gebietsschema der Umfrage an, während sie in die E-Mail eingebettet wird.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-109">**locale**: Specifies the locale of the survey while embedding it in the email.</span></span> <span data-ttu-id="b4bb7-110">Mehr Informationen: [Betten Sie eine Umfrage in eine E-Mail ein](send-survey-email.md#embed-a-survey-in-an-email)</span><span class="sxs-lookup"><span data-stu-id="b4bb7-110">More information: [Embed a survey in an email](send-survey-email.md#embed-a-survey-in-an-email)</span></span>

<span data-ttu-id="b4bb7-111">Um eine neue Umfragevariable zu erstellen:</span><span class="sxs-lookup"><span data-stu-id="b4bb7-111">To create a new survey variable:</span></span>

1.  <span data-ttu-id="b4bb7-112">Öffnen Sie die Umfrage, in der Sie Umfragevariablen verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-112">Open the survey in which you want to use survey variables.</span></span>

2.  <span data-ttu-id="b4bb7-113">Wählen Sie die Auslassungspunkte-Schaltfläche **(...)** in der Symbolleiste oben auf der Seite und wählen Sie dann **Umfragevariablen**.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-113">Select the ellipsis button **(…)** from the toolbar at the top of the page, and then select **Survey variables**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="b4bb7-114">![Schaltflächefür Umfragevariablen](media/custom-data-button.png "Schaltfläche Variablen der Umfrage")</span><span class="sxs-lookup"><span data-stu-id="b4bb7-114">![Survey variables button](media/custom-data-button.png "Survey variables button")</span></span>

3.  <span data-ttu-id="b4bb7-115">Wählen Sie **Neue Variable**.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-115">Select **New variable**.</span></span>

5.  <span data-ttu-id="b4bb7-116">Geben Sie einen Namen und einen Standardwert für die Umfragevariable ein.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-116">Enter a name and default value for the survey variable.</span></span>

> [!NOTE]
> - <span data-ttu-id="b4bb7-117">Sie können Umfrageeinladungen auch personalisieren, indem Sie Umfragevariablen verwenden.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-117">You can also personalize survey invitations by using survey variables.</span></span> <span data-ttu-id="b4bb7-118">Mehr Informationen: [Personalisieren Sie eine E-Mail](send-survey-email.md#personalize-an-email)</span><span class="sxs-lookup"><span data-stu-id="b4bb7-118">More information: [Personalize an email](send-survey-email.md#personalize-an-email)</span></span>
> - <span data-ttu-id="b4bb7-119">Verwenden Sie keine Umfragevariablen, wenn Sie planen, eine Umfrage anonym zu senden.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-119">Don't use survey variables if you plan to send a survey anonymously.</span></span> <span data-ttu-id="b4bb7-120">Bei einer anonymen Umfrage werden Variablen nicht durch aktuelle Daten ersetzt.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-120">The variables won't be replaced with actual data in an anonymous survey.</span></span>
> - <span data-ttu-id="b4bb7-121">Variablen der Umfrage werden beim Senden einer Umfrageeinladung durch die angegebenen Standardwerte ersetzt.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-121">Survey variables are replaced with the specified default values when sending a survey invitation.</span></span>
> - <span data-ttu-id="b4bb7-122">Sie können maximal 15 Variablen in einer Umfrage definieren.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-122">You can define a maximum of 15 variables in a survey.</span></span>

## <a name="add-survey-variables-to-a-question"></a><span data-ttu-id="b4bb7-123">Hinzufügen von Umfragevariablen zu einer Frage</span><span class="sxs-lookup"><span data-stu-id="b4bb7-123">Add survey variables to a question</span></span>

<span data-ttu-id="b4bb7-124">Nachdem Sie die erforderlichen Umfragevariablen erstellt haben, müssen Sie sie der noch Frage hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-124">After creating the required survey variables, you need to add them to the question.</span></span> 

1.  <span data-ttu-id="b4bb7-125">Öffnen Sie die Umfrage, in der Sie Umfragevariablen hinzufügen möchten.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-125">Open the survey in which you want to add survey variables.</span></span>

2.  <span data-ttu-id="b4bb7-126">Wählen Sie auf der Registerkarte **Fragen** den Fragetext aus, dem Sie eine Umfragevariable hinzufügen möchten.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-126">On the **Questions** tab, select the question text to which you want to add a survey variable.</span></span> <span data-ttu-id="b4bb7-127">Die Formatsymbolleiste wird angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-127">The formatting toolbar appears.</span></span>

3.  <span data-ttu-id="b4bb7-128">Positionieren Sie den Cursor an der Stelle, an der Sie die Umfragevariable hinzufügen möchten.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-128">Place the cursor at the location where you want to add the survey variable.</span></span>

4.  <span data-ttu-id="b4bb7-129">Wählen Sie in der Liste **Variablen** in der Formatierungssymbolleiste die Umfragevariable aus, die Sie hinzufügen möchten.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-129">From the **Variables** list in the formatting toolbar, select the survey variable you want to add.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="b4bb7-130">![Umfragevariablen hinzufügen ](media/add-pipe-data.png "Hinzufügen von Umfragevariablen")</span><span class="sxs-lookup"><span data-stu-id="b4bb7-130">![Add survey variables](media/add-pipe-data.png "Add survey variables")</span></span>

<span data-ttu-id="b4bb7-131">Nehmen wir zum Beispiel an, dass Sie eine Umfragevariable mit dem Namen **Produktname** erstellt haben und dass Sie den Vornamen des Kunden und den Produktnamen in einer Frage anzeigen möchten.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-131">For example, let's say that you've created a survey variable named **Product Name** and that you want to display the customer's first name and the product name in a question.</span></span> <span data-ttu-id="b4bb7-132">Wählen Sie **Vorname** und **Produktname** aus der Liste **Variablen**.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-132">Select **First Name** and **Product Name** from the **Variables** list.</span></span> <span data-ttu-id="b4bb7-133">*{{Vorname}}* und *{{Produktname}}* werden an der Cursorposition eingefügt.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-133">*{{First Name}}* and *{{Product Name}}* are inserted at the cursor location.</span></span>

<span data-ttu-id="b4bb7-134">Nehmen wir an, die Frage ist: *{{Vorname}}*, wie beurteilen Sie insgesamt Ihre Erfahrungen mit dem Kundenservice für *{{Produktname}}*?</span><span class="sxs-lookup"><span data-stu-id="b4bb7-134">Let's say the question is: *{{First Name}}*, overall, how would you rate your experience with customer service for *{{Product Name}}*?</span></span>

<span data-ttu-id="b4bb7-135">Diese Frage wird so aussehen, wenn ein Kunde namens Bert Hair die Umfrage zu einem Produkt namens Contoso Sales durchführt:</span><span class="sxs-lookup"><span data-stu-id="b4bb7-135">That question will look like this when a customer named Bert Hair takes the survey for a product named Contoso Sales:</span></span>

<span data-ttu-id="b4bb7-136">&nbsp;&nbsp;&nbsp;&nbsp;Bert, insgesamt, wie würden Sie Ihre Erfahrungen mit dem Kundenservice für Contoso Sales bewerten?</span><span class="sxs-lookup"><span data-stu-id="b4bb7-136">&nbsp;&nbsp;&nbsp;&nbsp;Bert, overall, how would you rate your experience with customer service for Contoso Sales?</span></span>

## <a name="specify-values-for-survey-variables"></a><span data-ttu-id="b4bb7-137">Geben Sie Werte für Umfragevariablen an</span><span class="sxs-lookup"><span data-stu-id="b4bb7-137">Specify values for survey variables</span></span>

<span data-ttu-id="b4bb7-138">Beim Erstellen muss für jede Umfragevariable der Standardwert angegeben werden, während Sie diese erstellen.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-138">You must specify default values for survey variables while you create them.</span></span> <span data-ttu-id="b4bb7-139">Wenn Sie keine Standardwerte angeben, wird für die Umfragevariablen nichts angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-139">If you don't specify default values, nothing will be displayed for the survey variables.</span></span> <span data-ttu-id="b4bb7-140">Sie können auch die Werte für Umfragevariablen angeben:</span><span class="sxs-lookup"><span data-stu-id="b4bb7-140">You can also specify the values for survey variables:</span></span>

- <span data-ttu-id="b4bb7-141">Beim Versenden von E-Mail-Einladungen.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-141">When sending email invitations.</span></span>
- <span data-ttu-id="b4bb7-142">Bei der Konfiguration eines Flows.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-142">When configuring a flow.</span></span>

### <a name="specify-values-when-sending-email-invitations"></a><span data-ttu-id="b4bb7-143">Geben Sie Werte für den Versand von E-Mail-Einladungen an</span><span class="sxs-lookup"><span data-stu-id="b4bb7-143">Specify values when sending email invitations</span></span>

<span data-ttu-id="b4bb7-144">Wenn Sie Umfragevariablen erstellt, aber keine Standardwerte angegeben haben, wird beim Senden der Umfrage oben auf der Seite eine Warnmeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-144">If you've created survey variables but didn't specify default values for them, a warning message is displayed at the top of the page when you send the survey.</span></span> <span data-ttu-id="b4bb7-145">Wählen Sie **Umfragevariablen definieren** zum Öffnen der **Umfragevariablen** Bereich und geben Sie dann die Standardwerte an.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-145">Select **Define survey variables** to open the **Survey variables** pane, and then specify the default values.</span></span>

### <a name="specify-values-in-a-flow"></a><span data-ttu-id="b4bb7-146">Werte in einem Flow angeben</span><span class="sxs-lookup"><span data-stu-id="b4bb7-146">Specify values in a flow</span></span>

<span data-ttu-id="b4bb7-147">Um Werte für Umfragevariablen in einem Flow anzugeben:</span><span class="sxs-lookup"><span data-stu-id="b4bb7-147">To specify values for survey variables in a flow:</span></span>

1.  <span data-ttu-id="b4bb7-148">Wählen Sie während der Konfiguration eines Flows **Bearbeiten im erweiterten Modus**.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-148">While configuring a flow, select **Edit in advanced mode**.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="b4bb7-149">![Bearbeiten Sie einen Flow im erweiterten Modus](media/flow-advanced-mode.png "Bearbeiten eines Flows im erweiterten Modus")</span><span class="sxs-lookup"><span data-stu-id="b4bb7-149">![Edit a flow in advanced mode](media/flow-advanced-mode.png "Edit a flow in advanced mode")</span></span>

2.  <span data-ttu-id="b4bb7-150">Gehen Sie zu dem Schritt, der die Umfrage sendet, und erweitern Sie sie.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-150">Go to the step that sends the survey, and expand it.</span></span>

3.  <span data-ttu-id="b4bb7-151">Wählen Sie **Erweiterte Optionen anzeigen**.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-151">Select **Show advanced options**.</span></span>

    <span data-ttu-id="b4bb7-152">![Erweiterte Optionen für einen Schritt in einem Flow anzeigen](media/flow-step-advanced-options-button.png "Zeigt erweiterte Optionen für einen Schritt in einem Flow an")</span><span class="sxs-lookup"><span data-stu-id="b4bb7-152">![Show advanced options for a step in a flow](media/flow-step-advanced-options-button.png "Show advanced options for a step in a flow")</span></span>

4.  <span data-ttu-id="b4bb7-153">Geben Sie die Werte für Umfragevariablen an.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-153">Specify the values for survey variables.</span></span>

    <span data-ttu-id="b4bb7-154">![Werte für Umfragevariablen festlegen](media/flow-step-advanced-options.png "Geben Sie Werte für Umfragevariablen an")</span><span class="sxs-lookup"><span data-stu-id="b4bb7-154">![Specify values for survey variables](media/flow-step-advanced-options.png "Specify values for survey variables")</span></span>

5.  <span data-ttu-id="b4bb7-155">Speichern Sie die Änderungen.</span><span class="sxs-lookup"><span data-stu-id="b4bb7-155">Save the changes.</span></span>

### <a name="see-also"></a><span data-ttu-id="b4bb7-156">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="b4bb7-156">See also</span></span>

[<span data-ttu-id="b4bb7-157">Eine neue Umfrage erstellen</span><span class="sxs-lookup"><span data-stu-id="b4bb7-157">Create a new survey</span></span>](create-new-survey.md)<br>
[<span data-ttu-id="b4bb7-158">Ein Design auf eine Umfrage anwenden</span><span class="sxs-lookup"><span data-stu-id="b4bb7-158">Apply a theme to a survey</span></span>](apply-theme.md)<br>
[<span data-ttu-id="b4bb7-159">Vorschau und Test einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="b4bb7-159">Preview and test a survey</span></span>](preview-test-survey.md)<br>
[<span data-ttu-id="b4bb7-160">Erstellen einer Verzweigungsregel</span><span class="sxs-lookup"><span data-stu-id="b4bb7-160">Create a branching rule</span></span>](create-branching-rule.md)<br>
[<span data-ttu-id="b4bb7-161">Text in einer Umfrage formatieren</span><span class="sxs-lookup"><span data-stu-id="b4bb7-161">Format text in a survey</span></span>](survey-text-format.md)<br>
[<span data-ttu-id="b4bb7-162">Erstellen eins klassischen Formulars</span><span class="sxs-lookup"><span data-stu-id="b4bb7-162">Create a classic form</span></span>](create-classic-form.md)<br>
[<span data-ttu-id="b4bb7-163">Erstellen einer mehrsprachigen Umfrage</span><span class="sxs-lookup"><span data-stu-id="b4bb7-163">Create a multilingual survey</span></span>](create-multilingual-survey.md)<br>
[<span data-ttu-id="b4bb7-164">Erstellen Sie eine mehrseitige Umfrage</span><span class="sxs-lookup"><span data-stu-id="b4bb7-164">Create a multiple-page survey</span></span>](create-multipage-survey.md)
