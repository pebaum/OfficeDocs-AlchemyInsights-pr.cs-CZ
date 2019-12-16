---
title: Výměna klasického kořenového webu s moderním webem
ms.author: pebaum
author: pebaum
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: fe1f0f662c49de2bd0b5b997697c98309cb7983f
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40042920"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a>Výměna klasického kořenového webu s moderním webem

Pokud bylo prostředí nastaveno do dubna 2019, můžete pomocí prostředí Microsoft PowerShell změnit kořenový web na moderní web:

- Pokud máte jiný web, který chcete použít jako kořenový web, můžete nahradit [(vyměnit) kořenový web](https://docs.microsoft.com/sharepoint/modern-root-site) . 
    - Pomocí metody [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) můžete při archivaci původního webu zaměnit umístění webu s jiným webem. K dispozici pro týmový web (není připojen ke skupině) a komunikační Web. 

- Další možnosti budou zavedeny brzy, což vám umožní nadále používat obsah webu, ale převést existující web na komunikační Web. 
>[!Important]
>Tyto možnosti budou postupně vyvráceny. Pokračujte v kontrole centra zpráv sady Office 365 pro aktualizace. 

## <a name="known-issues-with-swapping-sites"></a>Známé problémy s odkládání webů

- Cílový web může po krátkou dobu vrátit chybu "nenalezena" (HTTP 404).
- Obsah bude nutné znovu prohledat, aby se aktualizoval vyhledávací index. Není nutný žádný ruční krok-toto bude provedeno automaticky.
- Cokoli, co je závislé na "statických" odkazech (například soubory synchronizace souborů a OneNote), bude nutné ručně opravit.
- Pokud byl zdrojový web diskusním webem organizace, aktualizujte adresu URL.Získejte seznam všech organizačních diskusních serverů.
- Je možné, že weby projektového serveru budou muset být ověřeny, aby bylo zajištěno, že jsou stále správně spojeny.





