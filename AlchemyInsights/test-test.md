---
title: V Obchodě s termíny SharePointu Online chybí podmínky
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 54ac2dbc1f45f88541c2338f3b55a777b4b57123
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766846"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a><span data-ttu-id="3baeb-102">Povolení šifrování nástroje Bitlocker pomocí Intune</span><span class="sxs-lookup"><span data-stu-id="3baeb-102">Enabling Bitlocker Encryption with Intune</span></span>

<span data-ttu-id="3baeb-103">Zásady ochrany koncového bodu Intune lze použít ke konfiguraci nastavení šifrování Boitlocker u zařízení s Windows, jak je popsáno v : Nastavení Windows10 (a novější) k ochraně zařízení pomocí Intune</span><span class="sxs-lookup"><span data-stu-id="3baeb-103">Intune Endpoint Protection Policy can be used to configure Boitlocker encryption settings for Windows devices as described in : Windows10 (and later) settings to protect devices using Intune</span></span>

<span data-ttu-id="3baeb-104">Měli byste si být vědomi toho, že mnoho novějších zařízení se systémem Windows 10 podporuje automatické šifrování nástroje BitLocker, které se aktivuje bez použití zásad MDM.</span><span class="sxs-lookup"><span data-stu-id="3baeb-104">You should be aware that many newer devices running Windows 10 support automatic bitlocker encryption which is triggered without the application of MDM policy.</span></span> <span data-ttu-id="3baeb-105">To může mít vliv na použití zásady, pokud jsou nakonfigurována nevýchozí nastavení.</span><span class="sxs-lookup"><span data-stu-id="3baeb-105">This may impact application of policy if non default settings are configured.</span></span> <span data-ttu-id="3baeb-106">Další podrobnosti najdete v častých dotazech.</span><span class="sxs-lookup"><span data-stu-id="3baeb-106">See FAQ for more detail.</span></span>


<span data-ttu-id="3baeb-107">Častý  dotaz Q: Které edice systému Windows podporují šifrování zařízení pomocí zásad ochrany koncových bodů?</span><span class="sxs-lookup"><span data-stu-id="3baeb-107">FAQ  Q: Which editions of Windows support device encryption using the Endpoint Protection Policy?</span></span>
<span data-ttu-id="3baeb-108"> A: Nastavení v Zásadách ochrany koncového bodu Intune jsou implementovány pomocí nástroje CSP nástroje Bitlocker.</span><span class="sxs-lookup"><span data-stu-id="3baeb-108"> A: The settings in Intune Endpoint Protection Policy  are implemented using the Bitlocker CSP.</span></span><span data-ttu-id="3baeb-109">Ne všechny edice ani sestavení systému Windows podporují csp nástroje Bitlocker. 
     </span><span class="sxs-lookup"><span data-stu-id="3baeb-109">  Not all editions nor builds of Windows support the Bitlocker CSP. 
     </span></span> <span data-ttu-id="3baeb-110">V tomto okamžiku Windows Editions: Enterprise; Vzdělávání, Mobilní, Mobilní podnik a Professional (od sestavení 1809 dále) jsou podporovány.</span><span class="sxs-lookup"><span data-stu-id="3baeb-110">At this time Windows Editions: Enterprise; Education, Mobile, Mobile Enterprise and Professional (from build 1809 onwards) are supported.</span></span>




<span data-ttu-id="3baeb-111">Otázka: Pokud je zařízení již šifrováno pomocí nástroje Bitlocker pomocí výchozího nastavení operačního systému pro metodu šifrování a síla šifrování (XTS-AES-128), bude použití zásady s různými nastaveními automaticky aktivovat opětovné šifrování jednotky s novým nastavením?</span><span class="sxs-lookup"><span data-stu-id="3baeb-111">Q: If a device is already encrypted with Bitlocker using the OS default settings for encryption method and cipher strength (XTS-AES-128)  will applying a policy with different settings automatically trigger re-encryption of the drive with the new settings?</span></span>

<span data-ttu-id="3baeb-112">A: Ne.</span><span class="sxs-lookup"><span data-stu-id="3baeb-112">A: No.</span></span> <span data-ttu-id="3baeb-113">Chcete-li použít nové nastavení šifry, musí být jednotka nejprve dešifrována.</span><span class="sxs-lookup"><span data-stu-id="3baeb-113">In order to apply the new cipher settings the drive must first be decrypted.</span></span>

<span data-ttu-id="3baeb-114">Poznámka: U zařízení zaregistrovaných pomocí funkce Autopilot se automatické šifrování, ke kterému by došlo během OOBE, neaktivuje, dokud se nevyhodnotí zásady Intune, které umožňují použití nastavení na základě zásad namísto výchozích nastavení operačního systému</span><span class="sxs-lookup"><span data-stu-id="3baeb-114">Note For devices being enrolled with Autopilot the automatic encryption that would occur during OOBE is not triggered until Intune policy is evaluated which allows the policy based settings to be used in place of the OS defaults</span></span>




<span data-ttu-id="3baeb-115">Q Pokud je zařízení zašifrováno v důsledku použití zásad Intune, bude dešifrováno, když je tato zásada odebrána?</span><span class="sxs-lookup"><span data-stu-id="3baeb-115">Q If a device is encrypted as a result of the  application of Intune policy will it be decrypted when that policy is removed?</span></span>

<span data-ttu-id="3baeb-116">A: Odstranění zásad souvisejících s šifrováním nemá za následek dešifrování jednotek, které byly nakonfigurovány.</span><span class="sxs-lookup"><span data-stu-id="3baeb-116">A: Removal of encryption related policy does NOT result in decryption of the drives which were configured.</span></span>




<span data-ttu-id="3baeb-117">Otázka: Proč zásady dodržování předpisů intune ukazují, že moje zařízení nemá povoleno nástroj Bitlocker, ale je?</span><span class="sxs-lookup"><span data-stu-id="3baeb-117">Q: Why does intune Compliance policy show that my device does not have "Bitlocker Enabled" but it is?</span></span>

<span data-ttu-id="3baeb-118">A: Nastavení "Bitlocker povoleno" v zásadách dodržování předpisů intune využívá windows zařízení potvrzení stavu (DHA) klienta.</span><span class="sxs-lookup"><span data-stu-id="3baeb-118">A: The "Bitlocker enabled" setting in intune compliance policy utilizes the Windows Device Health Attestation  (DHA) client.</span></span> <span data-ttu-id="3baeb-119">Tento klient měří pouze stav zařízení při spuštění.</span><span class="sxs-lookup"><span data-stu-id="3baeb-119">This client only measures device state at boot time.</span></span> <span data-ttu-id="3baeb-120">Pokud tedy zařízení nebylo restartováno od dokončení šifrování nástrojem BitLocker, klientská služba DHA nenahlásí nástroj BitLocker jako aktivní.</span><span class="sxs-lookup"><span data-stu-id="3baeb-120">So if a device has not been rebooted since bitlocker encryption was completed the DHA client service will not report bitlocker as being active.</span></span>