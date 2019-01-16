---
title: Aktualizace záznamů DNS tak, aby web zůstal u současného poskytovatele hostingu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: a79302259e294ea5bf3b1d29393a412edb27a388
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281381"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a><span data-ttu-id="18ad5-102">Aktualizace záznamů DNS tak, aby web zůstal u současného poskytovatele hostingu</span><span class="sxs-lookup"><span data-stu-id="18ad5-102">Update DNS records to keep your website with your current hosting provider</span></span>

1. <span data-ttu-id="18ad5-103">Na stránce [Domény](https://portal.office.com/adminportal/home#/Domains) vyberte v seznamu domén doménu, kterou používáte pro svůj web, a potom v podokně správy vyberte **Nastavení DNS**.</span><span class="sxs-lookup"><span data-stu-id="18ad5-103">On the [Domains](https://portal.office.com/adminportal/home#/Domains) page, in the list of domains, select the domain you're using for your website, and then select **DNS settings** in the management pane.</span></span> 
    
2. <span data-ttu-id="18ad5-104">Vyberte **+ Nový vlastní záznam** a zadejte tyto údaje:</span><span class="sxs-lookup"><span data-stu-id="18ad5-104">Select **+ New custom record** and enter the following:</span></span> 
    
  - <span data-ttu-id="18ad5-105">Pro **Typ DNS** zadejte: **A (adresa)**</span><span class="sxs-lookup"><span data-stu-id="18ad5-105">For **DNS type** enter: **A (Address)**</span></span>
    
  - <span data-ttu-id="18ad5-106">Jako **Název hostitele nebo alias** zadejte tento symbol: **@**</span><span class="sxs-lookup"><span data-stu-id="18ad5-106">For **Host name or Alias**, type the following: **@**</span></span>
    
  - <span data-ttu-id="18ad5-107">Do pole **IP adresa** zadejte statickou IP adresu, na které je váš web právě hostovaný (třeba 172.16.140.1).</span><span class="sxs-lookup"><span data-stu-id="18ad5-107">For **IP Address**, type the static IP address for your website where it's currently hosted (for example, 172.16.140.1).</span></span> 
    
    <span data-ttu-id="18ad5-p101">Je nutné, aby to byla  *statická*  IP adresa webu, ne  *dynamická*  IP adresa. Na serveru, kde je web hostovaný, se ujistěte, že pro svůj veřejný web můžete získat statickou IP adresu.</span><span class="sxs-lookup"><span data-stu-id="18ad5-p101">This must be a  *static*  IP address for the website, not a  *dynamic*  IP address. Check with site where your website is hosted to make sure you can get a static IP address for your public website.</span></span> 
    
3. <span data-ttu-id="18ad5-110">Vyberte **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="18ad5-110">Select **Save**.</span></span> 
    
<span data-ttu-id="18ad5-111">Kromě toho můžete vytvořit záznam CNAME, který zákazníkům pomůže váš web najít.</span><span class="sxs-lookup"><span data-stu-id="18ad5-111">In addition, you can create a CNAME record to help customers find your website.</span></span>
  
1. <span data-ttu-id="18ad5-112">Vyberte **+ Nový vlastní záznam** a zadejte tyto údaje:</span><span class="sxs-lookup"><span data-stu-id="18ad5-112">Select **+ New custom record** and enter the following:</span></span> 
    
  - <span data-ttu-id="18ad5-113">Pro **Typ DNS** zadejte: **CNAME (alias)**</span><span class="sxs-lookup"><span data-stu-id="18ad5-113">For **DNS type** enter: **CNAME (Alias)**</span></span>
    
  - <span data-ttu-id="18ad5-114">Do **Název hostitele nebo alias** zadejte: **www**</span><span class="sxs-lookup"><span data-stu-id="18ad5-114">For **Host name or Alias**, type the following: **www**</span></span>
    
  - <span data-ttu-id="18ad5-115">Do pole **Ukazatel na adresu** zadejte plně kvalifikovaný název domény pro svůj web (třeba contoso.com).</span><span class="sxs-lookup"><span data-stu-id="18ad5-115">For **Points to address**, type the fully qualified domain name (FQDN) for your website (for example, contoso.com).</span></span> 
    
2. <span data-ttu-id="18ad5-116">Vyberte **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="18ad5-116">Select **Save**.</span></span> 
    

