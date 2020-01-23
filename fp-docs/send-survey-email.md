---
title: Senden einer Umfrage per E-Mail | MicrosoftDocs
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 12/23/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 69eff193e16e1d4c0624162d9b72ca8ef2245189
ms.sourcegitcommit: 12abf1856081a5f60a025c0ca305161eb0d0978a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/23/2019
ms.locfileid: "2922575"
---
# <a name="send-a-survey-by-using-email"></a><span data-ttu-id="5fa39-103">Senden Sie eine Umfrage per E-Mail.</span><span class="sxs-lookup"><span data-stu-id="5fa39-103">Send a survey by using email</span></span>

<span data-ttu-id="5fa39-104">Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden mit den folgenden Schritten:</span><span class="sxs-lookup"><span data-stu-id="5fa39-104">After creating a survey, you can send it through email by following these steps.</span></span>

1.  <span data-ttu-id="5fa39-105">Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie **Senden** aus der Symbolleiste oben auf der Seite.</span><span class="sxs-lookup"><span data-stu-id="5fa39-105">Open the survey you want to send, and select **Send** from the toolbar at the top of the page.</span></span> 

2. <span data-ttu-id="5fa39-106">Wählen Sie **E-Mail**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-106">Select **Email**.</span></span> <span data-ttu-id="5fa39-107">Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="5fa39-107">A default subject line and email message appear, along with a link to your survey in the message body.</span></span> <span data-ttu-id="5fa39-108">Sie können den Text an Ihre Anforderungen anpassen und formatieren.</span><span class="sxs-lookup"><span data-stu-id="5fa39-108">You can modify and format the text to meet your requirements.</span></span>

3.  <span data-ttu-id="5fa39-109">Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="5fa39-109">In the **To** field, enter the recipient's name or email address.</span></span> <span data-ttu-id="5fa39-110">Sie können das Feld **An** auf eine der folgenden Methoden ausfüllen:</span><span class="sxs-lookup"><span data-stu-id="5fa39-110">You can populate the **To** field by using any of the following methods:</span></span>

    - <span data-ttu-id="5fa39-111">Manuelle Eingabe einer E-Mail-Adresse.</span><span class="sxs-lookup"><span data-stu-id="5fa39-111">Entering an email address manually.</span></span>
    - <span data-ttu-id="5fa39-112">Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="5fa39-112">Entering a name, email address, or a distribution list from Azure Active Directory.</span></span>
    - <span data-ttu-id="5fa39-113">Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Service für Apps.</span><span class="sxs-lookup"><span data-stu-id="5fa39-113">Entering a contact or contact list/view from Common Data Service.</span></span> <span data-ttu-id="5fa39-114">Die Kontakte werden aus der ausgewählten Umgebung gefüllt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-114">The contacts are populated from the selected environment.</span></span> <span data-ttu-id="5fa39-115">Weitere Informationen: [Arbeiten mit Umgebungen](choose-environment.md)</span><span class="sxs-lookup"><span data-stu-id="5fa39-115">More information: [Work with environments](choose-environment.md)</span></span>
    - <span data-ttu-id="5fa39-116">Hochladen einer csv-Datei durch Auswahl von **Empfänger importieren**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-116">Uploading a .csv file by selecting **Import recipients**.</span></span> <span data-ttu-id="5fa39-117">Die CSV-Datei unterstützt den Import von maximal 10000 Empfängern.</span><span class="sxs-lookup"><span data-stu-id="5fa39-117">The CSV file supports importing a maximum of 10,000 recipients.</span></span>

4.  <span data-ttu-id="5fa39-118">Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [eiUmfrage-Link einfügen](#insert-survey-link).</span><span class="sxs-lookup"><span data-stu-id="5fa39-118">To insert the survey link into your email message, see [Insert a survey link](#insert-survey-link).</span></span>  

5.  <span data-ttu-id="5fa39-119">Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einem Link](#unsubscribe-from-a-survey).</span><span class="sxs-lookup"><span data-stu-id="5fa39-119">To add an unsubscribe link to your email message, see [Insert an unsubscribe link](#unsubscribe-from-a-survey).</span></span>  

6.  <span data-ttu-id="5fa39-120">Informationen zum Personalisieren der E-Mail mithilfe von Umfragevariablen finden Sie unter [Personalisieren Sie die Umfrage-E-Mail](#personalize-an-email).</span><span class="sxs-lookup"><span data-stu-id="5fa39-120">To personalize the email by using survey variables, see [Personalize the survey email](#personalize-an-email).</span></span>

7. <span data-ttu-id="5fa39-121">Informationen zum Einbetten der ersten Frage der Umfrage in Ihre E-Mail-Nachricht finden Sie unter [Betten Sie eine Umfrage in eine E-Mail ein](#embed-survey-in-an-email).</span><span class="sxs-lookup"><span data-stu-id="5fa39-121">To embed the first question of the survey into your email message, see [Embed a survey in an email](#embed-survey-in-an-email).</span></span>

8.  <span data-ttu-id="5fa39-122">Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-122">To select an email template, select a template from the **Template** list.</span></span> <span data-ttu-id="5fa39-123">Standardmäßig ist **Standardvorlage** ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-123">**Default Template** is selected by default.</span></span> <span data-ttu-id="5fa39-124">Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)</span><span class="sxs-lookup"><span data-stu-id="5fa39-124">More information: [Use email templates](#use-email-templates)</span></span>

8.  <span data-ttu-id="5fa39-125">Informationen zum Anpassen des Absenders der Umfrage-E-Mail finden Sie unter [Passen Sie die E-Mail-Adresse des Absenders an](#customize-sender-email-address).</span><span class="sxs-lookup"><span data-stu-id="5fa39-125">To customize the sender of the survey email, see [Customize the sender's email address](#customize-sender-email-address).</span></span>

9.  <span data-ttu-id="5fa39-126">Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-126">When you're ready to send your survey, select **Send**.</span></span>

> [!NOTE]
> <span data-ttu-id="5fa39-127">Sie können eine Umfrageeinladung an maximal 10000 Empfänger senden.</span><span class="sxs-lookup"><span data-stu-id="5fa39-127">You can send a survey invitation to a maximum of 10,000 recipients.</span></span>

<a name="insert-survey-link"></a>

## <a name="insert-a-survey-link"></a><span data-ttu-id="5fa39-128">Einen Befragungslink einfügen</span><span class="sxs-lookup"><span data-stu-id="5fa39-128">Insert a survey link</span></span>

<span data-ttu-id="5fa39-129">Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-129">The survey link is added to your email message by default.</span></span> <span data-ttu-id="5fa39-130">Um den Umfrage-Link an einer anderen Stelle in Ihrer E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Umfrage-Link**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-130">To insert the survey link in a different location in your email message, place the cursor at the required location, and then select **Insert** > **Survey link**.</span></span> <span data-ttu-id="5fa39-131">Sie können auch Text auswählen und dann **Einfügen** > **Umfrage-Link** wählen, um diesen Text als Umfrage-Link anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-131">You can also select text, and then select **Insert** > **Survey link** to display that text as the survey link.</span></span>

<a name="unsubscribe-from-a-survey"></a>

## <a name="insert-an-unsubscribe-link"></a><span data-ttu-id="5fa39-132">Link für eine Abonnementkündigung einfügen</span><span class="sxs-lookup"><span data-stu-id="5fa39-132">Insert an unsubscribe link</span></span>

<span data-ttu-id="5fa39-133">Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden.</span><span class="sxs-lookup"><span data-stu-id="5fa39-133">You can configure your email message to include a link that allows a respondent to unsubscribe from the survey.</span></span> <span data-ttu-id="5fa39-134">Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Link**Abmelden.</span><span class="sxs-lookup"><span data-stu-id="5fa39-134">To insert the unsubscribe link in the email message, place the cursor at the required location, and then select **Insert** > **Unsubscribe link**.</span></span> <span data-ttu-id="5fa39-135">Sie können auch Text auswählen und dann **Einfügen** > **Abmelde-Link** wählen, um diesen Text als Abmeldelink anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-135">You can also select text, and then select **Insert** > **Unsubscribe link** to display that text as the unsubscribe link.</span></span> <span data-ttu-id="5fa39-136">Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-136">By default, the unsubscribe link is added to all email message templates.</span></span>

<a name="personalize-an-email"></a>

## <a name="personalize-the-survey-email"></a><span data-ttu-id="5fa39-137">Personalisieren der Umfrage-E-Mail</span><span class="sxs-lookup"><span data-stu-id="5fa39-137">Personalize the survey email</span></span>

<span data-ttu-id="5fa39-138">Verwenden Sie Umfragevariablen, um Ihre Umfrage-E-Mail zu personalisieren&mdash;Sie können beispielsweise den Vornamen des Befragten hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-138">Use survey variables to personalize your survey email&mdash;for example, you can add the respondent's first name.</span></span> <span data-ttu-id="5fa39-139">Platzieren Sie den Cursor an der Stelle, an der der Name angezeigt werden soll, und wählen Sie **Variablen** und dann **Vorname** von der Liste.</span><span class="sxs-lookup"><span data-stu-id="5fa39-139">Place the cursor where you want the name to appear, select **Variables**, and then select **First name** from the list.</span></span> <span data-ttu-id="5fa39-140">Der Vorname des Befragten wird automatisch eingefügt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-140">The first name of the respondent will be automatically inserted.</span></span> <span data-ttu-id="5fa39-141">Alle in einer Umfrage erstellten Umfragevariablen werden in der Liste **Variablen** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-141">All the survey variables created in a survey are displayed in the **Variables** list.</span></span>

<span data-ttu-id="5fa39-142">Um eine neue Variable zu erstellen, wählen Sie **Neue Variable** aus der Liste **Variablen**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-142">To create a new variable, select **New variable** from the **Variables** list.</span></span> <span data-ttu-id="5fa39-143">Wenn für Umfragevariablen keine Standardwerte definiert wurden, wird oben auf der Seite eine Warnmeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-143">If default values haven't been defined for survey variables, a warning message is displayed at the top of the page.</span></span> <span data-ttu-id="5fa39-144">Weitere Informationen zum Erstellen von Variablen und zum Bereitstellen von Werten finden Sie unter [Personalisieren Sie eine Umfrage](personalize-survey.md).</span><span class="sxs-lookup"><span data-stu-id="5fa39-144">For more information about creating variables and providing values for them, see [Personalize a survey](personalize-survey.md).</span></span>

<a name="embed-survey-in-an-email"></a>

## <a name="embed-a-survey-in-an-email"></a><span data-ttu-id="5fa39-145">Betten Sie eine Umfrage in eine E-Mail ein</span><span class="sxs-lookup"><span data-stu-id="5fa39-145">Embed a survey in an email</span></span>

<span data-ttu-id="5fa39-146">Wenn Sie eine Frage zur Bewertung oder zum Netto-Promoter-Score als erste Frage in Ihrer Umfrage hinzugefügt haben, können Sie sie in Ihre E-Mail-Nachricht einbetten.</span><span class="sxs-lookup"><span data-stu-id="5fa39-146">If you have added a Rating or Net Promoter Score question as the first question in your survey, you can embed it in your email message.</span></span> <span data-ttu-id="5fa39-147">Um die Frage einzubetten, wählen Sie **Einbetten erste Frage**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-147">To embed the question, select **Embed first question**.</span></span> <span data-ttu-id="5fa39-148">Wenn Sie eine Frage einbetten, wird der Text in der E-Mail-Nachricht durch die Frage ersetzt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-148">When you embed a question, the text in the email message is replaced by the question.</span></span> <span data-ttu-id="5fa39-149">Wenn ein Befragter eine Option in der E-Mail auswählt, wird die gesamte Umfrage im Webbrowser geöffnet und der Befragte kann die Umfrage fortsetzen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-149">When a responder selects an option in the email, the complete survey is opened in the web browser and the responder can continue with completing the survey.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="5fa39-150">![Betten Sie eine Umfrage in eine E-Mail ein](media/embed-ques-email.png "Betten Sie eine Umfrage in eine E-Mail ein")</span><span class="sxs-lookup"><span data-stu-id="5fa39-150">![Embed a survey in an email](media/embed-ques-email.png "Embed a survey in an email")</span></span>

> [!NOTE]
> <span data-ttu-id="5fa39-151">Sie können die Frage nicht in eine E-Mail einbetten, wenn Sie das Mischen von Fragen in einer Umfrage aktiviert haben.</span><span class="sxs-lookup"><span data-stu-id="5fa39-151">You can't embed the question in an email if you have enabled question shuffling in a survey.</span></span>

<a name="use-email-templates"></a>

## <a name="use-email-templates"></a><span data-ttu-id="5fa39-152">E-Mail-Vorlagen verwenden</span><span class="sxs-lookup"><span data-stu-id="5fa39-152">Use email templates</span></span>

<span data-ttu-id="5fa39-153">Sie können eine E-Mail-Vorlage,&mdash;eine vorformatierte E-Mail-Nachricht&mdash;nutzen, mit der Sie schnell E-Mail-Nachrichten erstellen und senden können.</span><span class="sxs-lookup"><span data-stu-id="5fa39-153">You can use an email template&mdash;a preformatted email message&mdash;to quickly create and send email messages.</span></span> <span data-ttu-id="5fa39-154">Sie können den Text ändern und Ihre Änderungen dann in der aktuellen E-Mail-Vorlage speichern oder die Änderungen in einer neuen E-Mail-Vorlage speichern.</span><span class="sxs-lookup"><span data-stu-id="5fa39-154">You can modify the text, and then save your changes to the current email template or save the changes to a new email template.</span></span> <span data-ttu-id="5fa39-155">Wenn Sie keine andere Auswahl treffen, wird **Standardvorlage** für die Verwendung in einer E-Mail-Nachricht ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-155">Unless you make another selection, **Default Template** is selected for use in an email message.</span></span>

<span data-ttu-id="5fa39-156">Sie können diese Aktionen auf einer E-Mail-Vorlage durchführen:</span><span class="sxs-lookup"><span data-stu-id="5fa39-156">You can perform these actions on an email template:</span></span>

- <span data-ttu-id="5fa39-157">**Speichern**: Speichern Sie Ihre Änderungen an der aktuellen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="5fa39-157">**Save**: Save your changes to the current email template.</span></span>

- <span data-ttu-id="5fa39-158">**Speichern unter**: Speichern Sie Ihre Änderungen in einer neuen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="5fa39-158">**Save as**: Save your changes to a new email template.</span></span>

- <span data-ttu-id="5fa39-159">**Löschen**: Löschen Sie die aktuelle E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="5fa39-159">**Delete**: Delete the current email template.</span></span>

- <span data-ttu-id="5fa39-160">**Umbenennen**: Benennen Sie die aktuelle E-Mail-Vorlage um.</span><span class="sxs-lookup"><span data-stu-id="5fa39-160">**Rename**: Rename the current email template.</span></span>


> [!NOTE]
> - <span data-ttu-id="5fa39-161">Sie können maximal 10 E-Mail-Vorlagen speichern.</span><span class="sxs-lookup"><span data-stu-id="5fa39-161">You can save a maximum of 10 email templates.</span></span>
> - <span data-ttu-id="5fa39-162">Wenn eine E-Mail-Vorlage Umfragevariablen enthält, die nicht Teil der Umfrage sind, wird oben auf der Seite eine Fehlermeldung angezeigt, und Sie können die Umfrage nicht per E-Mail oder Microsoft senden Power Automate.</span><span class="sxs-lookup"><span data-stu-id="5fa39-162">If an email template includes survey variables that aren't part of the survey, an error message is displayed at the top of the page and you won't be allowed to send the survey through email or Microsoft Power Automate.</span></span> <span data-ttu-id="5fa39-163">Die Umfragevariablen werden rot hervorgehoben. Sie müssen diese hervorgehobenen Variablen aus der E-Mail-Nachricht entfernen, bevor Sie die Umfrage senden können.</span><span class="sxs-lookup"><span data-stu-id="5fa39-163">The survey variables will be highlighted in red; you must remove these highlighted variables from the email message before you can send the survey.</span></span>

<a name="customize-sender-email-address"></a>

## <a name="customize-the-senders-email-address"></a><span data-ttu-id="5fa39-164">Passen Sie die E-Mail-Adresse des Senders an</span><span class="sxs-lookup"><span data-stu-id="5fa39-164">Customize the sender's email address</span></span>

<span data-ttu-id="5fa39-165">Mithilfe der Anpassungsfunktion können Sie eine E-Mail-Adresse auswählen, die der Marke Ihres Unternehmens entspricht.</span><span class="sxs-lookup"><span data-stu-id="5fa39-165">The customization feature helps you select an email address that matches your company's brand.</span></span> <span data-ttu-id="5fa39-166">Sie können sich an den Microsoft-Support wenden, um den von Forms Pro bereitgestellten Speicherort zu erfahren, um anschließend CNAME-Datensätze manuell zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-166">You can contact Microsoft support for the Forms Pro provisioned location, and then create CNAME records manually.</span></span> <span data-ttu-id="5fa39-167">Die CNAME-Datensätze werden für die DKIM-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5fa39-167">The CNAME records will be used for DKIM authentication.</span></span> <span data-ttu-id="5fa39-168">Sie müssen zwei CNAME-Einträge pro benutzerdefinierter Domäne erstellen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-168">You must create two CNAME records per custom domain.</span></span> <span data-ttu-id="5fa39-169">Anschließend können Sie die E-Mail-Adresse anpassen, mit der die Umfrageeinladung an Ihre Befragten gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="5fa39-169">Thereafter, you'll be able to customize the email address that sends the survey invitation to your respondents.</span></span>

1. <span data-ttu-id="5fa39-170">Melden Sie sich mit Ihren Administrator-Anmeldeinformationen beim [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/support) an.</span><span class="sxs-lookup"><span data-stu-id="5fa39-170">Sign in to the [Power Platform admin center](https://admin.powerplatform.microsoft.com/support) with your admin credentials.</span></span>

2. <span data-ttu-id="5fa39-171">Wählen Sie **Hilfe + Support** > **Neue Supportanfragen** aus.</span><span class="sxs-lookup"><span data-stu-id="5fa39-171">Select **Help + support** > **New support request**.</span></span> <span data-ttu-id="5fa39-172">Das Support-Anfrageformular wird im rechten Bereich angezeigt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-172">The support request form is displayed in the right pane.</span></span>

3. <span data-ttu-id="5fa39-173">Geben Sie die Produktdetails wie folgt an:</span><span class="sxs-lookup"><span data-stu-id="5fa39-173">Specify the product details as follows:</span></span>

    - <span data-ttu-id="5fa39-174">**Produkt**: Dynamics 365 Customer Engagement</span><span class="sxs-lookup"><span data-stu-id="5fa39-174">**Product**: Dynamics 365 Customer Engagement</span></span>
    - <span data-ttu-id="5fa39-175">**Problemtyp**: Forms Pro</span><span class="sxs-lookup"><span data-stu-id="5fa39-175">**Problem type**: Forms Pro</span></span>
    - <span data-ttu-id="5fa39-176">**Umgebung**: Geben Sie die Common Data Service-Umgebung ein, oder wählen Sie sie aus</span><span class="sxs-lookup"><span data-stu-id="5fa39-176">**Environment**: Enter or select your Common Data Service environment</span></span>

4. <span data-ttu-id="5fa39-177">Wählen Sie **Lösungen anzeigen** aus.</span><span class="sxs-lookup"><span data-stu-id="5fa39-177">Select **See solutions**.</span></span>

5. <span data-ttu-id="5fa39-178">Wählen Sie **Erstellen Sie eine Supportanfrage** aus, und geben Sie dann Details wie folgt an:</span><span class="sxs-lookup"><span data-stu-id="5fa39-178">Select **Create a support request**, and specify details as follows:</span></span>

    - <span data-ttu-id="5fa39-179">**Problemtitel**: Passen Sie die Absender-E-Mail-Adresse an, um Umfrageeinladungen zu senden</span><span class="sxs-lookup"><span data-stu-id="5fa39-179">**Issue title**: Customize the From email address to send survey invitations</span></span>
    - <span data-ttu-id="5fa39-180">**Fehlerbeschreibung** : Geben Sie Ihre Problembeschreibung ein und fragen Sie nach dem von Forms Pro bereitgestellten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="5fa39-180">**Issue description**: Enter your issue description, and ask for your Forms Pro provisioned location.</span></span>
    - <span data-ttu-id="5fa39-181">**Wie schwer ist dieses Problem?**: Wählen Sie den Schweregrad des Problems.</span><span class="sxs-lookup"><span data-stu-id="5fa39-181">**How severe is this issue?**: Select the severity of the issue.</span></span>

6. <span data-ttu-id="5fa39-182">Wählen Sie **Weiter**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-182">Select **Next**.</span></span>

7. <span data-ttu-id="5fa39-183">Geben Sie Ihre Kontaktinformationen ein, und wählen Sie dann **Senden** aus.</span><span class="sxs-lookup"><span data-stu-id="5fa39-183">Enter your contact information, and then select **Submit**.</span></span> <span data-ttu-id="5fa39-184">Mit dem Microsoft-Support Team wird ein Ticket erstellt, das Sie über den bereitgestellten Speicherort informiert.</span><span class="sxs-lookup"><span data-stu-id="5fa39-184">A ticket is created with the Microsoft support team, which will contact you with the provisioned location.</span></span>

8.  <span data-ttu-id="5fa39-185">Nachdem Sie den bereitgestellten Speicherort erhalten haben, erstellen Sie zwei CNAME-Datensätze in Ihrer Domäne im folgenden Format:</span><span class="sxs-lookup"><span data-stu-id="5fa39-185">After you receive the provisioned location, create two CNAME records in your domain in the following format:</span></span>

    ``` text
    Host name:                    selector1._domainkey
    Points to address or value:   selector1<domainGUID>.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    selector2._domainkey
    Points to address or value:   selector2<domainGUID>.marketing.dynamics.com
    TTL:                          3600
    ```

    > [!IMPORTANT]
    > <span data-ttu-id="5fa39-186">Wenn Ihre benutzerdefinierte Domäne `contoso.com` lautet, ist die domainGuid `contosocom`.</span><span class="sxs-lookup"><span data-stu-id="5fa39-186">If your customized domain is `contoso.com`, your domainGuid will be `contosocom`.</span></span> <span data-ttu-id="5fa39-187">Sie müssen Punkte, Unterstriche und Bindestriche entfernen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-187">You must remove any periods, underscores, and dashes.</span></span>
    > <span data-ttu-id="5fa39-188">Die Auswahlmöglichkeiten richten sich nach dem von Forms Pro bereitgestellten Speicherort:</span><span class="sxs-lookup"><span data-stu-id="5fa39-188">The selectors will be as per the Forms Pro provisioned location:</span></span>
    > - <span data-ttu-id="5fa39-189">Für Nordamerika (NAM) lautet die Auswahl "fpnamkey1" oder "fpnamkey2".</span><span class="sxs-lookup"><span data-stu-id="5fa39-189">For North America (NAM), the selector will be "fpnamkey1" or "fpnamkey2".</span></span>
    > - <span data-ttu-id="5fa39-190">Für Europa (EUR) lautet die Auswahl "fpeurkey1" oder "fpeurkey2".</span><span class="sxs-lookup"><span data-stu-id="5fa39-190">For Europe (EUR), the selector will be "fpeurkey1" or "fpeurkey2".</span></span>

    <span data-ttu-id="5fa39-191">Nehmen wir an, Ihr von Forms Pro bereitgestellter Speicherort ist Nordamerika (NAM), und Sie haben zwei benutzerdefinierte Domänen: `contoso.com` und `contososuites.com`.</span><span class="sxs-lookup"><span data-stu-id="5fa39-191">Let's say your Forms Pro provisioned location is North America (NAM), and you have two custom domains: `contoso.com`  and `contososuites.com`.</span></span> <span data-ttu-id="5fa39-192">Sie müssen wie folgt zwei CNAME-Einträge pro Domain einrichten (insgesamt vier CNAME-Einträge):</span><span class="sxs-lookup"><span data-stu-id="5fa39-192">You need to set up two CNAME records per domain (a total of four CNAME records), as follows:</span></span>

    ``` text
    Host name:                    fpnamkey1._domainkey
    Points to address or value:   fpnamkey1contosocom.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    fpnamkey2._domainkey
    Points to address or value:   fpnamkey1contosocom.marketing.dynamics.com
    TTL:                          3600
    Host name:                    fpnamkey1._domainkey
    Points to address or value:   fpnamkey1contososuitescom.marketing.dynamics.com
    TTL:                          3600
    Host name:                    fpnamkey2._domainkey
    Points to address or value:   fpnamkey1contososuitescom.marketing.dynamics.com
    TTL:                          3600
    ```

9.  <span data-ttu-id="5fa39-193">Wenden Sie sich an den Microsoft-Support, und geben Sie die folgenden Informationen an:</span><span class="sxs-lookup"><span data-stu-id="5fa39-193">Contact Microsoft support and provide the following information:</span></span>

    - <span data-ttu-id="5fa39-194">Eine Liste der E-Mail-Adressen, die Sie erstellen möchten, z. B. support@contoso.com und noreply@contososuites.com.</span><span class="sxs-lookup"><span data-stu-id="5fa39-194">A list of email addresses you want to create, such as support@contoso.com and noreply@contososuites.com.</span></span>
    - <span data-ttu-id="5fa39-195">Eine Liste der Benutzer, die die Umfrageeinladungen mithilfe der benutzerdefinierten E-Mail senden.</span><span class="sxs-lookup"><span data-stu-id="5fa39-195">A list of users who will be sending the survey invitations by using the custom email.</span></span>

    <span data-ttu-id="5fa39-196">Basierend auf den bereitgestellten Informationen überprüft der Microsoft-Support die Datensätze und erstellt die DKIM-Schlüssel zum Signieren der E-Mails.</span><span class="sxs-lookup"><span data-stu-id="5fa39-196">Based on the information provided, Microsoft support will then verify the records and create the DKIM keys for signing the emails.</span></span> <span data-ttu-id="5fa39-197">Sie erhalten vom Microsoft-Support eine Bestätigung, dass die Datensatzüberprüfung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5fa39-197">You'll get a confirmation from Microsoft support that the record verification is complete.</span></span>

    > [!NOTE]
    > <span data-ttu-id="5fa39-198">Das SLA für die Erstellung von DKIM-Schlüsseln beträgt mindestens 3 bis 4 Wochen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-198">The SLA for creating DKIM keys is minimum 3 to 4 weeks.</span></span>

10. <span data-ttu-id="5fa39-199">Melden Sie sich bei Forms Pro an und öffnen Sie die den Bereich **Einstellungen**.</span><span class="sxs-lookup"><span data-stu-id="5fa39-199">Sign in to Forms Pro, and open the **Settings** pane.</span></span> <span data-ttu-id="5fa39-200">Wählen Sie die benutzerdefinierte E-Mail-Adresse an, die Sie verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="5fa39-200">Select the custom email address that you want to use for sending email.</span></span>  

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="5fa39-201">![Benutzerdefinierte E-Mail-Einstellung](media/custom-email-setting.png "Benutzerdefinierte E-Mail-Einstellung")</span><span class="sxs-lookup"><span data-stu-id="5fa39-201">![Custom email setting](media/custom-email-setting.png "Custom email setting")</span></span>

    <span data-ttu-id="5fa39-202">Verwenden Sie die benutzerdefinierte E-Mail, während Sie die Umfrageeinladung senden.</span><span class="sxs-lookup"><span data-stu-id="5fa39-202">Use the custom email while sending the survey invitation.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="5fa39-203">![Benutzerdefinierte Absender-E-Mail](media/custom-from-email.png "Benutzerdefinierte Absender-E-Mail")</span><span class="sxs-lookup"><span data-stu-id="5fa39-203">![Custom From email](media/custom-from-email.png "Custom From email")</span></span>

    > [!NOTE]
    > <span data-ttu-id="5fa39-204">Im Power Automate wird die benutzerdefinierte E-Mail-Adresse aus den Umfrageeinstellungen ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="5fa39-204">In Power Automate, the custom email address is picked from the survey settings.</span></span>

### <a name="frequently-asked-questions"></a><span data-ttu-id="5fa39-205">Häufig gestellte Fragen</span><span class="sxs-lookup"><span data-stu-id="5fa39-205">Frequently asked questions</span></span>

#### <a name="should-the-email-account-be-a-functioning-account-or-can-it-be-a-dummy-account"></a><span data-ttu-id="5fa39-206">Sollte das E-Mail-Konto ein funktionierendes Konto sein oder kann es ein Dummy-Konto sein?</span><span class="sxs-lookup"><span data-stu-id="5fa39-206">Should the email account be a functioning account, or can it be a dummy account?</span></span>

<span data-ttu-id="5fa39-207">Das E-Mail-Konto muss nicht funktionsfähig sein, um E-Mails zu senden. Es muss jedoch ein Postfach konfiguriert werden, wenn für das Konto Antworten erwartet werden.</span><span class="sxs-lookup"><span data-stu-id="5fa39-207">The email account need not be a functioning account to send emails; however, a mailbox must be configured if the account is expected to receive replies.</span></span> <span data-ttu-id="5fa39-208">In den meisten Fällen ist die E-Mail-Adresse, von der Umfrage-E-Mails gesendet werden, ein nicht überwachtes E-Mail-Konto und muss keine E-Mails empfangen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-208">In most cases, the email address from which survey emails are sent is an unmonitored email account, and need not receive emails.</span></span>

#### <a name="how-long-does-it-take-for-setup-to-be-completed"></a><span data-ttu-id="5fa39-209">Wie lange dauert es, bis das Setup abgeschlossen ist?</span><span class="sxs-lookup"><span data-stu-id="5fa39-209">How long does it take for setup to be completed?</span></span>

<span data-ttu-id="5fa39-210">Es dauert mindestens 3 bis 4 Wochen, bis die Einrichtung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5fa39-210">It will take a minimum of 3 to 4 weeks for setup to be completed.</span></span> <span data-ttu-id="5fa39-211">Nachdem der Microsoft-Support bestätigt hat, dass die Domain aktiv ist, können Sie mithilfe der benutzerdefinierten E-Mail mit dem Senden von Umfrageeinladungen beginnen.</span><span class="sxs-lookup"><span data-stu-id="5fa39-211">After Microsoft support confirms the domain is active, you can start sending survey invitations by using the custom email.</span></span>

### <a name="see-also"></a><span data-ttu-id="5fa39-212">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="5fa39-212">See also</span></span>

[<span data-ttu-id="5fa39-213">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="5fa39-213">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="5fa39-214">Senden Sie eine Umfrage mit Power Automate</span><span class="sxs-lookup"><span data-stu-id="5fa39-214">Send a survey by using Power Automate</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="5fa39-215">Eine Umfrage in einer Webseite einbetten</span><span class="sxs-lookup"><span data-stu-id="5fa39-215">Embed a survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="5fa39-216">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="5fa39-216">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="5fa39-217">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="5fa39-217">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="5fa39-218">Einbetten einer Umfrage in Power Apps</span><span class="sxs-lookup"><span data-stu-id="5fa39-218">Embed a survey in Power Apps</span></span>](embed-survey-powerapps.md)
