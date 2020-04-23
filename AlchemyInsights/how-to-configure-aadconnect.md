---
title: 646 Jak nakonfigurovat AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "646"
- "1300023"
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 713cda26e55f07f0438cb9ebe5aa9da86c4ebb3a
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43722524"
---
# <a name="configure-sync-features"></a><span data-ttu-id="43ed6-102">Konfigurace funkcí synchronizace</span><span class="sxs-lookup"><span data-stu-id="43ed6-102">Configure sync features</span></span>

<span data-ttu-id="43ed6-103">Azure AD Connect obsahuje několik funkcí, které jsou ve výchozím nastavení povolené nebo které můžete povolit později.</span><span class="sxs-lookup"><span data-stu-id="43ed6-103">Azure AD Connect includes several features that are enabled by default, or that you can enable later.</span></span> <span data-ttu-id="43ed6-104">Některé funkce vyžadují další konfiguraci v konkrétních prostředích.</span><span class="sxs-lookup"><span data-stu-id="43ed6-104">Some features require additional configuration in specific environments.</span></span>

- <span data-ttu-id="43ed6-105">[Omezení filtrování](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) objekty jsou synchronizovány do Služby Azure AD.</span><span class="sxs-lookup"><span data-stu-id="43ed6-105">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD.</span></span> <span data-ttu-id="43ed6-106">Ve výchozím nastavení jsou synchronizovány všechny účty počítačů uživatelů, kontaktů, skupin a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="43ed6-106">By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized.</span></span> <span data-ttu-id="43ed6-107">Můžete zahrnout nebo vyloučit objekty založené na doménách, vou nebo jiných atributech.</span><span class="sxs-lookup"><span data-stu-id="43ed6-107">You can include or exclude objects based on domains, OUs, or other attributes.</span></span>

- <span data-ttu-id="43ed6-108">[Synchronizace hodnot hash hesla](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizuje hodnotu hash hesla z místní služby Active Directory do služby Azure AD.</span><span class="sxs-lookup"><span data-stu-id="43ed6-108">[Password hash synchronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD.</span></span> <span data-ttu-id="43ed6-109">To umožňuje správu hesel na jednom místě, ale použití stejného hesla v místním i cloudovém prostředí.</span><span class="sxs-lookup"><span data-stu-id="43ed6-109">This allows password management in one location, but use of the same password in both on-premises and cloud environments.</span></span> <span data-ttu-id="43ed6-110">Vzhledem k tomu, že směrodatným zdrojem je služba Active Directory, můžete použít vlastní zásady hesel.</span><span class="sxs-lookup"><span data-stu-id="43ed6-110">Because Active Directory is the authoritative source, you can use your own password policies.</span></span>

- <span data-ttu-id="43ed6-111">[Samoobslužné resetování hesla (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) umožňuje uživatelům resetovat vlastní hesla v cloudu a zároveň stále používat místní zásady hesel.</span><span class="sxs-lookup"><span data-stu-id="43ed6-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span>

- <span data-ttu-id="43ed6-112">[Zpětný zápis zařízení](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) umožňuje registrovaným zařízením ve službě Azure AD, která mají být zapsána zpět do místní služby Active Directory, aby je bylo možné použít pro podmíněný přístup.</span><span class="sxs-lookup"><span data-stu-id="43ed6-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span>

- <span data-ttu-id="43ed6-113">[Zabránit náhodnému odstranění](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) je ve výchozím nastavení povoleno, aby se zabránilo příliš mnoha souběžným odstraněním objektů (více než 500 objektů na synchronizaci).</span><span class="sxs-lookup"><span data-stu-id="43ed6-113">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization).</span></span> <span data-ttu-id="43ed6-114">Toto nastavení můžete změnit tak, aby vyhovovalo potřebám vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="43ed6-114">You can change this setting to meet the needs of your organization.</span></span>

- <span data-ttu-id="43ed6-115">[Automatický upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je ve výchozím nastavení povolen pro expresní instalace a pomáhá zajistit, aby vaše verze Služby Azure AD Connect byla vždy aktuální.</span><span class="sxs-lookup"><span data-stu-id="43ed6-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span>
