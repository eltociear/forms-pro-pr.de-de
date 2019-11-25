---
title: Senden einer Umfrage per E-Mail | MicrosoftDocs
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 11/04/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: d48c4d15cdf98ba0ced17a6c497a2800ebecb066
ms.sourcegitcommit: 3225337823216f21b569779b829f069f53aa3742
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/04/2019
ms.locfileid: "2750442"
---
# <a name="send-a-survey-by-using-email"></a><span data-ttu-id="7d020-103">Senden Sie eine Umfrage per E-Mail.</span><span class="sxs-lookup"><span data-stu-id="7d020-103">Send a survey by using email</span></span>

<span data-ttu-id="7d020-104">Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden:</span><span class="sxs-lookup"><span data-stu-id="7d020-104">After creating a survey, you can send it through email:</span></span> 

1.  <span data-ttu-id="7d020-105">Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie **Senden** aus der Symbolleiste oben auf der Seite.</span><span class="sxs-lookup"><span data-stu-id="7d020-105">Open the survey you want to send, and select **Send** from the toolbar at the top of the page.</span></span> 

2. <span data-ttu-id="7d020-106">Wählen Sie **E-Mail**.</span><span class="sxs-lookup"><span data-stu-id="7d020-106">Select **Email**.</span></span> <span data-ttu-id="7d020-107">Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="7d020-107">A default subject line and email message appear, along with a link to your survey in the message body.</span></span> <span data-ttu-id="7d020-108">Sie können den Text an Ihre Anforderungen anpassen und formatieren.</span><span class="sxs-lookup"><span data-stu-id="7d020-108">You can modify and format the text to meet your requirements.</span></span>

3.  <span data-ttu-id="7d020-109">Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="7d020-109">In the **To** field, enter the recipient's name or email address.</span></span> <span data-ttu-id="7d020-110">Sie können das Feld **Bis** auf eine der folgenden Arten füllen:</span><span class="sxs-lookup"><span data-stu-id="7d020-110">You can populate the **To** field by any of the following ways:</span></span>
    - <span data-ttu-id="7d020-111">Manuelle Eingabe einer E-Mail-Adresse.</span><span class="sxs-lookup"><span data-stu-id="7d020-111">Entering an email address manually.</span></span>
    - <span data-ttu-id="7d020-112">Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="7d020-112">Entering a name, email address, or a distribution list from Azure Active Directory.</span></span>
    - <span data-ttu-id="7d020-113">Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Services für Apps.</span><span class="sxs-lookup"><span data-stu-id="7d020-113">Entering a contact or contact list/view from Common Data Services for Apps.</span></span> <span data-ttu-id="7d020-114">Die Kontakte werden aus der ausgewählten Umgebung gefüllt.</span><span class="sxs-lookup"><span data-stu-id="7d020-114">The contacts are populated from the selected environment.</span></span> <span data-ttu-id="7d020-115">Weitere Informationen zum Arbeiten mit Umgebungen finden Sie unter [Arbeiten mit Umgebungen](choose-environment.md).</span><span class="sxs-lookup"><span data-stu-id="7d020-115">For more information on working with environments, see [Work with environments](choose-environment.md).</span></span>
    - <span data-ttu-id="7d020-116">Hochladen einer csv-Datei durch Auswahl von **Empfänger importieren**.</span><span class="sxs-lookup"><span data-stu-id="7d020-116">Uploading a .csv file by selecting **Import recipients**.</span></span> <span data-ttu-id="7d020-117">Die CSV-Datei unterstützt den Import von maximal 10000 Empfängern.</span><span class="sxs-lookup"><span data-stu-id="7d020-117">The CSV file supports importing a maximum of 10000 recipients.</span></span>

4.  <span data-ttu-id="7d020-118">Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [Umfrage-Link einfügen](#insert-survey-link).</span><span class="sxs-lookup"><span data-stu-id="7d020-118">To insert the survey link into your email message, see [Insert survey link](#insert-survey-link).</span></span>  

5.  <span data-ttu-id="7d020-119">Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einer Umfrage](#unsubscribe-from-a-survey).</span><span class="sxs-lookup"><span data-stu-id="7d020-119">To add an unsubscribe link to your email message, see [Unsubscribe from a survey](#unsubscribe-from-a-survey).</span></span>  

6.  <span data-ttu-id="7d020-120">Informationen zur Personalisierung der E-Mail mithilfe von Umfragevariablen finden Sie unter [Personalisierung einer E-Mail](#personalize-an-email).</span><span class="sxs-lookup"><span data-stu-id="7d020-120">To personalize the email by using survey variables, see [Personalize an email](#personalize-an-email).</span></span>

7. <span data-ttu-id="7d020-121">Um die erste Frage der Umfrage in Ihre E-Mail-Nachricht einzubetten, siehe [Umfrage einbetten in eine E-Mail](#embed-survey-in-an-email).</span><span class="sxs-lookup"><span data-stu-id="7d020-121">To embed the first question of the survey into your email message, see [Embed survey in an email](#embed-survey-in-an-email).</span></span>

8.  <span data-ttu-id="7d020-122">Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**.</span><span class="sxs-lookup"><span data-stu-id="7d020-122">To select an email template, select a template from the **Template** drop-down list.</span></span> <span data-ttu-id="7d020-123">Standardmäßig ist **Standardvorlage** ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="7d020-123">By default, **Default Template** is selected.</span></span> <span data-ttu-id="7d020-124">Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)</span><span class="sxs-lookup"><span data-stu-id="7d020-124">More information: [Use email templates](#use-email-templates)</span></span>  

9.  <span data-ttu-id="7d020-125">Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.</span><span class="sxs-lookup"><span data-stu-id="7d020-125">When you're ready to send your survey, select **Send**.</span></span>

> [!NOTE]
> <span data-ttu-id="7d020-126">Sie können eine Umfrageeinladung an maximal 10000 Empfänger senden.</span><span class="sxs-lookup"><span data-stu-id="7d020-126">You can send a survey invitation to a maximum of 10000 recipients.</span></span>

## <a name="insert-survey-link"></a><span data-ttu-id="7d020-127">Umfrage-Link einfügen</span><span class="sxs-lookup"><span data-stu-id="7d020-127">Insert survey link</span></span>

<span data-ttu-id="7d020-128">Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="7d020-128">The survey link is added to your email message by default.</span></span> <span data-ttu-id="7d020-129">Um den Umfrage-Link an einer anderen Stelle in Ihrer E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie **Einfügen** > **Umfrage-Link**.</span><span class="sxs-lookup"><span data-stu-id="7d020-129">To insert the survey link in a different location in your email message, place the cursor at the required location, and select **Insert** > **Survey link**.</span></span> <span data-ttu-id="7d020-130">Sie können auch Text auswählen und dann **Einfügen** > **Umfrage-Link** wählen, um diesen Text als Umfrage-Link anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="7d020-130">You can also select text, and then select **Insert** > **Survey link** to display that text as the survey link.</span></span>

## <a name="unsubscribe-from-a-survey"></a><span data-ttu-id="7d020-131">Abmeldung von einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="7d020-131">Unsubscribe from a survey</span></span>

<span data-ttu-id="7d020-132">Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden.</span><span class="sxs-lookup"><span data-stu-id="7d020-132">You can configure your email message to include a link that allows a respondent to unsubscribe from the survey.</span></span> <span data-ttu-id="7d020-133">Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Link**Abmelden.</span><span class="sxs-lookup"><span data-stu-id="7d020-133">To insert the unsubscribe link in the email message, place the cursor at the required location, and then select **Insert** > **Unsubscribe link**.</span></span> <span data-ttu-id="7d020-134">Sie können auch Text auswählen und dann **Einfügen** > **Link**Abmelden wählen, um diesen Text als Abmeldelink anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="7d020-134">You can also select text, and then select **Insert** > **Unsubscribe link** to display that text as the unsubscribe link.</span></span> <span data-ttu-id="7d020-135">Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="7d020-135">By default, the unsubscribe link is added to all email message templates.</span></span>

## <a name="personalize-an-email"></a><span data-ttu-id="7d020-136">Eine E-Mail personalisieren</span><span class="sxs-lookup"><span data-stu-id="7d020-136">Personalize an email</span></span>

<span data-ttu-id="7d020-137">Personalisieren Sie Ihre Umfrage-E-Mail, indem Sie Umfrage-Variablen verwenden.</span><span class="sxs-lookup"><span data-stu-id="7d020-137">Personalize your survey email by using survey variables.</span></span> <span data-ttu-id="7d020-138">Positionieren Sie den Cursor beispielsweise an der Stelle, an der ein Vorname erscheinen soll.</span><span class="sxs-lookup"><span data-stu-id="7d020-138">For example, place the cursor where you want a first name to appear.</span></span> <span data-ttu-id="7d020-139">Wählen Sie **Variablen**, und wählen Sie dann **Vorname** aus der Auswahlliste.</span><span class="sxs-lookup"><span data-stu-id="7d020-139">Select **Variables**, and then select **First name** from the drop-down list.</span></span> <span data-ttu-id="7d020-140">Der Vorname des Befragten wird automatisch eingefügt.</span><span class="sxs-lookup"><span data-stu-id="7d020-140">The first name of the respondent will be automatically inserted.</span></span> <span data-ttu-id="7d020-141">Alle in einer Umfrage erstellten Umfragevariablen werden in der Liste **Variablen** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="7d020-141">All the survey variables created in a survey are displayed in the **Variables** list.</span></span>

<span data-ttu-id="7d020-142">Um eine neue Variable zu erstellen, wählen Sie **Neue Variable** aus der Liste **Variablen**.</span><span class="sxs-lookup"><span data-stu-id="7d020-142">To create a new variable, select **New variable** from the **Variables** list.</span></span> <span data-ttu-id="7d020-143">Informationen zum Erstellen und Bereitstellen von Werten für die Variablen finden Sie unter [Personalisieren einer Umfrage](personalize-survey.md)</span><span class="sxs-lookup"><span data-stu-id="7d020-143">For information on creating and providing values to the variables, see [Personalize a survey](personalize-survey.md)</span></span>

<span data-ttu-id="7d020-144">Wenn die Standardwerte für Umfragevariablen nicht definiert sind, wird oben auf der Seite eine Warnmeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="7d020-144">If the default values are not defined for survey variables, a warning message is displayed at the top of the page.</span></span>

## <a name="embed-survey-in-an-email"></a><span data-ttu-id="7d020-145">Einbetten der Umfrage in eine E-Mail</span><span class="sxs-lookup"><span data-stu-id="7d020-145">Embed survey in an email</span></span>

<span data-ttu-id="7d020-146">Wenn Sie eine Frage zur Bewertung oder zum Netto-Promoter-Score als erste Frage in Ihrer Umfrage hinzugefügt haben, können Sie sie in Ihre E-Mail-Nachricht einbetten.</span><span class="sxs-lookup"><span data-stu-id="7d020-146">If you have added a Rating or Net Promoter Score question as the first question in your survey, you can embed it in your email message.</span></span> <span data-ttu-id="7d020-147">Um die Frage einzubetten, wählen Sie **Einbetten erste Frage**.</span><span class="sxs-lookup"><span data-stu-id="7d020-147">To embed the question, select **Embed first question**.</span></span> <span data-ttu-id="7d020-148">Wenn Sie eine Frage einbetten, wird der Text in der E-Mail-Nachricht durch die Frage ersetzt.</span><span class="sxs-lookup"><span data-stu-id="7d020-148">When you embed a question, the text in the email message is replaced by the question.</span></span> <span data-ttu-id="7d020-149">Wenn ein Befragter eine Option in der E-Mail auswählt, wird die gesamte Umfrage im Webbrowser geöffnet und der Befragte kann die Umfrage fortsetzen.</span><span class="sxs-lookup"><span data-stu-id="7d020-149">When a responder selects an option in the email, the complete survey is opened in the web browser and the responder can continue with completing the survey.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="7d020-150">![Eingebettete Umfrage in eine E-Mail ](media/embed-ques-email.png "Einbetten der Umfrage in eine E-Mail")</span><span class="sxs-lookup"><span data-stu-id="7d020-150">![Embed survey in an email](media/embed-ques-email.png "Embed survey in an email")</span></span>

> [!NOTE]
> <span data-ttu-id="7d020-151">Sie können die Frage nicht in eine E-Mail einbetten, wenn Sie Verzweigungsregeln hinzugefügt oder die Fragen in einer Umfrage neu gemischt haben.</span><span class="sxs-lookup"><span data-stu-id="7d020-151">You cannot embed the question in an email if you have added any branching rules or shuffled the questions in a survey.</span></span>

## <a name="use-email-templates"></a><span data-ttu-id="7d020-152">E-Mail-Vorlagen verwenden</span><span class="sxs-lookup"><span data-stu-id="7d020-152">Use email templates</span></span>

<span data-ttu-id="7d020-153">Eine E-Mail-Vorlage ist eine vorformatierte E-Mail-Nachricht, mit der Sie schnell E-Mail-Nachrichten erstellen und senden können.</span><span class="sxs-lookup"><span data-stu-id="7d020-153">An email template is a preformatted email message that allows you to quickly create and send email messages.</span></span> <span data-ttu-id="7d020-154">Sie können den Text ändern und Ihre Änderungen dann in der aktuellen E-Mail-Vorlage speichern oder die Änderungen in einer neuen E-Mail-Vorlage speichern.</span><span class="sxs-lookup"><span data-stu-id="7d020-154">You can modify the text, and then save your changes to the current email template or save the changes to a new email template.</span></span> <span data-ttu-id="7d020-155">Wenn Sie keine andere Auswahl treffen, wird **Standardvorlage** für die Verwendung in einer E-Mail-Nachricht ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="7d020-155">Unless you make another selection, **Default Template** is selected for use in an email message.</span></span> 

<span data-ttu-id="7d020-156">Sie können diese Aktionen auf einer E-Mail-Vorlage durchführen:</span><span class="sxs-lookup"><span data-stu-id="7d020-156">You can perform these actions on an email template:</span></span>

- <span data-ttu-id="7d020-157">**Speichern**: Speichern Sie Ihre Änderungen an der aktuellen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="7d020-157">**Save**: Save your changes to the current email template.</span></span>

- <span data-ttu-id="7d020-158">**Speichern unter**: Speichern Sie Ihre Änderungen in einer neuen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="7d020-158">**Save as**: Save your changes to a new email template.</span></span>

- <span data-ttu-id="7d020-159">**Löschen**: Löschen Sie die aktuelle E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="7d020-159">**Delete**: Delete the current email template.</span></span>

- <span data-ttu-id="7d020-160">**Umbenennen**: Benennen Sie die aktuelle E-Mail-Vorlage um.</span><span class="sxs-lookup"><span data-stu-id="7d020-160">**Rename**: Rename the current email template.</span></span>

> [!NOTE]
> - <span data-ttu-id="7d020-161">Sie können maximal 10 E-Mail-Vorlagen speichern.</span><span class="sxs-lookup"><span data-stu-id="7d020-161">You can save a maximum of 10 email templates.</span></span>
> - <span data-ttu-id="7d020-162">Wenn Sie Umfragevariablen in einer E-Mail-Vorlage verwendet haben, die nicht Teil der Umfrage sind, wird oben auf der Seite eine Fehlermeldung angezeigt und es ist Ihnen nicht gestattet, die Umfrage per E-Mail oder Flow zu senden.</span><span class="sxs-lookup"><span data-stu-id="7d020-162">If you have used survey variables in an email template, which are not part of the survey, an error message is displayed at the top of the page and you are not allowed to send the survey through email or Flow.</span></span> <span data-ttu-id="7d020-163">Die Variablen der Umfrage sind rot markiert.</span><span class="sxs-lookup"><span data-stu-id="7d020-163">The survey variables are highlighted in red.</span></span> <span data-ttu-id="7d020-164">Sie müssen die hervorgehobenen Umfragevariablen aus der E-Mail-Nachricht entfernen, um die Umfrage zu senden.</span><span class="sxs-lookup"><span data-stu-id="7d020-164">You must remove the highlighted survey variables from the email message to send the survey.</span></span>

## <a name="see-also"></a><span data-ttu-id="7d020-165">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="7d020-165">See also</span></span>

[<span data-ttu-id="7d020-166">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="7d020-166">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="7d020-167">Senden Sie eine Umfrage mit Microsoft Flow</span><span class="sxs-lookup"><span data-stu-id="7d020-167">Send a survey by using Microsoft Flow</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="7d020-168">Eingebettete Umfrage in eine Webseite</span><span class="sxs-lookup"><span data-stu-id="7d020-168">Embed survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="7d020-169">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="7d020-169">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="7d020-170">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="7d020-170">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="7d020-171">Einbetten einer Umfrage in PowerApps</span><span class="sxs-lookup"><span data-stu-id="7d020-171">Embed a survey in PowerApps</span></span>](embed-survey-powerapps.md)
