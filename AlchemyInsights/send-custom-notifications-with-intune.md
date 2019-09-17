---
title: Odeslat vlastní oznámení s Intune
ms.author: brenduns
author: brenduns
manager: dougeby
ms.date: 07/31/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000679
ms.openlocfilehash: 1244f07fd56cf603280f1710520a04d579224e44
ms.sourcegitcommit: 16f08d051afca3c6d0de32826324f91cf63ab5ba
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/16/2019
ms.locfileid: "36992306"
---
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a><span data-ttu-id="d4bcd-102">Jak odesílat vlastní upozornění uživatelům spravovaných zařízení iOS a Android</span><span class="sxs-lookup"><span data-stu-id="d4bcd-102">How to send custom notifications to the users of managed iOS and Android devices</span></span>

<span data-ttu-id="d4bcd-103">Vlastní upozornění pro Intune jsou zpracována aplikací podnikového portálu na uživatelově zařízení.</span><span class="sxs-lookup"><span data-stu-id="d4bcd-103">Custom notifications for Intune are processed by the Company Portal app on a user’s device.</span></span> <span data-ttu-id="d4bcd-104">Aplikace poté vytvoří na tomto zařízení upozornění na nabízenou replikaci.</span><span class="sxs-lookup"><span data-stu-id="d4bcd-104">The app then creates the push notification on that device.</span></span>

<span data-ttu-id="d4bcd-105">Následují předpoklady zařízení pro podporu přijímání vlastních upozornění a pro aplikaci, aby bylo oznámení o nabízenou replikaci vytvořeno:</span><span class="sxs-lookup"><span data-stu-id="d4bcd-105">The following are device prerequisites to support receipt of custom notifications, and for the app to then create the push notification:</span></span>

- <span data-ttu-id="d4bcd-106">V zařízení musí být nainstalována aplikace podnikového portálu.</span><span class="sxs-lookup"><span data-stu-id="d4bcd-106">The device must have the Company Portal app installed.</span></span>  

- <span data-ttu-id="d4bcd-107">Zařízení musí umožňovat, aby aplikace podnikového portálu odesílal upozornění na nabízenou replikaci.</span><span class="sxs-lookup"><span data-stu-id="d4bcd-107">The device must allow the Company Portal app to send push notifications.</span></span> <span data-ttu-id="d4bcd-108">Při instalaci nebo aktualizaci aplikace vyzve uživatele k povolení oznámení.</span><span class="sxs-lookup"><span data-stu-id="d4bcd-108">When the app is installed or updated, it will prompt the user to permit notifications.</span></span>

- <span data-ttu-id="d4bcd-109">Zařízení pro Android musí mít nainstalovánu službu Google Play.</span><span class="sxs-lookup"><span data-stu-id="d4bcd-109">Android devices must have Google Play Services installed.</span></span>

- <span data-ttu-id="d4bcd-110">Zařízení musí být zaregistrováni v Intune.</span><span class="sxs-lookup"><span data-stu-id="d4bcd-110">The device must be enrolled with Intune.</span></span>

<span data-ttu-id="d4bcd-111">Další informace včetně postupu při odesílání zpráv naleznete v dokumentaci k této [funkci](https://docs.microsoft.com/intune/custom-notifications).</span><span class="sxs-lookup"><span data-stu-id="d4bcd-111">For more information including how to send a message, see the [feature documentation](https://docs.microsoft.com/intune/custom-notifications).</span></span>
