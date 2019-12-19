---
title: Při ověřování chyby přístupového tokenu při kontrole služby Desktop Analytics došlo k chybě.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2536"
- "9000657"
ms.openlocfilehash: 7472af5c4e19e5697b5fb4802ed1cbb2c74f1d19
ms.sourcegitcommit: f1fad2129d09660ec42dbce03ce2c6b4cfc9555a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/18/2019
ms.locfileid: "40741142"
---
# <a name="there-was-an-error-validating-access-token-error-during-desktop-analytics-onboarding"></a><span data-ttu-id="35f77-102">Při kontrole přístupového tokenu došlo k chybě při ověřování plochy</span><span class="sxs-lookup"><span data-stu-id="35f77-102">"There was an error validating access token" error during Desktop Analytics onboarding</span></span>

<span data-ttu-id="35f77-103">Tato chyba je obvykle dodržena při vypršení ověřovacího tokenu.</span><span class="sxs-lookup"><span data-stu-id="35f77-103">This error is normally observed when the authentication token expires.</span></span> <span data-ttu-id="35f77-104">Aktualizace stránky obvykle aktualizuje token.</span><span class="sxs-lookup"><span data-stu-id="35f77-104">Usually, refreshing the page refreshes the token.</span></span> <span data-ttu-id="35f77-105">Tento problém však může přetrvávat v případě, že u účtu, který je použit pro palubní službu Analytics, jsou použity zásady podmíněného přístupu.</span><span class="sxs-lookup"><span data-stu-id="35f77-105">However, this issue can persist if there are any Conditional Access policies applied to the account being used to on-board Desktop Analytics.</span></span> <span data-ttu-id="35f77-106">Chcete-li zjistit, zda u účtu používaného pro službu Desktop Analytics došlo k chybám, zkontrolujte protokoly Azure AD-in v Azure portálu.</span><span class="sxs-lookup"><span data-stu-id="35f77-106">You can review the Azure AD Sign In logs in the Azure Portal to see if there are any sign-in failures for the account being used for Desktop Analytics onboarding.</span></span>

<span data-ttu-id="35f77-107">Další informace o podmíněném přístupu naleznete v [plánu nasazení podmíněného přístupu](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span><span class="sxs-lookup"><span data-stu-id="35f77-107">For more information about Conditional Access, visit [Plan your Conditional Access deployment](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span></span>