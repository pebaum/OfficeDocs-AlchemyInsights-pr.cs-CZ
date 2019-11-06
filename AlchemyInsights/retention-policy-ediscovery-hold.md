---
title: 2609-uchovávání-nebo-eDiscovery-hold
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2609"
- "9000048"
ms.openlocfilehash: 85c41995545efd8e1526d9f7dce4a23929f85be5
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/05/2019
ms.locfileid: "37994052"
---
# <a name="unable-to-delete-items-in-sharepoint-online-or-onedrive-for-business"></a>Nelze odstranit položky ve službě SharePoint Online nebo OneDrive pro podnik

Je možné, že vy nebo vaši uživatelé nebudete moci odstranit položky ve službě SharePoint Online nebo OneDrive for Business, protože je použita zásada uchovávání informací, retenční štítek nebo blokování eDiscovery u služby SharePoint serveru OneDrive nebo u určité položky. To zahrnuje také to, že nelze odstranit dokument, verzi dokumentu, složku, knihovnu dokumentů, seznam, aplikaci, web nebo kolekci webů. Zde je několik příkladů chybových zpráv, které mohou být přijaty při pokusu o odstranění položky, která je uchovávané:

- "Tento web nelze odstranit, protože je zahrnut v zásadách uchovávání informací nebo uchování v systému eDiscovery."
- "Tento server obsahuje zásady kompatibility, které blokují odstranění."
- "Zásada kompatibility aktuálně blokuje odstranění tohoto webu"
- Tuto kolekci webů nelze odstranit, protože obsahuje weby, které jsou zahrnuty v zásadách blokování nebo uchovávání informací systému eDiscovery.
- "Před odstraněním složky musíte odstranit všechny položky v této složce"
- "Verze této položky nelze odstranit, protože jsou v zásadě blokování nebo jsou zásady uchovávání informací"
- "Při blokování nelze položku odstranit"
- "Popisek použitý u této položky zabraňuje úpravám nebo odstraňování."
- "Seznam nelze odstranit, pokud je v zásadách blokování nebo uchovávání informací"
- "Seznam nelze odstranit, pokud je blokován nebo pokud je na ni aplikovaná zásada uchovávání informací."

Chcete-li odstranit položky v jednom z těchto scénářů, je nutné odebrat zásady uchovávání informací, retenční štítek nebo blokování eDiscovery (nebo musí být web vyloučen z zásady uchovávání informací). Je třeba zakázat nebo vyloučit příslušné blokování, které způsobuje tento problém. Po odebrání zásad nebo blokování uchovávání informací může změna trvat až 24 hodin. 

Informace o různých funkcích uchování a držení, které lze použít pro weby služby SharePoint a účty OneDrive, naleznete v některém z následujících témat.

- [Přehled zásad uchovávání informací](https://docs.microsoft.com/microsoft-365/compliance/retention-policies)

- [Přehled retenčních štítků](https://docs.microsoft.com/microsoft-365/compliance/labels)

- [Správa blokování v rozšířeném eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/managing-holds)

- [eDiscovery uchovává](https://docs.microsoft.com/microsoft-365/compliance/ediscovery-cases#step-4-place-content-locations-on-hold)

- [Zásady zavírání a odstraňování starších serverů](https://support.office.com/article/Use-policies-for-site-closure-and-deletion-A8280D82-27FD-48C5-9ADF-8A5431208BA5)
