---
title: Soukromý kanál
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001223"
- "3205"
ms.openlocfilehash: be518df0d40123c1f0da6596bd6e2e91a0c2c8fa
ms.sourcegitcommit: 057d87c9d866fa1371d02350420d13774545c028
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/02/2020
ms.locfileid: "44005431"
---
# <a name="private-channels-in-microsoft-teams"></a><span data-ttu-id="6284d-102">Soukromé kanály v Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6284d-102">Private channels in Microsoft Teams</span></span>

<span data-ttu-id="6284d-103">Soukromé kanály jsou v Microsoft Teams novou funkcí.</span><span class="sxs-lookup"><span data-stu-id="6284d-103">Private channels is a new feature in Microsoft Teams.</span></span> <span data-ttu-id="6284d-104">Všimněte si, že soukromé kanály nelze převést ze standardních kanálů nebo naopak.</span><span class="sxs-lookup"><span data-stu-id="6284d-104">Note that private channels cannot be converted from standard channels or vice versa.</span></span>

<span data-ttu-id="6284d-105">Podrobnosti o soukromých kanálech, jako jsou informace o [vytváření a členství v privátním kanálu](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) a [soukromých webech služby SharePoint](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), naleznete [v tématu Soukromé kanály v Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/private-channels).</span><span class="sxs-lookup"><span data-stu-id="6284d-105">For details about private channels, such as information on [private channel creation and membership](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) and [private channel SharePoint sites](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), see [Private channels in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/private-channels).</span></span> 

<span data-ttu-id="6284d-106">**Poznámka:** Vzhledem k tomu, že konfigurace pro uchovávání zpráv soukromých kanálů ještě není podporována, klienti s povolenými zásadami uchovávání informací nebudou mít ve výchozím nastavení povoleny soukromé kanály.</span><span class="sxs-lookup"><span data-stu-id="6284d-106">**Note:** Because configuration for retention of private channel messages is not yet supported, tenants with retention policies enabled will not have private channels enabled by default.</span></span> <span data-ttu-id="6284d-107">Soukromé kanály můžou být povolené v Centru pro správu Teams.</span><span class="sxs-lookup"><span data-stu-id="6284d-107">Private channels can be enabled in the Teams admin center.</span></span> <span data-ttu-id="6284d-108">Všimněte si také, že zatímco uchovávání zpráv soukromých kanálů není podporováno, je podporováno uchovávání souborů sdílených v soukromých kanálech.</span><span class="sxs-lookup"><span data-stu-id="6284d-108">Also, note that while retention of private channel messages is not supported, retention of files shared in private channels is supported.</span></span>

<span data-ttu-id="6284d-109">**Potřebujete nového majitele týmu?**</span><span class="sxs-lookup"><span data-stu-id="6284d-109">**Need a new team owner?**</span></span>

<span data-ttu-id="6284d-110">Pokud váš vlastník soukromého kanálu odejde, můžete přidat nového vlastníka týmu přes Teams Powershell.</span><span class="sxs-lookup"><span data-stu-id="6284d-110">If your private channel owner leaves, you can add a new team owner via Teams Powershell.</span></span>


- <span data-ttu-id="6284d-111">Přejděte [sem](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) a nainstalujte Teams Powershell.</span><span class="sxs-lookup"><span data-stu-id="6284d-111">Go [here](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) to install Teams Powershell.</span></span>

<span data-ttu-id="6284d-112">Zde je rutina, kterou budete potřebovat:</span><span class="sxs-lookup"><span data-stu-id="6284d-112">Here is the cmdlet you will need:</span></span>

`
    Add-TeamChannelUser -GroupId <group_id> -DisplayName "<channel_name>" -User <UPN> -Role Owner
`

<span data-ttu-id="6284d-113">Další informace o Teams Powershellu najdete v [tématu Přehled teams powershellu](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="6284d-113">For more information on Teams Powershell, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span>
