---
title: Post SEPA Direct Debit Payments
description: When a direct debit collection is successfully processed by your bank, you can proceed to post receipt of the payment for the involved sales invoices.
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9b0e82feb77be2e66b618aab7322215637d4f89e
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-post-sepa-direct-debit-payment-receipts"></a><span data-ttu-id="6f67e-103">How to: Post SEPA Direct Debit Payment Receipts</span><span class="sxs-lookup"><span data-stu-id="6f67e-103">How to: Post SEPA Direct Debit Payment Receipts</span></span>
<span data-ttu-id="6f67e-104">When a direct debit collection is successfully processed by your bank, you can proceed to post receipt of the payment for the involved sales invoices.</span><span class="sxs-lookup"><span data-stu-id="6f67e-104">When a direct debit collection is successfully processed by your bank, you can proceed to post receipt of the payment for the involved sales invoices.</span></span> <span data-ttu-id="6f67e-105">For more information, see [How to: Create SEPA Direct Debit Collection Entries and Export to a Bank File](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).</span><span class="sxs-lookup"><span data-stu-id="6f67e-105">For more information, see [How to: Create SEPA Direct Debit Collection Entries and Export to a Bank File](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).</span></span>  

<span data-ttu-id="6f67e-106">You can post the payment receipt directly from the **Direct Debit Collections** window or the **Direct Debit Collect. Entries** window.</span><span class="sxs-lookup"><span data-stu-id="6f67e-106">You can post the payment receipt directly from the **Direct Debit Collections** window or the **Direct Debit Collect. Entries** window.</span></span> <span data-ttu-id="6f67e-107">Alternatively, you can relay the work to another user by preparing the related journal lines.</span><span class="sxs-lookup"><span data-stu-id="6f67e-107">Alternatively, you can relay the work to another user by preparing the related journal lines.</span></span>  

## <a name="to-post-a-direct-debit-payment-receipt-from-the-direct-debit-collections-window"></a><span data-ttu-id="6f67e-108">To post a direct-debit payment receipt from the Direct Debit Collections window</span><span class="sxs-lookup"><span data-stu-id="6f67e-108">To post a direct-debit payment receipt from the Direct Debit Collections window</span></span>  
1. <span data-ttu-id="6f67e-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Direct Debit Collections**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="6f67e-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Direct Debit Collections**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6f67e-110">Select a line for a direct debit collection that has been exported to a bank file and successfully processed by the bank.</span><span class="sxs-lookup"><span data-stu-id="6f67e-110">Select a line for a direct debit collection that has been exported to a bank file and successfully processed by the bank.</span></span> <span data-ttu-id="6f67e-111">For more information, see [How to: Create SEPA Direct Debit Collection Entries and Export to a Bank File](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).</span><span class="sxs-lookup"><span data-stu-id="6f67e-111">For more information, see [How to: Create SEPA Direct Debit Collection Entries and Export to a Bank File](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).</span></span>  
3. <span data-ttu-id="6f67e-112">Choose the **Post Payment Receipts** action.</span><span class="sxs-lookup"><span data-stu-id="6f67e-112">Choose the **Post Payment Receipts** action.</span></span>  
4. <span data-ttu-id="6f67e-113">In the **Post Direct Debit Collection** window, fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="6f67e-113">In the **Post Direct Debit Collection** window, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="6f67e-114">Field</span><span class="sxs-lookup"><span data-stu-id="6f67e-114">Field</span></span>|<span data-ttu-id="6f67e-115">Description</span><span class="sxs-lookup"><span data-stu-id="6f67e-115">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="6f67e-116">**Direct Debit Collection No.**</span><span class="sxs-lookup"><span data-stu-id="6f67e-116">**Direct Debit Collection No.**</span></span>|<span data-ttu-id="6f67e-117">Specify the direct debit collection that you want to post payment receipt for.</span><span class="sxs-lookup"><span data-stu-id="6f67e-117">Specify the direct debit collection that you want to post payment receipt for.</span></span>|  
    |<span data-ttu-id="6f67e-118">**General Journal Template**</span><span class="sxs-lookup"><span data-stu-id="6f67e-118">**General Journal Template**</span></span>|<span data-ttu-id="6f67e-119">Specify which general journal template to use for posting the payment receipt, such as the template for cash receipts.</span><span class="sxs-lookup"><span data-stu-id="6f67e-119">Specify which general journal template to use for posting the payment receipt, such as the template for cash receipts.</span></span>|  
    |<span data-ttu-id="6f67e-120">**General Journal Batch Name**</span><span class="sxs-lookup"><span data-stu-id="6f67e-120">**General Journal Batch Name**</span></span>|<span data-ttu-id="6f67e-121">Specify which general journal batch to use for posting the payment receipt.</span><span class="sxs-lookup"><span data-stu-id="6f67e-121">Specify which general journal batch to use for posting the payment receipt.</span></span>|  
    |<span data-ttu-id="6f67e-122">**Create Journal Only**</span><span class="sxs-lookup"><span data-stu-id="6f67e-122">**Create Journal Only**</span></span>|<span data-ttu-id="6f67e-123">Select this check box if you do not want to post the payment receipt when you choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="6f67e-123">Select this check box if you do not want to post the payment receipt when you choose the **OK** button.</span></span> <span data-ttu-id="6f67e-124">The payment receipt will be prepared in the specified journal and will not be posted until someone posts the journal lines in question.</span><span class="sxs-lookup"><span data-stu-id="6f67e-124">The payment receipt will be prepared in the specified journal and will not be posted until someone posts the journal lines in question.</span></span>|  

5. <span data-ttu-id="6f67e-125">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="6f67e-125">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="6f67e-126">See Also</span><span class="sxs-lookup"><span data-stu-id="6f67e-126">See Also</span></span>  
 <span data-ttu-id="6f67e-127">[Collecting Payments with SEPA Direct Debit](finance-collect-payments-with-sepa-direct-debit.md) </span><span class="sxs-lookup"><span data-stu-id="6f67e-127">[Collecting Payments with SEPA Direct Debit](finance-collect-payments-with-sepa-direct-debit.md) </span></span>  
 [<span data-ttu-id="6f67e-128">Sales</span><span class="sxs-lookup"><span data-stu-id="6f67e-128">Sales</span></span>](sales-manage-sales.md)
