---
title: Odeslat vlastní oznámení s Intune
ms.author: brenduns
author: brenduns
manager: dougeby
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000679"
- "2565"
ms.openlocfilehash: 969649084a2ac536ee1b41f225c3be5415a27c4b
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/27/2019
ms.locfileid: "40886850"
---
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a>Jak odesílat vlastní upozornění uživatelům spravovaných zařízení iOS a Android

Vlastní upozornění pro Intune jsou zpracována aplikací podnikového portálu na uživatelově zařízení. Aplikace poté vytvoří na tomto zařízení upozornění na nabízenou replikaci.

Následují předpoklady zařízení pro podporu přijímání vlastních upozornění a pro aplikaci, aby bylo oznámení o nabízenou replikaci vytvořeno:

- V zařízení musí být nainstalována aplikace podnikového portálu.  

- Zařízení musí umožňovat, aby aplikace podnikového portálu odesílal upozornění na nabízenou replikaci. Při instalaci nebo aktualizaci aplikace vyzve uživatele k povolení oznámení.

- Zařízení pro Android musí mít nainstalovánu službu Google Play.

- Zařízení musí být zaregistrováni v Intune.

Další informace včetně postupu při odesílání zpráv naleznete v dokumentaci k této [funkci](https://docs.microsoft.com/intune/custom-notifications).
