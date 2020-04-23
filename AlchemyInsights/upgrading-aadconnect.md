---
title: 932 Inovace služby AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: fcc5fddb5cfd15407d0533449035317d187931ed
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766486"
---
# <a name="upgrade-azure-ad-connect"></a>Upgrade Azure AD Connect

Ve výchozím nastavení je pro Azure AD Connect povolen automatický upgrade, který pomáhá zajistit, že používáte nejnovější verzi. Chcete-li ověřit nastavení automatického upgradu, použijte rutinu **Get-ADSyncAutoUpgrade** v prostředí Azure AD PowerShell. Rutina vrátí jednu z následujících hodnot:

- **Povoleno**: Automatický upgrade je povolen.

- **Zakázáno**: Automatický upgrade je zakázán.

- **Pozastaveno**: Systém již není způsobilý pro automatické upgrady. Tuto hodnotu nelze nakonfigurovat. Je to nastaveno systémem.

Další informace naleznete v [tématu Automatický upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).

Pokud chcete stáhnout nejnovější verzi Služby [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)Azure AD Connect, přejděte na .
