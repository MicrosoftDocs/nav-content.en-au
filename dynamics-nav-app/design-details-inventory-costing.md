---
title: Design Details - Inventory Costing
description: This documentation provides detailed technical insight to the concepts and principles that are used within the Inventory Costing features in [!INCLUDE[d365fin](includes/d365fin_md.md)].
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, inventory, costing
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4b6db42020e62301bd882b679c2b6004374f0e49
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-inventory-costing"></a><span data-ttu-id="c5bf8-103">Design Details: Inventory Costing</span><span class="sxs-lookup"><span data-stu-id="c5bf8-103">Design Details: Inventory Costing</span></span>
<span data-ttu-id="c5bf8-104">This documentation provides detailed technical insight to the concepts and principles that are used within the Inventory Costing features in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="c5bf8-104">This documentation provides detailed technical insight to the concepts and principles that are used within the Inventory Costing features in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

<span data-ttu-id="c5bf8-105">Inventory costing, also referred to as cost management, is concerned with recording and reporting business operating costs.</span><span class="sxs-lookup"><span data-stu-id="c5bf8-105">Inventory costing, also referred to as cost management, is concerned with recording and reporting business operating costs.</span></span>  

## <a name="in-this-section"></a><span data-ttu-id="c5bf8-106">In This Section</span><span class="sxs-lookup"><span data-stu-id="c5bf8-106">In This Section</span></span>  
[<span data-ttu-id="c5bf8-107">Design Details: Costing Methods</span><span class="sxs-lookup"><span data-stu-id="c5bf8-107">Design Details: Costing Methods</span></span>](design-details-costing-methods.md)  
[<span data-ttu-id="c5bf8-108">Design Details: Item Application</span><span class="sxs-lookup"><span data-stu-id="c5bf8-108">Design Details: Item Application</span></span>](design-details-item-application.md)  
[<span data-ttu-id="c5bf8-109">Design Details: Cost Adjustment</span><span class="sxs-lookup"><span data-stu-id="c5bf8-109">Design Details: Cost Adjustment</span></span>](design-details-cost-adjustment.md)  
[<span data-ttu-id="c5bf8-110">Design Details: Expected Cost Posting</span><span class="sxs-lookup"><span data-stu-id="c5bf8-110">Design Details: Expected Cost Posting</span></span>](design-details-expected-cost-posting.md)  
[<span data-ttu-id="c5bf8-111">Design Details: Average Cost</span><span class="sxs-lookup"><span data-stu-id="c5bf8-111">Design Details: Average Cost</span></span>](design-details-average-cost.md)  
[<span data-ttu-id="c5bf8-112">Design Details: Variance</span><span class="sxs-lookup"><span data-stu-id="c5bf8-112">Design Details: Variance</span></span>](design-details-variance.md)  
[<span data-ttu-id="c5bf8-113">Design Details: Rounding</span><span class="sxs-lookup"><span data-stu-id="c5bf8-113">Design Details: Rounding</span></span>](design-details-rounding.md)  
[<span data-ttu-id="c5bf8-114">Design Details: Cost Components</span><span class="sxs-lookup"><span data-stu-id="c5bf8-114">Design Details: Cost Components</span></span>](design-details-cost-components.md)  
[<span data-ttu-id="c5bf8-115">Design Details: Inventory Periods</span><span class="sxs-lookup"><span data-stu-id="c5bf8-115">Design Details: Inventory Periods</span></span>](design-details-inventory-periods.md)  
[<span data-ttu-id="c5bf8-116">Design Details: Inventory Posting</span><span class="sxs-lookup"><span data-stu-id="c5bf8-116">Design Details: Inventory Posting</span></span>](design-details-inventory-posting.md)  
[<span data-ttu-id="c5bf8-117">Design Details: Production Order Posting</span><span class="sxs-lookup"><span data-stu-id="c5bf8-117">Design Details: Production Order Posting</span></span>](design-details-production-order-posting.md)  
[<span data-ttu-id="c5bf8-118">Design Details: Assembly Order Posting</span><span class="sxs-lookup"><span data-stu-id="c5bf8-118">Design Details: Assembly Order Posting</span></span>](design-details-assembly-order-posting.md)  
[<span data-ttu-id="c5bf8-119">Design Details: Reconciliation with the General Ledger</span><span class="sxs-lookup"><span data-stu-id="c5bf8-119">Design Details: Reconciliation with the General Ledger</span></span>](design-details-reconciliation-with-the-general-ledger.md)  
[<span data-ttu-id="c5bf8-120">Design Details: Accounts in the General Ledger</span><span class="sxs-lookup"><span data-stu-id="c5bf8-120">Design Details: Accounts in the General Ledger</span></span>](design-details-accounts-in-the-general-ledger.md)  
[<span data-ttu-id="c5bf8-121">Design Details: Revaluation</span><span class="sxs-lookup"><span data-stu-id="c5bf8-121">Design Details: Revaluation</span></span>](design-details-revaluation.md)
