---
title: How to Transfer General Ledger Entries to Cost Entries
description: You can transfer general ledger entries to cost entries.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b7a78fb1023e8b664fd866eb1a8b5e42ff0de265
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-general-ledger-entries-to-cost-entries"></a><span data-ttu-id="5acd8-103">How to: Transfer General Ledger Entries to Cost Entries</span><span class="sxs-lookup"><span data-stu-id="5acd8-103">How to: Transfer General Ledger Entries to Cost Entries</span></span>
<span data-ttu-id="5acd8-104">You can transfer general ledger entries to cost entries.</span><span class="sxs-lookup"><span data-stu-id="5acd8-104">You can transfer general ledger entries to cost entries.</span></span>  

<span data-ttu-id="5acd8-105">Before you run the process for transferring general ledger entries to cost entries, you must prepare the transfer to avoid manual correction posting.</span><span class="sxs-lookup"><span data-stu-id="5acd8-105">Before you run the process for transferring general ledger entries to cost entries, you must prepare the transfer to avoid manual correction posting.</span></span>  

## <a name="to-prepare-the-transfer"></a><span data-ttu-id="5acd8-106">To prepare the transfer</span><span class="sxs-lookup"><span data-stu-id="5acd8-106">To prepare the transfer</span></span>  

1.  <span data-ttu-id="5acd8-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cost Accounting Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5acd8-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cost Accounting Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="5acd8-108">In the **Cost Accounting Setup** window, verify that the **Starting Date for G/L Transfer** field is set to the correct value.</span><span class="sxs-lookup"><span data-stu-id="5acd8-108">In the **Cost Accounting Setup** window, verify that the **Starting Date for G/L Transfer** field is set to the correct value.</span></span>  
3.  <span data-ttu-id="5acd8-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Cost Types**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5acd8-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Cost Types**, and then choose the related link.</span></span>  
4.  <span data-ttu-id="5acd8-110">In the **Cost Type Card** window, verify that the **G/L Account Range** field is linked correctly for each cost type to take entries from the general ledger.</span><span class="sxs-lookup"><span data-stu-id="5acd8-110">In the **Cost Type Card** window, verify that the **G/L Account Range** field is linked correctly for each cost type to take entries from the general ledger.</span></span>  
5.  <span data-ttu-id="5acd8-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5acd8-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
6.  <span data-ttu-id="5acd8-112">For each relevant general ledger account, in the **G/L Account Card** window, verify that the **Cost Type No.**</span><span class="sxs-lookup"><span data-stu-id="5acd8-112">For each relevant general ledger account, in the **G/L Account Card** window, verify that the **Cost Type No.**</span></span> <span data-ttu-id="5acd8-113">field is linked correctly to a cost type.</span><span class="sxs-lookup"><span data-stu-id="5acd8-113">field is linked correctly to a cost type.</span></span> <span data-ttu-id="5acd8-114">For more information, see [Defining the Relationship Between Cost Types and General Ledger Accounts](finance-defining-the-relationship-between-cost-types-and-general-ledger-accounts.md).</span><span class="sxs-lookup"><span data-stu-id="5acd8-114">For more information, see [Defining the Relationship Between Cost Types and General Ledger Accounts](finance-defining-the-relationship-between-cost-types-and-general-ledger-accounts.md).</span></span>  
7.  <span data-ttu-id="5acd8-115">Verify that all relevant general ledger entries have dimension values that correspond to a cost centre and a cost object.</span><span class="sxs-lookup"><span data-stu-id="5acd8-115">Verify that all relevant general ledger entries have dimension values that correspond to a cost center and a cost object.</span></span>  

## <a name="to-transfer-general-ledger-entries-to-cost-entries"></a><span data-ttu-id="5acd8-116">To transfer general ledger entries to cost entries</span><span class="sxs-lookup"><span data-stu-id="5acd8-116">To transfer general ledger entries to cost entries</span></span>  
1.  <span data-ttu-id="5acd8-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Transfer GL Entries to CA**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5acd8-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Transfer GL Entries to CA**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="5acd8-118">Choose the **Yes** button to start the transfer.</span><span class="sxs-lookup"><span data-stu-id="5acd8-118">Choose the **Yes** button to start the transfer.</span></span> <span data-ttu-id="5acd8-119">The process transfers all general ledger entries that have not already been transferred.</span><span class="sxs-lookup"><span data-stu-id="5acd8-119">The process transfers all general ledger entries that have not already been transferred.</span></span>  

    <span data-ttu-id="5acd8-120">During the transfer, the process creates connections in the entries in the **Cost Entry** table and the **Cost Register** table.</span><span class="sxs-lookup"><span data-stu-id="5acd8-120">During the transfer, the process creates connections in the entries in the **Cost Entry** table and the **Cost Register** table.</span></span> <span data-ttu-id="5acd8-121">This makes it possible to trace the source of cost entries.</span><span class="sxs-lookup"><span data-stu-id="5acd8-121">This makes it possible to trace the source of cost entries.</span></span>  

## <a name="see-also"></a><span data-ttu-id="5acd8-122">See Also</span><span class="sxs-lookup"><span data-stu-id="5acd8-122">See Also</span></span>  
 <span data-ttu-id="5acd8-123">[Criteria for Transferring General Ledger Entries to Cost Entries](finance-criteria-for-transferring-general-ledger-entries-to-cost-entries.md) </span><span class="sxs-lookup"><span data-stu-id="5acd8-123">[Criteria for Transferring General Ledger Entries to Cost Entries](finance-criteria-for-transferring-general-ledger-entries-to-cost-entries.md) </span></span>  
 <span data-ttu-id="5acd8-124">[Automatic Transfer and Combined Entries](finance-automatic-transfer-combined-entries.md) </span><span class="sxs-lookup"><span data-stu-id="5acd8-124">[Automatic Transfer and Combined Entries](finance-automatic-transfer-combined-entries.md) </span></span>  
 <span data-ttu-id="5acd8-125">[Results of the Transfer](finance-results-of-the-transfer.md) </span><span class="sxs-lookup"><span data-stu-id="5acd8-125">[Results of the Transfer](finance-results-of-the-transfer.md) </span></span>  
 <span data-ttu-id="5acd8-126">[Transferring and Posting Cost Entries](finance-transfer-and-post-cost-entries.md) </span><span class="sxs-lookup"><span data-stu-id="5acd8-126">[Transferring and Posting Cost Entries](finance-transfer-and-post-cost-entries.md) </span></span>  
 [<span data-ttu-id="5acd8-127">Defining the Relationship Between Cost Types and General Ledger Accounts</span><span class="sxs-lookup"><span data-stu-id="5acd8-127">Defining the Relationship Between Cost Types and General Ledger Accounts</span></span>](finance-defining-the-relationship-between-cost-types-and-general-ledger-accounts.md)   
