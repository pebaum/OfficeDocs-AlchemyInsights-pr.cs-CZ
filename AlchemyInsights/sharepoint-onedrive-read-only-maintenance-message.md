---
title: Jen pro čtení pro údržbu zpráva při pokusu o použití služby SharePoint nebo OneDrive
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: 5b1e56253d6deeb0f9ba2f753eff5c00ff9c51a2
ms.sourcegitcommit: cd79ecca88b2cb166f78f44ab8bc4e8136729418
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/23/2019
ms.locfileid: "36620716"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a><span data-ttu-id="0c049-102">Jen pro čtení pro údržbu zpráva při pokusu o použití služby SharePoint nebo OneDrive</span><span class="sxs-lookup"><span data-stu-id="0c049-102">Read-Only for Maintenance message when attempting to use SharePoint or OneDrive</span></span>

<span data-ttu-id="0c049-103">Uživatelé obdržet zprávu **Pro údržbu jen pro čtení** při pokusu o použití služby SharePoint nebo OneDrive pro jeden z následujících scénářů.</span><span class="sxs-lookup"><span data-stu-id="0c049-103">Users may receive a **Read-Only for Maintenance** message when attempting to use SharePoint or OneDrive for one of the following scenarios.</span></span> 

-   <span data-ttu-id="0c049-104">Aktivní nebo plánované údržby aktivity.</span><span class="sxs-lookup"><span data-stu-id="0c049-104">A planned or active maintenance activity.</span></span>  <span data-ttu-id="0c049-105">Kontrola je tak, že přejdete do [Centra zpráv](https://portal.office.com/adminportal/home#/messagecenter).</span><span class="sxs-lookup"><span data-stu-id="0c049-105">Check for them by navigating to the [Message Center](https://portal.office.com/adminportal/home#/messagecenter).</span></span>
-   <span data-ttu-id="0c049-106">Nejdůležitější, služby active incident, který se může vyskytovat.</span><span class="sxs-lookup"><span data-stu-id="0c049-106">A high-priority, active service incident that may be occurring.</span></span> <span data-ttu-id="0c049-107">Zkontrolujte všechny zpravodaje incidenty přechodem do [Stavu služby](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="0c049-107">Check for any advisories/incidents by navigating to [Service Health](https://portal.office.com/adminportal/home#/servicehealth).</span></span>
-   <span data-ttu-id="0c049-108">Vedlejší automatický retušovací obnovení scénář, který by mohl děje z důvodu nečekaných událostí na serverech, které může trvat méně než 30 min nebo tak.</span><span class="sxs-lookup"><span data-stu-id="0c049-108">A minor auto-healing recovery scenario that could be happening due to any unexpected events on the servers which might last for less than 30 min or so.</span></span> 
    
    <span data-ttu-id="0c049-109">Neexistují žádné zprávy centrum nebo zdravotní služby účtuje tyto menší výtěžnost, ale zpět na normální velikost by měla být velmi brzy.</span><span class="sxs-lookup"><span data-stu-id="0c049-109">There are no Message Center or Service Health posts for these minor recoveries but you should be back to normal very soon.</span></span>

<span data-ttu-id="0c049-110">Ve velmi málo případech můžeme pozorovat jeden z výše uvedených tří scénářů byly příčinou a obnovil službu ale nebylo zrušeno mezipaměti prohlížeče uživatele.</span><span class="sxs-lookup"><span data-stu-id="0c049-110">On very few occasions we observed that one of the three scenarios listed above have been the cause, and service has been restored, but the users browser cache hasn’t been cleared up.</span></span>

<span data-ttu-id="0c049-111">Pokuste se vymazat mezipaměť prohlížeče před navigací na webu.</span><span class="sxs-lookup"><span data-stu-id="0c049-111">Please attempt to clear the browser cache before navigating to the site.</span></span>

1. <span data-ttu-id="0c049-112">V prohlížeči Microsoft Edge vyberte **Nastavení**a vyberte **zabezpečení a ochrana osobních údajů**.</span><span class="sxs-lookup"><span data-stu-id="0c049-112">In your Microsoft Edge browser, select **Settings**, and then select **Privacy and Security**.</span></span>
2. <span data-ttu-id="0c049-113">V části **Procházení zrušte**vyberte **Zvolte, co chcete vymazat**.</span><span class="sxs-lookup"><span data-stu-id="0c049-113">Under **Clear browsing**, select **Choose what to clear**.</span></span>
3. <span data-ttu-id="0c049-114">Vyberte **soubory cookie a data webu uložené**a vyberte **Vymazat**.</span><span class="sxs-lookup"><span data-stu-id="0c049-114">Select **Cookies and saved website data**, and select **Clear**.</span></span>

>[!Note] 
> <span data-ttu-id="0c049-115">Takto se může lišit, pokud používáte jiné prohlížeče jako Mozilla Firefox nebo Google Chrome.</span><span class="sxs-lookup"><span data-stu-id="0c049-115">These steps may differ when using other browsers such as Mozilla Firefox or Google Chrome.</span></span>

>[!Note] 
> <span data-ttu-id="0c049-116">Další možností by bylo otevřít web služby SharePoint nebo OneDrive v nové okno InPrivate.</span><span class="sxs-lookup"><span data-stu-id="0c049-116">Another option would be to open your SharePoint site or OneDrive in a new InPrivate window.</span></span>