---
title: Erstellen einer neuen Umfrage
description: Anweisungen zum Erstellen einer neuen Umfrage mit Forms Pro, zur Vermeidung von Phishing-Schutz, zum Einschränken von Inhalten, die in Antworten zulässig sind, und zum Markieren von Fragen zur Stimmungsanalyse
keywords: ''
author: sbmjais
ms.author: shjais
manager: shujoshi
applies_to: ''
ms.date: 01/16/2020
ms.service: forms-pro
ms.topic: article
ms.assetid: EA713CA9-6B0B-45A3-A700-22C164465411
ms.custom: ''
search.appverid:
- FPR160
ms.openlocfilehash: 743f5b74e3451030020a32dcfd548be44ae2f420
ms.sourcegitcommit: 38563d8ed7de1c1d1d54c2b5cbd2d46c52c2478a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2020
ms.locfileid: "3161388"
---
# <a name="create-a-new-survey"></a>Erstellen einer neuen Umfrage

Wenn Sie eine Umfrage erstellen, definieren Sie die Arten von Fragen, die Sie stellen möchten, um die Antwort eines Leser zu messen. Neben der Formulierung von Fragen müssen Sie zusätzliche Überlegungen berücksichtigen, die in diesem Thema behandelt werden, z. B. wie Sie vermeiden können, dass Ihre Umfrage durch Phishing-Prävention in Microsoft Forms Pro blockiert wird, wie Sie die gewünschten Antworten erhalten, indem Sie die Art der Antworten einschränken, die Sie in textbasierten Fragen zulassen, und ob Sie Antworten für die Stimmungsanalyse markieren möchten.

## <a name="create-a-new-survey-with-forms-pro"></a>Erstellen Sie eine neue Umfrage mit Forms Pro

1.  Melden Sie sich bei Forms Pro mit Ihren Office 365-Anmeldeinformationen an.

2.  Wählen Sie unter **Meine Formulare** die Option **Neue Pro-Umfrage**.

    > [!div class=mx-imgBorder]
    > ![Neue Umfrage](media/new-survey-button.png "Neue Umfrage")

3.  Wählen Sie den Standardumfragetitel aus und geben Sie einen Titel für Ihre Umfrage ein. Sie können auch eine optionale Beschreibung eingeben.

    > [!div class=mx-imgBorder]
    > ![Umfragetitel und -beschreibung hinzufügen](media/survey-title.png "Umfragetitel und -beschreibung hinzufügen") 

4.  Wählen Sie **Neu hinzufügen**, um Fragetypen anzuzeigen, die zu Ihrer Umfrage hinzugefügt werden können. Sie können aus **Auswahl**, **Text**, **Bewertung** oder **Datum** Fragen wählen. Sie können auch **Mehr** (...) auswählen und **Rangliste**, **Likert**, oder **Net Promoter Score** Fragen wählen.

    > [!div class=mx-imgBorder]
    > ![Fragetypen](media/ques-types.png "Fragetypen")

5.  Wählen Sie die Fragetypen aus, die Sie hinzufügen möchten.

6.  Geben Sie den Fragetext und seine Antwortoptionen ein. Die Umfrage wird automatisch gespeichert.

    > [!div class=mx-imgBorder]
    > ![Umfrage](media/survey.png "Beispiel für eine Umfrage mit unterschiedlichen Fragetypen")

7. Um die Reihenfolge der Fragen in der Umfrage zu ändern, wählen Sie eine Frage aus, und wählen Sie dann die Pfeile nach oben oder unten auf der rechten Seite jeder Frage, um sie nach oben oder unten zu verschieben.

8. Um eine Frage vor der Anzeige in der Umfrage zu verbergen, bewegen Sie den Schalter **Sichtbar** auf die Aus-Position. Standardmäßig ist diese Option immer aktiviert. Sie können die Frage dem Antwortenden anhand einer Verzweigungsregel zeigen. Weitere Informationen: [Erstellen einer Verzweigungsregel](create-branching-rule.md)

    > [!div class=mx-imgBorder]
    > ![Fragesichtbarkeit festlegen](media/visibility-option.png "Festlegen der Sichtbarkeit einer Frage")

> [!NOTE]
> - Sie können Ihre Umfrage personalisieren, indem Sie den Fragen benutzerdefinierte Daten hinzufügen. Weitere Informationen: [Personalisieren einer Umfrage](personalize-survey.md)
> - Sie können optional Formatierungen auf die Umfragetitel anwenden, wie z.B. Umfragetitel, Umfragebeschreibung, Fragetext und Frage-Untertitel. Weitere Informationen: [Text in einer Umfrage formatieren](survey-text-format.md)
> - Sie können das Aussehen Ihrer Umfrage anpassen, indem Sie Ihre eigene Formatierung auf Umfrageelemente wie Titel, Beschreibung, Fragen und Frageuntertitel anwenden. Weitere Informationen: [Text in einer Umfrage formatieren](survey-text-format.md)
> - Sie können ein klassisches Formular innerhalb von Forms Pro erstellen. Weitere Informationen: [Erstellen eines klassischen Formulars](create-classic-form.md)
> - Sie können auch Quizzes innerhalb von Forms Pro erstellen, um Echtzeit-Feedback zu erhalten. Weitere Informationen: [Erstellen eines Quiz mit Microsoft Forms](https://support.office.com/article/create-a-quiz-with-microsoft-forms-a082a018-24a1-48c1-b176-4b3616cdc83d)

<a name="proactive-phishing-prevention"></a>

## <a name="avoid-having-your-survey-blocked-by-forms-pro-phishing-prevention"></a>Vermeiden Sie es, dass Ihre Umfrage durch die Phishing-Prävention von Forms Pro blockiert wird

*Phishing-Angriffe* versuchen, vertrauliche Informationen durch E-Mails, Websites, Textnachrichten oder andere Formen der elektronischen Kommunikation zu stehlen, die offizielle Kommunikation von legitimen Unternehmen oder Einzelpersonen zu sein scheinen. Phisher versuchen oft, Passwörter oder andere Anmeldeinformationen zu stehlen.

In Forms Pro haben wir automatisierte Maschinenüberprüfungen aktiviert, um böswillige Kennworterfassung in Umfragen proaktiv zu erkennen.

### <a name="survey-designer-experience"></a>Umfragedesignerumgebung

Wenn Sie eine Umfrage entworfen haben, die Fragen enthält, bei denen ein Befragter sein Kennwort, seine Kontoinformationen oder andere Sicherheitsinformationen angeben muss, wird die Umfrage automatisch blockiert und kann nicht verteilt werden. Der Administrator erhält eine Benachrichtigung und eine Option zum Entsperren der Umfrage. Wenn die Sie die Umfrage verteilen möchten, müssen Sie Ihren Administrator kontaktieren, damit er sie entsperrt.

### <a name="administrator-experience"></a>Administratorerfahrung

Wenn eine Umfrage automatisch gesperrt wird, erhält der Administrator eine tägliche Benachrichtigung im **Nachrichtencenter** mit einer Option, die Umfrage zu entsperren. Weitere Informationen: [Überprüfen und Entsperren von Formularen, die auf potenzielles Phishing erkannt und blockiert wurden](https://support.office.com/article/review-and-unblock-forms-detected-and-blocked-for-potential-phishing-879a90d7-6ef9-4145-933a-fb53a430bced)

## <a name="add-restrictions-in-text-based-questions"></a>Hinzufügen von Einschränkungen in textbasierten Fragen

Wenn Sie eine textbasierte Frage (d. h. eine Frage vom Typ Text) erstellen, können Sie der Art der Antworten, die Sie von Ihren Befragten akzeptieren, Einschränkungen hinzufügen. Sie können ihre Antworten beispielsweise auf eine Zahl, eine E-Mail-Adresse oder eine [Zeichenfolge](https://docs.microsoft.com/dotnet/standard/base-types/regular-expression-language-quick-reference) in einem vordefinierten Format (basierend auf einem regulären Ausdruck) wie z. B. einer Buchungs-ID beschränken.

1. Wählen Sie in der textbasierten Frage **Weitere Einstellungen** (...) und wählen dann **Einschränkungen**.
2. Wählen Sie in der Liste eine der folgenden Optionen aus der Liste **Einschränkungen**:
    - **Zahl**: Akzeptieren Sie nur Eingaben im Zahlenformat. Sie können aus verschiedenen Optionen auswählen, z.B. **Nur Zahl**, **Größer als**, **Kleiner als**, **Zwischen**und andere.
    - **E-Mail**: Akzeptieren Sie nur Eingaben, die eine gültige E-Mail-Adresse sind.
    - **Benutzerdefiniert**: Definieren Sie einen regulären Ausdruck und akzeptieren Sie nur Eingaben, die mit dem definierten Ausdruck übereinstimmen. Sie können dem regulären Ausdruck auch eine optionale Beschreibung hinzufügen, die dem Benutzer das Format vorschlägt, in dem die Texteingabe erwartet wird. Angenommen, Sie möchten eine Zeichenbeschränkung für das Texteingabefeld definieren, die die Eingabe von bis zu 200 englischen Zeichen ermöglicht. Sie geben den regulären Ausdruck als `\b[A-Za-z0-9]{200}\b` ein.

## <a name="calculate-sentiments-from-responses-to-text-based-questions"></a>Berechnen von Stimmungen aus Antworten auf textbasierte Fragen

Mithilfe der Standpunktanalyse können Sie ermitteln, ob die Benutzerantworten für eine Umfrage positiv, neutral oder negativ sind. Berechnen von Stimmungen aus Antworten auf textbasierte Fragen, die Sie ausgewählt haben. Um textbasierte Fragen für die Standpunktanalyse auszuwählen, wechseln Sie zur textbasierten Frage und verschieben Sie den **Stimmungsumschalter** auf die Ein-Position. Standardmäßig ist diese Option immer deaktiviert. Wenn Sie keine textbasierte Frage für die Standpunktanalyse auswählen, werden keine Stimmungsdaten generiert.

### <a name="see-also"></a>Siehe auch

[Ein Design auf eine Umfrage anwenden](apply-theme.md)<br>
[Vorschau und Test einer Umfrage](preview-test-survey.md)<br>
[Erstellen einer Verzweigungsregel](create-branching-rule.md)<br>
[Personalisieren einer Umfrage](personalize-survey.md)<br>
[Text in einer Umfrage formatieren](survey-text-format.md)<br>
[Erstellen eins klassischen Formulars](create-classic-form.md)<br>
[Erstellen einer mehrsprachigen Umfrage](create-multilingual-survey.md)<br>
[Erstellen Sie eine mehrseitige Umfrage](create-multipage-survey.md)
