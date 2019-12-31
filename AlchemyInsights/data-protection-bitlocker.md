---
title: DataProtection-nástroj BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1802"
- "9000220"
ms.openlocfilehash: c23a2a2bde240900119382a9c1185a6e02520149
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908703"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a><span data-ttu-id="b4496-102">Povolení šifrování nástrojem BitLocker pomocí nástroje Intune</span><span class="sxs-lookup"><span data-stu-id="b4496-102">Enabling Bitlocker encryption with Intune</span></span>

 <span data-ttu-id="b4496-103">Zásady ochrany koncového bodu Intune lze použít ke konfiguraci nastavení šifrování nástrojem BitLocker pro zařízení systému Windows.</span><span class="sxs-lookup"><span data-stu-id="b4496-103">Intune Endpoint Protection Policy can be used to configure Bitlocker encryption settings for Windows devices.</span></span> <span data-ttu-id="b4496-104">Další informace naleznete v [nastavení systému Windows 10 (a novějších) pro ochranu zařízení pomocí nástroje Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).</span><span class="sxs-lookup"><span data-stu-id="b4496-104">For more information, see [Windows 10 (and later) settings to protect devices using Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).</span></span>
 
<span data-ttu-id="b4496-105">Je třeba si uvědomit, že mnoho novějších zařízení používajících systém Windows 10 podporuje automatické šifrování nástrojem BitLocker, které je spuštěno bez použití zásad MDM.</span><span class="sxs-lookup"><span data-stu-id="b4496-105">You should be aware that many newer devices running Windows 10 support automatic Bitlocker encryption, which is triggered without the application of MDM policy.</span></span> <span data-ttu-id="b4496-106">To může mít vliv na použití zásady, pokud je nakonfigurováno jiné než výchozí nastavení.</span><span class="sxs-lookup"><span data-stu-id="b4496-106">This may impact application of policy if non-default settings are configured.</span></span> <span data-ttu-id="b4496-107">Další informace naleznete v následujících nejčastějších dotazech.</span><span class="sxs-lookup"><span data-stu-id="b4496-107">See the following FAQ for more detail.</span></span>
 
<span data-ttu-id="b4496-108">Informace o odstraňování potíží s nástrojem BitLocker naleznete [v tématu Poradce při potížích s zásadami nástroje BitLocker v systému Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).</span><span class="sxs-lookup"><span data-stu-id="b4496-108">For information about troubleshooting bitlocker issues, see [Troubleshoot BitLocker policies in Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).</span></span>
 
 
<span data-ttu-id="b4496-109">**Časté otázky**</span><span class="sxs-lookup"><span data-stu-id="b4496-109">**FAQ**</span></span>

 <span data-ttu-id="b4496-110">Q: které edice systému Windows podporují šifrování pomocí zásad ochrany koncových bodů?</span><span class="sxs-lookup"><span data-stu-id="b4496-110">Q: Which editions of Windows support device encryption using the Endpoint Protection Policy?</span></span><br>
 <span data-ttu-id="b4496-111">A: nastavení v zásadách ochrany koncových bodů nástroje Intune jsou implementována pomocí [zprostředkovatele kryptografických služeb (BitLocker](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp)).</span><span class="sxs-lookup"><span data-stu-id="b4496-111">A: The settings in Intune Endpoint Protection Policy  are implemented using the [Bitlocker CSP](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp).</span></span> <span data-ttu-id="b4496-112">Některé edice a verze systému Windows nepodporují nástroj BitLocker CSP.</span><span class="sxs-lookup"><span data-stu-id="b4496-112">Not all editions or builds of Windows support the Bitlocker CSP.</span></span> <br><br>
      <span data-ttu-id="b4496-113">V tomto okamžiku jsou podporovány následující edice systému Windows: Enterprise, školství, Mobile, Mobile Enterprise a Professional (sestavení 1809 a novější).</span><span class="sxs-lookup"><span data-stu-id="b4496-113">At this time, the following Windows editions are supported: Enterprise, Education, Mobile, Mobile Enterprise, and Professional (build 1809 and later).</span></span>
 
<span data-ttu-id="b4496-114">Q: Pokud je zařízení již zašifrováno pomocí nástroje BitLocker s použitím výchozího nastavení operačního systému pro šifrovací metodu a sílu šifrování (XTS-AES-128), použije zásada s různým nastavením automaticky opětovné spuštění šifrování jednotky s novým nastavením?</span><span class="sxs-lookup"><span data-stu-id="b4496-114">Q: If a device is already encrypted with Bitlocker using the OS default settings for encryption method and cipher strength (XTS-AES-128), will applying a policy with different settings automatically trigger re-encryption of the drive with the new settings?</span></span><br>
<span data-ttu-id="b4496-115">A: ne.</span><span class="sxs-lookup"><span data-stu-id="b4496-115">A: No.</span></span> <span data-ttu-id="b4496-116">Chcete-li použít nové nastavení šifrování, musí být jednotka nejprve dešifrována.</span><span class="sxs-lookup"><span data-stu-id="b4496-116">To apply the new cipher settings, the drive must first be decrypted.</span></span><br><br>
<span data-ttu-id="b4496-117">**Poznámka:** U zařízení, která jsou zapsáni pomocí funkce autopilot, nebude automatické šifrování, ke kterému dojde během počátečního spuštění počítače, spuštěno, dokud nebude vyhodnocena zásada Intune, která umožňuje použití nastavení založeného na zásadách namísto výchozích hodnot operačního systému.</span><span class="sxs-lookup"><span data-stu-id="b4496-117">**Note:** For devices being enrolled with Autopilot, the automatic encryption that would occur during OOBE is not triggered until Intune policy is evaluated, which allows the policy-based settings to be used in place of the OS defaults.</span></span>
 
<span data-ttu-id="b4496-118">Q: Pokud je zařízení zašifrováno v důsledku použití zásady Intune, bude při odebrání této zásady dešifrován?</span><span class="sxs-lookup"><span data-stu-id="b4496-118">Q: If a device is encrypted as a result of the  application of Intune policy, will it be decrypted when that policy is removed?</span></span><br>
<span data-ttu-id="b4496-119">A: odebrání zásad týkajících se šifrování nevede k dešifrování nakonfigurovaných jednotek.</span><span class="sxs-lookup"><span data-stu-id="b4496-119">A: Removal of encryption-related policy does NOT result in decryption of the drives that were configured.</span></span>
 
<span data-ttu-id="b4496-120">Q: Proč se v zásadách kompatibility Intune zobrazují, že zařízení nemá povolen nástroj BitLocker, i když je?</span><span class="sxs-lookup"><span data-stu-id="b4496-120">Q: Why does Intune Compliance Policy show that my device does not have Bitlocker enabled, even though it is?</span></span><br>
<span data-ttu-id="b4496-121">A: nastavení "BitLocker Enabled" v zásadách Compliance (Intune) používá klienta ověřování stavu zařízení systému Windows (DHA).</span><span class="sxs-lookup"><span data-stu-id="b4496-121">A: The "Bitlocker enabled" setting in the Intune Compliance Policy utilizes the Windows Device Health Attestation  (DHA) client.</span></span> <span data-ttu-id="b4496-122">Tento klient měří stav zařízení pouze při spuštění.</span><span class="sxs-lookup"><span data-stu-id="b4496-122">This client only measures device state at boot time.</span></span> <span data-ttu-id="b4496-123">Pokud tedy nebylo zařízení po dokončení šifrování nástrojem BitLocker ukončeno, nebude klientská služba pro připojení k obnovení dat vykazovat nástroj BitLocker jako aktivní.</span><span class="sxs-lookup"><span data-stu-id="b4496-123">So if a device has not been rebooted since Bitlocker encryption was completed, the DHA client service will not report Bitlocker as being active.</span></span>
 
 