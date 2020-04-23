---
title: Řešení problémů s registrací funkce Zabránění spuštění dat v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d32afde-47ab-4b1e-a669-662e5dbdc213
ms.custom:
- "783"
- "6200002"
ms.openlocfilehash: 11b0d73c34996fd84431b38d77b64536d386977e
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766702"
---
# <a name="troubleshoot-issues-with-dep-enrollment-in-microsoft-intune"></a><span data-ttu-id="06667-102">Řešení problémů s registrací funkce Zabránění spuštění dat v Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="06667-102">Troubleshoot issues with DEP enrollment in Microsoft Intune</span></span>

<span data-ttu-id="06667-103">Chcete-li problém vyřešit, zkontrolujte níže uvedené zdroje.</span><span class="sxs-lookup"><span data-stu-id="06667-103">Review the resources listed below to resolve your issue now.</span></span>
  
1. <span data-ttu-id="06667-104">Pokud zařízení zabránění spuštění dat není schopno zaregistrovat a je povoleno vícefaktorové ověřování, zakažte vícefaktorovou službu.</span><span class="sxs-lookup"><span data-stu-id="06667-104">If DEP device is unable to enroll and MFA (Multi-Factor Authentication) is enabled, please disable MFA.</span></span> <span data-ttu-id="06667-105">V současné době není pro zápis funkce Zabránění spuštění dat podporováno vícefaktorové finanční informace.</span><span class="sxs-lookup"><span data-stu-id="06667-105">Currently MFA is not supported for DEP enrollment</span></span>

2. <span data-ttu-id="06667-106">Pomocí [portálu pro řešení potíží intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) můžete diagnostikovat a řešit běžné chyby registrace.</span><span class="sxs-lookup"><span data-stu-id="06667-106">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="06667-107">Další podrobnosti naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune/help-desk-operators)</span><span class="sxs-lookup"><span data-stu-id="06667-107">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

3. <span data-ttu-id="06667-108">V těchto dokumentech naleznete seznam běžných chyb, které brání zápisu a řešení jednotlivých typů: [Příručka pro řešení potíží](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) a [dokument Pro řešení potíží](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune)</span><span class="sxs-lookup"><span data-stu-id="06667-108">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune)</span></span>

4. <span data-ttu-id="06667-109">[Informace o programu registrace zařízení](https://docs.microsoft.com/intune/device-enrollment-program-enroll-ios).</span><span class="sxs-lookup"><span data-stu-id="06667-109">[Learn about device enrollment program](https://docs.microsoft.com/intune/device-enrollment-program-enroll-ios).</span></span>
