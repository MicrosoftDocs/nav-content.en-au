---
title: Design Details - The Role of the Reorder Point
description: This topic highlights the importance of setting a reorder point, so that you when to order more inventory.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: desigh, reorder, demand, supply
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8035a670077e53981e9c366d22bdb20df06d8c1b
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-the-role-of-the-reorder-point"></a><span data-ttu-id="c9b58-103">Design Details: The Role of the Reorder Point</span><span class="sxs-lookup"><span data-stu-id="c9b58-103">Design Details: The Role of the Reorder Point</span></span>
<span data-ttu-id="c9b58-104">In addition to the general balancing of supply and demand, the planning system must also monitor inventory levels for the affected items to respect the defined reordering policies.</span><span class="sxs-lookup"><span data-stu-id="c9b58-104">In addition to the general balancing of supply and demand, the planning system must also monitor inventory levels for the affected items to respect the defined reordering policies.</span></span>  
  
<span data-ttu-id="c9b58-105">A reorder point represents demand during lead time.</span><span class="sxs-lookup"><span data-stu-id="c9b58-105">A reorder point represents demand during lead time.</span></span> <span data-ttu-id="c9b58-106">When the projected inventory passes below the inventory level defined by the reorder point, it is time to order more quantity.</span><span class="sxs-lookup"><span data-stu-id="c9b58-106">When the projected inventory passes below the inventory level defined by the reorder point, it is time to order more quantity.</span></span> <span data-ttu-id="c9b58-107">Meanwhile, the inventory is expected to decrease gradually and possibly reach zero (or the safety stock level), until the replenishment arrives.</span><span class="sxs-lookup"><span data-stu-id="c9b58-107">Meanwhile, the inventory is expected to decrease gradually and possibly reach zero (or the safety stock level), until the replenishment arrives.</span></span>  
  
<span data-ttu-id="c9b58-108">Accordingly, the planning system will suggest a forward-scheduled supply order at the point when the projected inventory passes below the reorder point.</span><span class="sxs-lookup"><span data-stu-id="c9b58-108">Accordingly, the planning system will suggest a forward-scheduled supply order at the point when the projected inventory passes below the reorder point.</span></span>  
  
<span data-ttu-id="c9b58-109">The reorder point reflects a certain inventory level.</span><span class="sxs-lookup"><span data-stu-id="c9b58-109">The reorder point reflects a certain inventory level.</span></span> <span data-ttu-id="c9b58-110">However, inventory levels can move significantly during the time bucket and, therefore, the planning system must constantly monitor the projected available inventory.</span><span class="sxs-lookup"><span data-stu-id="c9b58-110">However, inventory levels can move significantly during the time bucket and, therefore, the planning system must constantly monitor the projected available inventory.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="c9b58-111">See Also</span><span class="sxs-lookup"><span data-stu-id="c9b58-111">See Also</span></span>  
<span data-ttu-id="c9b58-112">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="c9b58-112">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
<span data-ttu-id="c9b58-113">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="c9b58-113">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="c9b58-114">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="c9b58-114">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
[<span data-ttu-id="c9b58-115">Design Details: Supply Planning</span><span class="sxs-lookup"><span data-stu-id="c9b58-115">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)