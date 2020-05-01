---
title: Řešení chyby Aplikace nebyla zjištěna
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000171"
- "1712"
ms.openlocfilehash: e07c6b128a39f1fb1c998d051aafe72205d8cbee
ms.sourcegitcommit: 82155846ce771c18050e6113d6c199b34a1504ff
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/24/2020
ms.locfileid: "43810477"
---
# <a name="mitigate-the-application-was-not-detected-error"></a><span data-ttu-id="774ff-102">Řešení chyby „Aplikace nebyla zjištěna“</span><span class="sxs-lookup"><span data-stu-id="774ff-102">Mitigate "The application was not detected" error</span></span>

<span data-ttu-id="774ff-103">K chybě „Aplikace nebyla po úspěšném dokončení instalace zjištěna“ při instalaci aplikace přes Intune může dojít na všech hlavních operačních systémech (Windows, iOS a Android).</span><span class="sxs-lookup"><span data-stu-id="774ff-103">The app installation error, “The application was not detected after installation completed successfully,” reported by Intune, may occur on all major OS platforms (Windows, iOS and Android).</span></span>

<span data-ttu-id="774ff-104">Nejběžnější případy, kdy k této chybě dochází:</span><span class="sxs-lookup"><span data-stu-id="774ff-104">The most common scenarios that generate this error include:</span></span>

- <span data-ttu-id="774ff-105">Aplikace se po prvotním nasazení aktualizovala mimo Intune (z obchodu s aplikacemi třetí strany).</span><span class="sxs-lookup"><span data-stu-id="774ff-105">The app has been updated outside of Intune (from a third-party app store) after the initial deployment.</span></span> <span data-ttu-id="774ff-106">Některé aplikace, jako je Google Chrome, se můžou aktualizovat automaticky.</span><span class="sxs-lookup"><span data-stu-id="774ff-106">For example some applications such as Google Chrome may perform auto updates.</span></span>
- <span data-ttu-id="774ff-107">Uživatel po počáteční instalaci odinstaloval aplikaci.</span><span class="sxs-lookup"><span data-stu-id="774ff-107">A user has uninstalled the app after the initial install.</span></span>

<span data-ttu-id="774ff-108">Abyste tento problém vyřešili, nejdřív zkontrolujte dotčená zařízení a zjistěte, proč k chybě došlo.</span><span class="sxs-lookup"><span data-stu-id="774ff-108">To mitigate this issue, first perform a review of the affected devices to determine the scenario in which the error occurs.</span></span>

- <span data-ttu-id="774ff-109">Pokud se aplikace aktualizovala mimo Intune, můžete pro její nasazení nastavit, aby ignorovalo verzi aplikace.</span><span class="sxs-lookup"><span data-stu-id="774ff-109">If the app has been updated outside of Intune, the app deployment can be set to ignore the application version.</span></span> <span data-ttu-id="774ff-110">Uděláte to tak, že v **Konfigurace aplikace > Informace o aplikaci** nastavíte **Ignorovat verzi aplikace** na **Ano**.</span><span class="sxs-lookup"><span data-stu-id="774ff-110">To do so, under **App Configuration > App Information**, set **Ignore App** version to **Yes**.</span></span>
- <span data-ttu-id="774ff-111">Při cílení na klienta může být vhodné nasadit aplikaci jako „povinnou“ a zajistit tak nasazení její nejnovější verze.</span><span class="sxs-lookup"><span data-stu-id="774ff-111">When targeting the client, it may be appropriate to deploy the application as “required,” and to ensure that the latest version is deployed.</span></span>
- <span data-ttu-id="774ff-112">Na platformě iOS jde případně použít funkci **automatických aktualizací** související s Programem hromadných nákupů Apple, kterou můžete nakonfigurovat, aby automaticky instalovala nové verze aplikací, jakmile budou dostupné.</span><span class="sxs-lookup"><span data-stu-id="774ff-112">Alternatively, on the iOS platform, it is possible to use the **autoupdate** functionality associated with the Apple Volume Purchase Program, which can be configured to automatically update to new application versions as they become available.</span></span>

<span data-ttu-id="774ff-113">Další informace o řešení problémů s instalací aplikací najdete v článku [Řešení problémů s instalací aplikací](https://docs.microsoft.com/intune/troubleshoot-app-install).</span><span class="sxs-lookup"><span data-stu-id="774ff-113">For more information about troubleshooting app installation issues, please see [Troubleshoot app installation issues](https://docs.microsoft.com/intune/troubleshoot-app-install).</span></span>