---
# required metadata

title: Removed or deprecated features in Dynamics 365 Finance 
description: This topic describes features that have been removed, or that are planned for removal from Dynamics 365 Finance.
author: roschlom
manager: AnnBe
ms.date: 12/07/2020
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-applications
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Application User, Developer, IT Pro
# ms.devlang: 
ms.reviewer: roschlom
# ms.tgt_pltfrm: 
ms.search.region: Global
# ms.search.industry: 
ms.author: sericks
ms.search.validFrom: 2020-03-02 
ms.dyn365.ops.version: Platform update 33

---

# Removed or deprecated features in Dynamics 365 Finance

[!include [banner](../includes/banner.md)]

This topic describes features that have been removed, or that are planned for removal from Dynamics 365 Finance.

- A *removed* feature is no longer available in the product.
- A *deprecated* feature is not in active development and may be removed in a future update.

This list is intended to help you consider these removals and deprecations for your own planning. 

> [!NOTE]
> Detailed information about objects in Finance and Operations apps can be found in the [Technical reference reports](https://docs.microsoft.com/dynamics/s-e/). You can compare the different versions of these reports to learn about objects that have changed or been removed in each version of Finance and Operations apps.

## Features removed or deprecated in the Finance 10.0.16 release

### "VAT declaration (CZ)" and "Control statement export (CZ)" Electronic reporting formats for Czech Republic

|   |  |
|------------|--------------------|
| **Reason for deprecation/removal** | Replaced with new formats |
| **Replaced by another feature?**   | Yes |
| **Product areas affected**         | Application |
| **Deployment option**              | All |
| **Status**                         | Deprecated: By January 22, 2022, we plan to no longer support "VAT declaration (CZ)", "Control statement export (CZ)" Electronic reporting (ER) formats. New VAT declaration XML (CZ), VAT declaration Excel (CZ), VAT control statement XML (CZ) formats are introduced instead under the "Tax declaration" model. |

### "Ledger transaction export format (BE)" Electronic reporting format and respective "Ledger transaction export (BE)" model for Belgium

|   |  |
|------------|--------------------|
| **Reason for deprecation/removal** | Replaced with new ER format under "Standard Audit File (SAF-T)" model.  |
| **Replaced by another feature?**   | Yes |
| **Product areas affected**         | Application |
| **Deployment option**              | All |
| **Status**                         | Deprecated: By December 1, 2021, we plan to no longer support the "Ledger transaction export format (BE)" Electronic reporting (ER) format and respective "Ledger transaction export (BE)" model. A new "General ledger data export (BE)" format together with "General ledger data model mapping" are introduced instead under the "Standard Audit File (SAF-T)" model. |

### "VAT 100" report for the United Kingdom in SSRS format

|   |  |
|------------|--------------------|
| **Reason for deprecation/removal** | Replaced with new ER format - "VAT Declaration Excel (UK)" format under "Tax declaration model".  |
| **Replaced by another feature?**   | Yes |
| **Product areas affected**         | Application |
| **Deployment option**              | All |
| **Status**                         | Deprecated: By December 1, 2021, we plan to no longer support the "VAT 100 report" in SSRS format. A new "VAT Declaration Excel (UK)" format under "Tax declaration model" was introduced in the [MTD VAT feature](../localizations/emea-gbr-mtd-vat-integration.md). |

## Features removed or deprecated in the Finance 10.0.15 release

### Internet Explorer 11 support for Dynamics 365 is deprecated

|   |  |
|------------|--------------------|
| **Reason for deprecation/removal** | Effective December 2020, Microsoft Internet Explorer 11 support for all Dynamics 365 products is deprecated, and Internet Explorer 11 won’t be supported after August 2021.<br><br>This will impact customers who use Dynamics 365 products that are designed to be used through an Internet Explorer 11 interface. After August 2021, Internet Explorer 11 won't be supported for such Dynamics 365 products. |
| **Replaced by another feature?**   | We recommend that customers transition to Microsoft Edge.|
| **Product areas affected**         | All Dynamics 365 products |
| **Deployment option**              | All|
| **Status**                         | Deprecated. Internet Explorer 11 won’t be supported after August 2021.|

## Features removed or deprecated in the Finance 10.0.12 release

### Polish SSRS reports: Sales VAT register, Purchase VAT register, EU summary VAT register – Feature reference PL-00014

|   |  |
|------------|--------------------|
| **Reason for deprecation/removal** | Not legally required.  |
| **Replaced by another feature?**   | Yes (Excel format for Standard Audit File with VAT declaration - JPK_VDEK) |
| **Product areas affected**         | Application |
| **Deployment option**              | All |
| **Status**                         | Deprecated: By July 1, 2021, we plan to no longer support the SSRS reports: **Sales VAT register, Purchase VAT register, EU summary VAT register – Feature reference PL-00014**. Excel format example for Standard Audit File with VAT declaration (JPK_VDEK) will be introduced instead. |

## Features removed or deprecated in the Finance 10.0.11 release

### Norwegian Standard main accounts

|   |  |
|------------|--------------------|
| **Reason for deprecation/removal** | Redesign  |
| **Replaced by another feature?**   | Yes (Replaced with ER format application-specific parameters) |
| **Product areas affected**         | Application |
| **Deployment option**              | All |
| **Status**                         | Deprecated: By April 1, 2021, we plan to no longer support functionality related to Standard main accounts: Reference field, related table, data entity. |

## Features removed or deprecated in the Finance 10.0.7 release

### Workflow request change dialog box no longer includes user selection drop-down list
|   |  |
|------------|--------------------|
| **Reason for deprecation/removal** | Changed to the feature with account groups selection.  |
| **Replaced by another feature?**   | Yes |
| **Product areas affected**         | Workflow |
| **Deployment option**              | All |
| **Status**                         | Deprecated: By December 1, 2020, we plan to no longer support Chinese voucher types setup without Account groups selection. Find more details about the new design in [What's new in 10.0.7](whats-new-changed-10-0-7.md). |

## Previous announcements about removed or deprecated features
To learn more about features that have been removed or deprecated in previous releases, see [Removed or deprecated features in previous releases](../../fin-ops-core/dev-itpro/migration-upgrade/deprecated-features.md).
