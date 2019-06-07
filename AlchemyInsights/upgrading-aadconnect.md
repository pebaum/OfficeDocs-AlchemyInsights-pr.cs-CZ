---
title: 932 AADConnect inovace
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 932
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 210f230929db72027a0f729b17901fe88eb45709
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34757284"
---
# <a name="upgrade-azure-ad-connect"></a>Inovace Azure AD připojit

Standardně je povoleno automatické inovace pro Azure AD připojit, což pomůže zajistit, že používáte nejnovější verzi. Chcete-li ověřit nastavení automatického upgradu, použijte rutiny **Get-ADSyncAutoUpgrade** v prostředí PowerShell Azure AD. Rutiny vrátí jednu z následujících hodnot: 

- **Povoleno**: je povolen automatický upgrade.

- **Zakázáno**: automatický upgrade je zakázáno.

- **Suspended**: systém je již oprávněni přijímat automatické upgrady. Nelze nastavit tuto hodnotu; systém je nastaven. 

Další informace naleznete v tématu [automatické inovace](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).

Chcete-li stáhnout nejnovější verzi Azure AD připojit, přejděte na [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).
