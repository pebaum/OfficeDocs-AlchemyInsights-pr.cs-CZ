---
title: 'AIP: Politiky se nechovají podle očekávání'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002266"
- "4780"
ms.openlocfilehash: 527556fcb02525eb88ea992c38a2ddfcba6f9453
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506551"
---
# <a name="aip-policies-not-behaving-as-expected"></a><span data-ttu-id="8e09c-102">AIP: Politiky se nechovají podle očekávání</span><span class="sxs-lookup"><span data-stu-id="8e09c-102">AIP: Policies not behaving as expected</span></span>

<span data-ttu-id="8e09c-103">Azure Information Protection: Zásady, které se nechovají očekávaným způsobem, naleznete v následujících tématech doporučené pokyny pro různé problémy se zásadami:</span><span class="sxs-lookup"><span data-stu-id="8e09c-103">Azure Information Protection: Policies not behaving as expected, see the following for recommended guidelines for various policy issues:</span></span>

1. <span data-ttu-id="8e09c-104">Pokud máte problémy s vizuálním značením, přečtěte si [prosím, kdy jsou použita vizuální označení](https://docs.microsoft.com/azure/information-protection/configure-policy-markings#when-visual-markings-are-applied).</span><span class="sxs-lookup"><span data-stu-id="8e09c-104">If you are having issues with visual markings, please review [When visual markings are applied](https://docs.microsoft.com/azure/information-protection/configure-policy-markings#when-visual-markings-are-applied).</span></span>
2. <span data-ttu-id="8e09c-105">Pokud máte problémy s automatickým popisováním, přečtěte si [postup konfigurace podmínek pro automatickou a doporučenou klasifikaci pro Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) a co [vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span><span class="sxs-lookup"><span data-stu-id="8e09c-105">If you are having issues with automatic labeling, please review [How to configure conditions for automatic and recommended classification for Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) and [What the sensitive information types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span></span>
3. <span data-ttu-id="8e09c-106">Pokud máte problémy s ochranou nativní/pfile, zkontrolujte [konfiguraci rozhraní API souboru](https://docs.microsoft.com/azure/information-protection/develop/file-api-configuration).</span><span class="sxs-lookup"><span data-stu-id="8e09c-106">If you are having issues with Native/Pfile protection, please review [File API configuration](https://docs.microsoft.com/azure/information-protection/develop/file-api-configuration).</span></span>
4. <span data-ttu-id="8e09c-107">Zkontrolujte, jestli používáte zásady s vymezeným oborem, které nejsou správně nakonfigurovány: [Jak nakonfigurovat zásady Ochrany informací Azure pro konkrétní uživatele pomocí zásad s vymezeným oborem](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).</span><span class="sxs-lookup"><span data-stu-id="8e09c-107">Check if you are using scoped policies that aren't configured properly: [How to configure the Azure Information Protection policy for specific users by using scoped policies](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).</span></span>
5. <span data-ttu-id="8e09c-108">Pokud automatické popisování nefunguje pro aplikaci Outlook při připojování dokumentu s popiskem, ověřte, zda drmencryptProperty není definována, jak je popsáno zde: [Nastavení registru IRM pro zabezpečení](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).</span><span class="sxs-lookup"><span data-stu-id="8e09c-108">If automatic labeling isn't working for Outlook when attaching a labeled document, verify that DRMEncryptProperty isn't defined as described here: [IRM registry settings for security](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).</span></span>

<span data-ttu-id="8e09c-109">Pokud stále dochází k problémům, shromažďovat protokoly klientů Azure Information Protection a připojit exportované protokoly k tomuto lístku.</span><span class="sxs-lookup"><span data-stu-id="8e09c-109">If you still are experiencing issues, please collect Azure Information Protection client logs and attach the exported logs to this ticket.</span></span>

1. <span data-ttu-id="8e09c-110">Otevřete dokument Office nebo vytvořte nový e-mail v Outlooku.</span><span class="sxs-lookup"><span data-stu-id="8e09c-110">Open an Office document or create a new email in Outlook.</span></span>
2. <span data-ttu-id="8e09c-111">Klepněte na tlačítko **Chránit/citlivost**  >  **nápovědy a zpětné vazby**.</span><span class="sxs-lookup"><span data-stu-id="8e09c-111">Click **Protect/Sensitivity** > **Help and feedback**.</span></span>
3. <span data-ttu-id="8e09c-112">Klepněte na **položku Exportovat protokoly**.</span><span class="sxs-lookup"><span data-stu-id="8e09c-112">Click **Export Logs**.</span></span>
4. <span data-ttu-id="8e09c-113">Uložte protokoly do zvoleného umístění a připojte je k této žádosti o službu.</span><span class="sxs-lookup"><span data-stu-id="8e09c-113">Save the logs to your choice of location, and attach them to this service request.</span></span>

<span data-ttu-id="8e09c-114">Další zdroje informací:</span><span class="sxs-lookup"><span data-stu-id="8e09c-114">Additional resources:</span></span>

- [<span data-ttu-id="8e09c-115">Konfigurace popisku pro vizuální označení pro Azure Information Protection</span><span class="sxs-lookup"><span data-stu-id="8e09c-115">How to configure a label for visual markings for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/configure-policy-markings)
- [<span data-ttu-id="8e09c-116">Kontrola dokumentace ochrany informací Azure</span><span class="sxs-lookup"><span data-stu-id="8e09c-116">Review Azure Information Protection documentation</span></span>](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [<span data-ttu-id="8e09c-117">Použití štítků citlivosti v aplikacích Office</span><span class="sxs-lookup"><span data-stu-id="8e09c-117">Use sensitivity labels in Office apps</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels-office-apps)

