---
title: Aktualizace záznamů DNS tak, aby web zůstal u současného poskytovatele hostingu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "42"
- "43"
- "100002"
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: 7bd36c3954d12d3ee4ac624a2f827d8e5cd88082
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/29/2019
ms.locfileid: "36665753"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a>Aktualizace záznamů DNS tak, aby web zůstal u současného poskytovatele hostingu

1. Ve středisku pro správce služeb Microsoft 365 přejděte do **Nastavení** > [domény](https://portal.office.com/adminportal/home#/Domains) stránky a v seznamu domény, vyberte domény, které používáte pro svůj web.

2. Vyberte **+ Nový vlastní záznam** a zadejte tyto údaje:

  - Pro **Typ DNS** zadejte: **A (adresa)**

  - Jako **Název hostitele nebo alias** zadejte tento symbol: **@**

  - Do pole **IP adresa** zadejte statickou IP adresu, na které je váš web právě hostovaný (třeba 172.16.140.1).

    Je nutné, aby to byla  *statická*  IP adresa webu, ne  *dynamická*  IP adresa. Na serveru, kde je web hostovaný, se ujistěte, že pro svůj veřejný web můžete získat statickou IP adresu.

3. Vyberte **Uložit**.

Kromě toho můžete vytvořit záznam CNAME, který zákazníkům pomůže váš web najít.
  
1. Vyberte **+ Nový vlastní záznam** a zadejte tyto údaje:

  - Pro **Typ DNS** zadejte: **CNAME (alias)**

  - Do **Název hostitele nebo alias** zadejte: **www**

  - Do pole **Ukazatel na adresu** zadejte plně kvalifikovaný název domény pro svůj web (třeba contoso.com).

2. Vyberte **Uložit**.
