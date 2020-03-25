---
title: Senden Sie eine Umfrage per E-Mail.
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 02/24/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 7bf609261c6808328031ef8afd35f3a91fa6ac68
ms.sourcegitcommit: b67bc5a218afc5d99d49aad2ea10dfd68c8dc338
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/02/2020
ms.locfileid: "3094354"
---
# <a name="send-a-survey-by-using-email"></a><span data-ttu-id="a3301-103">Senden Sie eine Umfrage per E-Mail.</span><span class="sxs-lookup"><span data-stu-id="a3301-103">Send a survey by using email</span></span>

<span data-ttu-id="a3301-104">Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden mit den folgenden Schritten:</span><span class="sxs-lookup"><span data-stu-id="a3301-104">After creating a survey, you can send it through email by following these steps.</span></span>

1.  <span data-ttu-id="a3301-105">Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie **Senden** aus der Symbolleiste oben auf der Seite.</span><span class="sxs-lookup"><span data-stu-id="a3301-105">Open the survey you want to send, and select **Send** from the toolbar at the top of the page.</span></span> 

2. <span data-ttu-id="a3301-106">Wählen Sie **E-Mail**.</span><span class="sxs-lookup"><span data-stu-id="a3301-106">Select **Email**.</span></span> <span data-ttu-id="a3301-107">Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="a3301-107">A default subject line and email message appear, along with a link to your survey in the message body.</span></span> <span data-ttu-id="a3301-108">Sie können den Text an Ihre Anforderungen anpassen und formatieren.</span><span class="sxs-lookup"><span data-stu-id="a3301-108">You can modify and format the text to meet your requirements.</span></span>

3.  <span data-ttu-id="a3301-109">Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="a3301-109">In the **To** field, enter the recipient's name or email address.</span></span> <span data-ttu-id="a3301-110">Sie können das Feld **An** auf eine der folgenden Methoden ausfüllen:</span><span class="sxs-lookup"><span data-stu-id="a3301-110">You can populate the **To** field by using any of the following methods:</span></span>

    - <span data-ttu-id="a3301-111">Manuelle Eingabe einer E-Mail-Adresse.</span><span class="sxs-lookup"><span data-stu-id="a3301-111">Entering an email address manually.</span></span>
    - <span data-ttu-id="a3301-112">Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="a3301-112">Entering a name, email address, or a distribution list from Azure Active Directory.</span></span>
    - <span data-ttu-id="a3301-113">Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Service für Apps.</span><span class="sxs-lookup"><span data-stu-id="a3301-113">Entering a contact or contact list/view from Common Data Service.</span></span> <span data-ttu-id="a3301-114">Die Kontakte werden aus der ausgewählten Umgebung gefüllt.</span><span class="sxs-lookup"><span data-stu-id="a3301-114">The contacts are populated from the selected environment.</span></span> <span data-ttu-id="a3301-115">Weitere Informationen: [Arbeiten mit Umgebungen](choose-environment.md)</span><span class="sxs-lookup"><span data-stu-id="a3301-115">More information: [Work with environments](choose-environment.md)</span></span>
    - <span data-ttu-id="a3301-116">Hochladen einer CSV-Datei durch Auswahl von **Empfänger importieren**.</span><span class="sxs-lookup"><span data-stu-id="a3301-116">Uploading a CSV file by selecting **Import recipients**.</span></span> <span data-ttu-id="a3301-117">Die CSV-Datei unterstützt den Import von maximal 10000 Empfängern.</span><span class="sxs-lookup"><span data-stu-id="a3301-117">The CSV file supports importing a maximum of 10,000 recipients.</span></span>

4.  <span data-ttu-id="a3301-118">Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [eiUmfrage-Link einfügen](#insert-survey-link).</span><span class="sxs-lookup"><span data-stu-id="a3301-118">To insert the survey link into your email message, see [Insert a survey link](#insert-survey-link).</span></span>  

5.  <span data-ttu-id="a3301-119">Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einem Link](#unsubscribe-from-a-survey).</span><span class="sxs-lookup"><span data-stu-id="a3301-119">To add an unsubscribe link to your email message, see [Insert an unsubscribe link](#unsubscribe-from-a-survey).</span></span>  

6.  <span data-ttu-id="a3301-120">Informationen zum Personalisieren der E-Mail mithilfe von Umfragevariablen finden Sie unter [Personalisieren Sie die Umfrage-E-Mail](#personalize-an-email).</span><span class="sxs-lookup"><span data-stu-id="a3301-120">To personalize the email by using survey variables, see [Personalize the survey email](#personalize-an-email).</span></span>

7. <span data-ttu-id="a3301-121">Informationen zum Einbetten der ersten Frage der Umfrage in Ihre E-Mail-Nachricht finden Sie unter [Betten Sie eine Umfrage in eine E-Mail ein](#embed-survey-in-an-email).</span><span class="sxs-lookup"><span data-stu-id="a3301-121">To embed the first question of the survey into your email message, see [Embed a survey in an email](#embed-survey-in-an-email).</span></span>

8.  <span data-ttu-id="a3301-122">Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**.</span><span class="sxs-lookup"><span data-stu-id="a3301-122">To select an email template, select a template from the **Template** list.</span></span> <span data-ttu-id="a3301-123">Standardmäßig ist **Standardvorlage** ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="a3301-123">**Default Template** is selected by default.</span></span> <span data-ttu-id="a3301-124">Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)</span><span class="sxs-lookup"><span data-stu-id="a3301-124">More information: [Use email templates](#use-email-templates)</span></span>

9.  <span data-ttu-id="a3301-125">Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.</span><span class="sxs-lookup"><span data-stu-id="a3301-125">When you're ready to send your survey, select **Send**.</span></span>

> [!NOTE]
> <span data-ttu-id="a3301-126">Sie können eine Umfrageeinladung an maximal 10000 Empfänger senden.</span><span class="sxs-lookup"><span data-stu-id="a3301-126">You can send a survey invitation to a maximum of 10,000 recipients.</span></span>

<a name="insert-survey-link"></a>

## <a name="insert-a-survey-link"></a><span data-ttu-id="a3301-127">Einen Befragungslink einfügen</span><span class="sxs-lookup"><span data-stu-id="a3301-127">Insert a survey link</span></span>

<span data-ttu-id="a3301-128">Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a3301-128">The survey link is added to your email message by default.</span></span> <span data-ttu-id="a3301-129">Um den Umfragelink an einer anderen Stelle in Ihre E-Mail-Nachricht einzufügen, platzieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Umfragelink**.</span><span class="sxs-lookup"><span data-stu-id="a3301-129">To insert the survey link in a different location in your email message, place the cursor at the location you want, and then select **Insert** > **Survey link**.</span></span> <span data-ttu-id="a3301-130">Sie können auch Text auswählen und dann **Einfügen** > **Umfrage-Link** wählen, um diesen Text als Umfrage-Link anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="a3301-130">You can also select text, and then select **Insert** > **Survey link** to display that text as the survey link.</span></span>

<a name="unsubscribe-from-a-survey"></a>

## <a name="insert-an-unsubscribe-link"></a><span data-ttu-id="a3301-131">Link für eine Abonnementkündigung einfügen</span><span class="sxs-lookup"><span data-stu-id="a3301-131">Insert an unsubscribe link</span></span>

<span data-ttu-id="a3301-132">Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden.</span><span class="sxs-lookup"><span data-stu-id="a3301-132">You can configure your email message to include a link that allows a respondent to unsubscribe from the survey.</span></span> <span data-ttu-id="a3301-133">Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Link**Abmelden.</span><span class="sxs-lookup"><span data-stu-id="a3301-133">To insert the unsubscribe link in the email message, place the cursor at the required location, and then select **Insert** > **Unsubscribe link**.</span></span> <span data-ttu-id="a3301-134">Sie können auch Text auswählen und dann **Einfügen** > **Abmelde-Link** wählen, um diesen Text als Abmeldelink anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="a3301-134">You can also select text, and then select **Insert** > **Unsubscribe link** to display that text as the unsubscribe link.</span></span> <span data-ttu-id="a3301-135">Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a3301-135">By default, the unsubscribe link is added to all email message templates.</span></span>

<a name="personalize-an-email"></a>

## <a name="personalize-the-survey-email"></a><span data-ttu-id="a3301-136">Personalisieren der Umfrage-E-Mail</span><span class="sxs-lookup"><span data-stu-id="a3301-136">Personalize the survey email</span></span>

<span data-ttu-id="a3301-137">Verwenden Sie Umfragevariablen, um Ihre Umfrage-E-Mail zu personalisieren&mdash;Sie können beispielsweise den Vornamen des Befragten hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="a3301-137">Use survey variables to personalize your survey email&mdash;for example, you can add the respondent's first name.</span></span> <span data-ttu-id="a3301-138">Platzieren Sie den Cursor an der Stelle, an der der Name angezeigt werden soll, und wählen Sie **Variablen** und dann **Vorname** von der Liste.</span><span class="sxs-lookup"><span data-stu-id="a3301-138">Place the cursor where you want the name to appear, select **Variables**, and then select **First name** from the list.</span></span> <span data-ttu-id="a3301-139">Der Vorname des Befragten wird automatisch eingefügt.</span><span class="sxs-lookup"><span data-stu-id="a3301-139">The first name of the respondent will be automatically inserted.</span></span> <span data-ttu-id="a3301-140">Alle in einer Umfrage erstellten Umfragevariablen werden in der Liste **Variablen** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a3301-140">All the survey variables created in a survey are displayed in the **Variables** list.</span></span>

<span data-ttu-id="a3301-141">Um eine neue Variable zu erstellen, wählen Sie **Neue Variable** aus der Liste **Variablen**.</span><span class="sxs-lookup"><span data-stu-id="a3301-141">To create a new variable, select **New variable** from the **Variables** list.</span></span> <span data-ttu-id="a3301-142">Wenn für Umfragevariablen keine Standardwerte definiert wurden, wird oben auf der Seite eine Warnmeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a3301-142">If default values haven't been defined for survey variables, a warning message is displayed at the top of the page.</span></span> <span data-ttu-id="a3301-143">Weitere Informationen zum Erstellen von Variablen und zum Bereitstellen von Werten finden Sie unter [Personalisieren Sie eine Umfrage](personalize-survey.md).</span><span class="sxs-lookup"><span data-stu-id="a3301-143">For more information about creating variables and providing values for them, see [Personalize a survey](personalize-survey.md).</span></span>

<a name="embed-survey-in-an-email"></a>

## <a name="embed-a-survey-in-an-email"></a><span data-ttu-id="a3301-144">Betten Sie eine Umfrage in eine E-Mail ein</span><span class="sxs-lookup"><span data-stu-id="a3301-144">Embed a survey in an email</span></span>

<span data-ttu-id="a3301-145">Wenn Sie als erste Frage in Ihrer Umfrage eine Frage zur Auswahl (Einzelantwort), Bewertung (Stern- oder Smileysymbol) oder Net Promoter Score hinzugefügt haben, können Sie diese in Ihre E-Mail-Nachricht einbetten.</span><span class="sxs-lookup"><span data-stu-id="a3301-145">If you have added a Choice (single answer), Rating (star or smiley symbol), or Net Promoter Score question as the first question in your survey, you can embed it in your email message.</span></span> <span data-ttu-id="a3301-146">Um die Frage einzubetten, wählen Sie **Einbetten erste Frage**.</span><span class="sxs-lookup"><span data-stu-id="a3301-146">To embed the question, select **Embed first question**.</span></span> <span data-ttu-id="a3301-147">Wenn Sie eine Frage einbetten, wird der Text in der E-Mail-Nachricht durch die Frage ersetzt.</span><span class="sxs-lookup"><span data-stu-id="a3301-147">When you embed a question, the text in the email message is replaced by the question.</span></span> <span data-ttu-id="a3301-148">Wenn ein Beantworter eine Option zur Beantwortung der Frage auswählt, wird die gesamte Umfrage in einem Webbrowser geöffnet und der Beantworter kann mit dem Ausfüllen der Umfrage fortfahren.</span><span class="sxs-lookup"><span data-stu-id="a3301-148">When a responder selects an option to answer the question, the whole survey is opened in a web browser and the responder can continue with completing the survey.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="a3301-149">![Betten Sie eine Umfrage in eine E-Mail ein](media/embed-ques-email.png "Betten Sie eine Umfrage in eine E-Mail ein")</span><span class="sxs-lookup"><span data-stu-id="a3301-149">![Embed a survey in an email](media/embed-ques-email.png "Embed a survey in an email")</span></span>

> [!NOTE]
> - <span data-ttu-id="a3301-150">Sie können eine Frage nicht in eine E-Mail einbetten, wenn Sie das Mischen von Fragen in der Umfrage aktiviert haben.</span><span class="sxs-lookup"><span data-stu-id="a3301-150">You can't embed a question in an email if you've enabled question shuffling in the survey.</span></span>
> - <span data-ttu-id="a3301-151">Wenn Sie eine eingebettete Umfrage in einer E-Mail über Power Automate senden möchten, müssen Sie die Frage in eine E-Mail einbetten und als neue E-Mail-Vorlage speichern.</span><span class="sxs-lookup"><span data-stu-id="a3301-151">If you want to send an embedded survey in an email through Power Automate, you must embed the question in an email and save it as a new email template.</span></span> <span data-ttu-id="a3301-152">Während Sie einen Flow konfigurieren, müssen Sie die neue E-Mail-Vorlage auswählen.</span><span class="sxs-lookup"><span data-stu-id="a3301-152">While configuring a flow, you must select the new email template.</span></span> <span data-ttu-id="a3301-153">Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)</span><span class="sxs-lookup"><span data-stu-id="a3301-153">More information: [Use email templates](#use-email-templates)</span></span>

<span data-ttu-id="a3301-154">Wenn Sie eine mehrsprachige Umfrage erstellt haben, können Sie Umfragevariablen verwenden, um das Standardgebietsschema für die Anzeige der Umfrage festzulegen.</span><span class="sxs-lookup"><span data-stu-id="a3301-154">If you've created a multilingual survey, you can use survey variables to set the default locale for displaying the survey.</span></span> <span data-ttu-id="a3301-155">Um das Standardgebietsschema festzulegen, öffnen Sie den Bereich **Umfragevariablen** und geben Sie dann einen Wert für die Variable **Lokalisierung** an.</span><span class="sxs-lookup"><span data-stu-id="a3301-155">To set the default locale, open the **Survey variables** pane, and then specify a value for the **locale** variable.</span></span> <span data-ttu-id="a3301-156">Der Wert muss ein Sprachcode sein, z. B. **en** oder **fr**.</span><span class="sxs-lookup"><span data-stu-id="a3301-156">The value must be a language code, for example **en** or **fr**.</span></span>

<a name="use-email-templates"></a>

## <a name="use-email-templates"></a><span data-ttu-id="a3301-157">E-Mail-Vorlagen verwenden</span><span class="sxs-lookup"><span data-stu-id="a3301-157">Use email templates</span></span>

<span data-ttu-id="a3301-158">Sie können eine E-Mail-Vorlage,&mdash;eine vorformatierte E-Mail-Nachricht&mdash;nutzen, mit der Sie schnell E-Mail-Nachrichten erstellen und senden können.</span><span class="sxs-lookup"><span data-stu-id="a3301-158">You can use an email template&mdash;a preformatted email message&mdash;to quickly create and send email messages.</span></span> <span data-ttu-id="a3301-159">Sie können den Text ändern und Ihre Änderungen dann in der aktuellen E-Mail-Vorlage speichern oder die Änderungen in einer neuen E-Mail-Vorlage speichern.</span><span class="sxs-lookup"><span data-stu-id="a3301-159">You can modify the text, and then save your changes to the current email template or save the changes to a new email template.</span></span> <span data-ttu-id="a3301-160">Wenn Sie keine andere Auswahl treffen, wird **Standardvorlage** für die Verwendung in einer E-Mail-Nachricht ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="a3301-160">Unless you make another selection, **Default Template** is selected for use in an email message.</span></span>

<span data-ttu-id="a3301-161">Sie können diese Aktionen auf einer E-Mail-Vorlage durchführen:</span><span class="sxs-lookup"><span data-stu-id="a3301-161">You can perform these actions on an email template:</span></span>

- <span data-ttu-id="a3301-162">**Speichern**: Speichern Sie Ihre Änderungen an der aktuellen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="a3301-162">**Save**: Save your changes to the current email template.</span></span>

- <span data-ttu-id="a3301-163">**Speichern unter**: Speichern Sie Ihre Änderungen in einer neuen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="a3301-163">**Save as**: Save your changes to a new email template.</span></span>

- <span data-ttu-id="a3301-164">**Löschen**: Löschen Sie die aktuelle E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="a3301-164">**Delete**: Delete the current email template.</span></span>

- <span data-ttu-id="a3301-165">**Umbenennen**: Benennen Sie die aktuelle E-Mail-Vorlage um.</span><span class="sxs-lookup"><span data-stu-id="a3301-165">**Rename**: Rename the current email template.</span></span>


> [!NOTE]
> - <span data-ttu-id="a3301-166">Sie können maximal 10 E-Mail-Vorlagen speichern.</span><span class="sxs-lookup"><span data-stu-id="a3301-166">You can save a maximum of 10 email templates.</span></span>
> - <span data-ttu-id="a3301-167">Wenn eine E-Mail-Vorlage Umfragevariablen enthält, die nicht Teil der Umfrage sind, wird oben auf der Seite eine Fehlermeldung angezeigt, und Sie können die Umfrage nicht per E-Mail oder Microsoft senden Power Automate.</span><span class="sxs-lookup"><span data-stu-id="a3301-167">If an email template includes survey variables that aren't part of the survey, an error message is displayed at the top of the page and you won't be allowed to send the survey through email or Microsoft Power Automate.</span></span> <span data-ttu-id="a3301-168">Die Umfragevariablen werden rot hervorgehoben. Sie müssen diese hervorgehobenen Variablen aus der E-Mail-Nachricht entfernen, bevor Sie die Umfrage senden können.</span><span class="sxs-lookup"><span data-stu-id="a3301-168">The survey variables will be highlighted in red; you must remove these highlighted variables from the email message before you can send the survey.</span></span>

### <a name="see-also"></a><span data-ttu-id="a3301-169">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="a3301-169">See also</span></span>

[<span data-ttu-id="a3301-170">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="a3301-170">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="a3301-171">Senden Sie eine Umfrage mit Power Automate</span><span class="sxs-lookup"><span data-stu-id="a3301-171">Send a survey by using Power Automate</span></span>](send-survey-flow.md)<br>
[<span data-ttu-id="a3301-172">Eine Umfrage in einer Webseite einbetten</span><span class="sxs-lookup"><span data-stu-id="a3301-172">Embed a survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="a3301-173">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="a3301-173">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="a3301-174">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="a3301-174">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="a3301-175">Einbetten einer Umfrage in Power Apps</span><span class="sxs-lookup"><span data-stu-id="a3301-175">Embed a survey in Power Apps</span></span>](embed-survey-powerapps.md)
