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
# <a name="private-channels-in-microsoft-teams"></a>Soukromé kanály v Microsoft Teams

Soukromé kanály jsou v Microsoft Teams novou funkcí. Všimněte si, že soukromé kanály nelze převést ze standardních kanálů nebo naopak.

Podrobnosti o soukromých kanálech, jako jsou informace o [vytváření a členství v privátním kanálu](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) a [soukromých webech služby SharePoint](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), naleznete [v tématu Soukromé kanály v Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/private-channels). 

**Poznámka:** Vzhledem k tomu, že konfigurace pro uchovávání zpráv soukromých kanálů ještě není podporována, klienti s povolenými zásadami uchovávání informací nebudou mít ve výchozím nastavení povoleny soukromé kanály. Soukromé kanály můžou být povolené v Centru pro správu Teams. Všimněte si také, že zatímco uchovávání zpráv soukromých kanálů není podporováno, je podporováno uchovávání souborů sdílených v soukromých kanálech.

**Potřebujete nového majitele týmu?**

Pokud váš vlastník soukromého kanálu odejde, můžete přidat nového vlastníka týmu přes Teams Powershell.


- Přejděte [sem](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) a nainstalujte Teams Powershell.

Zde je rutina, kterou budete potřebovat:

`
    Add-TeamChannelUser -GroupId <group_id> -DisplayName "<channel_name>" -User <UPN> -Role Owner
`

Další informace o Teams Powershellu najdete v [tématu Přehled teams powershellu](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).
