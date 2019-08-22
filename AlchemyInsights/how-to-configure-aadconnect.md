---
title: 646 jak konfigurovat AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "646"
- "1300023"
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 316d7253494c55a9bc94797d493897c2ddec516c
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36541578"
---
# <a name="configure-sync-features"></a><span data-ttu-id="7c3f4-102">Konfigurace funkce synchronizace</span><span class="sxs-lookup"><span data-stu-id="7c3f4-102">Configure sync features</span></span>

<span data-ttu-id="7c3f4-103">Azure AD připojit obsahuje několik funkcí, které jsou ve výchozím nastavení povolena, nebo můžete povolit později.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-103">Azure AD Connect includes several features that are enabled by default, or that you can enable later.</span></span> <span data-ttu-id="7c3f4-104">Některé funkce vyžadují další konfiguraci v konkrétním prostředí.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-104">Some features require additional configuration in specific environments.</span></span>

- <span data-ttu-id="7c3f4-105">Omezení [filtrování](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) objektů jsou synchronizovány do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-105">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD.</span></span> <span data-ttu-id="7c3f4-106">Ve výchozím nastavení, všechny uživatelé, kontakty, skupiny a Windows 10 účtů počítače synchronizovány.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-106">By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized.</span></span> <span data-ttu-id="7c3f4-107">Můžete zahrnout nebo vyloučit objekty založené na doménách, organizačních jednotkách nebo jiných atributech.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-107">You can include or exclude objects based on domains, OUs, or other attributes.</span></span>

- <span data-ttu-id="7c3f4-108">[Synchronizace hesel hash](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizuje hodnotu hash hesla adresářové služby Active Directory v prostorách Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-108">[Password hash synchronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD.</span></span> <span data-ttu-id="7c3f4-109">To umožňuje správu hesel na jednom místě, ale použít stejné heslo v obou místních a cloudových prostředí.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-109">This allows password management in one location, but use of the same password in both on-premises and cloud environments.</span></span> <span data-ttu-id="7c3f4-110">Vzhledem k tomu, že služba Active Directory je autoritativní zdroj, můžete použít vlastní zásady hesla.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-110">Because Active Directory is the authoritative source, you can use your own password policies.</span></span>

- <span data-ttu-id="7c3f4-111">[Obnovení hesla samoobslužné (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) umožňuje uživatelům obnovit hesla v cloudu přitom stále použít místní zásady hesla.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span>

- <span data-ttu-id="7c3f4-112">[Zpětný zápis zařízení](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) umožňuje registrovaným zařízením v Azure AD pro zápis zpět do služby Active Directory v prostorách tak slouží pro podmíněný přístup.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span>

- <span data-ttu-id="7c3f4-113">[Zabránit náhodnému odstranění](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) je povoleno ve výchozím nastavení pomáhá zabránit odstranění příliš mnoho souběžných objektu (více než 500 objektů na synchronizaci).</span><span class="sxs-lookup"><span data-stu-id="7c3f4-113">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization).</span></span> <span data-ttu-id="7c3f4-114">Můžete změnit toto nastavení podle potřeb vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-114">You can change this setting to meet the needs of your organization.</span></span>

- <span data-ttu-id="7c3f4-115">[Automatický upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je povolena ve výchozím nastavení pro expresní instalace a pomáhá zajistit, že vaše verze Azure AD připojit, je vždy aktuální.</span><span class="sxs-lookup"><span data-stu-id="7c3f4-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span>
