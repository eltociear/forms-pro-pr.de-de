---
title: Senden einer Umfrage per E-Mail | MicrosoftDocs
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 12/02/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 218ab18e8448011bf4b8e914ae43d0854d02ef2f
ms.sourcegitcommit: 7f28e8040b2a3e56ba0caff0d48053974e3a1e80
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/02/2019
ms.locfileid: "2856185"
---
# <a name="send-a-survey-by-using-email"></a><span data-ttu-id="d88d6-103">Senden Sie eine Umfrage per E-Mail.</span><span class="sxs-lookup"><span data-stu-id="d88d6-103">Send a survey by using email</span></span>

<span data-ttu-id="d88d6-104">Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden:</span><span class="sxs-lookup"><span data-stu-id="d88d6-104">After creating a survey, you can send it through email:</span></span> 

1.  <span data-ttu-id="d88d6-105">Öffnen Sie die Umfrage, die Sie senden möchten, und wählen Sie **Senden** aus der Symbolleiste oben auf der Seite.</span><span class="sxs-lookup"><span data-stu-id="d88d6-105">Open the survey you want to send, and select **Send** from the toolbar at the top of the page.</span></span> 

2. <span data-ttu-id="d88d6-106">Wählen Sie **E-Mail**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-106">Select **Email**.</span></span> <span data-ttu-id="d88d6-107">Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="d88d6-107">A default subject line and email message appear, along with a link to your survey in the message body.</span></span> <span data-ttu-id="d88d6-108">Sie können den Text an Ihre Anforderungen anpassen und formatieren.</span><span class="sxs-lookup"><span data-stu-id="d88d6-108">You can modify and format the text to meet your requirements.</span></span>

3.  <span data-ttu-id="d88d6-109">Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="d88d6-109">In the **To** field, enter the recipient's name or email address.</span></span> <span data-ttu-id="d88d6-110">Sie können das Feld **Bis** auf eine der folgenden Arten füllen:</span><span class="sxs-lookup"><span data-stu-id="d88d6-110">You can populate the **To** field by any of the following ways:</span></span>
    - <span data-ttu-id="d88d6-111">Manuelle Eingabe einer E-Mail-Adresse.</span><span class="sxs-lookup"><span data-stu-id="d88d6-111">Entering an email address manually.</span></span>
    - <span data-ttu-id="d88d6-112">Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="d88d6-112">Entering a name, email address, or a distribution list from Azure Active Directory.</span></span>
    - <span data-ttu-id="d88d6-113">Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Services für Apps.</span><span class="sxs-lookup"><span data-stu-id="d88d6-113">Entering a contact or contact list/view from Common Data Services for Apps.</span></span> <span data-ttu-id="d88d6-114">Die Kontakte werden aus der ausgewählten Umgebung gefüllt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-114">The contacts are populated from the selected environment.</span></span> <span data-ttu-id="d88d6-115">Weitere Informationen zum Arbeiten mit Umgebungen finden Sie unter [Arbeiten mit Umgebungen](choose-environment.md).</span><span class="sxs-lookup"><span data-stu-id="d88d6-115">For more information on working with environments, see [Work with environments](choose-environment.md).</span></span>
    - <span data-ttu-id="d88d6-116">Hochladen einer csv-Datei durch Auswahl von **Empfänger importieren**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-116">Uploading a .csv file by selecting **Import recipients**.</span></span> <span data-ttu-id="d88d6-117">Die CSV-Datei unterstützt den Import von maximal 10000 Empfängern.</span><span class="sxs-lookup"><span data-stu-id="d88d6-117">The CSV file supports importing a maximum of 10000 recipients.</span></span>

4.  <span data-ttu-id="d88d6-118">Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [Umfrage-Link einfügen](#insert-survey-link).</span><span class="sxs-lookup"><span data-stu-id="d88d6-118">To insert the survey link into your email message, see [Insert survey link](#insert-survey-link).</span></span>  

5.  <span data-ttu-id="d88d6-119">Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einer Umfrage](#unsubscribe-from-a-survey).</span><span class="sxs-lookup"><span data-stu-id="d88d6-119">To add an unsubscribe link to your email message, see [Unsubscribe from a survey](#unsubscribe-from-a-survey).</span></span>  

6.  <span data-ttu-id="d88d6-120">Informationen zur Personalisierung der E-Mail mithilfe von Umfragevariablen finden Sie unter [Personalisierung einer E-Mail](#personalize-an-email).</span><span class="sxs-lookup"><span data-stu-id="d88d6-120">To personalize the email by using survey variables, see [Personalize an email](#personalize-an-email).</span></span>

7. <span data-ttu-id="d88d6-121">Um die erste Frage der Umfrage in Ihre E-Mail-Nachricht einzubetten, siehe [Umfrage einbetten in eine E-Mail](#embed-survey-in-an-email).</span><span class="sxs-lookup"><span data-stu-id="d88d6-121">To embed the first question of the survey into your email message, see [Embed survey in an email](#embed-survey-in-an-email).</span></span>

8.  <span data-ttu-id="d88d6-122">Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-122">To select an email template, select a template from the **Template** drop-down list.</span></span> <span data-ttu-id="d88d6-123">Standardmäßig ist **Standardvorlage** ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-123">By default, **Default Template** is selected.</span></span> <span data-ttu-id="d88d6-124">Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates)</span><span class="sxs-lookup"><span data-stu-id="d88d6-124">More information: [Use email templates](#use-email-templates)</span></span>  

9.  <span data-ttu-id="d88d6-125">Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-125">When you're ready to send your survey, select **Send**.</span></span>

> [!NOTE]
> <span data-ttu-id="d88d6-126">Sie können eine Umfrageeinladung an maximal 10000 Empfänger senden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-126">You can send a survey invitation to a maximum of 10000 recipients.</span></span>

## <a name="insert-survey-link"></a><span data-ttu-id="d88d6-127">Umfrage-Link einfügen</span><span class="sxs-lookup"><span data-stu-id="d88d6-127">Insert survey link</span></span>

<span data-ttu-id="d88d6-128">Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-128">The survey link is added to your email message by default.</span></span> <span data-ttu-id="d88d6-129">Um den Umfrage-Link an einer anderen Stelle in Ihrer E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie **Einfügen** > **Umfrage-Link**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-129">To insert the survey link in a different location in your email message, place the cursor at the required location, and select **Insert** > **Survey link**.</span></span> <span data-ttu-id="d88d6-130">Sie können auch Text auswählen und dann **Einfügen** > **Umfrage-Link** wählen, um diesen Text als Umfrage-Link anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="d88d6-130">You can also select text, and then select **Insert** > **Survey link** to display that text as the survey link.</span></span>

## <a name="unsubscribe-from-a-survey"></a><span data-ttu-id="d88d6-131">Abmeldung von einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="d88d6-131">Unsubscribe from a survey</span></span>

<span data-ttu-id="d88d6-132">Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-132">You can configure your email message to include a link that allows a respondent to unsubscribe from the survey.</span></span> <span data-ttu-id="d88d6-133">Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Einfügen** > **Link**Abmelden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-133">To insert the unsubscribe link in the email message, place the cursor at the required location, and then select **Insert** > **Unsubscribe link**.</span></span> <span data-ttu-id="d88d6-134">Sie können auch Text auswählen und dann **Einfügen** > **Link**Abmelden wählen, um diesen Text als Abmeldelink anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="d88d6-134">You can also select text, and then select **Insert** > **Unsubscribe link** to display that text as the unsubscribe link.</span></span> <span data-ttu-id="d88d6-135">Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-135">By default, the unsubscribe link is added to all email message templates.</span></span>

## <a name="personalize-an-email"></a><span data-ttu-id="d88d6-136">Eine E-Mail personalisieren</span><span class="sxs-lookup"><span data-stu-id="d88d6-136">Personalize an email</span></span>

<span data-ttu-id="d88d6-137">Personalisieren Sie Ihre Umfrage-E-Mail, indem Sie Umfrage-Variablen verwenden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-137">Personalize your survey email by using survey variables.</span></span> <span data-ttu-id="d88d6-138">Positionieren Sie den Cursor beispielsweise an der Stelle, an der ein Vorname erscheinen soll.</span><span class="sxs-lookup"><span data-stu-id="d88d6-138">For example, place the cursor where you want a first name to appear.</span></span> <span data-ttu-id="d88d6-139">Wählen Sie **Variablen**, und wählen Sie dann **Vorname** aus der Auswahlliste.</span><span class="sxs-lookup"><span data-stu-id="d88d6-139">Select **Variables**, and then select **First name** from the drop-down list.</span></span> <span data-ttu-id="d88d6-140">Der Vorname des Befragten wird automatisch eingefügt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-140">The first name of the respondent will be automatically inserted.</span></span> <span data-ttu-id="d88d6-141">Alle in einer Umfrage erstellten Umfragevariablen werden in der Liste **Variablen** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-141">All the survey variables created in a survey are displayed in the **Variables** list.</span></span>

<span data-ttu-id="d88d6-142">Um eine neue Variable zu erstellen, wählen Sie **Neue Variable** aus der Liste **Variablen**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-142">To create a new variable, select **New variable** from the **Variables** list.</span></span> <span data-ttu-id="d88d6-143">Informationen zum Erstellen und Bereitstellen von Werten für die Variablen finden Sie unter [Personalisieren einer Umfrage](personalize-survey.md)</span><span class="sxs-lookup"><span data-stu-id="d88d6-143">For information on creating and providing values to the variables, see [Personalize a survey](personalize-survey.md)</span></span>

<span data-ttu-id="d88d6-144">Wenn die Standardwerte für Umfragevariablen nicht definiert sind, wird oben auf der Seite eine Warnmeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-144">If the default values are not defined for survey variables, a warning message is displayed at the top of the page.</span></span>

## <a name="embed-survey-in-an-email"></a><span data-ttu-id="d88d6-145">Einbetten der Umfrage in eine E-Mail</span><span class="sxs-lookup"><span data-stu-id="d88d6-145">Embed survey in an email</span></span>

<span data-ttu-id="d88d6-146">Wenn Sie eine Frage zur Bewertung oder zum Netto-Promoter-Score als erste Frage in Ihrer Umfrage hinzugefügt haben, können Sie sie in Ihre E-Mail-Nachricht einbetten.</span><span class="sxs-lookup"><span data-stu-id="d88d6-146">If you have added a Rating or Net Promoter Score question as the first question in your survey, you can embed it in your email message.</span></span> <span data-ttu-id="d88d6-147">Um die Frage einzubetten, wählen Sie **Einbetten erste Frage**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-147">To embed the question, select **Embed first question**.</span></span> <span data-ttu-id="d88d6-148">Wenn Sie eine Frage einbetten, wird der Text in der E-Mail-Nachricht durch die Frage ersetzt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-148">When you embed a question, the text in the email message is replaced by the question.</span></span> <span data-ttu-id="d88d6-149">Wenn ein Befragter eine Option in der E-Mail auswählt, wird die gesamte Umfrage im Webbrowser geöffnet und der Befragte kann die Umfrage fortsetzen.</span><span class="sxs-lookup"><span data-stu-id="d88d6-149">When a responder selects an option in the email, the complete survey is opened in the web browser and the responder can continue with completing the survey.</span></span>

> [!div class=mx-imgBorder]
> <span data-ttu-id="d88d6-150">![Eingebettete Umfrage in eine E-Mail ](media/embed-ques-email.png "Einbetten der Umfrage in eine E-Mail")</span><span class="sxs-lookup"><span data-stu-id="d88d6-150">![Embed survey in an email](media/embed-ques-email.png "Embed survey in an email")</span></span>

> [!NOTE]
> <span data-ttu-id="d88d6-151">Sie können die Frage nicht in eine E-Mail einbetten, wenn Sie Verzweigungsregeln hinzugefügt oder die Fragen in einer Umfrage neu gemischt haben.</span><span class="sxs-lookup"><span data-stu-id="d88d6-151">You cannot embed the question in an email if you have added any branching rules or shuffled the questions in a survey.</span></span>

## <a name="use-email-templates"></a><span data-ttu-id="d88d6-152">E-Mail-Vorlagen verwenden</span><span class="sxs-lookup"><span data-stu-id="d88d6-152">Use email templates</span></span>

<span data-ttu-id="d88d6-153">Eine E-Mail-Vorlage ist eine vorformatierte E-Mail-Nachricht, mit der Sie schnell E-Mail-Nachrichten erstellen und senden können.</span><span class="sxs-lookup"><span data-stu-id="d88d6-153">An email template is a preformatted email message that allows you to quickly create and send email messages.</span></span> <span data-ttu-id="d88d6-154">Sie können den Text ändern und Ihre Änderungen dann in der aktuellen E-Mail-Vorlage speichern oder die Änderungen in einer neuen E-Mail-Vorlage speichern.</span><span class="sxs-lookup"><span data-stu-id="d88d6-154">You can modify the text, and then save your changes to the current email template or save the changes to a new email template.</span></span> <span data-ttu-id="d88d6-155">Wenn Sie keine andere Auswahl treffen, wird **Standardvorlage** für die Verwendung in einer E-Mail-Nachricht ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-155">Unless you make another selection, **Default Template** is selected for use in an email message.</span></span> 

<span data-ttu-id="d88d6-156">Sie können diese Aktionen auf einer E-Mail-Vorlage durchführen:</span><span class="sxs-lookup"><span data-stu-id="d88d6-156">You can perform these actions on an email template:</span></span>

- <span data-ttu-id="d88d6-157">**Speichern**: Speichern Sie Ihre Änderungen an der aktuellen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="d88d6-157">**Save**: Save your changes to the current email template.</span></span>

- <span data-ttu-id="d88d6-158">**Speichern unter**: Speichern Sie Ihre Änderungen in einer neuen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="d88d6-158">**Save as**: Save your changes to a new email template.</span></span>

- <span data-ttu-id="d88d6-159">**Löschen**: Löschen Sie die aktuelle E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="d88d6-159">**Delete**: Delete the current email template.</span></span>

- <span data-ttu-id="d88d6-160">**Umbenennen**: Benennen Sie die aktuelle E-Mail-Vorlage um.</span><span class="sxs-lookup"><span data-stu-id="d88d6-160">**Rename**: Rename the current email template.</span></span>

> [!NOTE]
> - <span data-ttu-id="d88d6-161">Sie können maximal 10 E-Mail-Vorlagen speichern.</span><span class="sxs-lookup"><span data-stu-id="d88d6-161">You can save a maximum of 10 email templates.</span></span>
> - <span data-ttu-id="d88d6-162">Wenn Sie Umfragevariablen in einer E-Mail-Vorlage verwendet haben, die nicht Teil der Umfrage sind, wird oben auf der Seite eine Fehlermeldung angezeigt und es ist Ihnen nicht gestattet, die Umfrage per E-Mail oder Flow zu senden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-162">If you have used survey variables in an email template, which are not part of the survey, an error message is displayed at the top of the page and you are not allowed to send the survey through email or Flow.</span></span> <span data-ttu-id="d88d6-163">Die Variablen der Umfrage sind rot markiert.</span><span class="sxs-lookup"><span data-stu-id="d88d6-163">The survey variables are highlighted in red.</span></span> <span data-ttu-id="d88d6-164">Sie müssen die hervorgehobenen Umfragevariablen aus der E-Mail-Nachricht entfernen, um die Umfrage zu senden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-164">You must remove the highlighted survey variables from the email message to send the survey.</span></span>

## <a name="customize-the-sender-email-address"></a><span data-ttu-id="d88d6-165">Anpassen der Absender-E-Mail-Adresse</span><span class="sxs-lookup"><span data-stu-id="d88d6-165">Customize the sender email address</span></span>

<span data-ttu-id="d88d6-166">Mithilfe der Anpassungsfunktion können Sie eine E-Mail-Adresse auswählen, die der Marke Ihres Unternehmens entspricht.</span><span class="sxs-lookup"><span data-stu-id="d88d6-166">The customization feature helps you select an email address that matches your company's brand.</span></span> <span data-ttu-id="d88d6-167">Sie können sich an den Microsoft-Support wenden, um den von Forms Pro bereitgestellten Speicherort zu erfahren, um anschließend CNAME-Datensätze manuell zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="d88d6-167">You can contact Microsoft support for the Forms Pro provisioned location, and then create CNAME records manually.</span></span> <span data-ttu-id="d88d6-168">Die CNAME-Datensätze werden für die DKIM-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="d88d6-168">The CNAME records will be used for DKIM authentication.</span></span> <span data-ttu-id="d88d6-169">Für jede benutzerdefinierte Domäne müssen zwei CNAME-Einträge erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-169">Two CNAME records must be created per custom domain.</span></span> <span data-ttu-id="d88d6-170">Anschließend kann die E-Mail-Adresse angepasst werden, über die die Umfrageeinladung an Ihre Befragten gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="d88d6-170">Thereafter, the email address can be customized that will be used to send the survey invitation to your respondents.</span></span>

1. <span data-ttu-id="d88d6-171">Melden Sie sich mit Ihren Administrator-Anmeldeinformationen beim [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/support) an.</span><span class="sxs-lookup"><span data-stu-id="d88d6-171">Sign in to the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/support) with your admin credentials.</span></span>

2. <span data-ttu-id="d88d6-172">Wählen Sie **Hilfe + Support** > **Neue Supportanfragen** aus.</span><span class="sxs-lookup"><span data-stu-id="d88d6-172">Select **Help + support** > **New support request**.</span></span> <span data-ttu-id="d88d6-173">Das Support-Anfrageformular wird im rechten Bereich angezeigt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-173">The support request form is displayed in the right pane.</span></span>

3. <span data-ttu-id="d88d6-174">Geben Sie die Produktdetails wie folgt an:</span><span class="sxs-lookup"><span data-stu-id="d88d6-174">Specify the product details as follows:</span></span>

    - <span data-ttu-id="d88d6-175">**Produkt**: Dynamics 365 Customer Engagement</span><span class="sxs-lookup"><span data-stu-id="d88d6-175">**Product**: Dynamics 365 Customer Engagement</span></span>
    - <span data-ttu-id="d88d6-176">**Problemtyp**: Forms Pro</span><span class="sxs-lookup"><span data-stu-id="d88d6-176">**Problem type**: Forms Pro</span></span>
    - <span data-ttu-id="d88d6-177">**Umgebung**: Geben Sie die Common Data Service-Umgebung ein, oder wählen Sie sie aus</span><span class="sxs-lookup"><span data-stu-id="d88d6-177">**Environment**: Enter or select your Common Data Service environment</span></span>

4. <span data-ttu-id="d88d6-178">Wählen Sie **Lösungen anzeigen** aus.</span><span class="sxs-lookup"><span data-stu-id="d88d6-178">Select **See solutions**.</span></span>

5. <span data-ttu-id="d88d6-179">Wählen Sie **Erstellen Sie eine Supportanfrage** aus, und geben Sie Details wie folgt an:</span><span class="sxs-lookup"><span data-stu-id="d88d6-179">Select **Create a support request** and specify details as follows:</span></span>

    - <span data-ttu-id="d88d6-180">**Problemtitel**: Passen Sie die Absender-E-Mail-Adresse an, um Umfrageeinladungen zu senden</span><span class="sxs-lookup"><span data-stu-id="d88d6-180">**Issue title**: Customize the From email address to send survey invitations</span></span>
    - <span data-ttu-id="d88d6-181">**Problembeschreibung**: Geben Sie Ihre Problembeschreibung ein, und fragen Sie nach dem von Forms Pro bereitgestellten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="d88d6-181">**Issue description**: Enter your issue description and ask for Forms Pro provisioned location.</span></span>
    - <span data-ttu-id="d88d6-182">**Wie schwer ist dieses Problem?**: Wählen Sie den Schweregrad des Problems.</span><span class="sxs-lookup"><span data-stu-id="d88d6-182">**How severe is this issue?**: Select the severity of the issue.</span></span>

6. <span data-ttu-id="d88d6-183">Wählen Sie **Weiter**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-183">Select **Next**.</span></span> 

7. <span data-ttu-id="d88d6-184">Geben Sie Ihre Kontaktinformationen ein, und wählen Sie dann **Senden** aus.</span><span class="sxs-lookup"><span data-stu-id="d88d6-184">Fill your contact information and select **Submit**.</span></span> <span data-ttu-id="d88d6-185">Es wird ein Ticket beim Microsoft-Support erstellt, und das Support-Team teilt Ihnen den bereitgestellten Speicherort mit.</span><span class="sxs-lookup"><span data-stu-id="d88d6-185">A ticket is created with Microsoft support and the support team will contact you with the provisioned location.</span></span>

8.  <span data-ttu-id="d88d6-186">Nachdem Sie den bereitgestellten Speicherort erhalten haben, erstellen Sie zwei CNAME-Datensätze in Ihrer Domäne im folgenden Format:</span><span class="sxs-lookup"><span data-stu-id="d88d6-186">After you receive the provisioned location, create two CNAME records in your domain in the following format:</span></span> 

    ``` text
    Host name:                    selector1._domainkey
    Points to address or value:   selector1<domainGUID>.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    selector2._domainkey
    Points to address or value:   selector2<domainGUID>.marketing.dynamics.com
    TTL:                          3600
    ```

    > [!IMPORTANT]
    > <span data-ttu-id="d88d6-187">Wenn Ihre benutzerdefinierte Domäne `contoso.com` lautet, ist die domainGuid `contosocom`.</span><span class="sxs-lookup"><span data-stu-id="d88d6-187">If your customized domain is `contoso.com`, your domainGuid will be `contosocom`.</span></span> <span data-ttu-id="d88d6-188">Sie müssen Punkte, Unterstriche und Bindestriche entfernen.</span><span class="sxs-lookup"><span data-stu-id="d88d6-188">You must remove any periods, underscores, and dashes.</span></span>
    > <span data-ttu-id="d88d6-189">Die Auswahlmöglichkeiten richten sich nach dem von Forms Pro bereitgestellten Speicherort:</span><span class="sxs-lookup"><span data-stu-id="d88d6-189">The selectors will be as per the Forms Pro provisioned location:</span></span>
    > - <span data-ttu-id="d88d6-190">Für Nordamerika (NAM) lautet die Auswahl „fpnamkey1“ oder „fpnamkey2“.</span><span class="sxs-lookup"><span data-stu-id="d88d6-190">For North America (NAM), selector will be "fpnamkey1" or " fpnamkey2".</span></span>
    > - <span data-ttu-id="d88d6-191">Für Europa (EUR) lautet die Auswahl „fpeurkey1“ oder „fpeurkey2“.</span><span class="sxs-lookup"><span data-stu-id="d88d6-191">For Europe (EUR), selector will be "fpeurkey1" or " fpeurkey2".</span></span>

    <span data-ttu-id="d88d6-192">Nehmen wir an, Ihr von Forms Pro bereitgestellter Speicherort ist Nordamerika (NAM), und Sie haben zwei benutzerdefinierte Domänen: `cohovineyard.com` und `cohowinery.com`.</span><span class="sxs-lookup"><span data-stu-id="d88d6-192">Let's say your Forms Pro provisioned location is North America (NAM), and you have two custom domains: `cohovineyard.com`  and `cohowinery.com`.</span></span> <span data-ttu-id="d88d6-193">Sie müssten zwei CNAME-Einträge pro Domäne (insgesamt vier CNAME-Datensätze) wie folgt einrichten:</span><span class="sxs-lookup"><span data-stu-id="d88d6-193">You would need to set up two CNAME records per domain (a total of four CNAME records) as follows:</span></span>

    ``` text
    Host name:                    fpnamkey1._domainkey
    Points to address or value:   fpnamkey1cohovineyardcom.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    fpnamkey2._domainkey
    Points to address or value:   fpnamkey1cohovineyardcom.marketing.dynamics.com
    TTL:                          3600
    Host name:                    fpnamkey1._domainkey
    Points to address or value:   fpnamkey1cohowinerycom.marketing.dynamics.com
    TTL:                          3600 
    Host name:                    fpnamkey2._domainkey
    Points to address or value:   fpnamkey1cohowinerycom.marketing.dynamics.com
    TTL:                          3600
    ```

9.  <span data-ttu-id="d88d6-194">Wenden Sie sich an den Microsoft-Support, und geben Sie die folgenden Informationen an:</span><span class="sxs-lookup"><span data-stu-id="d88d6-194">Contact Microsoft support and provide the following information:</span></span>

    - <span data-ttu-id="d88d6-195">Eine Liste der E-Mail-Adressen, die Sie erstellen möchten, z. B. support@cohovineyard.com und noreply@cohowinery.com.</span><span class="sxs-lookup"><span data-stu-id="d88d6-195">A list of email addresses you want to create, such as support@cohovineyard.com and noreply@cohowinery.com.</span></span>
    - <span data-ttu-id="d88d6-196">Eine Liste der Benutzer, die die Umfrageeinladungen mithilfe der benutzerdefinierten E-Mail senden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-196">A list of users who will be sending the survey invitations using the custom email.</span></span>

    <span data-ttu-id="d88d6-197">Basierend auf den bereitgestellten Informationen überprüft der Microsoft-Support die Datensätze und erstellt die DKIM-Schlüssel zum Signieren der E-Mails.</span><span class="sxs-lookup"><span data-stu-id="d88d6-197">Based on the information provided, Microsoft support will then verify the records and create the DKIM keys for signing the emails.</span></span> <span data-ttu-id="d88d6-198">Sie erhalten vom Microsoft-Support eine Bestätigung, dass die Datensatzüberprüfung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="d88d6-198">You will get a confirmation from Microsoft support that the record verification is complete.</span></span>

10. <span data-ttu-id="d88d6-199">Melden Sie sich bei Forms Pro an, und öffnen Sie die den Bereich **Einstellungen**.</span><span class="sxs-lookup"><span data-stu-id="d88d6-199">Sign in to Forms Pro and open the **Settings** pane.</span></span> <span data-ttu-id="d88d6-200">Wählen Sie die benutzerdefinierte E-Mail-Adresse aus, die zum Senden von E-Mails verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d88d6-200">Select the custom email address that should be used for sending email.</span></span>  

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="d88d6-201">![Benutzerdefinierte E-Mail-Einstellung](media/custom-email-setting.png "Benutzerdefinierte E-Mail-Einstellung")</span><span class="sxs-lookup"><span data-stu-id="d88d6-201">![Custom email setting](media/custom-email-setting.png "Custom email setting")</span></span>

    <span data-ttu-id="d88d6-202">Verwenden Sie die benutzerdefinierte E-Mail, während Sie die Umfrageeinladung senden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-202">Use the custom email while sending the survey invitation.</span></span>

    > [!div class=mx-imgBorder]
    > <span data-ttu-id="d88d6-203">![Benutzerdefinierte Absender-E-Mail](media/custom-from-email.png "Benutzerdefinierte Absender-E-Mail")</span><span class="sxs-lookup"><span data-stu-id="d88d6-203">![Custom From email](media/custom-from-email.png "Custom From email")</span></span>

    > [!NOTE]
    > <span data-ttu-id="d88d6-204">In Power Automate wird eine benutzerdefinierte E-Mail-Adresse aus den Umfrageeinstellungen ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="d88d6-204">In Power Automate, custom email address is picked from the survey settings.</span></span>

### <a name="frequently-asked-questions"></a><span data-ttu-id="d88d6-205">Häufig gestellte Fragen</span><span class="sxs-lookup"><span data-stu-id="d88d6-205">Frequently asked questions</span></span>

#### <a name="should-the-email-account-be-a-functioning-account-or-can-it-be-a-dummy-account"></a><span data-ttu-id="d88d6-206">Sollte das E-Mail-Konto ein funktionierendes Konto sein oder kann es ein Dummy-Konto sein?</span><span class="sxs-lookup"><span data-stu-id="d88d6-206">Should the email account be a functioning account, or can it be a dummy account?</span></span>

<span data-ttu-id="d88d6-207">Das E-Mail-Konto muss nicht funktionsfähig sein, um E-Mails zu senden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-207">The email account need not be a functioning account to send emails.</span></span> <span data-ttu-id="d88d6-208">Wenn über dieses E-Mail-Konto Antworten erwartet werden, muss ein Postfach konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="d88d6-208">If replies are expected to be received on that email account, a mailbox must be configured.</span></span> <span data-ttu-id="d88d6-209">In den meisten Fällen handelt es sich bei der E-Mail-Adresse, von der ein Kunde Umfrage-E-Mails sendet, um nicht überwachte E-Mail-Konten, die keine E-Mails empfangen müssen.</span><span class="sxs-lookup"><span data-stu-id="d88d6-209">In most cases, the email address from which a customer sends survey emails are unmonitored email accounts and need not receive emails.</span></span>

#### <a name="how-long-does-it-take-for-the-setup-to-complete"></a><span data-ttu-id="d88d6-210">Wie lange dauert es, bis die Einrichtung abgeschlossen ist?</span><span class="sxs-lookup"><span data-stu-id="d88d6-210">How long does it take for the setup to complete?</span></span>

<span data-ttu-id="d88d6-211">Es kann zwischen 24 und 72 Stunden dauern, bis das Setup abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="d88d6-211">It may take up to 24 to 72 hours for the setup to complete.</span></span> <span data-ttu-id="d88d6-212">Nachdem der Microsoft-Support bestätigt hat, dass die Domäne aktiv ist, können Sie mit dem Senden von Umfrageeinladungen mithilfe der benutzerdefinierten E-Mail beginnen.</span><span class="sxs-lookup"><span data-stu-id="d88d6-212">After the Microsoft support confirms the domain is active, you can start sending survey invitations using the custom email.</span></span>

## <a name="see-also"></a><span data-ttu-id="d88d6-213">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="d88d6-213">See also</span></span>

[<span data-ttu-id="d88d6-214">Arbeiten Sie mit den Umfrageeinstellungen</span><span class="sxs-lookup"><span data-stu-id="d88d6-214">Work with survey settings</span></span>](invite-settings.md)<br>
[<span data-ttu-id="d88d6-215">Senden Sie eine Umfrage mit Microsoft Flow</span><span class="sxs-lookup"><span data-stu-id="d88d6-215">Send a survey by using Microsoft Flow</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="d88d6-216">Eingebettete Umfrage in eine Webseite</span><span class="sxs-lookup"><span data-stu-id="d88d6-216">Embed survey in a webpage</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="d88d6-217">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="d88d6-217">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="d88d6-218">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="d88d6-218">Send a survey QR code</span></span>](send-survey-qrcode.md)<br>
[<span data-ttu-id="d88d6-219">Einbetten einer Umfrage in PowerApps</span><span class="sxs-lookup"><span data-stu-id="d88d6-219">Embed a survey in PowerApps</span></span>](embed-survey-powerapps.md)
