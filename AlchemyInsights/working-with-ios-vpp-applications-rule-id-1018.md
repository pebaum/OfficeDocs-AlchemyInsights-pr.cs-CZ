---
title: Práce s iOS VPP aplikace Id 1018
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 88a1ef66bf337b3a0094976c122330591aee77ff
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43719950"
---
# <a name="working-with-ios-vpp-applications"></a>Práce s aplikacemi vpp iOS

Přečtěte si [článek Jak spravovat aplikace pro iOS zakoupené v programu pro nákup objemu pomocí Microsoft Intune,](https://docs.microsoft.com/intune/vpp-apps-ios) kde se dozvíte o funkcích, omezeních a krocích, jak využít Program hromadných nákupů Apple a jeho podporu v Microsoft Intune.
  
 **Běžné problémy:** "Přiřadil jsem uživatelům aplikaci IOS VPP, ale instalace se nezdařila."
  
- K tomu může dojít, pokud se jeden token VPP používá mezi více poskytovateli správy mobilních zařízení. VPP tokeny od společnosti Apple lze používat pouze s jedním poskytovatelem. Pokud jste použili token VPP s více poskytovateli, musíte token znovu nahrát do Intune.

- Instalace může také selhat, pokud celkový počet instalací překročí počet licencí. Pokud chcete zobrazit sestavu využití licencí, přejděte na stránku \> **licence aplikací** Pro Aplikace Pro **Aplikace Intune.** Informace o tom, jak získat licence, které se používají, najdete v [tomto článku.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
