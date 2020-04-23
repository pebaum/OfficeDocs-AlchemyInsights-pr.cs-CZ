---
title: Poradce při potížích se synchronizací hesel
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: edd4f68466296f72c2dc0bafda45e6749d62d942
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43732503"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="f25f4-102">Poradce při potížích se synchronizací hesel</span><span class="sxs-lookup"><span data-stu-id="f25f4-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="f25f4-103">Řešení problémů, kdy se žádná hesla synchronizují s Azure AD Connect verze 1.1.614.0 nebo novějším:</span><span class="sxs-lookup"><span data-stu-id="f25f4-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="f25f4-104">Otevřete novou relaci prostředí Windows PowerShell na serveru Azure AD Connect s možností **Spustit jako správce.**</span><span class="sxs-lookup"><span data-stu-id="f25f4-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span>

2. <span data-ttu-id="f25f4-105">Spuštění **zásad vzdáleného podpisu set-executionpolicy** nebo **zásady spuštění bez omezení**.</span><span class="sxs-lookup"><span data-stu-id="f25f4-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span>

3. <span data-ttu-id="f25f4-106">Spusťte Průvodce připojením Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="f25f4-106">Start the Azure AD Connect wizard.</span></span>

4. <span data-ttu-id="f25f4-107">Přejděte na stránku **Další úkoly,** vyberte **Poradce při potížích**a klepněte na tlačítko **Další**.</span><span class="sxs-lookup"><span data-stu-id="f25f4-107">Navigate to the **Additional Tasks** page, select **Troubleshoot**, and click **Next**.</span></span>

5. <span data-ttu-id="f25f4-108">Na stránce Poradce při potížích klikněte na **Spustit a spusťte nabídku řešení potíží** v PowerShellu.</span><span class="sxs-lookup"><span data-stu-id="f25f4-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span>

6. <span data-ttu-id="f25f4-109">V hlavní nabídce vyberte **Poradce při potížích se synchronizací hesel**.</span><span class="sxs-lookup"><span data-stu-id="f25f4-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span>

7. <span data-ttu-id="f25f4-110">V dílčí nabídce vyberte **synchronizace hesel nefunguje vůbec**.</span><span class="sxs-lookup"><span data-stu-id="f25f4-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span>

<span data-ttu-id="f25f4-111">**Vysvětlení výsledků úlohy řešení potíží**</span><span class="sxs-lookup"><span data-stu-id="f25f4-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="f25f4-112">Úloha řešení potíží provádí následující kontroly:</span><span class="sxs-lookup"><span data-stu-id="f25f4-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="f25f4-113">Ověří, že funkce synchronizace hesel je povolená pro vašeho klienta Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f25f4-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>

- <span data-ttu-id="f25f4-114">Ověří, že server Azure AD Connect není v pracovním režimu.</span><span class="sxs-lookup"><span data-stu-id="f25f4-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>

- <span data-ttu-id="f25f4-115">Pro každý existující místní konektor služby Active Directory (který odpovídá existující doménové struktuře služby Active Directory):</span><span class="sxs-lookup"><span data-stu-id="f25f4-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>

- 
  - <span data-ttu-id="f25f4-116">Ověří, zda je povolena funkce synchronizace hesel.</span><span class="sxs-lookup"><span data-stu-id="f25f4-116">Validates that the password synchronization feature is enabled.</span></span>

  - <span data-ttu-id="f25f4-117">Vyhledá události prezenčního signálu synchronizace hesel v protokolech událostí aplikace systému Windows.</span><span class="sxs-lookup"><span data-stu-id="f25f4-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>

  - <span data-ttu-id="f25f4-118">Pro každou doménu služby Active Directory v místním konektoru služby Active Directory:</span><span class="sxs-lookup"><span data-stu-id="f25f4-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>

  - <span data-ttu-id="f25f4-119">Ověří, že doména je dosažitelná ze serveru Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="f25f4-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>

  - <span data-ttu-id="f25f4-120">Ověří, zda účty služby AD DS používané místním konektorem služby Active Directory mají správné uživatelské jméno, heslo a oprávnění vyžadovaná pro synchronizaci hesel.</span><span class="sxs-lookup"><span data-stu-id="f25f4-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>

<span data-ttu-id="f25f4-121">Další nápovědu k řešení potíží se synchronizací hesel [najdete v tématu Poradce při potížích se synchronizací hesel pomocí synchronizace služby Azure AD Connect](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span><span class="sxs-lookup"><span data-stu-id="f25f4-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  