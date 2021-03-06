---
title: Buy Basic + Test Plans access
titleSuffix: Azure DevOps
ms.custom: 
description: Steps for administrators to follow on how to buy a Basic + Test Plans access for users
ms.prod: devops
ms.technology: devops-billing
ms.assetid:
ms.topic: quickstart
ms.manager: jillfra
ms.author: chcomley
author: chcomley
ms.date: 05/17/2019
monikerRange: '>= tfs-2013'
---

# Buy Basic + Test Plans access for users

[!INCLUDE [temp](../../_shared/version-vsts-tfs-all-versions.md)]

In this article, learn how to pay for more users who need access to [Azure Repos](https://azure.microsoft.com/en-us/services/devops/repos/), [Azure Boards](https://azure.microsoft.com/en-us/services/devops/boards/), and [Azure Test Plans](https://azure.microsoft.com/en-us/services/devops/test-plans/).
 
[Visual Studio Enterprise](https://visualstudio.microsoft.com/vs/enterprise/), [Visual Studio Test Professional](https://visualstudio.microsoft.com/vs/test-professional/) and [MSDN Platforms](https://visualstudio.microsoft.com/msdn-platforms/) subscribers have Basic + Test Plans included with their subscription, and their subscription is detected when they sign in to Azure DevOps for the first time.

## Prerequisites

Ensure the following is true:

* [Billing is set up for your organization](set-up-billing-for-your-organization-vs.md)
* You have [Project Collection Administrator or organization Owner permissions](../accounts/faq-add-delete-users.md#find-owner)

## Increase amount of paid users

1. Sign in to your organization (```https://dev.azure.com/{yourorganization}```).
2. Select ![gear icon](../../_img/icons/gear-icon.png) **Organization settings**.
  
   ![Open Organization settings](../../_shared/_img/settings/open-admin-settings-vert.png)

3. Select **Billing**.

   ![Select Billing tab in Organization settings](_img/_shared/select-billing-organization-settings.png)

4. Enter the number of **paid users**, next to Basic + Test Plans, and then choose **Save**. 

   ![Enter amount of Basic + Test Plans](_img/_shared/enter-amount-basic-plus-test-plans.png)

5. Select **Confirm purchase**.

   ![Select Confirm purchase to add more Basic users](_img/buy-more-basic-access/select-confirm-purchase.png)


<a name="transitioning-test-manager-to-basic-plus-test-plans"></a>

> [!NOTE]
> We're moving from assignment of the Test Manager extension to assignment of the Basic + Test Plans access level, so you may have one or the other to assign, but the amount you can assign is the same for either. [Learn more](https://devblogs.microsoft.com/devops/a-simpler-way-to-buy-azure-devops/).

## Decrease amount of paid users

As your team contracts, you can decrease the number of paid users in your organization. Follow the same process as increasing the amount, only enter a lesser quantity of **paid users**, and then select **Save**.

> [!IMPORTANT]
> To reduce or cancel users who have paid Basic + Test Plans access for the next month, make your changes before the last day of the month.
> Your charges won't change until the next month because paid users are monthly purchases.

1. Sign in to your organization (```https://dev.azure.com/{yourorganization}```).
2. Select ![gear icon](../../_img/icons/gear-icon.png) **Organization settings**.
  
   ![Open Organization settings](../../_shared/_img/settings/open-admin-settings-vert.png)

3. Select **Billing**.

   ![Select Billing tab in Organization settings](_img/_shared/select-billing-organization-settings.png)

4. Enter a lesser quantity of **Basic + Test Plans users**, and then choose **Save**.

## Next steps

> [!div class="nextstepaction"]
> [Buy CI/CD](buy-more-build-vs.md#prerequisites)

## Related articles

* [Add backup billing managers](add-backup-billing-managers.md)
* [Change the Azure subscription for billing](change-azure-subscription.md)
* [Azure DevOps pricing](https://azure.microsoft.com/pricing/details/visual-studio-team-services/)
* [Azure DevOps billing support](https://azure.microsoft.com/support/devops/)
