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
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36554326"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>Kdy se můj profil změní v synchronizaci s aplikací profilů uživatelů služby SharePoint?

Služba SharePoint Online používá k importu uživatelů a skupin do aplikace profilů uživatelů úlohu časovače importu služby Active Directory (AD Import). 
  
1. Import adresáře AD synchronizuje změny z úložiště adresářů online služby SharePoint s aplikací profilů uživatelů. Tyto změny jsou zpracovány v dávkách.
    
2. Úloha časovače bude spuštěna, dokud nebudou změny synchronizovány.
    
> [!NOTE]
> Doba, po kterou je úloha spouštěna, závisí na počtu změn procesů. Velký počet změn trvá déle. Smlouva o rozsahu služeb (SLA) uvádí, že změna uživatele v adresáři služby SharePoint Online se odrazí v aplikaci profilů uživatelů za 24 hodin. 
  
[Další informace o synchronizaci profilů uživatelů ve službě SharePoint Online](https://go.microsoft.com/fwlink/?linkid=875671)
  

