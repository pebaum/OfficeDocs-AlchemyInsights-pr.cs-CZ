---
title: Šifrování pomocí pravidel přenosu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5154"
ms.openlocfilehash: 3f16c7e7be99a50cd57f47ea2801b3022c4aec95
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915088"
---
# <a name="encryption-with-transport-rules"></a><span data-ttu-id="cf9b4-102">Šifrování pomocí pravidel přenosu</span><span class="sxs-lookup"><span data-stu-id="cf9b4-102">Encryption with transport rules</span></span>

<span data-ttu-id="cf9b4-103">V [Centru pro správu Exchange](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC) můžete v pravidlech toku pošty používat funkce šifrování zpráv Office (OME) ke spouštění šifrování zpráv.</span><span class="sxs-lookup"><span data-stu-id="cf9b4-103">In the [Exchange Admin Center](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC), you can use Office Message Encryption(OME) capabilities in your mail flow rules to trigger message encryption.</span></span> <span data-ttu-id="cf9b4-104">U podmínky Pravidlo přenosu vyberte možnost **Použít šifrování zpráv Office 365 a ochranu práv**.</span><span class="sxs-lookup"><span data-stu-id="cf9b4-104">Choose the **Apply Office 365 Message Encryption and rights protection** option on the Transport Rule condition.</span></span>

- <span data-ttu-id="cf9b4-105">Další informace najdete v článku [Definování pravidla toku pošty pro šifrování](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span><span class="sxs-lookup"><span data-stu-id="cf9b4-105">For more information, see [Define Mail flow rule to encrypt](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span></span>

- <span data-ttu-id="cf9b4-106">V PowerShellu použijte rutinu [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) a nastavte parametr *ApplyOME* na $true.</span><span class="sxs-lookup"><span data-stu-id="cf9b4-106">In Powershell, use the [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) cmdlet and set the *ApplyOME* parameter to $true.</span></span>
