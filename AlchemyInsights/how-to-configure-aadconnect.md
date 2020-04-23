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
# <a name="configure-sync-features"></a>Konfigurace funkcí synchronizace

Azure AD Connect obsahuje několik funkcí, které jsou ve výchozím nastavení povolené nebo které můžete povolit později. Některé funkce vyžadují další konfiguraci v konkrétních prostředích.

- [Omezení filtrování](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) objekty jsou synchronizovány do Služby Azure AD. Ve výchozím nastavení jsou synchronizovány všechny účty počítačů uživatelů, kontaktů, skupin a Windows 10. Můžete zahrnout nebo vyloučit objekty založené na doménách, vou nebo jiných atributech.

- [Synchronizace hodnot hash hesla](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizuje hodnotu hash hesla z místní služby Active Directory do služby Azure AD. To umožňuje správu hesel na jednom místě, ale použití stejného hesla v místním i cloudovém prostředí. Vzhledem k tomu, že směrodatným zdrojem je služba Active Directory, můžete použít vlastní zásady hesel.

- [Samoobslužné resetování hesla (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) umožňuje uživatelům resetovat vlastní hesla v cloudu a zároveň stále používat místní zásady hesel.

- [Zpětný zápis zařízení](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) umožňuje registrovaným zařízením ve službě Azure AD, která mají být zapsána zpět do místní služby Active Directory, aby je bylo možné použít pro podmíněný přístup.

- [Zabránit náhodnému odstranění](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) je ve výchozím nastavení povoleno, aby se zabránilo příliš mnoha souběžným odstraněním objektů (více než 500 objektů na synchronizaci). Toto nastavení můžete změnit tak, aby vyhovovalo potřebám vaší organizace.

- [Automatický upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je ve výchozím nastavení povolen pro expresní instalace a pomáhá zajistit, aby vaše verze Služby Azure AD Connect byla vždy aktuální.
