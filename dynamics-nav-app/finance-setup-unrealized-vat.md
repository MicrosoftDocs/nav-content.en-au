---
title: Setting Up Unrealized Value Added Tax
description: If you're using cash-based accounting, you can specify how to handle unrealised GST for sales and purchases.
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cash, VAT, unrealized, cash-based
ms.date: 09/08/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f5786a79e8f12bd86b3d6f7ce53e0c698b19cef4
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-set-up-unrealized-vat-for-cash-based-accounting"></a><span data-ttu-id="84e4b-103">How to: Set Up Unrealised GST for Cash-Based Accounting</span><span class="sxs-lookup"><span data-stu-id="84e4b-103">How to: Set Up Unrealized VAT for Cash-Based Accounting</span></span>
<span data-ttu-id="84e4b-104">If you're using cash-based accounting methods, you can set up [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] to handle unrealized VAT.</span><span class="sxs-lookup"><span data-stu-id="84e4b-104">If you're using cash-based accounting methods, you can set up [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] to handle unrealized VAT.</span></span>

## <a name="to-use-general-ledger-accounts-for-unrealized-vat"></a><span data-ttu-id="84e4b-105">To use general ledger accounts for unrealised GST</span><span class="sxs-lookup"><span data-stu-id="84e4b-105">To use general ledger accounts for unrealized VAT</span></span>
<span data-ttu-id="84e4b-106">You can choose to have GST amounts calculated and posted to a temporary general ledger account when an invoice is posted, and then posted to the correct general ledger account and included in GST statements when the actual payment of the invoice is posted.</span><span class="sxs-lookup"><span data-stu-id="84e4b-106">You can choose to have VAT amounts calculated and posted to a temporary general ledger account when an invoice is posted, and then posted to the correct general ledger account and included in VAT statements when the actual payment of the invoice is posted.</span></span> <span data-ttu-id="84e4b-107">Before you can do this, you must complete the GST posting setup.</span><span class="sxs-lookup"><span data-stu-id="84e4b-107">Before you can do this, you must complete the VAT posting setup.</span></span>

<span data-ttu-id="84e4b-108">To use accounts for unrealised GST, follow these steps:</span><span class="sxs-lookup"><span data-stu-id="84e4b-108">To use accounts for unrealized VAT, follow these steps:</span></span>
1. <span data-ttu-id="84e4b-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, and enter **General Ledger Setup**.</span><span class="sxs-lookup"><span data-stu-id="84e4b-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, and enter **General Ledger Setup**.</span></span> 
2. <span data-ttu-id="84e4b-110">On the **General Ledger Setup** page, on the **General** FastTab, choose **Show More**, and then choose the **Unrealized VAT** check box.</span><span class="sxs-lookup"><span data-stu-id="84e4b-110">On the **General Ledger Setup** page, on the **General** FastTab, choose **Show More**, and then choose the **Unrealized VAT** check box.</span></span>
3. <span data-ttu-id="84e4b-111">Close the page.</span><span class="sxs-lookup"><span data-stu-id="84e4b-111">Close the page.</span></span>
4. <span data-ttu-id="84e4b-112">choose the **Search for Page or Report** icon ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon"), and enter **VAT Posting Setup**.</span><span class="sxs-lookup"><span data-stu-id="84e4b-112">choose the **Search for Page or Report** icon ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon"), and enter **VAT Posting Setup**.</span></span> 
5. <span data-ttu-id="84e4b-113">On the **VAT Posting Setup** page, choose the VAT posting group, and then choose **Edit**.</span><span class="sxs-lookup"><span data-stu-id="84e4b-113">On the **VAT Posting Setup** page, choose the VAT posting group, and then choose **Edit**.</span></span> 
6. <span data-ttu-id="84e4b-114">In the **Unrealized VAT Type** field, choose an option to specify how to allocate payments to the invoice amount (excluding VAT) and the VAT amount itself, and how to transfer VAT amounts from the unrealized VAT account to the realized account.</span><span class="sxs-lookup"><span data-stu-id="84e4b-114">In the **Unrealized VAT Type** field, choose an option to specify how to allocate payments to the invoice amount (excluding VAT) and the VAT amount itself, and how to transfer VAT amounts from the unrealized VAT account to the realized account.</span></span> <span data-ttu-id="84e4b-115">The following table describes the options.</span><span class="sxs-lookup"><span data-stu-id="84e4b-115">The following table describes the options.</span></span>

| <span data-ttu-id="84e4b-116">Option</span><span class="sxs-lookup"><span data-stu-id="84e4b-116">Option</span></span> | <span data-ttu-id="84e4b-117">Description</span><span class="sxs-lookup"><span data-stu-id="84e4b-117">Description</span></span> |
| --- | --- |
| <span data-ttu-id="84e4b-118">Blank</span><span class="sxs-lookup"><span data-stu-id="84e4b-118">Blank</span></span> | <span data-ttu-id="84e4b-119">Choose this option if you don't want to use the unrealised GST feature.</span><span class="sxs-lookup"><span data-stu-id="84e4b-119">Choose this option if you don't want to use the unrealized VAT feature.</span></span> |
| <span data-ttu-id="84e4b-120">Percentage</span><span class="sxs-lookup"><span data-stu-id="84e4b-120">Percentage</span></span> | <span data-ttu-id="84e4b-121">Payments covers both GST and the invoice amount in proportion to the payment's percentage of the remaining invoice amount.</span><span class="sxs-lookup"><span data-stu-id="84e4b-121">Payments covers both VAT and the invoice amount in proportion to the payment's percentage of the remaining invoice amount.</span></span> <span data-ttu-id="84e4b-122">The paid GST amount is transferred from the unrealised GST account to the realised GST account.</span><span class="sxs-lookup"><span data-stu-id="84e4b-122">The paid VAT amount is transferred from the unrealized VAT account to the realized VAT account.</span></span> |
| <span data-ttu-id="84e4b-123">First</span><span class="sxs-lookup"><span data-stu-id="84e4b-123">First</span></span> | <span data-ttu-id="84e4b-124">Payments cover GST first and then invoice amounts.</span><span class="sxs-lookup"><span data-stu-id="84e4b-124">Payments cover VAT first and then invoice amounts.</span></span> <span data-ttu-id="84e4b-125">In this case, the amount transferred from the unrealised GST account to the GST account will equal the amount of the payment until the total GST has been paid.</span><span class="sxs-lookup"><span data-stu-id="84e4b-125">In this case, the amount transferred from the unrealized VAT account to the VAT account will equal the amount of the payment until the total VAT has been paid.</span></span> |
| <span data-ttu-id="84e4b-126">Last</span><span class="sxs-lookup"><span data-stu-id="84e4b-126">Last</span></span> | <span data-ttu-id="84e4b-127">Payments cover the invoice amount first and then GST.</span><span class="sxs-lookup"><span data-stu-id="84e4b-127">Payments cover the invoice amount first and then VAT.</span></span> <span data-ttu-id="84e4b-128">In this case, no amount will be transferred from the unrealised GST account to the GST account until the total amount of the invoice, excluding GST, has been paid.</span><span class="sxs-lookup"><span data-stu-id="84e4b-128">In this case, no amount will be transferred from the unrealized VAT account to the VAT account until the total amount of the invoice, excluding VAT, has been paid.</span></span> |
| <span data-ttu-id="84e4b-129">First (Fully Paid)</span><span class="sxs-lookup"><span data-stu-id="84e4b-129">First (Fully Paid)</span></span> | <span data-ttu-id="84e4b-130">Payments will cover VAT first (like the _First_ option), but no amount will be transferred to the VAT account until the full amount of VAT has been paid.</span><span class="sxs-lookup"><span data-stu-id="84e4b-130">Payments will cover VAT first (like the _First_ option), but no amount will be transferred to the VAT account until the full amount of VAT has been paid.</span></span> |
| <span data-ttu-id="84e4b-131">Last (Fully Paid)</span><span class="sxs-lookup"><span data-stu-id="84e4b-131">Last (Fully Paid)</span></span> | <span data-ttu-id="84e4b-132">Payments will cover invoice amount first (like the _Last_ option), but no amount will be transferred to the VAT account until the full amount of VAT has been paid.</span><span class="sxs-lookup"><span data-stu-id="84e4b-132">Payments will cover invoice amount first (like the _Last_ option), but no amount will be transferred to the VAT account until the full amount of VAT has been paid.</span></span> |

6. <span data-ttu-id="84e4b-133">In the **Sales VAT Unreal. Account** field, choose the account for unrealized sales VAT.</span><span class="sxs-lookup"><span data-stu-id="84e4b-133">In the **Sales VAT Unreal. Account** field, choose the account for unrealized sales VAT.</span></span>

    > [!NOTE]  
>   <span data-ttu-id="84e4b-134">The GST amount will be posted to this account, and stay there until the customer payment is posted.</span><span class="sxs-lookup"><span data-stu-id="84e4b-134">The VAT amount will be posted to this account, and stay there until the customer payment is posted.</span></span> <span data-ttu-id="84e4b-135">The amount is then transferred to the account for GST.</span><span class="sxs-lookup"><span data-stu-id="84e4b-135">The amount is then transferred to the account for sales VAT.</span></span>
7. <span data-ttu-id="84e4b-136">In the **Purch. VAT Unreal. Account** field, enter the general ledger count for unrealized purchase VAT.</span><span class="sxs-lookup"><span data-stu-id="84e4b-136">In the **Purch. VAT Unreal. Account** field, enter the general ledger count for unrealized purchase VAT.</span></span>

    > [!NOTE]  
>   <span data-ttu-id="84e4b-137">The GST amount will be posted to this account, and stay there until the customer payment is posted.</span><span class="sxs-lookup"><span data-stu-id="84e4b-137">The VAT amount will be posted to this account, and stay there until the customer payment is posted.</span></span> <span data-ttu-id="84e4b-138">The amount is then transferred to the account for GST.</span><span class="sxs-lookup"><span data-stu-id="84e4b-138">The amount is then transferred to the account for sales VAT.</span></span>

## <a name="see-also"></a><span data-ttu-id="84e4b-139">See Also</span><span class="sxs-lookup"><span data-stu-id="84e4b-139">See Also</span></span>
[<span data-ttu-id="84e4b-140">Setting Up Value Added Tax</span><span class="sxs-lookup"><span data-stu-id="84e4b-140">Setting Up Value Added Tax</span></span>](finance-setup-vat.md)