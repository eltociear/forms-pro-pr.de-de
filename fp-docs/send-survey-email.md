---
title: Senden einer Umfrage per E-Mail | MicrosoftDocs
description: Anweisungen zum Senden einer Umfrage per E-Mail
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 07/01/2019
ms.service: forms-pro
ms.topic: article
ms.assetid: c5d53c06-299d-43bc-a7ac-e6185c9695e3
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: c6f2c80afd0390c6398ffe7811a3b509732cbd3f
ms.sourcegitcommit: 5661ec673caaeeba4c63158a98a0f6e083cb73cd
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2019
ms.locfileid: "1778311"
---
# <a name="send-a-survey-by-using-email"></a><span data-ttu-id="61fb5-103">Senden Sie eine Umfrage per E-Mail.</span><span class="sxs-lookup"><span data-stu-id="61fb5-103">Send a survey by using email</span></span>



<span data-ttu-id="61fb5-104">Nachdem Sie eine Umfrage erstellt haben, können Sie diese per E-Mail versenden:</span><span class="sxs-lookup"><span data-stu-id="61fb5-104">After creating a survey, you can send it through email:</span></span> 

1.  <span data-ttu-id="61fb5-105">Öffnen Sie die Umfrage, die Sie senden möchten, und gehen Sie zu **Umfrage senden** &gt; **E-Mail**.</span><span class="sxs-lookup"><span data-stu-id="61fb5-105">Open the survey you want to send, and go to **Send Survey** &gt; **Email**.</span></span> <span data-ttu-id="61fb5-106">Eine Standard-Betreffzeile und eine E-Mail-Nachricht werden angezeigt, zusammen mit einem Link zu Ihrer Umfrage im Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="61fb5-106">A default subject line and email message appear, along with a link to your survey in the message body.</span></span> <span data-ttu-id="61fb5-107">Sie können den Text an Ihre Anforderungen anpassen und formatieren.</span><span class="sxs-lookup"><span data-stu-id="61fb5-107">You can modify and format the text to meet your requirements.</span></span>

2.  <span data-ttu-id="61fb5-108">Geben Sie im Feld **An** den Namen oder die E-Mail-Adresse des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="61fb5-108">In the **To** field, enter the recipient's name or email address.</span></span> <span data-ttu-id="61fb5-109">Sie können das Feld **An** auf eine der folgenden Arten füllen:</span><span class="sxs-lookup"><span data-stu-id="61fb5-109">You can populate the **To** field by either of the following ways:</span></span>
    - <span data-ttu-id="61fb5-110">Manuelle Eingabe einer E-Mail-Adresse.</span><span class="sxs-lookup"><span data-stu-id="61fb5-110">Entering an email address manually.</span></span>
    - <span data-ttu-id="61fb5-111">Eingabe eines Namens, einer E-Mail-Adresse oder einer Verteilerliste von Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="61fb5-111">Entering a name, email address, or a distribution list from Azure Active Directory.</span></span>
    - <span data-ttu-id="61fb5-112">Eingabe eines Kontakts oder einer Kontaktliste/Ansicht von Common Data Services für Apps.</span><span class="sxs-lookup"><span data-stu-id="61fb5-112">Entering a contact or contact list/view from Common Data Services for Apps.</span></span> <span data-ttu-id="61fb5-113">Die Kontakte werden aus der ausgewählten Umgebung gefüllt.</span><span class="sxs-lookup"><span data-stu-id="61fb5-113">The contacts are populated from the selected environment.</span></span> <span data-ttu-id="61fb5-114">Weitere Informationen zum Arbeiten mit Umgebungen finden Sie unter [Arbeiten Sie mit Umgebungen](choose-environment.md).</span><span class="sxs-lookup"><span data-stu-id="61fb5-114">For more information on working with environments, see: [Work with environments](choose-environment.md).</span></span> 
    - <span data-ttu-id="61fb5-115">Hochladen einer csv-Datei durch Auswahl von **Empfänger importieren**.</span><span class="sxs-lookup"><span data-stu-id="61fb5-115">Uploading a .csv file by selecting **Import recipients**.</span></span>

3.  <span data-ttu-id="61fb5-116">Um den Umfrage-Link in Ihre E-Mail-Nachricht einzufügen, siehe [Umfrage-Link einfügen](#insert-survey-link).</span><span class="sxs-lookup"><span data-stu-id="61fb5-116">To insert the survey link into your email message, see [Insert survey link](#insert-survey-link).</span></span>  

4.  <span data-ttu-id="61fb5-117">Um einen Abmeldelink zu Ihrer E-Mail-Nachricht hinzuzufügen, siehe [Abmeldung von einer Umfrage](#unsubscribe-from-a-survey).</span><span class="sxs-lookup"><span data-stu-id="61fb5-117">To add an unsubscribe link to your email message, see [Unsubscribe from a survey](#unsubscribe-from-a-survey).</span></span>  

5.  <span data-ttu-id="61fb5-118">Um die E-Mail unter Verwendung von Vor- und Nachnamen des Befragten zu personalisieren, siehe [Personalisieren einer E-Mail](#personalize-an-email).</span><span class="sxs-lookup"><span data-stu-id="61fb5-118">To personalize the email by using first and last names of the respondent, see [Personalize an email](#personalize-an-email).</span></span>  

6.  <span data-ttu-id="61fb5-119">Um eine E-Mail-Vorlage auszuwählen, wählen Sie eine Vorlage aus der Dropdown-Liste **Vorlage**.</span><span class="sxs-lookup"><span data-stu-id="61fb5-119">To select an email template, select a template from the **Template** drop-down list.</span></span> <span data-ttu-id="61fb5-120">Standardmäßig ist **Standardvorlage** ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="61fb5-120">By default, **Default Template** is selected.</span></span> <span data-ttu-id="61fb5-121">Mehr Informationen: [E-Mail-Vorlagen verwenden](#use-email-templates).</span><span class="sxs-lookup"><span data-stu-id="61fb5-121">More information: [Use email templates](#use-email-templates).</span></span>  

7.  <span data-ttu-id="61fb5-122">Wenn Sie bereit sind, Ihre Umfrage zu senden, wählen Sie **Senden**.</span><span class="sxs-lookup"><span data-stu-id="61fb5-122">When you're ready to send your survey, select **Send**.</span></span>

> [!NOTE]
> <span data-ttu-id="61fb5-123">In dieser Version können Sie eine Umfrageeinladung an maximal 100 Empfänger senden.</span><span class="sxs-lookup"><span data-stu-id="61fb5-123">For this release, you can send a survey invitation to maximum 100 recipients.</span></span>

## <a name="insert-survey-link"></a><span data-ttu-id="61fb5-124">Umfrage-Link einfügen</span><span class="sxs-lookup"><span data-stu-id="61fb5-124">Insert survey link</span></span>

<span data-ttu-id="61fb5-125">Der Umfrage-Link wird standardmäßig zu Ihrer E-Mail-Nachricht hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="61fb5-125">The survey link is added to your email message by default.</span></span> <span data-ttu-id="61fb5-126">Um den Umfrage-Link an einer anderen Stelle in Ihrer E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie **Umfrage-Link einfügen**.</span><span class="sxs-lookup"><span data-stu-id="61fb5-126">To insert the survey link in a different location in your email message, place the cursor at the required location, and select **Insert survey link**.</span></span> <span data-ttu-id="61fb5-127">Sie können auch Text auswählen und dann **Umfrage-Link einfügen** wählen, um diesen Text als Umfrage-Link anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="61fb5-127">You can also select text, and then select **Insert survey link** to display that text as the survey link.</span></span>

## <a name="unsubscribe-from-a-survey"></a><span data-ttu-id="61fb5-128">Abmeldung von einer Umfrage</span><span class="sxs-lookup"><span data-stu-id="61fb5-128">Unsubscribe from a survey</span></span>

<span data-ttu-id="61fb5-129">Sie können Ihre E-Mail-Nachricht so konfigurieren, dass sie einen Link enthält, der es einem Befragten ermöglicht, sich von der Umfrage abzumelden.</span><span class="sxs-lookup"><span data-stu-id="61fb5-129">You can configure your email message to include a link that allows a respondent to unsubscribe from the survey.</span></span> <span data-ttu-id="61fb5-130">Um den Abmeldelink in die E-Mail-Nachricht einzufügen, positionieren Sie den Cursor an der gewünschten Stelle und wählen Sie dann **Abmeldelink einfügen**.</span><span class="sxs-lookup"><span data-stu-id="61fb5-130">To insert the unsubscribe link in the email message, place the cursor at the required location, and then select **Insert unsubscribe link**.</span></span> <span data-ttu-id="61fb5-131">Sie können auch Text auswählen und dann **Link zum Abmelden einfügen** wählen, um diesen Text als Abmeldelink anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="61fb5-131">You can also select text, and then select **Insert unsubscribe link** to display that text as the unsubscribe link.</span></span> <span data-ttu-id="61fb5-132">Standardmäßig wird der Link zum Abmelden zu allen E-Mail-Nachrichtenvorlagen hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="61fb5-132">By default, the unsubscribe link is added to all email message templates.</span></span>

## <a name="personalize-an-email"></a><span data-ttu-id="61fb5-133">Eine E-Mail personalisieren</span><span class="sxs-lookup"><span data-stu-id="61fb5-133">Personalize an email</span></span>

<span data-ttu-id="61fb5-134">Personalisieren Sie Ihre Umfrage-E-Mail, indem Sie Platzhalter verwenden.</span><span class="sxs-lookup"><span data-stu-id="61fb5-134">Personalize your survey email by using placeholders.</span></span> <span data-ttu-id="61fb5-135">Positionieren Sie den Cursor beispielsweise an der Stelle, an der ein Vorname erscheinen soll.</span><span class="sxs-lookup"><span data-stu-id="61fb5-135">For example, place the cursor where you want a first name to appear.</span></span> <span data-ttu-id="61fb5-136">Wählen Sie **Personalisieren**, und wählen Sie dann **Vorname** aus der Auswahlliste.</span><span class="sxs-lookup"><span data-stu-id="61fb5-136">Select **Personalize**, and then select **First name** from the drop-down list.</span></span> <span data-ttu-id="61fb5-137">Der Vorname des Befragten wird automatisch eingefügt.</span><span class="sxs-lookup"><span data-stu-id="61fb5-137">The first name of the respondent will be automatically inserted.</span></span> 

<span data-ttu-id="61fb5-138">Die folgenden Variablen stehen zur Verfügung:</span><span class="sxs-lookup"><span data-stu-id="61fb5-138">The following variables are available:</span></span>

- <span data-ttu-id="61fb5-139">**Vorname**: Fügt den Vornamen des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="61fb5-139">**First name**: Inserts first name of the recipient.</span></span>

- <span data-ttu-id="61fb5-140">**Nachname**: Fügt den Nachnamen des Empfängers ein.</span><span class="sxs-lookup"><span data-stu-id="61fb5-140">**Last name**: Inserts last name of the recipient.</span></span>


## <a name="use-email-templates"></a><span data-ttu-id="61fb5-141">E-Mail-Vorlagen verwenden</span><span class="sxs-lookup"><span data-stu-id="61fb5-141">Use email templates</span></span>

<span data-ttu-id="61fb5-142">Eine E-Mail-Vorlage ist eine vorformatierte E-Mail-Nachricht, mit der Sie schnell E-Mail-Nachrichten erstellen und senden können.</span><span class="sxs-lookup"><span data-stu-id="61fb5-142">An email template is a preformatted email message that allows you to quickly create and send email messages.</span></span> <span data-ttu-id="61fb5-143">Sie können den Text ändern und Ihre Änderungen dann in der aktuellen E-Mail-Vorlage speichern oder die Änderungen in einer neuen E-Mail-Vorlage speichern.</span><span class="sxs-lookup"><span data-stu-id="61fb5-143">You can modify the text, and then save your changes to the current email template or save the changes to a new email template.</span></span> <span data-ttu-id="61fb5-144">Wenn Sie keine andere Auswahl treffen, wird **Standardvorlage** für die Verwendung in einer E-Mail-Nachricht ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="61fb5-144">Unless you make another selection, **Default Template** is selected for use in an email message.</span></span> 

<span data-ttu-id="61fb5-145">Sie können diese Aktionen auf einer E-Mail-Vorlage durchführen:</span><span class="sxs-lookup"><span data-stu-id="61fb5-145">You can perform these actions on an email template:</span></span>

- <span data-ttu-id="61fb5-146">**Speichern**: Speichern Sie Ihre Änderungen an der aktuellen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="61fb5-146">**Save**: Save your changes to the current email template.</span></span>

- <span data-ttu-id="61fb5-147">**Speichern unter**: Speichern Sie Ihre Änderungen in einer neuen E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="61fb5-147">**Save as**: Save your changes to a new email template.</span></span>

- <span data-ttu-id="61fb5-148">**Löschen**: Löschen Sie die aktuelle E-Mail-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="61fb5-148">**Delete**: Delete the current email template.</span></span>

- <span data-ttu-id="61fb5-149">**Umbenennen**: Benennen Sie die aktuelle E-Mail-Vorlage um.</span><span class="sxs-lookup"><span data-stu-id="61fb5-149">**Rename**: Rename the current email template.</span></span>

> [!NOTE]
> <span data-ttu-id="61fb5-150">Sie können maximal 10 E-Mail-Vorlagen speichern.</span><span class="sxs-lookup"><span data-stu-id="61fb5-150">You can save a maximum of 10 email templates.</span></span>

## <a name="see-also"></a><span data-ttu-id="61fb5-151">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="61fb5-151">See also</span></span>

[<span data-ttu-id="61fb5-152">Definieren Sie, wer an einer Umfrage teilnehmen darf</span><span class="sxs-lookup"><span data-stu-id="61fb5-152">Define who can respond to a survey</span></span>](invite-settings.md)<br>
[<span data-ttu-id="61fb5-153">Senden Sie eine Umfrage mit Microsoft Flow</span><span class="sxs-lookup"><span data-stu-id="61fb5-153">Send a survey by using Microsoft Flow</span></span>](send-survey-microsoft-flow.md)<br>
[<span data-ttu-id="61fb5-154">Eingebettete Umfrage in eine Webseite</span><span class="sxs-lookup"><span data-stu-id="61fb5-154">Embed survey in a web page</span></span>](embed-web-page.md)<br>
[<span data-ttu-id="61fb5-155">Senden Sie einen Umfrage-Link an andere</span><span class="sxs-lookup"><span data-stu-id="61fb5-155">Send a survey link to others</span></span>](send-survey-link.md)<br>
[<span data-ttu-id="61fb5-156">Senden Sie eine Umfrage QR-Code</span><span class="sxs-lookup"><span data-stu-id="61fb5-156">Send a survey QR code</span></span>](send-survey-qrcode.md)
