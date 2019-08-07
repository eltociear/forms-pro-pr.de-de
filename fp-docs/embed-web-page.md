---
title: Einbetten einer Umfrage in eine Webseite | MicrosoftDocs
description: Anleitung zum Einbetten einer Umfrage in eine Webseite
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 06/14/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: 649b3390-c3a5-4166-a014-ae3cfd14cc71
ms.custom: ''
ms.openlocfilehash: f0a0691d88d0eb10821940d973bd731e3c4da838
ms.sourcegitcommit: 4f20bfe750e8d4eb2db4dca0479699eb365c8c9e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2019
ms.locfileid: "1724519"
---
# <a name="embed-survey-in-a-webpage"></a><span data-ttu-id="32a1c-103">Einbetten der Umfrage in eine Webseite</span><span class="sxs-lookup"><span data-stu-id="32a1c-103">Embed survey in a webpage</span></span>



<span data-ttu-id="32a1c-104">Sie können Ihre Umfrage in eine Webseite einbetten, indem Sie den Einbettungscode der Umfrage in den Quellcode Ihrer Webseite einfügen.</span><span class="sxs-lookup"><span data-stu-id="32a1c-104">You can embed your survey in a webpage by pasting the survey's embed code into your webpage’s source code.</span></span> <span data-ttu-id="32a1c-105">Sie können wählen, wie die Umfrage angezeigt werden soll:</span><span class="sxs-lookup"><span data-stu-id="32a1c-105">You can choose how you want the survey to appear:</span></span>

- <span data-ttu-id="32a1c-106">**Inline**: Zeigt die Umfrage statisch auf der Webseite an.</span><span class="sxs-lookup"><span data-stu-id="32a1c-106">**Inline**: Displays the survey statically on the webpage.</span></span>

- <span data-ttu-id="32a1c-107">**Pop-up**: Zeigt die Umfrage in einem Popup-Fenster an, das auf der Aktion des Befragten basiert.</span><span class="sxs-lookup"><span data-stu-id="32a1c-107">**Pop-up**: Displays the survey in a pop-up window based on the respondent’s action.</span></span>

- <span data-ttu-id="32a1c-108">**Schaltfläche**: Zeigt die Umfrage an, wenn eine Schaltfläche ausgewählt ist.</span><span class="sxs-lookup"><span data-stu-id="32a1c-108">**Button**: Displays the survey when a button is selected.</span></span> <span data-ttu-id="32a1c-109">Standardmäßig lautet der Schaltflächenname **Feedback**.</span><span class="sxs-lookup"><span data-stu-id="32a1c-109">By default, the button name is **Provide feedback**.</span></span>

<span data-ttu-id="32a1c-110">Sie können auch eigene Kontextparameter auswählen oder definieren.</span><span class="sxs-lookup"><span data-stu-id="32a1c-110">You can also select or define custom context parameters.</span></span> <span data-ttu-id="32a1c-111">Kontextparameter ermöglichen es Ihnen, die Informationen Ihrer Befragten und den Kontext, in dem die Antwort gegeben wurde, zu erfassen und diese Daten in der Umfrageantwort zu speichern.</span><span class="sxs-lookup"><span data-stu-id="32a1c-111">Context parameters allow you to capture your respondent’s information and the context in which the response was provided and store that data in the survey response.</span></span> <span data-ttu-id="32a1c-112">Standardmäßig sind **Vorname**, **Nachname**, **E-Mail** und **URL** als Kontextparameter verfügbar.</span><span class="sxs-lookup"><span data-stu-id="32a1c-112">By default, **First name**, **Last name**, **Email**, and **URL** are available as context parameters.</span></span> <span data-ttu-id="32a1c-113">Zusätzlich können Sie 10 benutzerdefinierte Kontextparameter definieren.</span><span class="sxs-lookup"><span data-stu-id="32a1c-113">Additionally, you can define 10 custom context parameters.</span></span>

<span data-ttu-id="32a1c-114">Wenn eine Antwort Einbettungsparameter enthält, werden diese auf der Registerkarte **Personalisierte Daten** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="32a1c-114">If a response contains embed parameters, they are displayed on the **Personalized data** tab.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="32a1c-115">![Kontextparameter in einer Umfrageantwort](media/survey-response-context-param.png "Kontextparameter in einer Umfrageantwort")</span><span class="sxs-lookup"><span data-stu-id="32a1c-115">![Context parameters in a survey response](media/survey-response-context-param.png "Context parameters in a survey response")</span></span>

<span data-ttu-id="32a1c-116">Um Ihre Umfrage einzubetten:</span><span class="sxs-lookup"><span data-stu-id="32a1c-116">To embed your survey:</span></span>

1.  <span data-ttu-id="32a1c-117">Öffnen Sie die Umfrage, die Sie einbetten möchten, und gehen Sie zu **Umfrage senden** &gt;**Einbetten**.</span><span class="sxs-lookup"><span data-stu-id="32a1c-117">Open the survey you want to embed, and go to **Send Survey** &gt;**Embed**.</span></span>

2.  <span data-ttu-id="32a1c-118">Wählen Sie unter **Auswählen des Einbettungstyps für Ihre Umfrage** eine der folgenden Optionen aus:</span><span class="sxs-lookup"><span data-stu-id="32a1c-118">Under **Select the embed type for your survey**, select one of the following options:</span></span>

    -   <span data-ttu-id="32a1c-119">Inline</span><span class="sxs-lookup"><span data-stu-id="32a1c-119">Inline</span></span>

    -   <span data-ttu-id="32a1c-120">Pop-up</span><span class="sxs-lookup"><span data-stu-id="32a1c-120">Pop-up</span></span>

    -   <span data-ttu-id="32a1c-121">Schaltfläche</span><span class="sxs-lookup"><span data-stu-id="32a1c-121">Button</span></span>

3.  <span data-ttu-id="32a1c-122">Optional können Sie unter **Auswählen von Parametern zum Hinzufügen von Einbettungscode** einen oder alle Out-of-the-box-Parameter auswählen oder **Benutzerdefinierten Parameter hinzufügen** wählen, um einen neuen Parameter zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="32a1c-122">Optionally, under **Select parameters to add in embed code**, select one or all out-of-the-box parameters, or select **Add custom parameter** to create a new parameter.</span></span>

4.  <span data-ttu-id="32a1c-123">Wählen Sie **Code generieren**.</span><span class="sxs-lookup"><span data-stu-id="32a1c-123">Select **Generate code**.</span></span> <span data-ttu-id="32a1c-124">Der Einbettungscode wird gemäß den ausgewählten Optionen generiert.</span><span class="sxs-lookup"><span data-stu-id="32a1c-124">The embed code is generated as per the selected options.</span></span>

5.  <span data-ttu-id="32a1c-125">Wählen Sie **Kopieren**, und fügen Sie dann den Einbettungscode in eine Webseite ein, um Ihre Umfrage einzubetten.</span><span class="sxs-lookup"><span data-stu-id="32a1c-125">Select **Copy**, and then paste the embed code into a webpage to embed your survey.</span></span> <span data-ttu-id="32a1c-126">Sie müssen dann den Quellcode der Webseite aktualisieren, um die Umfrage auf der Webseite anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="32a1c-126">You must then update the webpage’s source code to render the survey on the webpage.</span></span> <span data-ttu-id="32a1c-127">Informationen zum Aktualisieren des Quellcodes finden Sie unter [Update des Quellcodes einer Webseite](#update-a-webpages-source-code).</span><span class="sxs-lookup"><span data-stu-id="32a1c-127">For information on how to update the source code, see [Update a webpage's source code](#update-a-webpages-source-code).</span></span>  

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="32a1c-128">![Einbetten einer Umfrage in eine Webseite](media/survey-embed.png "Einbetten einer Umfrage in eine Webseite")</span><span class="sxs-lookup"><span data-stu-id="32a1c-128">![embed a survey in a web page](media/survey-embed.png "Embed a survey in a web page")</span></span>  

## <a name="update-a-webpages-source-code"></a><span data-ttu-id="32a1c-129">Aktualisieren des Quellcodes einer Webseite</span><span class="sxs-lookup"><span data-stu-id="32a1c-129">Update a webpage's source code</span></span>

<span data-ttu-id="32a1c-130">Nachdem Sie den Einbettungscode generiert haben, müssen Sie ihn in den Quellcode Ihrer Webseite einfügen.</span><span class="sxs-lookup"><span data-stu-id="32a1c-130">After generating the embed code, you must add it into your webpage’s source code.</span></span> <span data-ttu-id="32a1c-131">Erstellen Sie dann eine Methode, die die Funktion **renderSurvey** aufruft, um die Umfrage auf der Webseite anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="32a1c-131">Then create a method that calls the **renderSurvey** function to render the survey on the webpage.</span></span> <span data-ttu-id="32a1c-132">Sie müssen sicherstellen, dass die Werte in der Funktion **renderSurvey** in der gleichen Reihenfolge übergeben werden wie die Parameter, die in der Funktion **renderSurvey** im Embed-Code definiert sind.</span><span class="sxs-lookup"><span data-stu-id="32a1c-132">You must ensure that the values in the **renderSurvey** function are passed in the same order as the parameters that are defined in the **renderSurvey** function in the embed code.</span></span>

<span data-ttu-id="32a1c-133">Für eine Inline-Umfrage muss ein übergeordneter **div** Container definiert werden, damit die Umfrage angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="32a1c-133">For an inline survey, a parent **div** container must be defined for the survey to be displayed.</span></span>

### <a name="scenario-to-embed-an-inline-survey"></a><span data-ttu-id="32a1c-134">Szenario zur Einbindung einer Inline-Umfrage</span><span class="sxs-lookup"><span data-stu-id="32a1c-134">Scenario to embed an inline survey</span></span>

<span data-ttu-id="32a1c-135">Angenommen, Sie möchten eine Inline-Umfrage in Ihre Webseite einbetten und drei Kontextparameter auswählen (**Vorname**, **Nachname** und **E-Mail**) und einen benutzerdefinierten Kontextparameter erstellen (**PageTitle**).</span><span class="sxs-lookup"><span data-stu-id="32a1c-135">Let's say you want to embed an inline survey into your webpage, and that you select three out-of-the-box context parameters (**First name**, **Last name**, and **Email**) and create one custom context parameter (**PageTitle**).</span></span> <span data-ttu-id="32a1c-136">Der Embed-Code wird wie folgt generiert:</span><span class="sxs-lookup"><span data-stu-id="32a1c-136">The embed code is generated as follows:</span></span>

```JavaScript
<script src="https://www.contoso.com/Embed.js" type="text/javascript"></script><link rel="stylesheet" type="text/css" href="https://www.contoso.com/Embed.css" /><script type = "text/javascript" >function renderSurvey(parentElementId, Firstname, Lastname, Email, PageTitle){var se = new SurveyEmbed("JtSG9ha000000000020pTSB1AovM_5u8bQH1UQjlNQjZRWV0000000000","https://www.contoso.com/");var context = {"Firstname": Firstname,"Lastname": Lastname,"Email": Email,"PageTitle": PageTitle,};se.renderInline(parentElementId, context);}</script>
```

<span data-ttu-id="32a1c-137">Im vorhergehenden Einbettungscode enthält die Funktion `renderSurvey` neben den ausgewählten Parametern auch den Parameter `parentElementId`.</span><span class="sxs-lookup"><span data-stu-id="32a1c-137">In the preceding embed code, the `renderSurvey` function contains the `parentElementId` parameter in addition to the selected parameters.</span></span> <span data-ttu-id="32a1c-138">Der Parameter `parentElementId` erhält beim Aufruf die Container-ID `div`.</span><span class="sxs-lookup"><span data-stu-id="32a1c-138">The `parentElementId` parameter receives the `div` container ID when it is called.</span></span>

<span data-ttu-id="32a1c-139">Sie haben auf der Webseite, auf der Sie die Umfrage anzeigen möchten, einen `div`-Container mit der ID `surveyDiv` erstellt.</span><span class="sxs-lookup"><span data-stu-id="32a1c-139">You created a `div` container with the ID `surveyDiv` on the webpage where you want to display the survey.</span></span> <span data-ttu-id="32a1c-140">Dieser `div`-Container zeigt die Umfrage statisch in einem bestimmten Bereich auf der Webseite an.</span><span class="sxs-lookup"><span data-stu-id="32a1c-140">This `div` container displays the survey statically in a designated area on the webpage.</span></span> <span data-ttu-id="32a1c-141">Da Sie die Umfrage beim Laden der Seite laden möchten, erstellen Sie eine Methode wie folgt:</span><span class="sxs-lookup"><span data-stu-id="32a1c-141">Because you'll want to load the survey when the page loads, create a method as follows:</span></span>

```JavaScript
<script>
     window.addEventListener('load', function () {
            renderSurvey("surveyDiv", "Bert", "Hair", "bert.hair@contoso.com", "Product Overview");
        }, false);
</script>

```

<span data-ttu-id="32a1c-142">Die vorhergehende Methode ruft die Funktion `renderSurvey` auf und übergibt die erforderlichen Werte entsprechend.</span><span class="sxs-lookup"><span data-stu-id="32a1c-142">The preceding method calls the `renderSurvey` function and passes the required values accordingly.</span></span> <span data-ttu-id="32a1c-143">In dieser Methode werden statische Benutzerdetails übergeben, aber Sie können eine Funktion bereitstellen, die die angemeldeten Benutzerdetails abruft.</span><span class="sxs-lookup"><span data-stu-id="32a1c-143">In this method, static user details are passed, but you can provide a function that retrieves the logged-in user details.</span></span>

## <a name="see-also"></a><span data-ttu-id="32a1c-144">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="32a1c-144">See also</span></span>

[<span data-ttu-id="32a1c-145">Definieren Sie, wer an einer Umfrage teilnehmen darf</span><span class="sxs-lookup"><span data-stu-id="32a1c-145">Define who can respond to a survey</span></span>](invite-settings.md)<br>
[<span data-ttu-id="32a1c-146">Senden Sie eine Umfrage per E-Mail</span><span class="sxs-lookup"><span data-stu-id="32a1c-146">Send a survey by using email</span></span>](send-survey-email.md)<br>
[<span data-ttu-id="32a1c-147">Senden Sie eine Umfrage mit Microsoft Flow</span><span class="sxs-lookup"><span data-stu-id="32a1c-147">Send a survey by using Microsoft Flow</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="32a1c-148">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="32a1c-148">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="32a1c-149">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="32a1c-149">Send a survey QR code</span></span>](send-survey-qrcode.md)