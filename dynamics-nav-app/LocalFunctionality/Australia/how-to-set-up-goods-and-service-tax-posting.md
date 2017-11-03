---
title: How to Set Up Goods and Service Tax Posting
description: Goods and services tax (GST) is the tax that is applied on most goods and services. The GST that is paid and received during a period is reported in the Business Activity Statement (BAS) that has to be submitted to the Australian Taxation Office (ATO).
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: cb8eb8b92b9414dca98502a18003f5c5c092318e
ms.contentlocale: en-au
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-goods-and-service-tax-posting"></a><span data-ttu-id="27cd8-104">How to: Set Up Goods and Service Tax Posting</span><span class="sxs-lookup"><span data-stu-id="27cd8-104">How to: Set Up Goods and Service Tax Posting</span></span>
<span data-ttu-id="27cd8-105">Goods and services tax (GST) is the tax that is applied on most goods and services.</span><span class="sxs-lookup"><span data-stu-id="27cd8-105">Goods and services tax (GST) is the tax that is applied on most goods and services.</span></span> <span data-ttu-id="27cd8-106">The GST that is paid and received during a period is reported in the Business Activity Statement (BAS) that has to be submitted to the Australian Taxation Office (ATO).</span><span class="sxs-lookup"><span data-stu-id="27cd8-106">The GST that is paid and received during a period is reported in the Business Activity Statement (BAS) that has to be submitted to the Australian Taxation Office (ATO).</span></span>  

<span data-ttu-id="27cd8-107">To set up posting details for GST, you must define the posting groups, rate of GST, and the accounts to which GST is to be posted.</span><span class="sxs-lookup"><span data-stu-id="27cd8-107">To set up posting details for GST, you must define the posting groups, rate of GST, and the accounts to which GST is to be posted.</span></span> <span data-ttu-id="27cd8-108">You can set up this information for a particular combination business posting groups and product posting groups.</span><span class="sxs-lookup"><span data-stu-id="27cd8-108">You can set up this information for a particular combination business posting groups and product posting groups.</span></span>  

<span data-ttu-id="27cd8-109">You must set up GST posting before you generate the BAS report.</span><span class="sxs-lookup"><span data-stu-id="27cd8-109">You must set up GST posting before you generate the BAS report.</span></span>  

## <a name="to-set-up-goods-and-sales-tax-posting"></a><span data-ttu-id="27cd8-110">To set up goods and sales tax posting</span><span class="sxs-lookup"><span data-stu-id="27cd8-110">To set up goods and sales tax posting</span></span>  

1.  <span data-ttu-id="27cd8-111">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Posting Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="27cd8-111">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Posting Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="27cd8-112">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="27cd8-112">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="27cd8-113">Field</span><span class="sxs-lookup"><span data-stu-id="27cd8-113">Field</span></span>|<span data-ttu-id="27cd8-114">Description</span><span class="sxs-lookup"><span data-stu-id="27cd8-114">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="27cd8-115">**GST Bus. Posting Group**</span><span class="sxs-lookup"><span data-stu-id="27cd8-115">**VAT Bus. Posting Group**</span></span>|<span data-ttu-id="27cd8-116">Specifies the GST business posting group code.</span><span class="sxs-lookup"><span data-stu-id="27cd8-116">Specifies the VAT business posting group code.</span></span>|  
    |<span data-ttu-id="27cd8-117">**GST Prod. Posting Group**</span><span class="sxs-lookup"><span data-stu-id="27cd8-117">**VAT Prod. Posting Group**</span></span>|<span data-ttu-id="27cd8-118">Specifies the GST product posting group code.</span><span class="sxs-lookup"><span data-stu-id="27cd8-118">Specifies the VAT product posting group code.</span></span>|  
    |<span data-ttu-id="27cd8-119">**GST Identifier**</span><span class="sxs-lookup"><span data-stu-id="27cd8-119">**VAT Identifier**</span></span>|<span data-ttu-id="27cd8-120">Specifies the code that is used to group similar GST setups with similar attributes.</span><span class="sxs-lookup"><span data-stu-id="27cd8-120">Specifies the code that is used to group similar VAT setups with similar attributes.</span></span><br /><br /> <span data-ttu-id="27cd8-121">For example, you can group a number of GST posting setups that have a common GST percentage.</span><span class="sxs-lookup"><span data-stu-id="27cd8-121">For example, you can group a number of VAT posting setups that have a common VAT percentage.</span></span>|  
    |<span data-ttu-id="27cd8-122">**GST %**</span><span class="sxs-lookup"><span data-stu-id="27cd8-122">**VAT %**</span></span>|<span data-ttu-id="27cd8-123">Specifies the GST rate.</span><span class="sxs-lookup"><span data-stu-id="27cd8-123">Specifies the VAT rate.</span></span>|  
    |<span data-ttu-id="27cd8-124">**GST Calculation Type**</span><span class="sxs-lookup"><span data-stu-id="27cd8-124">**VAT Calculation Type**</span></span>|<span data-ttu-id="27cd8-125">Specifies the method that is used to calculate the purchase or sale of items.</span><span class="sxs-lookup"><span data-stu-id="27cd8-125">Specifies the method that is used to calculate the purchase or sale of items.</span></span>|  
    |<span data-ttu-id="27cd8-126">**GST Account**</span><span class="sxs-lookup"><span data-stu-id="27cd8-126">**Sales VAT Account**</span></span>|<span data-ttu-id="27cd8-127">Specifies the number of the general ledger account to which you want to post the sales GST.</span><span class="sxs-lookup"><span data-stu-id="27cd8-127">Specifies the number of the general ledger account to which you want to post the sales VAT.</span></span><br /><br /> <span data-ttu-id="27cd8-128">If you have selected the **Reverse Charge GST** option in the **GST Calculation Type** field, then do not enter a value in this field.</span><span class="sxs-lookup"><span data-stu-id="27cd8-128">If you have selected the **Reverse Charge VAT** option in the **VAT Calculation Type** field, then do not enter a value in this field.</span></span>|  
    |<span data-ttu-id="27cd8-129">**Input Tax Credit Account**</span><span class="sxs-lookup"><span data-stu-id="27cd8-129">**Purchase VAT Account**</span></span>|<span data-ttu-id="27cd8-130">Specifies the number of the general ledger account to which you want to post the input tax credit.</span><span class="sxs-lookup"><span data-stu-id="27cd8-130">Specifies the number of the general ledger account to which you want to post the purchase VAT.</span></span>|  
    |<span data-ttu-id="27cd8-131">**Reverse Chrg. GST Acc.**</span><span class="sxs-lookup"><span data-stu-id="27cd8-131">**Reverse Chrg. VAT Acc.**</span></span>|<span data-ttu-id="27cd8-132">Specifies the number of the general ledger account to which you want to post the reverse charge GST.</span><span class="sxs-lookup"><span data-stu-id="27cd8-132">Specifies the number of the general ledger account to which you want to post the reverse charge VAT.</span></span><br /><br /> <span data-ttu-id="27cd8-133">You can enter a value in this field only if you have selected the **Reverse Charge GST** option in the **GST Calculation Type** field.</span><span class="sxs-lookup"><span data-stu-id="27cd8-133">You can enter a value in this field only if you have selected the **Reverse Charge VAT** option in the **VAT Calculation Type** field.</span></span>|  

3.  <span data-ttu-id="27cd8-134">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="27cd8-134">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="27cd8-135">See Also</span><span class="sxs-lookup"><span data-stu-id="27cd8-135">See Also</span></span>  
 [<span data-ttu-id="27cd8-136">How to: Report BAS Information</span><span class="sxs-lookup"><span data-stu-id="27cd8-136">How to: Report BAS Information</span></span>](how-to-report-bas-information.md)  
 [<span data-ttu-id="27cd8-137">How to: Print Goods and Service Tax Settlement Reports</span><span class="sxs-lookup"><span data-stu-id="27cd8-137">How to: Print Goods and Service Tax Settlement Reports</span></span>](how-to-print-goods-and-service-tax-settlement-reports.md)

