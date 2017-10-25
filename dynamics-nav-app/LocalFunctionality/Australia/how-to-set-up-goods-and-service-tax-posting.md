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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2f2ab0a6ce6ded33a71f474a01aab48bbcbd34a0
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-goods-and-service-tax-posting"></a>How to: Set Up Goods and Service Tax Posting
Goods and services tax (GST) is the tax that is applied on most goods and services. The GST that is paid and received during a period is reported in the Business Activity Statement (BAS) that has to be submitted to the Australian Taxation Office (ATO).  
  
 To set up posting details for GST, you must define the posting groups, rate of GST, and the accounts to which GST is to be posted. You can set up this information for a particular combination business posting groups and product posting groups.  
  
 You must set up GST posting before you generate the BAS report.  
  
### <a name="to-set-up-goods-and-sales-tax-posting"></a>To set up goods and sales tax posting  
  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **GST Posting Setup**, and then choose the appropriate link.  
  
2.  Fill in the fields as described in the following table.  
  
    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**GST Bus. Posting Group**|Specifies the GST business posting group code.|  
    |**GST Prod. Posting Group**|Specifies the GST product posting group code.|  
    |**GST Identifier**|Specifies the code that is used to group similar GST setups with similar attributes.<br /><br /> For example, you can group a number of GST posting setups that have a common GST percentage.|  
    |**GST %**|Specifies the GST rate.|  
    |**GST Calculation Type**|Specifies the method that is used to calculate the purchase or sale of items.|  
    |**GST Account**|Specifies the number of the general ledger account to which you want to post the sales GST.<br /><br /> If you have selected the **Reverse Charge GST** option in the **GST Calculation Type** field, then do not enter a value in this field.|  
    |**Input Tax Credit Account**|Specifies the number of the general ledger account to which you want to post the input tax credit.|  
    |**Reverse Chrg. GST Acc.**|Specifies the number of the general ledger account to which you want to post the reverse charge GST.<br /><br /> You can enter a value in this field only if you have selected the **Reverse Charge GST** option in the **GST Calculation Type** field.|  
  
3.  Choose the **OK** button.  
  
## <a name="see-also"></a>See Also  
 BAS-Update   
 [How to: Print Goods and Service Tax Settlement Reports](how-to-print-goods-and-service-tax-settlement-reports.md)
