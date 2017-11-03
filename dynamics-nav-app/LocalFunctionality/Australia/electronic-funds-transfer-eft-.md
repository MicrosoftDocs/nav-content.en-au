---
title: Electronic Funds Transfer (EFT)
description: You can pay vendors using the electronic funds transfer (EFT) system in Australia.
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
ms.openlocfilehash: 9794e8c5c4c19896c55dcea9f45769142fbfab36
ms.contentlocale: en-au
ms.lasthandoff: 10/23/2017

---
# <a name="electronic-funds-transfer-eft"></a>Electronic Funds Transfer (EFT)
You can pay vendors using the electronic funds transfer (EFT) system in Australia.  

## <a name="setting-up-electronic-funds-transfer-in-includenavnowincludesnavnowmdmd"></a>Setting up Electronic Funds Transfer in [!INCLUDE[navnow](../../includes/navnow_md.md)]  
 [!INCLUDE[navnow](../../includes/navnow_md.md)] can export EFT files that you can then upload to your bank’s website for additional processing. To submit EFT files, you must set up the following information:  

-   You must add EFT information to the bank account or bank accounts that you will use to pay vendors electronically. The EFT-specific fields are on the **Transfer** FastTab in the Bank Account Card window.  

-   For those vendors that you want to pay electronically, you must select the EFT Payment field and specify the vendor bank account in the EFT Vendor Bank Account Code field in the Vendor Card window.  

 When you have set up bank accounts and vendors, you can create EFT file that are based on entries in the payment journal. For more information, see Create EFT File. When you create an EFT file, an entry is made in the **EFT Register** table. In the EFT Register window, you can drill down to see the vendor ledger entries for the EFT file. In the Payment Journal window, you can also import existing EFT register entries to the payment journal by using the **Transfer EFT Register** batch job.

## <a name="see-also"></a>See Also  
[How to: Export Payments to a Bank File](../..(payables-how-export-payments-bank-file.md)

