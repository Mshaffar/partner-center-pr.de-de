---
title: 'Umstellung auf Azure-Plan: Einstieg | Partner Center'
ms.topic: article
ms.date: 12/02/2019
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Hier erfahren Sie etwas über die Commerce-Funktionalität des Azure-Plans zum Kauf von Azure-Diensten zu nutzungsbasierten Tarifen für Kunden. Informieren Sie sich auch über die neuen Sicherheitsanforderungen.
author: LauraBrenner
ms.author: labrenne
Keywords: Azure, Azure-Plan, Abonnements erwerben, Abonnements
robots: ''
ms.localizationpriority: High
ms.openlocfilehash: 49807f982a75d55572e783c832896461b546cfd3
ms.sourcegitcommit: 449cb8c32880217ad7543712b02a84ae69869289
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2020
ms.locfileid: "74681934"
---
# <a name="move-to-azure-plan---get-started"></a>Umstellung auf Azure-Plan: Einstieg

Microsoft hat eine neue Commerce-Oberfläche in Partner Center eingeführt.  Mit dieser neuen Commerce-Funktionalität erhalten die Partner Zugriff auf Azure-Dienste zu nutzungsbasierten Tarifen im Rahmen des Microsoft-Kundenvertrags.

Dieser Plan vereinfacht den Kaufvorgang – Sie können mehrere Azure-Abonnements in einem Azure-Plan verwalten. Sie brauchen keine separate Bestellung pro Azure-Abonnement mehr zu übermitteln. Und im Rahmen dieser neuen Commerce-Funktionalität für Azure haben wir die Vereinheitlichung zu einem einzelnen Preisprinzip mit globaler Gültigkeit durchgeführt, das es CSP-Partnern ermöglicht, Azure zu den veröffentlichten Preisen anzubieten.

Die Anforderungen unserer Kunden an digitale Transformation erfordern neue Qualifikationen auf Seiten der Partner. Viele Kunden suchen nach Partnern, um Dienstleistungen jenseits der Transaktion anzubieten, um ihre Reise in der Cloud problemloser zu gestalten und sie bei der effizienten Nutzung von Azure-Diensten zu unterstützen. Microsoft-Partner spielen in allen Phasen des Kundenlebenszyklus eine entscheidende Rolle. Diese Arten von Partnerdiensten werden kontinuierlich angeboten und beinhalten Azure-Vermögensüberwachung, Richtlinien- und Governanceverwaltung, Setup und Optimieren der Konfiguration sowie eine Vielzahl weiterer Dienste. Sie erfordern einen Partner, der bestens mit der Azure-Umgebung des Kunden vertraut ist und fortlaufende und passende Governance und Steuerung über die von ihm verwalteten zugrunde liegenden Ressourcen besitzt. Abrechnungspartner, die diese Verwaltung des Cloudbetriebs rund um die Uhr bieten, sind im Rahmen dieser Arbeit zu **vom Partner erworbenen Gutschriften für verwaltete Dienste** qualifiziert.

## <a name="make-sure-your-customers-have-signed-the-microsoft-customer-agreement"></a>Vergewissern Sie sich, dass Ihre Kunden den Microsoft-Kundenvertrag unterzeichnet haben.

Ab dem 1. Oktober 2019 steht der Microsoft-Kundenvertrag zur Verfügung– ein unbefristeter Vertrag, der das Kauferlebnis des Kunden mit einem vollständig digitalen Prozess vereinfacht und optimiert. Alle Kunden, die die neue Commerce-Funktionalität in CSP für Azure nutzen möchten, müssen den Microsoft-Kundenvertrag unterzeichnen.

Partner, die unter dem neuen Azure-Plan Transaktionen durchführen und eine neue Bestellung aufgeben möchten, sollten die Zustimmung des Kunden zum Microsoft-Kundenvertrag über das Partner Center-Dashboard und die entsprechende API in der Produktionsumgebung bestätigen.

Ab dem 1. Februar 2020 wird der vorhandene Microsoft Cloud-Vertrag aus dem CSP-Programm entfernt. Ab diesem Zeitpunkt ist die Partnerbestätigung (Nachweis) der Kundenakzeptanz für den neuen Microsoft-Kundenvertrag für alle anderen Angebote erforderlich, einschließlich Microsoft 365, Dynamics 365 und vorhandenem Azure. Partner im CSP können keine neue Bestellung für den Kunden ohne Nachweis des Microsoft-Kundenvertrags aufgeben.

Vollständige Detailinformationen finden Sie unter [Bestätigen der Zustimmung des Kunden zum Microsoft-Kundenvertrag](confirm-customer-agreement.md)

## <a name="security-and-access-control-practices"></a>Sicherheits- und Zugriffssteuerungs-Verfahren

Zum Schutz von Partnern und Kunden führen wir eine Reihe von verbindlichen Sicherheitsanforderungen für Berater, Control Panel-Anbieter und Partner ein, die am Cloud Solution Provider-Programm teilnehmen.

Partner, die die obligatorischen Sicherheitsanforderungen nicht implementieren, werden nicht in der Lage sein, im Cloud Solution Provider-Programm zu agieren oder Kundenmandanten mit delegierten Administratorrechten zu verwalten, sobald diese Anforderungen durchgesetzt sind. Wir sind dabei, einen Termin für die technische Durchsetzung der Anforderungen festzulegen und werden die Partner mit detaillierten Informationen zu diesem Termin benachrichtigen.

## <a name="actions-to-take-to-implement-mfa"></a>Erforderliche Aktionen zum Implementieren der MFA

Angesichts der privilegierten Natur der Partner müssen wir sicherstellen, dass jeder Benutzer für jede einzelne Authentifizierung über eine MFA-Herausforderung verfügt. Dies kann auf eine der folgenden Arten erreicht werden:

- Implementieren von Azure AD Premium und Sicherstellen, dass die mehrstufige Authentifizierung (Multi-Factor-Authentication, MFA) für jeden Benutzer erzwungen wird
- Implementieren der [Azure AD-Sicherheitsstandards](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-security-defaults)
- Implementieren der Lösung eines Drittanbieters und Sicherstellen, dass MFA für jeden Benutzer erzwungen wird

Seit dem 1. August 2019 sind alle Partner verpflichtet, die mehrstufige Authentifizierung für alle Benutzer, einschließlich Dienstkonten, in ihrem Partnermandanten durchzusetzen. Detailinformationen zu diesen Sicherheitsanforderungen finden Sie unter [Sicherheitsanforderungen für Partner](https://docs.microsoft.com/partner-center/partner-security-requirements).

Microsoft empfiehlt Partnern eine sorgfältige Nutzung von RBAC unter Berücksichtigung der empfohlenen Methoden, die in Form der [Azure Active Directory-Ressourcen zur privilegierten Identitätsverwaltung](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/pim-configure) zur Verfügung stehen.

## <a name="read-more-about-the-azure-plan"></a>Weitere Informationen zum Azure-Plan

- [Erwerb des Azure-Plans](purchase-azure-plan.md)

- [Vergleich von Azure-Angeboten](compare-azure-offers.md)

- [Vom Partner erworbenes Guthaben – Übersicht](partner-earned-credit.md)

- Die Berechnung des vom Partner erworbenen Guthabens (Partner-Earned Credit, PEC) und die Rollen und Berechtigungen, die zu deren Erwerb qualifizieren, stehen in der Preisliste in Ihrem Partner Center-Dashboard zur Verfügung (Anmeldung erforderlich).

- [Wie von Partnern erworbene Guthaben berechnet werden – Details](partner-earned-credit-explanation.md)
- [Erläuterungen zur Azure-Plan-Preisliste](azure-plan-price-list.md)
- [Umstellung Ihrer Kunden auf einen Azure-Plan](azure-plan-transition.md)
- [Verwalten von Abonnements und Ressourcen in einem Azure-Plan](azure-plan-manage.md)
- [Die vollständige Liste der Länder/Regionien, in denen Azure-Plan verfügbar ist](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3QN0x)
