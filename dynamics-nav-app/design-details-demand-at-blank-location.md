---
title: Design Details - Demand and Supply
description: This topic introduces the concept of demand, which is the common term used for any kind of gross demand, such as a sales order and component need from a production order.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, demand, supply, inventory, planning
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d744b55835f5553e249a536e0fca0eb0046fda7b
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-demand-and-supply"></a><span data-ttu-id="d1a56-103">Design Details: Demand and Supply</span><span class="sxs-lookup"><span data-stu-id="d1a56-103">Design Details: Demand and Supply</span></span>
<span data-ttu-id="d1a56-104">Demand is the common term used for any kind of gross demand, such as a sales order and component need from a production order.</span><span class="sxs-lookup"><span data-stu-id="d1a56-104">Demand is the common term used for any kind of gross demand, such as a sales order and component need from a production order.</span></span> <span data-ttu-id="d1a56-105">In addition, the program allows more technical types of demand, such as negative inventory and purchase returns.</span><span class="sxs-lookup"><span data-stu-id="d1a56-105">In addition, the program allows more technical types of demand, such as negative inventory and purchase returns.</span></span>  
  
<span data-ttu-id="d1a56-106">Supply is the common term used for any kind of positive or inbound quantity, such as inventory, purchases, assembly, production, or inbound transfers.</span><span class="sxs-lookup"><span data-stu-id="d1a56-106">Supply is the common term used for any kind of positive or inbound quantity, such as inventory, purchases, assembly, production, or inbound transfers.</span></span> <span data-ttu-id="d1a56-107">In addition, a sales return may also represent supply.</span><span class="sxs-lookup"><span data-stu-id="d1a56-107">In addition, a sales return may also represent supply.</span></span>  
  
<span data-ttu-id="d1a56-108">To sort out the many sources of demand and supply, the planning system organises them on two time lines called inventory profiles.</span><span class="sxs-lookup"><span data-stu-id="d1a56-108">To sort out the many sources of demand and supply, the planning system organizes them on two time lines called inventory profiles.</span></span> <span data-ttu-id="d1a56-109">One profile holds demand events, and the other holds the corresponding supply events.</span><span class="sxs-lookup"><span data-stu-id="d1a56-109">One profile holds demand events, and the other holds the corresponding supply events.</span></span> <span data-ttu-id="d1a56-110">Each event represents one order network entity, such as a sales order line, an item ledger entry, or a production order line.</span><span class="sxs-lookup"><span data-stu-id="d1a56-110">Each event represents one order network entity, such as a sales order line, an item ledger entry, or a production order line.</span></span>  
  
<span data-ttu-id="d1a56-111">When inventory profiles are loaded, the different demand-supply sets are balanced to output a supply plan that fulfills the listed goals.</span><span class="sxs-lookup"><span data-stu-id="d1a56-111">When inventory profiles are loaded, the different demand-supply sets are balanced to output a supply plan that fulfills the listed goals.</span></span>  
  
<span data-ttu-id="d1a56-112">Planning parameters and inventory levels are other types of demand and supply respectively, which undergo integrated balancing to replenish stock items.</span><span class="sxs-lookup"><span data-stu-id="d1a56-112">Planning parameters and inventory levels are other types of demand and supply respectively, which undergo integrated balancing to replenish stock items.</span></span> <span data-ttu-id="d1a56-113">For more information, see [Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md).</span><span class="sxs-lookup"><span data-stu-id="d1a56-113">For more information, see [Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md).</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="d1a56-114">See Also</span><span class="sxs-lookup"><span data-stu-id="d1a56-114">See Also</span></span>  
<span data-ttu-id="d1a56-115">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="d1a56-115">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
<span data-ttu-id="d1a56-116">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span><span class="sxs-lookup"><span data-stu-id="d1a56-116">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span></span>  
[<span data-ttu-id="d1a56-117">Design Details: Supply Planning</span><span class="sxs-lookup"><span data-stu-id="d1a56-117">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)