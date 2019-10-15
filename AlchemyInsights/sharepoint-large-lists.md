---
title: Velké seznamy služby SharePoint
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 2/12/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "407"
- "530001"
ms.assetid: ee07bf74-7aeb-4c47-8f5d-f496d6c09d79
ms.openlocfilehash: 222ad554de0d94dcfd4e34e9a2c6aa8ab4e6f81f
ms.sourcegitcommit: d7e1b097d3866782f508527c797426dc56c6ba17
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/14/2019
ms.locfileid: "37488510"
---
# <a name="work-with-large-lists-and-libraries-in-sharepoint"></a><span data-ttu-id="eb558-102">Práce s velkými seznamy a knihovnami ve službě SharePoint</span><span class="sxs-lookup"><span data-stu-id="eb558-102">Work with large lists and libraries in SharePoint</span></span>

<span data-ttu-id="eb558-103">Seznamy a knihovny SharePoint mohou obsahovat až 30 000 000 položek, ale pokud mají více než 5 000 položek, může se při pokusu o práci s nimi zobrazit chyba prahové hodnoty zobrazení seznamu.</span><span class="sxs-lookup"><span data-stu-id="eb558-103">SharePoint lists and libraries can contain up to 30 million items, but when they have more than 5,000 items, you might see a List View Threshold error when you try to work with them.</span></span> <span data-ttu-id="eb558-104">Tato prahová hodnota je v místě, aby byla zachována výkonnost služby.</span><span class="sxs-lookup"><span data-stu-id="eb558-104">This threshold is in place to maintain performance of the service.</span></span> <span data-ttu-id="eb558-105">Nedá se to změnit.</span><span class="sxs-lookup"><span data-stu-id="eb558-105">It can't be changed.</span></span> <span data-ttu-id="eb558-106">Chcete-li předejít bití této prahové hodnoty:</span><span class="sxs-lookup"><span data-stu-id="eb558-106">To avoid hitting this threshold:</span></span>

<span data-ttu-id="eb558-107">**Použít moderní**</span><span class="sxs-lookup"><span data-stu-id="eb558-107">**Use modern**</span></span>

<span data-ttu-id="eb558-108">Pohledy zobrazující mnoho položek fungují nejlépe v moderních zkušenostech.</span><span class="sxs-lookup"><span data-stu-id="eb558-108">Views showing many items work best in the modern experience.</span></span> <span data-ttu-id="eb558-109">[Použijte moderní zkušenost](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) , abyste zabránili chybám, které byste mohli vidět v klasickém zážitku.</span><span class="sxs-lookup"><span data-stu-id="eb558-109">[Use the modern experience](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) to avoid errors you might see in the classic experience.</span></span>

<span data-ttu-id="eb558-110">**Přidání indexů**</span><span class="sxs-lookup"><span data-stu-id="eb558-110">**Add indexes**</span></span>

<span data-ttu-id="eb558-111">Při filtrování nebo řazení podle sloupce, který neobsahuje rejstřík, se může zobrazit chybová zpráva.</span><span class="sxs-lookup"><span data-stu-id="eb558-111">When you filter or sort by a column that doesn't have an index, you might see an error message.</span></span> <span data-ttu-id="eb558-112">Ručně [přidejte rejstřík](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) z **Nastavení seznamu** v nabídce nastavení a poté **indexované sloupce**.</span><span class="sxs-lookup"><span data-stu-id="eb558-112">[Add an index](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manually from **List Settings** in the settings menu, then **Indexed Columns**.</span></span>

<span data-ttu-id="eb558-113">**Upravit zobrazení seznamu**</span><span class="sxs-lookup"><span data-stu-id="eb558-113">**Edit the list view**</span></span>

<span data-ttu-id="eb558-114">Pokud při práci s velkým seznamem dojde k chybě, [upravte zobrazení seznamu](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span><span class="sxs-lookup"><span data-stu-id="eb558-114">If an error occurs when working with a large list, [edit your list view](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span></span>

<span data-ttu-id="eb558-115">Při následujících čtyřech změnách budou odebrány chyby prahu zobrazení seznamu.</span><span class="sxs-lookup"><span data-stu-id="eb558-115">The following four changes will remove list view threshold errors.</span></span> <span data-ttu-id="eb558-116">Proveďte všechny čtyři změny, abyste odstranili všechny chyby.</span><span class="sxs-lookup"><span data-stu-id="eb558-116">Make all four changes to remove all errors.</span></span> <span data-ttu-id="eb558-117">Pokud se stále zobrazují chyby, zkontrolujte [správu rozsáhlých seznamů a knihoven](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span><span class="sxs-lookup"><span data-stu-id="eb558-117">If you are still getting errors, check [Manage large lists and libraries](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span></span>

1. <span data-ttu-id="eb558-118">Vyberte **žádný** z obou **pořadí podle sloupce** a **potom seřaďte podle sloupce**.</span><span class="sxs-lookup"><span data-stu-id="eb558-118">Select **None** from both **First sort by the column** and **Then sort by the column**.</span></span>
2. <span data-ttu-id="eb558-119">**Podle sloupce** vyberte **žádný** z obou prvních skupin a **poté seskupte podle sloupce**.</span><span class="sxs-lookup"><span data-stu-id="eb558-119">Select **None** from both **First group by the column** and **Then group by the column**.</span></span>
3. <span data-ttu-id="eb558-120">V části **součty** vyberte možnost **žádný** pro všechny sloupce.</span><span class="sxs-lookup"><span data-stu-id="eb558-120">Select **None** for all columns in the **Totals** section.</span></span>
4. <span data-ttu-id="eb558-121">V sekci **sloupce** odznačte všechny sloupce kromě jednoho.</span><span class="sxs-lookup"><span data-stu-id="eb558-121">Deselect all but one column for display from the **Columns** section.</span></span>

