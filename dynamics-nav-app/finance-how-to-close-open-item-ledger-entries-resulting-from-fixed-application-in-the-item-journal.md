---
title: How to Close Open Item Ledger Entries Resulting from Fixed Application in the Item Journal
description: You can use the **Applies-from Entry** field in the **Item Journal** window to create a fixed application between an inbound transaction and the original outbound transaction. For example, to correct the outbound transaction or to process its return.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/09/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b0b0daad01f8108d035739e387b38af4f0311ff9
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-close-open-item-ledger-entries-resulting-from-fixed-application-in-the-item-journal"></a><span data-ttu-id="eeefe-104">How to: Close Open Item Ledger Entries Resulting from Fixed Application in the Item Journal</span><span class="sxs-lookup"><span data-stu-id="eeefe-104">How to: Close Open Item Ledger Entries Resulting from Fixed Application in the Item Journal</span></span>
<span data-ttu-id="eeefe-105">You can use the **Applies-from Entry** field in the **Item Journal** window to create a fixed application between an inbound transaction and the original outbound transaction.</span><span class="sxs-lookup"><span data-stu-id="eeefe-105">You can use the **Applies-from Entry** field in the **Item Journal** window to create a fixed application between an inbound transaction and the original outbound transaction.</span></span> <span data-ttu-id="eeefe-106">For example, to correct the outbound transaction or to process its return.</span><span class="sxs-lookup"><span data-stu-id="eeefe-106">For example, to correct the outbound transaction or to process its return.</span></span> <span data-ttu-id="eeefe-107">For more information, see Applies-from Entry.</span><span class="sxs-lookup"><span data-stu-id="eeefe-107">For more information, see Applies-from Entry.</span></span>  

> [!IMPORTANT]  
>  <span data-ttu-id="eeefe-108">Fixed applications made in this manner only apply the cost, not the quantity.</span><span class="sxs-lookup"><span data-stu-id="eeefe-108">Fixed applications made in this manner only apply the cost, not the quantity.</span></span> <span data-ttu-id="eeefe-109">Accordingly, the posted positive item ledger entry will not close the applied outbound entry and will itself remain open.</span><span class="sxs-lookup"><span data-stu-id="eeefe-109">Accordingly, the posted positive item ledger entry will not close the applied outbound entry and will itself remain open.</span></span> <span data-ttu-id="eeefe-110">This also applies when you post a fixed application for a positive entry to a negative entry that has not been closed by a regular positive entry, then both the negative and the positive entries will remain open.</span><span class="sxs-lookup"><span data-stu-id="eeefe-110">This also applies when you post a fixed application for a positive entry to a negative entry that has not been closed by a regular positive entry, then both the negative and the positive entries will remain open.</span></span>  
>   
>  <span data-ttu-id="eeefe-111">This also means that you cannot close an inventory period if such an entry exists.</span><span class="sxs-lookup"><span data-stu-id="eeefe-111">This also means that you cannot close an inventory period if such an entry exists.</span></span>  

<span data-ttu-id="eeefe-112">The following procedure shows how to close such entries by performing two corrective postings in the item journal.</span><span class="sxs-lookup"><span data-stu-id="eeefe-112">The following procedure shows how to close such entries by performing two corrective postings in the item journal.</span></span>  

## <a name="to-close-open-item-ledger-entries-that-result-from-a-fixed-application-in-the-item-journal"></a><span data-ttu-id="eeefe-113">To close open item ledger entries that result from a fixed application in the item journal</span><span class="sxs-lookup"><span data-stu-id="eeefe-113">To close open item ledger entries that result from a fixed application in the item journal</span></span>  

1.  <span data-ttu-id="eeefe-114">Use the **Applies-from Entry** field to post a positive adjustment with the corresponding quantity.</span><span class="sxs-lookup"><span data-stu-id="eeefe-114">Use the **Applies-from Entry** field to post a positive adjustment with the corresponding quantity.</span></span> <span data-ttu-id="eeefe-115">This closes the original negative entry with a fixed application.</span><span class="sxs-lookup"><span data-stu-id="eeefe-115">This closes the original negative entry with a fixed application.</span></span>  
2.  <span data-ttu-id="eeefe-116">Use the **Applies-to Entry** field to post a negative adjustment.</span><span class="sxs-lookup"><span data-stu-id="eeefe-116">Use the **Applies-to Entry** field to post a negative adjustment.</span></span> <span data-ttu-id="eeefe-117">This closes the original corrective positive entry with a fixed application.</span><span class="sxs-lookup"><span data-stu-id="eeefe-117">This closes the original corrective positive entry with a fixed application.</span></span>  

## <a name="see-also"></a><span data-ttu-id="eeefe-118">See Also</span><span class="sxs-lookup"><span data-stu-id="eeefe-118">See Also</span></span>  
[<span data-ttu-id="eeefe-119"> How to: Remove and Reapply Item Ledger Entries</span><span class="sxs-lookup"><span data-stu-id="eeefe-119"> How to: Remove and Reapply Item Ledger Entries</span></span>](finance-how-to-remove-and-reapply-item-entries.md)  
 <span data-ttu-id="eeefe-120">[How to: Process Sales Returns and Cancellations](sales-how-process-sales-returns-cancellations.md) </span><span class="sxs-lookup"><span data-stu-id="eeefe-120">[How to: Process Sales Returns and Cancellations](sales-how-process-sales-returns-cancellations.md) </span></span>  
 <span data-ttu-id="eeefe-121">[Setting Up Inventory Valuation and Costing](finance-set-up-inventory-valuation-and-costing.md) </span><span class="sxs-lookup"><span data-stu-id="eeefe-121">[Setting Up Inventory Valuation and Costing](finance-set-up-inventory-valuation-and-costing.md) </span></span>  
 <span data-ttu-id="eeefe-122">[Managing Inventory Costs](finance-manage-inventory-costs.md) </span><span class="sxs-lookup"><span data-stu-id="eeefe-122">[Managing Inventory Costs](finance-manage-inventory-costs.md) </span></span>  
 [<span data-ttu-id="eeefe-123">Design Details: Costing Methods</span><span class="sxs-lookup"><span data-stu-id="eeefe-123">Design Details: Costing Methods</span></span>](design-details-costing-methods.md)
