---
title: Synchronizace profilů
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: d1a72a85767e36fefbfa8eee266befcaf2e48af0
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29920081"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>Při změny profilu aplikace profilů uživatelů služby SharePoint synchronizovat?

SharePoint Online používá Active Directory Import úlohy časovače (AD Import) Import uživatelů a skupin do aplikace profilů uživatelů. 
  
1. AD Import synchronizuje změny z úložiště služby SharePoint Online adresáře aplikace profilů uživatelů. Tyto změny jsou zpracovány v dávkách.
    
2. Úloha časovače se spustí, až budou změny synchronizovány.
    
> [!NOTE]
> Čas potřebný ke spuštění úlohy závisí na počtu změn ke zpracování. Velký počet změn trvá déle. Smlouvy úrovně služeb (SLA) uvádí, že změna k uživateli v adresáři služby SharePoint Online se odrazí v aplikaci profilů uživatelů do 24 hodin. 
  
[Další informace o synchronizace profilů uživatelů v Online služby SharePoint](https://go.microsoft.com/fwlink/?linkid=875671)
  

