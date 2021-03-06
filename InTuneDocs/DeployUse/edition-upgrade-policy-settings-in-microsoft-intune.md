---
# required metadata

title: Windows edition upgrade policy settings | Microsoft Intune
description:
keywords:
author: robstackmsft
manager: jeffgilb
ms.date: 04/28/2016
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 8589866a-3f13-489b-a5cd-cee017d16d54

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: jeffgilb
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# Windows edition upgrade policy settings in Microsoft Intune
The Microsoft Intune **Edition Upgrade Policy** lets you automatically upgrade devices that run one of the following Windows 10 versions to a newer edition:
* Windows 10 Desktop
* Windows 10 Holographic

## Before you start
Before you begin to upgrade devices to the latest version, you will need one of the following:
* A product key which is valid to install the new version of Windows on all devices you target with the policy (for Windows 10 Desktop editions).
* A license file from Microsoft which contains the licensing information to install the new version of Windows on all devices you target with the policy (for Windows 10 Mobile and Windows 10 Holographic editions).
* The Windows 10 devices you target must be enrolled in Microsoft Intune.

## Edition upgrade policy settings

|Setting name|Details|
|-|-|
|**Name**|Enter a name for the edition upgrade policy.|
|**Description**|Optionally, enter a description for the policy that helps you identify it in the Intune console.
|**Edition to upgrade to**|From the drop-down list, select the version of Windows 10 Desktop, Windows 10 Holographic, or Windows 10 Mobile that you want to upgrade targeted devices to.
|**Product Key**|Specify the product key that you obtained from Microsoft which can be used to upgrade all targeted Windows 10 Desktop devices.<br>After you create a policy containing a product key, you cannot edit the product key later. This is because the key is obscured for security reasons. To change the product key, you must re-enter the entire key.
|**License File**|Click **Browse** to select the license file you obtained from Microsoft that contains license information for the Windows Holographic edition you want to upgrade targeted devices to.

### See also
[Manage settings and features on your devices with Microsoft Intune policies](manage-settings-and-features-on-your-devices-with-microsoft-intune-policies.md)