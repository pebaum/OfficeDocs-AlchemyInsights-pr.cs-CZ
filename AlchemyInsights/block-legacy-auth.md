---
title: BlockLegacyAuth
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3154"
- "9001194"
ms.openlocfilehash: e7bff5f9fcf6f2f2c77e93c2f27f585f2cc18bea
ms.sourcegitcommit: 98231a228ecb2bf14ec3b96d4dd4ccf2507617a3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/01/2020
ms.locfileid: "43079253"
---
# <a name="blocking-legacy-authentication"></a><span data-ttu-id="45e29-102">Blokování staršíverze ověřování</span><span class="sxs-lookup"><span data-stu-id="45e29-102">Blocking legacy authentication</span></span>

<span data-ttu-id="45e29-103">Starší verze ověřování je termín, který odkazuje na požadavek na ověření ze strany:</span><span class="sxs-lookup"><span data-stu-id="45e29-103">Legacy authentication is a term that refers to an authentication request made by:</span></span>

- <span data-ttu-id="45e29-104">Starší klienti Office, kteří nepoužívají moderní ověřování (například klient Office 2010).</span><span class="sxs-lookup"><span data-stu-id="45e29-104">Older Office clients that do not use modern authentication (for example, Office 2010 client).</span></span>

- <span data-ttu-id="45e29-105">Každý klient, který používá starší poštovní protokoly, například IMAP/SMTP/POP3.</span><span class="sxs-lookup"><span data-stu-id="45e29-105">Any client that uses legacy mail protocols such as IMAP/SMTP/POP3.</span></span>

<span data-ttu-id="45e29-106">Další informace o blokování staršíverze ověřování a povolení moderníověřování naleznete [v průvodní verze ověřování](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication).</span><span class="sxs-lookup"><span data-stu-id="45e29-106">For more information on blocking legacy authentication and enabling modern authentication, refer to [Blocking legacy authentication](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication).</span></span>

<span data-ttu-id="45e29-107">Výchozí nastavení zabezpečení ve službě Azure Active Directory (Azure AD) usnadňují zabezpečení a pomáhají chránit vaši organizaci.</span><span class="sxs-lookup"><span data-stu-id="45e29-107">Security defaults in Azure Active Directory (Azure AD) make it easier to be secure and help protect your organization.</span></span> <span data-ttu-id="45e29-108">Výchozí hodnoty zabezpečení obsahují předem nakonfigurovaná nastavení zabezpečení pro běžné útoky.</span><span class="sxs-lookup"><span data-stu-id="45e29-108">Security defaults contain preconfigured security settings for common attacks.</span></span>
<span data-ttu-id="45e29-109">Další informace o výchozích hodnotách zabezpečení naleznete v odkazech [Co jsou výchozí hodnoty zabezpečení?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults).</span><span class="sxs-lookup"><span data-stu-id="45e29-109">For more information about security defaults, refer to [What are security defaults?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults).</span></span> 

<span data-ttu-id="45e29-110">**Poznámka:** Pokud váš tenant byl vytvořen na nebo po 22.12.2019, je možné, že dochází k nové chování zabezpečené ve výchozím nastavení a již mají výchozí nastavení zabezpečení povoleno ve vašem tenantovi.</span><span class="sxs-lookup"><span data-stu-id="45e29-110">**Note**:  If your tenant was created on or after October 22nd, 2019, it's possible you are experiencing the new secure-by-default behavior and already have security defaults enabled in your tenant.</span></span>  <span data-ttu-id="45e29-111">Ve snaze chránit všechny naše uživatele, výchozí zabezpečení se zavádí do všech nových klientů vytvořených.</span><span class="sxs-lookup"><span data-stu-id="45e29-111">In an effort to protect all of our users, security defaults is being rolled out to all new tenants created.</span></span>
