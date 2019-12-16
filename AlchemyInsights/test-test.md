---
title: Chybějící termíny v úložišti termínů služby SharePoint Online
ms.author: pebaum
author: pebaum
ms.date: 10/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 28913b8e57e39d51e8957b7408c19337a119c589
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40053506"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a><span data-ttu-id="8ff5e-102">Povolení šifrování nástrojem BitLocker pomocí nástroje Intune</span><span class="sxs-lookup"><span data-stu-id="8ff5e-102">Enabling Bitlocker Encryption with Intune</span></span>

<span data-ttu-id="8ff5e-103">Zásady ochrany koncových bodů Intune lze použít ke konfiguraci nastavení šifrování nástroje Boitlocker pro zařízení systému Windows, jak je popsáno v následujícím nastavení: Windows10 (a novější) k ochraně zařízení pomocí nástroje Intune.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-103">Intune Endpoint Protection Policy can be used to configure Boitlocker encryption settings for Windows devices as described in : Windows10 (and later) settings to protect devices using Intune</span></span>

<span data-ttu-id="8ff5e-104">Je třeba si uvědomit, že mnoho novějších zařízení používajících systém Windows 10 podporuje automatické šifrování nástrojem BitLocker, které je spuštěno bez použití zásad MDM.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-104">You should be aware that many newer devices running Windows 10 support automatic bitlocker encryption which is triggered without the application of MDM policy.</span></span> <span data-ttu-id="8ff5e-105">To může mít vliv na použití zásad, pokud není nakonfigurováno výchozí nastavení.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-105">This may impact application of policy if non default settings are configured.</span></span> <span data-ttu-id="8ff5e-106">Podrobnější informace naleznete v nejčastějších dotazech.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-106">See FAQ for more detail.</span></span>


<span data-ttu-id="8ff5e-107">FAQ  Q: které edice systému Windows podporují šifrování pomocí zásad ochrany koncových bodů?</span><span class="sxs-lookup"><span data-stu-id="8ff5e-107">FAQ  Q: Which editions of Windows support device encryption using the Endpoint Protection Policy?</span></span>
<span data-ttu-id="8ff5e-108"> A: nastavení v zásadách ochrany koncového bodu nástroje Intune je implementováno pomocí zprostředkovatele kryptografických služeb pro nástroj BitLocker.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-108"> A: The settings in Intune Endpoint Protection Policy  are implemented using the Bitlocker CSP.</span></span><span data-ttu-id="8ff5e-109">Některé edice a verze systému Windows nepodporují nástroj BitLocker CSP. 
     </span><span class="sxs-lookup"><span data-stu-id="8ff5e-109">  Not all editions nor builds of Windows support the Bitlocker CSP. 
     </span></span> <span data-ttu-id="8ff5e-110">V tomto okamžiku edice Windows: Enterprise; Podporovány jsou vzdělávání, Mobile, Mobile Enterprise a Professional (od sestavení 1809 dále).</span><span class="sxs-lookup"><span data-stu-id="8ff5e-110">At this time Windows Editions: Enterprise; Education, Mobile, Mobile Enterprise and Professional (from build 1809 onwards) are supported.</span></span>




<span data-ttu-id="8ff5e-111">Q: Pokud je zařízení již zašifrováno pomocí nástroje BitLocker s použitím výchozího nastavení operačního systému pro šifrovací metodu a sílu šifrování (XTS-AES-128), použije zásada s odlišným nastavením automaticky opětovné spuštění šifrování jednotky s novým nastavením?</span><span class="sxs-lookup"><span data-stu-id="8ff5e-111">Q: If a device is already encrypted with Bitlocker using the OS default settings for encryption method and cipher strength (XTS-AES-128)  will applying a policy with different settings automatically trigger re-encryption of the drive with the new settings?</span></span>

<span data-ttu-id="8ff5e-112">A: ne.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-112">A: No.</span></span> <span data-ttu-id="8ff5e-113">Chcete-li použít nové nastavení šifrování, musí být jednotka nejprve dešifrována.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-113">In order to apply the new cipher settings the drive must first be decrypted.</span></span>

<span data-ttu-id="8ff5e-114">Poznámka: u zařízení, která jsou zapsáni pomocí funkce autopilot, nebude aktivováno automatické šifrování, které by se spustilo během počátečního nastavení počítače (OOBE), dokud nebude vyhodnocena zásada Intune, která umožňuje použití parametrů založených na zásadách místo výchozích</span><span class="sxs-lookup"><span data-stu-id="8ff5e-114">Note For devices being enrolled with Autopilot the automatic encryption that would occur during OOBE is not triggered until Intune policy is evaluated which allows the policy based settings to be used in place of the OS defaults</span></span>




<span data-ttu-id="8ff5e-115">Q Pokud je zařízení zašifrováno v důsledku použití zásady Intune, bude při odebrání této zásady dešifrován?</span><span class="sxs-lookup"><span data-stu-id="8ff5e-115">Q If a device is encrypted as a result of the  application of Intune policy will it be decrypted when that policy is removed?</span></span>

<span data-ttu-id="8ff5e-116">A: odebrání zásady související s šifrováním nevede k dešifrování nakonfigurovaných jednotek.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-116">A: Removal of encryption related policy does NOT result in decryption of the drives which were configured.</span></span>




<span data-ttu-id="8ff5e-117">Q: Proč se v zásadách kompatibility intun ukazuje, že zařízení nemá "nástroj BitLocker Enabled", ale je?</span><span class="sxs-lookup"><span data-stu-id="8ff5e-117">Q: Why does intune Compliance policy show that my device does not have "Bitlocker Enabled" but it is?</span></span>

<span data-ttu-id="8ff5e-118">A: nastavení "BitLocker Enabled" v zásadách Compliance (Intune) používá klienta ověřování stavu zařízení systému Windows (DHA).</span><span class="sxs-lookup"><span data-stu-id="8ff5e-118">A: The "Bitlocker enabled" setting in intune compliance policy utilizes the Windows Device Health Attestation  (DHA) client.</span></span> <span data-ttu-id="8ff5e-119">Tento klient měří stav zařízení pouze při spuštění.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-119">This client only measures device state at boot time.</span></span> <span data-ttu-id="8ff5e-120">Pokud tedy nebylo zařízení znovu dokončeno od dokončení šifrování nástrojem BitLocker, nebude klientská služba DHA hlásit nástroj BitLocker jako aktivní.</span><span class="sxs-lookup"><span data-stu-id="8ff5e-120">So if a device has not been rebooted since bitlocker encryption was completed the DHA client service will not report bitlocker as being active.</span></span>