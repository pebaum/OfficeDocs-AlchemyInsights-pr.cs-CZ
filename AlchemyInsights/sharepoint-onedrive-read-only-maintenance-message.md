---
title: Zpráva jen pro čtení pro zprávu o údržbě při pokusu o použití služby SharePoint nebo OneDrive
ms.author: pebaum
author: pebaum
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
ms.openlocfilehash: 02cf1aa7abae365a3d317af9e785648d1c1517e1
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051274"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a><span data-ttu-id="7525b-102">Zpráva jen pro čtení pro zprávu o údržbě při pokusu o použití služby SharePoint nebo OneDrive</span><span class="sxs-lookup"><span data-stu-id="7525b-102">Read-Only for Maintenance message when attempting to use SharePoint or OneDrive</span></span>

<span data-ttu-id="7525b-103">Při pokusu o použití služby SharePoint nebo OneDrive pro jeden z následujících scénářů se uživatelům může zobrazit zpráva **o údržbě jen pro čtení** .</span><span class="sxs-lookup"><span data-stu-id="7525b-103">Users may receive a **Read-Only for Maintenance** message when attempting to use SharePoint or OneDrive for one of the following scenarios.</span></span> 

-   <span data-ttu-id="7525b-104">Plánovaná nebo aktivní aktivita údržby.</span><span class="sxs-lookup"><span data-stu-id="7525b-104">A planned or active maintenance activity.</span></span>  <span data-ttu-id="7525b-105">Vyhledejte je pomocí navigace do [centra zpráv](https://portal.office.com/adminportal/home#/messagecenter).</span><span class="sxs-lookup"><span data-stu-id="7525b-105">Check for them by navigating to the [Message Center](https://portal.office.com/adminportal/home#/messagecenter).</span></span>
-   <span data-ttu-id="7525b-106">Vysoce prioritní, aktivní servisní incident, který se může objevovat.</span><span class="sxs-lookup"><span data-stu-id="7525b-106">A high-priority, active service incident that may be occurring.</span></span> <span data-ttu-id="7525b-107">Vyhledejte všechny informační zpravodaje a incidenty přechodem na [stav služby](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="7525b-107">Check for any advisories/incidents by navigating to [Service Health](https://portal.office.com/adminportal/home#/servicehealth).</span></span>
-   <span data-ttu-id="7525b-108">Malý scénář zotavení s automatickým uzdravením, který by mohl být způsoben událostmi, které by mohly trvat méně než 30 min.</span><span class="sxs-lookup"><span data-stu-id="7525b-108">A minor auto-healing recovery scenario that could be happening due to any unexpected events on the servers which might last for less than 30 min or so.</span></span> 
    
    <span data-ttu-id="7525b-109">U těchto menších obnovení není k dispozici žádné Centrum zpráv ani příspěvky na stav služby, ale měli byste se brzy vrátit k normálu.</span><span class="sxs-lookup"><span data-stu-id="7525b-109">There are no Message Center or Service Health posts for these minor recoveries but you should be back to normal very soon.</span></span>

<span data-ttu-id="7525b-110">Během několika málo případů jsme si byli velmi dobře vypozorovali, že jeden ze tří výše uvedených scénářů byl příčinou a služba byla obnovena, ale mezipaměť uživatelů prohlížeče nebyla vymazána.</span><span class="sxs-lookup"><span data-stu-id="7525b-110">On very few occasions we observed that one of the three scenarios listed above have been the cause, and service has been restored, but the users browser cache hasn’t been cleared up.</span></span>

<span data-ttu-id="7525b-111">Před přechodem na web se pokuste vymazat mezipaměť prohlížeče.</span><span class="sxs-lookup"><span data-stu-id="7525b-111">Please attempt to clear the browser cache before navigating to the site.</span></span>

1. <span data-ttu-id="7525b-112">V prohlížeči Microsoft Edge klepněte na položku **Nastavení**a vyberte položku **Ochrana osobních údajů a zabezpečení**.</span><span class="sxs-lookup"><span data-stu-id="7525b-112">In your Microsoft Edge browser, select **Settings**, and then select **Privacy and Security**.</span></span>
2. <span data-ttu-id="7525b-113">V části **procházení s jasnou**volbou vyberte **položku, kterou chcete vymazat**.</span><span class="sxs-lookup"><span data-stu-id="7525b-113">Under **Clear browsing**, select **Choose what to clear**.</span></span>
3. <span data-ttu-id="7525b-114">Vyberte **soubory cookie a uložená data webu**a vyberte možnost **Vymazat**.</span><span class="sxs-lookup"><span data-stu-id="7525b-114">Select **Cookies and saved website data**, and select **Clear**.</span></span>

>[!Note] 
> <span data-ttu-id="7525b-115">Tyto kroky se mohou lišit v případě použití jiných prohlížečů, jako je Mozilla Firefox nebo Google Chrome.</span><span class="sxs-lookup"><span data-stu-id="7525b-115">These steps may differ when using other browsers such as Mozilla Firefox or Google Chrome.</span></span>

>[!Note] 
> <span data-ttu-id="7525b-116">Další možností je otevření webu služby SharePoint nebo funkce OneDrive v novém okně se službou InPrivate.</span><span class="sxs-lookup"><span data-stu-id="7525b-116">Another option would be to open your SharePoint site or OneDrive in a new InPrivate window.</span></span>