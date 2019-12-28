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
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a><span data-ttu-id="35857-102">Jak odesílat vlastní upozornění uživatelům spravovaných zařízení iOS a Android</span><span class="sxs-lookup"><span data-stu-id="35857-102">How to send custom notifications to the users of managed iOS and Android devices</span></span>

<span data-ttu-id="35857-103">Vlastní upozornění pro Intune jsou zpracována aplikací podnikového portálu na uživatelově zařízení.</span><span class="sxs-lookup"><span data-stu-id="35857-103">Custom notifications for Intune are processed by the Company Portal app on a user’s device.</span></span> <span data-ttu-id="35857-104">Aplikace poté vytvoří na tomto zařízení upozornění na nabízenou replikaci.</span><span class="sxs-lookup"><span data-stu-id="35857-104">The app then creates the push notification on that device.</span></span>

<span data-ttu-id="35857-105">Následují předpoklady zařízení pro podporu přijímání vlastních upozornění a pro aplikaci, aby bylo oznámení o nabízenou replikaci vytvořeno:</span><span class="sxs-lookup"><span data-stu-id="35857-105">The following are device prerequisites to support receipt of custom notifications, and for the app to then create the push notification:</span></span>

- <span data-ttu-id="35857-106">V zařízení musí být nainstalována aplikace podnikového portálu.</span><span class="sxs-lookup"><span data-stu-id="35857-106">The device must have the Company Portal app installed.</span></span>  

- <span data-ttu-id="35857-107">Zařízení musí umožňovat, aby aplikace podnikového portálu odesílal upozornění na nabízenou replikaci.</span><span class="sxs-lookup"><span data-stu-id="35857-107">The device must allow the Company Portal app to send push notifications.</span></span> <span data-ttu-id="35857-108">Při instalaci nebo aktualizaci aplikace vyzve uživatele k povolení oznámení.</span><span class="sxs-lookup"><span data-stu-id="35857-108">When the app is installed or updated, it will prompt the user to permit notifications.</span></span>

- <span data-ttu-id="35857-109">Zařízení pro Android musí mít nainstalovánu službu Google Play.</span><span class="sxs-lookup"><span data-stu-id="35857-109">Android devices must have Google Play Services installed.</span></span>

- <span data-ttu-id="35857-110">Zařízení musí být zaregistrováni v Intune.</span><span class="sxs-lookup"><span data-stu-id="35857-110">The device must be enrolled with Intune.</span></span>

<span data-ttu-id="35857-111">Další informace včetně postupu při odesílání zpráv naleznete v dokumentaci k této [funkci](https://docs.microsoft.com/intune/custom-notifications).</span><span class="sxs-lookup"><span data-stu-id="35857-111">For more information including how to send a message, see the [feature documentation](https://docs.microsoft.com/intune/custom-notifications).</span></span>
