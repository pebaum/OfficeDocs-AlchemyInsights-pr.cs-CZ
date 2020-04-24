---
title: Duplicitní záznam zařízení na portálu.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: 277afc59705e6040f0f9ae0c8cad965bd7d3ef65
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2020
ms.locfileid: "43789682"
---
# <a name="duplicate-device-record-in-the-portal"></a><span data-ttu-id="a1012-102">Duplicitní záznam zařízení na portálu.</span><span class="sxs-lookup"><span data-stu-id="a1012-102">Duplicate device record in the portal</span></span>

<span data-ttu-id="a1012-103">Pokud zařízení nehlásí správný přehled o stavu na stránce Správce konfigurace, můžou se vám na portálu zobrazovat dva záznamy. </span><span class="sxs-lookup"><span data-stu-id="a1012-103">You may see 2 records for a device in the portal if the device does not correctly report the co-management status to the Configuration Manager site.</span></span> <span data-ttu-id="a1012-104">Pokud chcete zkontrolovat stav konkrétního zařízení, podívejte se do sloupce **Spoluspravované** na zařízení v konzole Správce konfigurace.</span><span class="sxs-lookup"><span data-stu-id="a1012-104">To check the co-management status of a device, review the **Co-managed** column for the device in the Configuration Manager console.</span></span> <span data-ttu-id="a1012-105">Pokud není sloupec zobrazený, můžete ho přidat kliknutím pravým tlačítkem myši na záhlaví sloupce a vybrat ho ze seznamu.</span><span class="sxs-lookup"><span data-stu-id="a1012-105">If the column is not visible, you may add it by right-clicking any of the column headers, and selecting it from the list.</span></span>

<span data-ttu-id="a1012-106">Spoluspravovaná hodnota musí být **Ano**.</span><span class="sxs-lookup"><span data-stu-id="a1012-106">The Co-managed value must be **Yes**.</span></span> <span data-ttu-id="a1012-107">Pokud je hodnota**Ne**, otevřete na klientském zařízení aplet Správce konfigurace a zkontrolujte **vlastnosti spolusprávy** na kartě Obecné.</span><span class="sxs-lookup"><span data-stu-id="a1012-107">If the value is **No**, open the Configuration Manager client applet on the client device and check the **Co-management** property in the General tab.</span></span>

- <span data-ttu-id="a1012-108">Pokud je hodnota**Povolena**, znamená to, že se jedná o problémy komunikace klienta s bodem správy.</span><span class="sxs-lookup"><span data-stu-id="a1012-108">If the value is **Enabled**, this indicates problems with client communication with the Management Point.</span></span> <span data-ttu-id="a1012-109">Abyste mohli prozkoumat potenciální problémy s připojením, podívejte se prosím na **CcmMessaging. log** na zařízení.</span><span class="sxs-lookup"><span data-stu-id="a1012-109">Please review the **CcmMessaging.log** on the device to investigate potential connectivity issues.</span></span>

- <span data-ttu-id="a1012-110">Pokud je hodnota **Zakázaná** a zařízení se registruje v Intune, ujistěte se prosím, že zařízení dostalo zásadu pro spolusprávu, a to tak, že na zařízení zkontrolujete \*\*CoManagementHandler.log. \*\*</span><span class="sxs-lookup"><span data-stu-id="a1012-110">If the value is **Disabled** and the device is enrolled in Intune, please ensure that the device has received the Co-management policy by reviewing the **CoManagementHandler.log** on the device.</span></span>
