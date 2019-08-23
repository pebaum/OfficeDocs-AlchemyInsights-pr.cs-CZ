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
ms.openlocfilehash: b9b90dad6c5fa41afcd4e4c9a929594735eca066
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36554326"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>Při změny profilu aplikace profilů uživatelů služby SharePoint synchronizovat?

SharePoint Online používá Active Directory Import úlohy časovače (AD Import) Import uživatelů a skupin do aplikace profilů uživatelů. 
  
1. AD Import synchronizuje změny z úložiště služby SharePoint Online adresáře aplikace profilů uživatelů. Tyto změny jsou zpracovány v dávkách.
    
2. Úloha časovače se spustí, až budou změny synchronizovány.
    
> [!NOTE]
> Čas potřebný ke spuštění úlohy závisí na počtu změn ke zpracování. Velký počet změn trvá déle. Smlouvy úrovně služeb (SLA) uvádí, že změna k uživateli v adresáři služby SharePoint Online se odrazí v aplikaci profilů uživatelů do 24 hodin. 
  
[Další informace o synchronizace profilů uživatelů v Online služby SharePoint](https://go.microsoft.com/fwlink/?linkid=875671)
  

