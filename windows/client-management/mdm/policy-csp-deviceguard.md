---
title: Policy CSP - DeviceGuard
description: Policy CSP - DeviceGuard
ms.author: maricia
ms.topic: article
ms.prod: w10
ms.technology: windows
author: nickbrower
ms.date: 12/14/2017
---

# Policy CSP - DeviceGuard



<hr/>

<!--StartPolicies-->
## DeviceGuard policies  

<dl>
  <dd>
    <a href="#deviceguard-enablevirtualizationbasedsecurity">DeviceGuard/EnableVirtualizationBasedSecurity</a>
  </dd>
  <dd>
    <a href="#deviceguard-lsacfgflags">DeviceGuard/LsaCfgFlags</a>
  </dd>
  <dd>
    <a href="#deviceguard-requireplatformsecurityfeatures">DeviceGuard/RequirePlatformSecurityFeatures</a>
  </dd>
</dl>

<hr/>
<!--StartPolicy-->
<a href="" id="deviceguard-enablevirtualizationbasedsecurity"></a>**DeviceGuard/EnableVirtualizationBasedSecurity**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--EndSKU-->
<!--StartScope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--EndScope-->
<!--StartDescription-->
 
<p style="margin-left: 20px">Added in Windows 10, version 1709. Turns on virtualization based security(VBS) at the next reboot. virtualization based security uses the Windows Hypervisor to provide support for security services. Value type is integer.

<!--EndDescription-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 (default) - disable virtualization based security.
-   1 - enable virtualization based security.

<!--/SupportedValues-->
<!--EndPolicy-->
<hr/>
<!--StartPolicy-->
<a href="" id="deviceguard-lsacfgflags"></a>**DeviceGuard/LsaCfgFlags**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--EndSKU-->
<!--StartScope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--EndScope-->
<!--StartDescription-->
 
<p style="margin-left: 20px">Added in Windows 10, version 1709. This setting lets users turn on Credential Guard with virtualization-based security to help protect credentials at next reboot. Value type is integer.

<!--EndDescription-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 (default) - (Disabled) Turns off Credential Guard remotely if configured previously without UEFI Lock.
-   1 - (Enabled with UEFI lock) Turns on Credential Guard with UEFI lock.
-   2 - (Enabled without lock) Turns on Credential Guard without UEFI lock.

<!--/SupportedValues-->
<!--EndPolicy-->
<hr/>
<!--StartPolicy-->
<a href="" id="deviceguard-requireplatformsecurityfeatures"></a>**DeviceGuard/RequirePlatformSecurityFeatures**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--EndSKU-->
<!--StartScope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--EndScope-->
<!--StartDescription-->
Added in Windows 10, version 1709. Specifies the platform security level at the next reboot. Value type is integer.
 
<p style="margin-left: 20px">

<!--EndDescription-->
<!--SupportedValues-->
The following list shows the supported values:

-   1 (default) - Turns on VBS with Secure Boot.
-   3 - Turns on VBS with Secure Boot and direct memory access (DMA). DMA requires hardware support.

<!--/SupportedValues-->
<!--EndPolicy-->
<hr/>

Footnote:

-   1 - Added in Windows 10, version 1607.
-   2 - Added in Windows 10, version 1703.
-   3 - Added in Windows 10, version 1709.

<!--EndPolicies-->

