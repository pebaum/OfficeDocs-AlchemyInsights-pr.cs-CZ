---
title: Aktualizace záznamů DNS tak, aby web zůstal u současného poskytovatele hostingu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: e0dadba1e3ffd1cf0d49c0a76ec2efbbc6ae92db
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29906113"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a>Aktualizace záznamů DNS tak, aby web zůstal u současného poskytovatele hostingu

1. Na stránce [Domény](https://portal.office.com/adminportal/home#/Domains) vyberte v seznamu domén doménu, kterou používáte pro svůj web, a potom v podokně správy vyberte **Nastavení DNS**. 
    
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
    

