---
title: Power BI service features by license type
description: "In the Power BI service, users have capabilities that are based on the type of per-user license that they have (free, Pro, PPU) and whether the content they're interacting with is in a Premium capacity workspace."
author: mihart
ms.author: mihart
ms.reviewer: ''
ms.service: powerbi
ms.subservice: pbi-fundamentals
ms.topic: conceptual
ms.date: 03/25/2024
ms.custom: licensing support
LocalizationGroup: Get started
---

# Power BI service per-user and capacity-based licenses

> [!NOTE]
> The Power BI service is available as a standalone service and as one of the services that's integrated with [Microsoft Fabric](/fabric/get-started/microsoft-fabric-overview). Administration and licensing of the Power BI service is now integrated with Microsoft Fabric.

There are three kinds of Power BI *per-user* licenses: Fabric free, Power BI Pro, and Power BI Premium Per User (PPU). Which type of license you need to use Fabric and to use Power BI is determined by where your content is stored, how you plan on interacting with that content, and if that content uses Premium features. The other type of license is a Premium *capacity-based* license. PPU and Pro users with access to a [Power BI Premium, Fabric F64 or greater](/power-bi/enterprise) capacity-based license, can create content in workspaces that are assigned to Premium capacity. PPU and Pro users can then grant colleagues, including free users, access to those Premium workspaces. 

> [!NOTE]
> A Premium Per User (PPU) workspace is not the same as a Premium capacity workspace.  

## Sign up for a license

There are several ways to begin using the Power BI service and Fabric. 
- If you already have a subscription to Microsoft 365, [check to see if that subscriptions includes a Power BI and Fabric license](../consumer/end-user-license.md).  
- If you don't already have Microsoft 365, [Sign up for a new Microsoft 365 trial](../enterprise/service-admin-signing-up-for-power-bi-with-a-new-office-365-trial.md). 
- If your [administrator already purchased a subscription and assigned you a license](../enterprise/service-admin-manage-licenses.md). Check for a license by typing app.powerbi.com into your browser.
- If you're not ready to buy, start with a [trial license](service-self-service-signup-for-power-bi.md#use-self-service-sign-up-to-start-an-individual-fabric-trial).
- If you're signing up as an individual and not an organization, [use self-service to try or buy](service-self-service-signup-purchase-for-power-bi.md) the Power BI service or Fabric.


## Power BI service licenses

There are licenses that apply to an individual (per-user) and a license (often also referred to as a *subscription*) that applies to the type of storage capacity that an organization purchases. Each of the three per-user licenses is unique, and each grants access to certain Power BI service features and capabilities. The combination of per-user license and capacity determines the features and capabilities available to you. Just a few of those capabilities are: sharing, collaborating, and editing.

### Free per-user license

Users with free licenses can use the Power BI service to connect to data and create reports and dashboards for their own use. They can't use the Power BI sharing or collaborating features with others, or publish content to other people's workspaces. However, Pro and PPU users can share content and collaborate with free users if the content is saved in workspaces hosted in Premium capacity or Fabric F64 or greater capacity. To learn more about workspaces, see [Types of workspaces](../consumer/end-user-workspaces.md#types-of-workspaces). To learn more about features available to users with a free license, see [Power BI service feature list](../consumer/end-user-features.md).

### Pro license 

Power BI Pro is an individual per-user license that lets users create content and also read, and interact with content that others publish to the Power BI service. Users with this license type can share content and collaborate with other Power BI Pro users. Only Power BI Pro users can publish or share content with other Pro users or consume content that's created by other Pro users, unless a Power BI Premium capacity hosts that content. If a Power BI Premium capacity hosts the content, then Pro users can share content and collaborate with free and PPU users too. 

### Premium per user (PPU) license

A PPU per-user license provides the license holder with all of the capabilities of Power BI Pro plus access to most Premium capacity-based features. A Power BI PPU license unlocks access to extra of features, capabilities, and types of content that are only available with a paid license. This access is limited to the PPU license holder and other colleagues who also have a PPU license. For example, in order to collaborate and share content in a PPU workspace, all users must have a PPU license.

When you use a PPU license, content created by you can only be shared with other users who also have a PPU license. The exception is when that content is saved in a workspace hosted in Premium capacity. The table summarizes the basic capabilities of each license type.

### Premium capacity

A capacity-based Premium license (often referred to as a Premium *subscription*) allows Pro or PPU users to create and save content in Premium capacity workspaces. They can then share that workspace with colleagues who have any license type. Only users with a Pro or PPU license can create and save content in Premium capacities, and only if their organization purchased Premium capacity. 

To discover more about Power BI Premium, see [What is Power BI Premium?](../enterprise/service-premium-what-is.md)

| License type | Capabilities when workspace is in shared capacity | Extra capabilities when workspace is in Premium capacity |
| --------- | ----------- | ----------- |
| Fabric (free) | Access to content they create for themselves. | Consume content shared with them by Pro or PPU users |
| Power BI Pro | Publish content to other workspaces, share dashboards, subscribe to dashboards and reports, share with users who have a Pro license | Distribute content to users who have free or PPU licenses |
| Power BI Premium Per User (PPU) | Publish content to other workspaces, share dashboards, subscribe to dashboards and reports, share with *users who have a PPU license* | Distribute content to users who have free and Pro licenses |

For a comparison of Power BI Pro and Power BI Premium, see the _Power BI features comparison_ section of [Power BI pricing](https://powerbi.microsoft.com/pricing/).

To learn more about the capabilities your license provides, see [Feature availability for users with free licenses](../consumer/end-user-features.md) and [Types of licenses for Power BI consumers](../consumer/end-user-license.md).

## Related content

* [Sign up for the Power BI service as an individual](service-self-service-signup-for-power-bi.md)
* [Comparing Power BI Desktop and the Power BI service](service-service-vs-desktop.md)
