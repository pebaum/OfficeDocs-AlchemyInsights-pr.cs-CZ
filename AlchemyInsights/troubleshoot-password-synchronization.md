---
title: Poradce při potížích s synchronizace hesel
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 1320c0fe839337188162824439be6f15f86b6c90
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30767169"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="59c6b-102">Poradce při potížích s synchronizace hesel</span><span class="sxs-lookup"><span data-stu-id="59c6b-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="59c6b-103">Řešení problémů, kde žádná hesla jsou synchronizované s Azure AD připojit verze 1.1.614.0 nebo novější:</span><span class="sxs-lookup"><span data-stu-id="59c6b-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="59c6b-104">Otevřete novou relaci prostředí Windows PowerShell na serveru Azure AD připojit pomocí možnosti **Spustit jako správce** .</span><span class="sxs-lookup"><span data-stu-id="59c6b-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span> 
    
2. <span data-ttu-id="59c6b-105">Spouštění **RemoteSigned zásady nastavení spouštění** nebo **neomezený zásady nastavení spouštění**.</span><span class="sxs-lookup"><span data-stu-id="59c6b-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span> 
    
3. <span data-ttu-id="59c6b-106">Spustíte Průvodce Azure AD připojit.</span><span class="sxs-lookup"><span data-stu-id="59c6b-106">Start the Azure AD Connect wizard.</span></span>
    
4. <span data-ttu-id="59c6b-107">Přejděte \*\* další úkoly \*\* vyberte \*\* poradce \*\* a klepněte na tlačítko **Další**.</span><span class="sxs-lookup"><span data-stu-id="59c6b-107">Navigate to the \*\* Additional Tasks \*\* page, select \*\* Troubleshoot \*\*, and click **Next**.</span></span> 
    
5. <span data-ttu-id="59c6b-108">Na stránce řešení potíží v nabídce **spuštění, chcete-li spustit Poradce při potížích** v prostředí PowerShell.</span><span class="sxs-lookup"><span data-stu-id="59c6b-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span> 
    
6. <span data-ttu-id="59c6b-109">V hlavní nabídce vyberte možnost **Poradce při potížích s synchronizace hesel**.</span><span class="sxs-lookup"><span data-stu-id="59c6b-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span> 
    
7. <span data-ttu-id="59c6b-110">V dílčí nabídce vyberte možnost **Synchronizace hesel nefunguje vůbec**.</span><span class="sxs-lookup"><span data-stu-id="59c6b-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span> 
    
 <span data-ttu-id="59c6b-111">**Porozumět výsledky řešení úloh**</span><span class="sxs-lookup"><span data-stu-id="59c6b-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="59c6b-112">Řešení úloh provádí následující kontroly:</span><span class="sxs-lookup"><span data-stu-id="59c6b-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="59c6b-113">Ověří, zda je povolena funkce Synchronizace hesel pro vašeho klienta Azure AD.</span><span class="sxs-lookup"><span data-stu-id="59c6b-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>
    
- <span data-ttu-id="59c6b-114">Ověří, že Azure AD připojit server není v režimu pracovní.</span><span class="sxs-lookup"><span data-stu-id="59c6b-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>
    
- <span data-ttu-id="59c6b-115">Pro každý existující místní konektor služby Active Directory (která odpovídá existující doménové struktuře služby Active Directory):</span><span class="sxs-lookup"><span data-stu-id="59c6b-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>
    
- 
  - <span data-ttu-id="59c6b-116">Ověří, zda je povolena funkce Synchronizace hesel.</span><span class="sxs-lookup"><span data-stu-id="59c6b-116">Validates that the password synchronization feature is enabled.</span></span>
    
  - <span data-ttu-id="59c6b-117">Hledá hesla synchronizace prezenční signál události v protokolu událostí aplikací systému Windows.</span><span class="sxs-lookup"><span data-stu-id="59c6b-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>
    
  - <span data-ttu-id="59c6b-118">Pro každou doménu služby Active Directory v rámci konektor služby Active Directory v prostorách:</span><span class="sxs-lookup"><span data-stu-id="59c6b-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>
    
  - <span data-ttu-id="59c6b-119">Ověří, že je dosažitelný z Azure AD připojit server k doméně.</span><span class="sxs-lookup"><span data-stu-id="59c6b-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>
    
  - <span data-ttu-id="59c6b-120">Ověří, zda účty služba Active Directory Domain Services (služba AD DS) používá konektor služby Active Directory v prostorách má správné uživatelské jméno, heslo a oprávnění nutná pro funkci Synchronizace hesel.</span><span class="sxs-lookup"><span data-stu-id="59c6b-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>
    
<span data-ttu-id="59c6b-121">Další pomoc s odstraňováním heslo synchronizace viz [Synchronizace hesel Poradce při potížích s synchronizace Azure AD připojit](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span><span class="sxs-lookup"><span data-stu-id="59c6b-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  

