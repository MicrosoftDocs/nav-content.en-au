---
title: Create New Value Entries for Items in the Inventory
description: Describes how to appreciate or depreciate the value entries of one or more items in the inventory by posting their current, calculated value.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: costing, inventory cost, value entries
ms.date: 08/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5bc7e72a44f002e42ad9b3d37c9eab6cd512eff3
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-revalue-inventory"></a>How to: Revalue Inventory
If you want to appreciate or depreciate an item or a specific item ledger entry, you must use the revaluation journal.

## <a name="to-revalue-inventory"></a>To revalue inventory
1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Revaluation Journal**, and then choose the related link.
2. Choose the **Calculate Inventory Value** action.
3. In the **Calculate Inventory Value** window, fill in the fields as necessary. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Choose the **OK** button.
5. On each line in the **Revaluation Journal** window, in the **Unit Cost (Revalued)** field, enter the new unit cost. Alternatively, enter the new total amount in the **Inventory Value (Revalued)** field.

    The relevant fields are automatically updated. Note that the **Amount** field shows the actual change in inventory value for the selected item ledger entry. It calculates the difference between the **Inventory Value (Calculated)** field and the **Inventory Value (Revalued)** field.
6. When you have completed all lines in the revaluation journal, choose the **Post** action.

New value entries are now created to reflect the revaluations that you have posted. You can see the new values on the respective item cards.

## <a name="see-also"></a>See Also
[Design Details: Revaluation](design-details-revaluation.md)  
[Inventory](inventory-manage-inventory.md)  
[Sales](sales-manage-sales.md)  
[Purchasing](purchasing-manage-purchasing.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

