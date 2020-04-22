---
title: Moderní web jako kořenový web
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.date: 04/21/2020
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: 0388f95e2b7815dcbbb6aca200f44e55e9c5724f
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713784"
---
# <a name="modern-site-as-root-site"></a>Moderní web jako kořenový web

Začali jsme zavádět novou funkci, která vám umožní [vyměnit váš klasický kořenový web s moderním webem](https://docs.microsoft.com/sharepoint/modern-root-site). Pomocí [invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) můžete při archivaci původního webu vyměnit umístění webu s jiným webem. K dispozici jak pro týmový web (není připojen ke skupině), tak pro komunikační web.

>[!Important]
> Neodstraňujte klasický kořenový web a vytvořte moderní komunikační web. Společnost Microsoft to nepodporuje. Odstraněním kořenového webu budou všechny weby služby SharePoint ve vaší organizaci nepřístupné všem uživatelům, dokud web neobnovíte nebo nevytvoříte nový web na stejné adrese URL. Tuto funkci budeme komunikovat prostřednictvím centra zpráv. Měli byste očekávat, že funkce, která má být zapnuta ve vašem tenantovi v brzké době.

## <a name="known-issues-with-swapping-sites"></a>Známé problémy s výměnou webů
- Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.
- Obsah bude nutné znovu procházet, aby se aktualizoval index vyhledávání. Zde není nutný žádný ruční krok, bude to provedeno automaticky.
- Vše, co závisí na "statických" odkazech (například synchronizace souborů a soubory aplikace OneNote), bude nutné ručně opravit.
- Servery microsoftoffice může být nutné ověřit, aby bylo zajištěno, že jsou stále správně přidruženy. 
