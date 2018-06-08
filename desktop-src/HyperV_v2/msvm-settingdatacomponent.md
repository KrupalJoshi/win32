---
Description: Establish a relationship between an instance of the Msvm\_EmulatedEthernetPortSettingData or Msvm\_SyntheticEthernetPortSettingData class with an instance of the Msvm\_GuestNetworkAdapterConfiguration class.
ms.assetid: 82262e67-1e72-4bad-974e-f18d00a94c3d
title: Msvm\_SettingDataComponent class
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Msvm\_SettingDataComponent class

Establish a relationship between an instance of the [**Msvm\_EmulatedEthernetPortSettingData**](msvm-emulatedethernetportsettingdata.md) or [**Msvm\_SyntheticEthernetPortSettingData**](msvm-syntheticethernetportsettingdata.md) class with an instance of the [**Msvm\_GuestNetworkAdapterConfiguration**](msvm-guestnetworkadapterconfiguration.md) class.

The following syntax is simplified Managed Object Format (MOF) code, and it includes all of the inherited properties.

## Syntax

``` syntax
[Association, Aggregation, Dynamic, Provider("VmmsWmiInstanceAndMethodProvider"), AMENDMENT]
class Msvm_SettingDataComponent : CIM_Component
{
  CIM_ResourceAllocationSettingData     REF GroupComponent;
  Msvm_GuestNetworkAdapterConfiguration REF PartComponent;
};
```

## Members

The **Msvm\_SettingDataComponent** class has these types of members:

-   [Properties](#properties)

### Properties

The **Msvm\_SettingDataComponent** class has these properties.

<dl> <dt>

**GroupComponent**
</dt> <dd> <dl> <dt>

Data type: **[**CIM\_ResourceAllocationSettingData**](https://msdn.microsoft.com/library/mt146214)**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**Key**](https://msdn.microsoft.com/library/aa392157), [**Override**](https://msdn.microsoft.com/library/aa393650) ("GroupComponent"), [**Aggregate**](https://msdn.microsoft.com/library/aa393650)
</dt> </dl>

A reference to an instance of the [**Msvm\_EmulatedEthernetPortSettingData**](msvm-emulatedethernetportsettingdata.md) or [**Msvm\_SyntheticEthernetPortSettingData**](msvm-syntheticethernetportsettingdata.md) class that represents an Ethernet port.

</dd> <dt>

**PartComponent**
</dt> <dd> <dl> <dt>

Data type: **[**Msvm\_GuestNetworkAdapterConfiguration**](msvm-guestnetworkadapterconfiguration.md)**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**Key**](https://msdn.microsoft.com/library/aa392157), [**Override**](https://msdn.microsoft.com/library/aa393650) ("PartComponent")
</dt> </dl>

A reference to an instance of the [**Msvm\_GuestNetworkAdapterConfiguration**](msvm-guestnetworkadapterconfiguration.md) class that represents a guest network adapter configuration.

</dd> </dl>

## Requirements



|                                     |                                                                                                         |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8 \[desktop apps only\]<br/>                                                              |
| Minimum supported server<br/> | Windows Server 2012 \[desktop apps only\]<br/>                                                    |
| Namespace<br/>                | Root\\Virtualization\\V2<br/>                                                                     |
| MOF<br/>                      | <dl> <dt>WindowsVirtualization.V2.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Vmms.exe</dt> </dl>                     |



 

 



