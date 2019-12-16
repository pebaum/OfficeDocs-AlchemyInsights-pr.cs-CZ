---
title: Moderní web jako kořenový web
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.date: 8/7/2019
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: 2e2bb02b9dbaf7f8ede0b4c5ba8c8f29453309cb
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40054695"
---
# <a name="modern-site-as-root-site"></a>Moderní web jako kořenový web

Zahájili jsme novou funkci, která vám umožní [vyměnit klasickou kořenovou lokalitu webů s moderním webem](https://docs.microsoft.com/sharepoint/modern-root-site). Pomocí metody [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) můžete při archivaci původního webu zaměnit umístění webu s jiným webem. K dispozici pro týmový web (není připojen ke skupině) a komunikační Web.

>[!Important]
> Neodstraňujte klasickou kořenovou lokalitu, abyste vytvořili moderní komunikační Web. Společnost Microsoft tuto podporu nepodporuje. Odstranění kořenového webu způsobí, že všechny weby služby SharePoint ve vaší organizaci nebudou přístupné všem uživatelům, dokud web neobnovíte nebo vytvoříte nový web na stejné adrese URL. Tuto funkci budeme komunikovat prostřednictvím centra zpráv. Měli byste očekávat, že bude funkce v nájemci brzy zapnuta.

## <a name="known-issues-with-swapping-sites"></a>Známé problémy s odkládání webů
- Cílový web může po krátkou dobu vrátit chybu "nenalezena" (HTTP 404).
- Obsah bude nutné znovu prohledat, aby se aktualizoval vyhledávací index. Zde není nutné provádět žádný ruční krok, bude to provedeno automaticky.
- Cokoli, co je závislé na "statických" odkazech (například soubory synchronizace souborů a OneNote), bude nutné ručně opravit.
- Je možné, že weby projektového serveru budou muset být ověřeny, aby bylo zajištěno, že jsou stále správně spojeny. 
