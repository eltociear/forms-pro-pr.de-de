---
title: Einbetten einer Umfrage in eine Webseite | MicrosoftDocs
description: Anleitung zum Einbetten einer Umfrage in eine Webseite
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/06/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 649b3390-c3a5-4166-a014-ae3cfd14cc71
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 0fcda0c613deb22bfa35f268be5070c89d86224b
ms.sourcegitcommit: 2b2ffca387514568ff95dd1e566ba1850a416744
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2019
ms.locfileid: "2900381"
---
# <a name="embed-a-survey-in-a-webpage"></a><span data-ttu-id="830bc-103">Eine Umfrage in einer Webseite einbetten</span><span class="sxs-lookup"><span data-stu-id="830bc-103">Embed a survey in a webpage</span></span>

<span data-ttu-id="830bc-104">Sie können Ihre Umfrage in eine Webseite einbetten, indem Sie den Einbettungscode der Umfrage in den Quellcode Ihrer Webseite einfügen.</span><span class="sxs-lookup"><span data-stu-id="830bc-104">You can embed your survey in a webpage by pasting the survey's embed code into your webpage's source code.</span></span> <span data-ttu-id="830bc-105">Sie können eine der folgenden Optionen eingebetteten Stile für die Umfrage auswählen:</span><span class="sxs-lookup"><span data-stu-id="830bc-105">You can choose one of the following embed styles for your survey:</span></span>

- <span data-ttu-id="830bc-106">**Inline**: Zeigt die Umfrage statisch auf der Webseite an.</span><span class="sxs-lookup"><span data-stu-id="830bc-106">**Inline**: Displays the survey statically on the webpage.</span></span>

- <span data-ttu-id="830bc-107">**Popup**: Zeigt die Umfrage in einem Popupfenster an, das auf der Aktion der antwortenden Seite basiert.</span><span class="sxs-lookup"><span data-stu-id="830bc-107">**Pop-up**: Displays the survey in a pop-up window based on the respondent's action.</span></span>

- <span data-ttu-id="830bc-108">**Schaltfläche**: Zeigt die Umfrage an, wenn eine Schaltfläche ausgewählt ist.</span><span class="sxs-lookup"><span data-stu-id="830bc-108">**Button**: Displays the survey when a button is selected.</span></span> <span data-ttu-id="830bc-109">Standardmäßig lautet der Schaltflächenname **Feedback**.</span><span class="sxs-lookup"><span data-stu-id="830bc-109">By default, the button name is **Provide feedback**.</span></span>

<span data-ttu-id="830bc-110">Sie können auch eine Anzeigendichte für die Umfrage auswählen.</span><span class="sxs-lookup"><span data-stu-id="830bc-110">You can also select a display density for your survey.</span></span> <span data-ttu-id="830bc-111">Die Anzeigedichte steuert die Größe des Leerraums und die Größe der Elemente auf dem Bildschirm.</span><span class="sxs-lookup"><span data-stu-id="830bc-111">The display density controls the amount of white space and the size of the elements on the screen.</span></span> <span data-ttu-id="830bc-112">Die folgenden Optionen stehen für die Anzeigedichte zur Verfügung:</span><span class="sxs-lookup"><span data-stu-id="830bc-112">The following options are available for display density:</span></span>

- <span data-ttu-id="830bc-113">**Standard**: Zeigt die Umfrage mit dem Standardumfang an Leerraum und Elementen in Standardgröße auf dem Bildschirm an.</span><span class="sxs-lookup"><span data-stu-id="830bc-113">**Standard**: Displays the survey with the standard amount of white space and standard-size elements on the screen.</span></span>

- <span data-ttu-id="830bc-114">**Kompakt**: Zeigt die Umfrage mit einem reduzierten Umfang an Leerraum und kleineren Elementen auf dem Bildschirm an.</span><span class="sxs-lookup"><span data-stu-id="830bc-114">**Compact**: Displays the survey with a reduced amount of white space and smaller elements on the screen.</span></span> <span data-ttu-id="830bc-115">Standardmäßig ist **Kompakt** ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="830bc-115">By default, **Compact** is selected.</span></span> <span data-ttu-id="830bc-116">Diese Anzeigedichte ist nützlich, um die Umfrage auf kleineren Bildschirmen wie Mobilgeräten oder Tablets anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="830bc-116">This display density is useful for displaying the survey on smaller screens, such as mobile devices or tablets.</span></span>

<span data-ttu-id="830bc-117">Wenn Sie Umfragevariablen erstellt haben, werden sie verwendet, um die Informationen Ihrer antwortenden Seite und den Kontext, in dem die Antwort gegeben wurde, zu erfassen und diese Daten in der Umfrageantwort zu speichern.</span><span class="sxs-lookup"><span data-stu-id="830bc-117">If you've created survey variables, they'll be used to capture your respondent's information and the context in which the response was provided, and store that data in the survey response.</span></span> <span data-ttu-id="830bc-118">Sie können bei Bedarf auch neue Umfragevariablen erstellen.</span><span class="sxs-lookup"><span data-stu-id="830bc-118">You can also create new survey variables, if you need.</span></span> <span data-ttu-id="830bc-119">Wenn die entsprechenden Werte nicht an die Umfragevariablen im Einbettungscode übergeben werden, werden die Standardwerte verwendet.</span><span class="sxs-lookup"><span data-stu-id="830bc-119">If the appropriate values aren't passed to survey variables in the embed code, the default values will be used.</span></span>

<span data-ttu-id="830bc-120">Die Werte von Umfragevariablen in einer Antwort werden auf der Registerkarte **Personalisierte Daten** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="830bc-120">The values of survey variables in a response are displayed on the **Personalized data** tab.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="830bc-121">![Umfragevariablen in einer Umfrageantwort](media/survey-response-context-param.png "Umfragevariablen in einer Umfrageantwort")</span><span class="sxs-lookup"><span data-stu-id="830bc-121">![Survey variables in a survey response](media/survey-response-context-param.png "Survey variables in a survey response")</span></span>

<span data-ttu-id="830bc-122">Um Ihre Umfrage einzubetten:</span><span class="sxs-lookup"><span data-stu-id="830bc-122">To embed your survey:</span></span>

1.  <span data-ttu-id="830bc-123">Öffnen Sie die Umfrage, die Sie einbetten möchten, und wählen Sie dann **Senden** aus der Symbolleiste oben auf der Seite aus.</span><span class="sxs-lookup"><span data-stu-id="830bc-123">Open the survey you want to embed, and then select **Send** from the toolbar at the top of the page.</span></span>

2.  <span data-ttu-id="830bc-124">Wählen Sie **Einbetten** aus.</span><span class="sxs-lookup"><span data-stu-id="830bc-124">Select **Embed**.</span></span>

3. <span data-ttu-id="830bc-125">Wählen Sie unter **Anzeigendichte auswählen** eine der folgenden Optionen aus:</span><span class="sxs-lookup"><span data-stu-id="830bc-125">Under **Select display density**, select one of the following options:</span></span>

    - <span data-ttu-id="830bc-126">Standard</span><span class="sxs-lookup"><span data-stu-id="830bc-126">Standard</span></span>

    - <span data-ttu-id="830bc-127">Kompakt</span><span class="sxs-lookup"><span data-stu-id="830bc-127">Compact</span></span>

4.  <span data-ttu-id="830bc-128">Wählen Sie unter **Eingebetteten Stil auswählen** eine der folgenden Optionen aus:</span><span class="sxs-lookup"><span data-stu-id="830bc-128">Under **Set embed style**, select one of the following options:</span></span>

    -   <span data-ttu-id="830bc-129">Inline</span><span class="sxs-lookup"><span data-stu-id="830bc-129">Inline</span></span>

    -   <span data-ttu-id="830bc-130">Pop-up</span><span class="sxs-lookup"><span data-stu-id="830bc-130">Pop-up</span></span>

    -   <span data-ttu-id="830bc-131">Schaltfläche</span><span class="sxs-lookup"><span data-stu-id="830bc-131">Button</span></span>

5.  <span data-ttu-id="830bc-132">Wählen Sie optional unter **Umfragevariablen** die Option **Neue Variablen** aus, um eine Variable zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="830bc-132">Optionally, under **Survey variables**, select **New variable** to create a new variable.</span></span>

6.  <span data-ttu-id="830bc-133">Wählen Sie **Code generieren**.</span><span class="sxs-lookup"><span data-stu-id="830bc-133">Select **Generate code**.</span></span> <span data-ttu-id="830bc-134">Der Einbettungscode wird gemäß den von Ihnen ausgewählten Optionen generiert.</span><span class="sxs-lookup"><span data-stu-id="830bc-134">The embed code is generated in accordance with the options you selected.</span></span>

7.  <span data-ttu-id="830bc-135">Wählen Sie **Kopieren**, und fügen Sie dann den Einbettungscode in eine Webseite ein, um Ihre Umfrage einzubetten.</span><span class="sxs-lookup"><span data-stu-id="830bc-135">Select **Copy**, and then paste the embed code into a webpage to embed your survey.</span></span> <span data-ttu-id="830bc-136">Sie müssen dann den Quellcode der Webseite aktualisieren, um die Umfrage auf der Webseite anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="830bc-136">You must then update the webpage's source code to render the survey on the webpage.</span></span> <span data-ttu-id="830bc-137">Informationen darüber, wie der Quellcodes aktualisiert wird, finden Sie unter [Update des Quellcodes einer Webseite](#update-a-webpages-source-code).</span><span class="sxs-lookup"><span data-stu-id="830bc-137">For information about how to update the source code, see [Update a webpage's source code](#update-a-webpages-source-code).</span></span>  

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="830bc-138">![Eine Umfrage in einer Webseite einbetten](media/survey-embed.png "Eine Umfrage in einer Webseite einbetten")</span><span class="sxs-lookup"><span data-stu-id="830bc-138">![embed a survey in a webpage](media/survey-embed.png "Embed a survey in a webpage")</span></span>  

## <a name="update-a-webpages-source-code"></a><span data-ttu-id="830bc-139">Aktualisieren des Quellcodes einer Webseite</span><span class="sxs-lookup"><span data-stu-id="830bc-139">Update a webpage's source code</span></span>

<span data-ttu-id="830bc-140">Nachdem Sie den Einbettungscode generiert haben, müssen Sie ihn dem Quellcode Ihrer Webseite hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="830bc-140">After generating the embed code, you must add it to your webpage's source code.</span></span> <span data-ttu-id="830bc-141">Dann erstellen Sie eine Methode, die die Funktion **renderSurvey** aufruft, um die Umfrage auf der Webseite anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="830bc-141">Then you create a method that calls the **renderSurvey** function to render the survey on the webpage.</span></span> <span data-ttu-id="830bc-142">Sie müssen sicherstellen, dass die Werte in der Funktion **renderSurvey** in der gleichen Reihenfolge übergeben werden wie die Umfragevariablen, die in der Funktion **renderSurvey** im Embed-Code definiert sind.</span><span class="sxs-lookup"><span data-stu-id="830bc-142">You must ensure that the values in the **renderSurvey** function are passed in the same order as the survey variables that are defined in the **renderSurvey** function in the embed code.</span></span>

<span data-ttu-id="830bc-143">Für eine Inline-Umfrage muss ein übergeordneter **div** Container definiert werden, damit die Umfrage angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="830bc-143">For an inline survey, a parent **div** container must be defined for the survey to be displayed.</span></span>

### <a name="scenario-to-embed-an-inline-survey"></a><span data-ttu-id="830bc-144">Szenario zur Einbindung einer Inline-Umfrage</span><span class="sxs-lookup"><span data-stu-id="830bc-144">Scenario to embed an inline survey</span></span>

<span data-ttu-id="830bc-145">Wir nehmen einmal an, Sie möchten eine Inline-Umfrage in Ihre Webseite einbetten und haben zwei Umfragevariablen erstellt (**E-Mail** und **PageTitle**).</span><span class="sxs-lookup"><span data-stu-id="830bc-145">Let's say you want to embed an inline survey into your webpage, and you've created two survey variables (**Email** and **PageTitle**).</span></span> <span data-ttu-id="830bc-146">Der Embed-Code wird wie folgt generiert:</span><span class="sxs-lookup"><span data-stu-id="830bc-146">The embed code is generated as follows:</span></span>

```JavaScript
<script src="https://www.contoso.com/Embed.js" type="text/javascript"></script><link rel="stylesheet" type="text/css" href="https://www.contoso.com/Embed.css" /><script type = "text/javascript" >function renderSurvey(parentElementId, FirstName, LastName, Email, PageTitle){var se = new SurveyEmbed("JtSG9ha000000000020pTSB1AovM_5u8bQH1UQjlNQjZRWV0000000000","https://www.contoso.com/");var context = {"FirstName": FirstName,"LastName": LastName,"Email": Email,"PageTitle": PageTitle,};se.renderInline(parentElementId, context);}</script>
```

<span data-ttu-id="830bc-147">Im vorhergehenden Einbettungscode enthält die Funktion `renderSurvey` neben dem ausgewählten `parentElementId`-Parameter auch die Umfragevariablen.</span><span class="sxs-lookup"><span data-stu-id="830bc-147">In the preceding embed code, the `renderSurvey` function contains the `parentElementId` parameter in addition to the survey variables.</span></span> <span data-ttu-id="830bc-148">Der Parameter `parentElementId` erhält beim Aufruf die Container-ID `div`.</span><span class="sxs-lookup"><span data-stu-id="830bc-148">The `parentElementId` parameter receives the `div` container ID when it's called.</span></span>

<span data-ttu-id="830bc-149">Sie haben auf der Webseite, auf der Sie die Umfrage anzeigen möchten, einen `div`-Container mit der ID `surveyDiv` erstellt.</span><span class="sxs-lookup"><span data-stu-id="830bc-149">You created a `div` container with the ID `surveyDiv` on the webpage where you want to display the survey.</span></span> <span data-ttu-id="830bc-150">Dieser `div`-Container zeigt die Umfrage statisch in einem bestimmten Bereich auf der Webseite an.</span><span class="sxs-lookup"><span data-stu-id="830bc-150">This `div` container displays the survey statically in a designated area on the webpage.</span></span> <span data-ttu-id="830bc-151">Da Sie die Umfrage beim Laden der Seite laden möchten, erstellen Sie eine Methode wie folgt:</span><span class="sxs-lookup"><span data-stu-id="830bc-151">Because you'll want to load the survey when the page loads, create a method as follows:</span></span>

```JavaScript
<script>
     window.addEventListener('load', function () {
            renderSurvey("surveyDiv", "Bert", "Hair", "bert.hair@contoso.com", "Product Overview");
        }, false);
</script>

```

<span data-ttu-id="830bc-152">Die vorhergehende Methode ruft die Funktion `renderSurvey` auf und übergibt die erforderlichen Werte entsprechend.</span><span class="sxs-lookup"><span data-stu-id="830bc-152">The preceding method calls the `renderSurvey` function and passes the required values accordingly.</span></span> <span data-ttu-id="830bc-153">In dieser Methode werden statische Benutzerdetails übergeben, aber Sie können eine Funktion bereitstellen, die die angemeldeten Benutzerdetails abruft.</span><span class="sxs-lookup"><span data-stu-id="830bc-153">In this method, static user details are passed, but you can provide a function that retrieves the logged-in user details.</span></span>

### <a name="see-also"></a><span data-ttu-id="830bc-154">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="830bc-154">See also</span></span>

[<span data-ttu-id="830bc-155">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="830bc-155">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="830bc-156">Senden Sie eine Umfrage per E-Mail</span><span class="sxs-lookup"><span data-stu-id="830bc-156">Send a survey by using email</span></span>](send-survey-email.md)<br>
[<span data-ttu-id="830bc-157">Senden Sie eine Umfrage mit Power Automate</span><span class="sxs-lookup"><span data-stu-id="830bc-157">Send a survey by using Power Automate</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="830bc-158">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="830bc-158">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="830bc-159">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="830bc-159">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="830bc-160">Einbetten einer Umfrage in Power Apps</span><span class="sxs-lookup"><span data-stu-id="830bc-160">Embed a survey in Power Apps</span></span>](embed-survey-powerapps.md)
