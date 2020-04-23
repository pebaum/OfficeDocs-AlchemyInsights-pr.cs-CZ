---
title: Výměna klasického kořenového webu za moderní web
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: f4831c6a232a4dee0f8f5ac0c83e4307221cfe2d
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43741537"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a>Výměna klasického kořenového webu za moderní web

Pokud bylo vaše prostředí nastaveno před dubnem 2019, můžete změnit kořenový web na moderní web pomocí prostředí Microsoft PowerShell:

- Pokud máte jiný web, který chcete použít jako kořenový web, můžete s ním nahradit [(swapovat) kořenový web.](https://docs.microsoft.com/sharepoint/modern-root-site) 
    - Pomocí [invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) můžete při archivaci původního webu vyměnit umístění webu s jiným webem. K dispozici jak pro týmový web (není připojen ke skupině), tak pro komunikační web. 

- Brzy budou zavedeny další funkce, které vám umožní pokračovat v používání obsahu na webu, ale převést stávající web na komunikační web. 
>[!Important]
>Tyto možnosti budou postupně zaváděny. Pokračujte v kontrole aktualizací v Centru zpráv. 

## <a name="known-issues-with-swapping-sites"></a>Známé problémy s výměnou webů

- Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.
- Obsah bude nutné znovu procházet, aby se aktualizoval index vyhledávání. Není vyžadován žádný ruční krok - to bude provedeno automaticky.
- Vše, co závisí na "statických" odkazech (například synchronizace souborů a soubory aplikace OneNote), bude nutné ručně opravit.
- Pokud byl zdrojový web organizační zpravodajský web, aktualizujte adresu URL.Získejte seznam všech organizačních zpravodajských webů.
- Servery microsoftoffice může být nutné ověřit, aby bylo zajištěno, že jsou stále správně přidruženy.
