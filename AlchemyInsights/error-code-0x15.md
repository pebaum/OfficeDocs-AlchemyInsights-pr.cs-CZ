---
title: Kód chyby 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Pokud se zobrazuje chyba při aktivaci sady Office 2013 na nasazení služby Remote Desktop Services (RDS), zvažte povolení ADAL úpravou registru.
ms.openlocfilehash: 89f9270169e13fd7706f7826c624ef8ae4d47b3f
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29499375"
---
<span data-ttu-id="07377-103">Pokud se zobrazuje chyba při aktivaci sady Office 2013 na nasazení služby Remote Desktop Services (RDS), zvažte povolení ADAL úpravou registru.</span><span class="sxs-lookup"><span data-stu-id="07377-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="07377-104">**Klíč registru**</span><span class="sxs-lookup"><span data-stu-id="07377-104">**Registry key**</span></span>|<span data-ttu-id="07377-105">**Typ**</span><span class="sxs-lookup"><span data-stu-id="07377-105">**Type**</span></span>|<span data-ttu-id="07377-106">**Value (Hodnota)**</span><span class="sxs-lookup"><span data-stu-id="07377-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="07377-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="07377-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="07377-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="07377-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="07377-109">1.</span><span class="sxs-lookup"><span data-stu-id="07377-109">1</span></span>  <br/> |
   
<span data-ttu-id="07377-110">Další informace naleznete v tématu [Povolení moderní ověřování Office 2013 na zařízení systému Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="07377-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="07377-p101">ADAL je povolena ve výchozím nastavení sady Office 365 ProPlus a Office 2016. > remote Desktop Services (RDS) se dříve nazývala Terminálové služby.</span><span class="sxs-lookup"><span data-stu-id="07377-p101">ADAL is enabled by default in Office 365 ProPlus and Office 2016. >  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  

