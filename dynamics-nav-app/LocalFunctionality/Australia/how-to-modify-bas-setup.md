---
title: How to Modify BAS Setup
description: To complete the Business Activity Statement (BAS) setup, you must map fuel tax credits to general ledger accounts. Do not map an account for field 7C if you only have a fuel tax credit that the ATO owes you and you do not owe anything to ATO. In this case, you can consider mapping only field 7D.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: ff06503bfe68157d16d1c3f4092d771b1a29c1e0
ms.contentlocale: en-au
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-modify-bas-setup"></a>How to: Modify BAS Setup
To complete the Business Activity Statement (BAS) setup, you must map fuel tax credits to general ledger accounts. Do not map an account for field 7C if you only have a fuel tax credit that the ATO owes you and you do not owe anything to ATO. In this case, you can consider mapping only field 7D.  

## <a name="to-modify-and-map-bas-setup-for-the-fuel-tax-credit-fields"></a>To modify and map BAS Setup for the fuel tax credit fields  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS Setup Names**, and then choose the related link.  
2.  Choose the **BAS Setup** action.  
3.  In the **BAS Setup**  window, on a new line 16000, in the **Field No.** field, enter 72.  
4.  In the **Account Totalling** field, select the appropriate general ledger account. The account should have a credit balance.  
5.  In the **BAS Setup**  window, on a new line 17000, in the **Field No.** field, enter 73.  
6.  In the **Account Totalling** field, select the appropriate general ledger account. The account should have a debit balance.  
7.  Choose the **OK** button.  

## <a name="see-also"></a>See Also  
 [BAS Fuel Tax Credits](bas-fuel-tax-credits.md)   
 [How to: Set Up BAS XML Fields](how-to-set-up-bas-xml-fields.md)   
 [Business Activity Statements](business-activity-statements.md)

