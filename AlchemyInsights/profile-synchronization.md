---
title: Synchronizace profilu
ms.author: arnek
author: arnek
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: dc6e0280961d14aa3e6bd466afbe0cbe89418d17
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43768106"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>Kdy se změny profilu synchronizují s aplikací profilu uživatele služby SharePoint?

SharePoint Online používá úlohu časovače importu služby Active Directory (Import služby AD) k importu uživatelů a skupin do aplikace profilů uživatelů. 
  
1. Import služby AD synchronizuje změny z úložiště adresářů SharePointu Online do aplikace profiluživatele. Tyto změny jsou zpracovány v dávkách.
    
2. Úloha časovače se spustí, dokud nejsou synchronizovány změny.
    
> [!NOTE]
> Čas potřebný ke spuštění úlohy závisí na počtu změn procesu. Velký počet změn trvá déle. Smlouva o úrovni služeb (SLA) uvádí, že změna uživatele v adresáři SharePointu Online se projeví v aplikaci profil uživatele do 24 hodin. 
  
[Další informace o synchronizaci profilu uživatelů v SharePointu Online](https://go.microsoft.com/fwlink/?linkid=875671)
  

