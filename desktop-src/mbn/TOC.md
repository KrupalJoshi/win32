# [Mobile Broadband](mobile-broadband-networks-portal.md)
## [Mobile Broadband API Best Practices](mobile-broadband-best-practices.md)
## [Mobile Broadband API Reference](mobile-broadband-networks-api-reference.md)
### [Mobile Broadband API Enumerations](mobile-broadband-networks-api-enumerations.md)
#### [MBN_ACTIVATION_STATE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_activation_state)
#### [MBN_AUTH_PROTOCOL](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_auth_protocol)
#### [MBN_BAND_CLASS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_band_class)
#### [MBN_CELLULAR_CLASS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_cellular_class)
#### [MBN_COMPRESSION](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_compression)
#### [MBN_CONNECTION_MODE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_connection_mode)
#### [MBN_CONTEXT_CONSTANTS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_context_constants)
#### [MBN_CONTEXT_TYPE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_context_type)
#### [MBN_CTRL_CAPS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_ctrl_caps)
#### [MBN_DATA_CLASS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_data_class)
#### [MBN_DEVICE_SERVICES_INTERFACE_STATE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_device_services_interface_state)
#### [MBN_INTERFACE_CAPS_CONSTANTS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_interface_caps_constants)
#### [MBN_MSG_STATUS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_msg_status)
#### [MBN_PIN_CONSTANTS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_pin_constants)
#### [MBN_PIN_FORMAT](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_pin_format)
#### [MBN_PIN_MODE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_pin_mode)
#### [MBN_PIN_STATE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_pin_state)
#### [MBN_PIN_TYPE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_pin_type)
#### [MBN_PROVIDER_CONSTANTS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_provider_constants)
#### [MBN_PROVIDER_STATE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_provider_state)
#### [MBN_RADIO](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_radio)
#### [MBN_READY_STATE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_ready_state)
#### [MBN_REGISTER_MODE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_register_mode)
#### [MBN_REGISTER_STATE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_register_state)
#### [MBN_REGISTRATION_CONSTANTS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_registration_constants)
#### [MBN_SIGNAL_CONSTANTS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_signal_constants)
#### [MBN_SMS_CAPS](https://msdn.microsoft.com/en-us/library/Dd323239(v=VS.85).aspx)
#### [MBN_SMS_CDMA_ENCODING](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_sms_cdma_encoding)
#### [MBN_SMS_CDMA_LANG](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_sms_cdma_lang)
#### [MBN_SMS_CONSTANTS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_sms_constants)
#### [MBN_SMS_FLAG](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_sms_flag)
#### [MBN_SMS_FORMAT](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_sms_format)
#### [MBN_SMS_STATUS_FLAG](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_sms_status_flag)
#### [MBN_VOICE_CALL_STATE](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_voice_call_state)
#### [MBN_VOICE_CLASS](/windows/desktop/api/mbnapi/ne-mbnapi-mbn_voice_class)
### [Mobile Broadband API Interfaces](mobile-broadband-networks-api-interfaces.md)
#### [IMbnConnection](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnection)
##### [Connect Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnection-connect)
##### [Disconnect Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnection-disconnect)
##### [GetActivationNetworkError Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnection-getactivationnetworkerror)
##### [GetConnectionState Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnection-getconnectionstate)
##### [GetVoiceCallState Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnection-getvoicecallstate)
##### [ConnectionID Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnection-get_connectionid)
##### [InterfaceID Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnection-get_interfaceid)
#### [IMbnConnectionContext](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectioncontext)
##### [GetProvisionedContexts Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectioncontext-getprovisionedcontexts)
##### [SetProvisionedContext Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectioncontext-setprovisionedcontext)
#### [IMbnConnectionContextEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectioncontextevents)
##### [OnProvisionedContextListChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectioncontextevents-onprovisionedcontextlistchange)
##### [OnSetProvisionedContextComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectioncontextevents-onsetprovisionedcontextcomplete)
#### [IMbnConnectionEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectionevents)
##### [OnConnectComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionevents-onconnectcomplete)
##### [OnConnectStateChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionevents-onconnectstatechange)
##### [OnDisconnectComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionevents-ondisconnectcomplete)
##### [OnVoiceCallStateChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionevents-onvoicecallstatechange)
#### [IMbnConnectionManager](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectionmanager)
##### [GetConnection Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionmanager-getconnection)
##### [GetConnections Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionmanager-getconnections)
#### [IMbnConnectionManagerEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectionmanagerevents)
##### [OnConnectionArrival Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionmanagerevents-onconnectionarrival)
##### [OnConnectionRemoval Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionmanagerevents-onconnectionremoval)
#### [IMbnConnectionProfile](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectionprofile)
##### [Delete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofile-delete)
##### [GetProfileXmlData Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofile-getprofilexmldata)
##### [UpdateProfile Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofile-updateprofile)
#### [IMbnConnectionProfileEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectionprofileevents)
##### [OnProfileUpdate Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofileevents-onprofileupdate)
#### [IMbnConnectionProfileManager](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectionprofilemanager)
##### [CreateConnectionProfile Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofilemanager-createconnectionprofile)
##### [GetConnectionProfile Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofilemanager-getconnectionprofile)
##### [GetConnectionProfiles Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofilemanager-getconnectionprofiles)
#### [IMbnConnectionProfileManagerEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnconnectionprofilemanagerevents)
##### [OnConnectionProfileArrival Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofilemanagerevents-onconnectionprofilearrival)
##### [OnConnectionProfileRemoval Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnconnectionprofilemanagerevents-onconnectionprofileremoval)
#### [IMbnDeviceService](/windows/desktop/api/mbnapi/nn-mbnapi-imbndeviceservice)
##### [QuerySupportedCommands method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-querysupportedcommands)
##### [OpenCommandSession method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-opencommandsession)
##### [CloseCommandSession method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-closecommandsession)
##### [SetCommand method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-setcommand)
##### [QueryCommand method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-querycommand)
##### [OpenDataSession method](https://msdn.microsoft.com/en-us/library/Hh780536(v=VS.85).aspx)
##### [CloseDataSession method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-closedatasession)
##### [WriteData method](https://msdn.microsoft.com/en-us/library/Hh780540(v=VS.85).aspx)
##### [IsDataSessionOpen property](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-get_isdatasessionopen)
##### [InterfaceID property](https://msdn.microsoft.com/en-us/library/Hh780532(v=VS.85).aspx)
##### [DeviceServiceID property](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-get_deviceserviceid)
##### [IsCommandSessionOpen property](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservice-get_iscommandsessionopen)
#### [IMbnDeviceServicesContext](/windows/desktop/api/mbnapi/nn-mbnapi-imbndeviceservicescontext)
##### [EnumerateDeviceServices method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicescontext-enumeratedeviceservices)
##### [GetDeviceService method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicescontext-getdeviceservice)
##### [MaxCommandSize property](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicescontext-get_maxcommandsize)
##### [MaxDataSize property](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicescontext-get_maxdatasize)
#### [IMbnDeviceServicesEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbndeviceservicesevents)
##### [OnQuerySupportedCommandsComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onquerysupportedcommandscomplete)
##### [OnOpenCommandSessionComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onopencommandsessioncomplete)
##### [OnCloseCommandSessionComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onclosecommandsessioncomplete)
##### [OnSetCommandComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onsetcommandcomplete)
##### [OnQueryCommandComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onquerycommandcomplete)
##### [OnEventNotification method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-oneventnotification)
##### [OnOpenDataSessionComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onopendatasessioncomplete)
##### [OnCloseDataSessionComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onclosedatasessioncomplete)
##### [OnWriteDataComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onwritedatacomplete)
##### [OnReadData method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-onreaddata)
##### [OnInterfaceStateChange method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesevents-oninterfacestatechange)
#### [IMbnDeviceServicesManager](/windows/desktop/api/mbnapi/nn-mbnapi-imbndeviceservicesmanager)
##### [GetDeviceServicesContext method](/windows/desktop/api/mbnapi/nf-mbnapi-imbndeviceservicesmanager-getdeviceservicescontext)
#### [IMbnInterface](/windows/desktop/api/mbnapi/nn-mbnapi-imbninterface)
##### [GetConnection Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-getconnection)
##### [GetInterfaceCapability Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-getinterfacecapability)
##### [GetHomeProvider Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-gethomeprovider)
##### [GetPreferredProviders Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-getpreferredproviders)
##### [GetReadyState Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-getreadystate)
##### [GetSubscriberInformation Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-getsubscriberinformation)
##### [GetVisibleProviders Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-getvisibleproviders)
##### [InEmergencyMode Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-inemergencymode)
##### [ScanNetwork Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-scannetwork)
##### [SetPreferredProviders Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-setpreferredproviders)
##### [InterfaceID Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterface-get_interfaceid)
#### [IMbnInterfaceEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbninterfaceevents)
##### [OnEmergencyModeChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfaceevents-onemergencymodechange)
##### [OnInterfaceCapabilityAvailable Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfaceevents-oninterfacecapabilityavailable)
##### [OnHomeProviderAvailable Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfaceevents-onhomeprovideravailable)
##### [OnPreferredProvidersChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfaceevents-onpreferredproviderschange)
##### [OnReadyStateChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfaceevents-onreadystatechange)
##### [OnSetPreferredProvidersComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfaceevents-onsetpreferredproviderscomplete)
##### [OnScanNetworkComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfaceevents-onscannetworkcomplete)
##### [OnSubscriberInformationChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfaceevents-onsubscriberinformationchange)
#### [IMbnInterfaceManager](/windows/desktop/api/mbnapi/nn-mbnapi-imbninterfacemanager)
##### [GetInterface Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfacemanager-getinterface)
##### [GetInterfaces Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfacemanager-getinterfaces)
#### [IMbnInterfaceManagerEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbninterfacemanagerevents)
##### [OnInterfaceArrival Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfacemanagerevents-oninterfacearrival)
##### [OnInterfaceRemoval Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbninterfacemanagerevents-oninterfaceremoval)
#### [IMbnMultiCarrier](/windows/desktop/api/mbnapi/nn-mbnapi-imbnmulticarrier)
##### [SetHomeProvider method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrier-sethomeprovider)
##### [GetPreferredProviders method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrier-getpreferredproviders)
##### [GetVisibleProviders method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrier-getvisibleproviders)
##### [GetSupportedCellularClasses method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrier-getsupportedcellularclasses)
##### [GetCurrentCellularClass method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrier-getcurrentcellularclass)
##### [ScanNetwork method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrier-scannetwork)
#### [IMbnMultiCarrierEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnmulticarrierevents)
##### [OnSetHomeProviderComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrierevents-onsethomeprovidercomplete)
##### [OnCurrentCellularClassChange method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrierevents-oncurrentcellularclasschange)
##### [OnInterfaceCapabilityChange method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrierevents-oninterfacecapabilitychange)
##### [OnPreferredProvidersChange method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrierevents-onpreferredproviderschange)
##### [OnScanNetworkComplete method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnmulticarrierevents-onscannetworkcomplete)
#### [IMbnPin](/windows/desktop/api/mbnapi/nn-mbnapi-imbnpin)
##### [Change Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-change)
##### [Disable Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-disable)
##### [Enable Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-enable)
##### [Enter Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-enter)
##### [GetPinManager Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-getpinmanager)
##### [Unblock Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-unblock)
##### [PinFormat Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-get_pinformat)
##### [PinLengthMax Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-get_pinlengthmax)
##### [PinLengthMin Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-get_pinlengthmin)
##### [PinMode Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-get_pinmode)
##### [PinType Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpin-get_pintype)
#### [IMbnPinEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnpinevents)
##### [OnChangeComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinevents-onchangecomplete)
##### [OnDisableComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinevents-ondisablecomplete)
##### [OnEnableComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinevents-onenablecomplete)
##### [OnEnterComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinevents-onentercomplete)
##### [OnUnblockComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinevents-onunblockcomplete)
#### [IMbnPinManager](/windows/desktop/api/mbnapi/nn-mbnapi-imbnpinmanager)
##### [GetPin Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinmanager-getpin)
##### [GetPinList Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinmanager-getpinlist)
##### [GetPinState Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinmanager-getpinstate)
#### [IMbnPinManagerEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnpinmanagerevents)
##### [OnGetPinStateComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinmanagerevents-ongetpinstatecomplete)
##### [OnPinListAvailable Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnpinmanagerevents-onpinlistavailable)
#### [IMbnRadio](/windows/desktop/api/mbnapi/nn-mbnapi-imbnradio)
##### [SetSoftwareRadioState Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnradio-setsoftwareradiostate)
##### [HardwareRadioState Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnradio-get_hardwareradiostate)
##### [SoftwareRadioState Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnradio-get_softwareradiostate)
#### [IMbnRadioEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnradioevents)
##### [OnRadioStateChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnradioevents-onradiostatechange)
##### [OnSetSoftwareRadioStateComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnradioevents-onsetsoftwareradiostatecomplete)
#### [IMbnRegistration](/windows/desktop/api/mbnapi/nn-mbnapi-imbnregistration)
##### [GetAvailableDataClasses Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getavailabledataclasses)
##### [GetCurrentDataClass Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getcurrentdataclass)
##### [GetPacketAttachNetworkError Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getpacketattachnetworkerror)
##### [GetProviderID Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getproviderid)
##### [GetProviderName Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getprovidername)
##### [GetRegisterMode Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getregistermode)
##### [GetRegisterState Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getregisterstate)
##### [GetRegistrationNetworkError Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getregistrationnetworkerror)
##### [GetRoamingText Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-getroamingtext)
##### [SetRegisterMode Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistration-setregistermode)
#### [IMbnRegistrationEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnregistrationevents)
##### [OnPacketServiceStateChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistrationevents-onpacketservicestatechange)
##### [OnRegisterModeAvailable Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistrationevents-onregistermodeavailable)
##### [OnRegisterStateChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistrationevents-onregisterstatechange)
##### [OnSetRegisterModeComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnregistrationevents-onsetregistermodecomplete)
#### [IMbnServiceActivation](/windows/desktop/api/mbnapi/nn-mbnapi-imbnserviceactivation)
##### [Activate Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnserviceactivation-activate)
#### [IMbnServiceActivationEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnserviceactivationevents)
##### [OnActivationComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnserviceactivationevents-onactivationcomplete)
#### [IMbnSignal](/windows/desktop/api/mbnapi/nn-mbnapi-imbnsignal)
##### [GetSignalError Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsignal-getsignalerror)
##### [GetSignalStrength Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsignal-getsignalstrength)
#### [IMbnSignalEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnsignalevents)
##### [OnSignalStateChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsignalevents-onsignalstatechange)
#### [IMbnSms](/windows/desktop/api/mbnapi/nn-mbnapi-imbnsms)
##### [GetSmsConfiguration Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsms-getsmsconfiguration)
##### [GetSmsStatus Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsms-getsmsstatus)
##### [SetSmsConfiguration Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsms-setsmsconfiguration)
##### [SmsDelete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsms-smsdelete)
##### [SmsRead Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsms-smsread)
##### [SmsSendCdma Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsms-smssendcdma)
##### [SmsSendCdmaPdu Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsms-smssendcdmapdu)
##### [SmsSendPdu Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsms-smssendpdu)
#### [IMbnSmsConfiguration](/windows/desktop/api/mbnapi/nn-mbnapi-imbnsmsconfiguration)
##### [CdmaShortMsgSize Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsconfiguration-get_cdmashortmsgsize)
##### [MaxMessageIndex Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsconfiguration-get_maxmessageindex)
##### [ServiceCenterAddress Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsconfiguration-get_servicecenteraddress)
##### [SmsFormat Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsconfiguration-get_smsformat)
#### [IMbnSmsEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnsmsevents)
##### [OnSetSmsConfigurationComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsevents-onsetsmsconfigurationcomplete)
##### [OnSmsConfigurationChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsevents-onsmsconfigurationchange)
##### [OnSmsDeleteComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsevents-onsmsdeletecomplete)
##### [OnSmsNewClass0Message Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsevents-onsmsnewclass0message)
##### [OnSmsReadComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsevents-onsmsreadcomplete)
##### [OnSmsSendComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsevents-onsmssendcomplete)
##### [OnSmsStatusChange Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsevents-onsmsstatuschange)
#### [IMbnSmsReadMsgPdu](/windows/desktop/api/mbnapi/nn-mbnapi-imbnsmsreadmsgpdu)
##### [Index Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgpdu-get_index)
##### [Message Property](https://msdn.microsoft.com/en-us/library/Dd535740(v=VS.85).aspx)
##### [PduData Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgpdu-get_pdudata)
##### [Status Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgpdu-get_status)
#### [IMbnSmsReadMsgTextCdma](/windows/desktop/api/mbnapi/nn-mbnapi-imbnsmsreadmsgtextcdma)
##### [Address Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgtextcdma-get_address)
##### [EncodingID Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgtextcdma-get_encodingid)
##### [Index Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgtextcdma-get_index)
##### [LanguageID Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgtextcdma-get_languageid)
##### [Message Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgtextcdma-get_message)
##### [SizeInCharacters Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgtextcdma-get_sizeincharacters)
##### [Status Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgtextcdma-get_status)
##### [Timestamp Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsmsreadmsgtextcdma-get_timestamp)
#### [IMbnSubscriberInformation](/windows/desktop/api/mbnapi/nn-mbnapi-imbnsubscriberinformation)
##### [SimIccID Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsubscriberinformation-get_simiccid)
##### [SubscriberID Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsubscriberinformation-get_subscriberid)
##### [TelephoneNumbers Property](/windows/desktop/api/mbnapi/nf-mbnapi-imbnsubscriberinformation-get_telephonenumbers)
#### [IMbnVendorSpecificEvents](/windows/desktop/api/mbnapi/nn-mbnapi-imbnvendorspecificevents)
##### [OnEventNotification Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnvendorspecificevents-oneventnotification)
##### [OnSetVendorSpecificComplete Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnvendorspecificevents-onsetvendorspecificcomplete)
#### [IMbnVendorSpecificOperation](/windows/desktop/api/mbnapi/nn-mbnapi-imbnvendorspecificoperation)
##### [SetVendorSpecific Method](/windows/desktop/api/mbnapi/nf-mbnapi-imbnvendorspecificoperation-setvendorspecific)
### [Mobile Broadband API Structures](mobile-broadband-networks-api-structures.md)
#### [MBN_CONTEXT](/windows/desktop/api/mbnapi/ns-mbnapi-mbn_context)
#### [MBN_DEVICE_SERVICE](/windows/desktop/api/mbnapi/ns-mbnapi-mbn_device_service)
#### [MBN_INTERFACE_CAPS](/windows/desktop/api/mbnapi/ns-mbnapi-mbn_interface_caps)
#### [MBN_PIN_INFO](/windows/desktop/api/mbnapi/ns-mbnapi-mbn_pin_info)
#### [MBN_PROVIDER](/windows/desktop/api/mbnapi/ns-mbnapi-mbn_provider)
#### [MBN_PROVIDER2](/windows/desktop/api/mbnapi/ns-mbnapi-mbn_provider2)
#### [MBN_SMS_FILTER](/windows/desktop/api/mbnapi/ns-mbnapi-mbn_sms_filter)
#### [MBN_SMS_STATUS_INFO](/windows/desktop/api/mbnapi/ns-mbnapi-mbn_sms_status_info)
#### [WWAN_INTERFACE_INFO](wwan-interface-info.md)
#### [WWAN_INTERFACE_INFO_LIST](wwan-interface-info-list.md)
#### [WWAN_INTERFACE_STATUS](wwan-interface-status.md)
### [Wireless Wide Area Network Functions](mobile-broadband-api-functions.md)
#### [WwanCloseHandle](wwanclosehandle.md)
#### [WwanEnumerateInterfaces](wwanenumerateinterfaces.md)
#### [WwanFreeMemory](wwanfreememory.md)
#### [WwanOpenHandle](wwanopenhandle.md)
#### [WwanQueryInterface](wwanqueryinterface.md)
## [Mobile Broadband Profile Schema Reference](schema-schema.md)
### [Mobile Broadband Profile Schema v1](mobile-broadband-profile-schema.md)
#### [Mobile Broadband Profile Schema v1 Elements](schema-elements.md)
##### [AccessString (contextType) Element](schema-accessstring-contexttype-element.md)
##### [AuthProtocol (contextType) Element](schema-authprotocol-contexttype-element.md)
##### [AutoConnectOnInternet (MBNProfile) Element](schema-autoconnectoninternet-mbnprofile-element.md)
##### [Compression (contextType) Element](schema-compression-contexttype-element.md)
##### [ConnectionMode (MBNProfile) Element](schema-connectionmode-mbnprofile-element.md)
##### [Context (MBNProfile) Element](schema-context-mbnprofile-element.md)
##### [DataRoamingPartners (MBNProfile) Element](schema-dataroamingpartners-mbnprofile-element.md)
##### [Description (MBNProfile) Element](schema-description-mbnprofile-element.md)
##### [HomeProviderName (MBNProfile) Element](schema-homeprovidername-mbnprofile-element.md)
##### [ICONFilePath (MBNProfile) Element](schema-iconfilepath-mbnprofile-element.md)
##### [IgnorePassword (UserLogonCred) Element](schema-ignorepassword-userlogoncred-element.md)
##### [IsDefault (MBNProfile) Element](schema-isdefault-mbnprofile-element.md)
##### [MBNProfile Element](schema-mbnprofile-element.md)
##### [Name (MBNProfile) Element](schema-name-mbnprofile-element.md)
##### [Password (UserLogonCred) Element](schema-password-userlogoncred-element.md)
##### [ProfileCreationType (MBNProfile) Element](schema-profilecreationtype-mbnprofile-element.md)
##### [Provider (DataRoamingPartners) Element](schema-provider-dataroamingpartners-element.md)
##### [ProviderID (providerType) Element](schema-providerid-providertype-element.md)
##### [ProviderName (providerType) Element](schema-providername-providertype-element.md)
##### [SimIccID (MBNProfile) Element](schema-simiccid-mbnprofile-element.md)
##### [SubscriberID (MBNProfile) Element](schema-subscriberid-mbnprofile-element.md)
##### [UserLogonCred (contextType) Element](schema-userlogoncred-contexttype-element.md)
##### [UserName (UserLogonCred) Element](schema-username-userlogoncred-element.md)
#### [Mobile Broadband Profile Schema v1 Simple Types](schema-simple-types.md)
##### [iconFileType Simple Type](schema-iconfiletype-simpletype.md)
##### [nameType Simple Type](schema-nametype-simpletype.md)
##### [providerIdType Simple Type](schema-provideridtype-simpletype.md)
##### [providerNameType Simple Type](schema-providernametype-simpletype.md)
##### [simIccIDType Simple Type](schema-simiccidtype-simpletype.md)
##### [subscriberIdType Simple Type](schema-subscriberidtype-simpletype.md)
#### [Mobile Broadband Profile Schema v1 Complex Types](schema-complex-types.md)
##### [contextType Complex Type](schema-contexttype-complextype.md)
##### [providerType Complex Type](schema-providertype-complextype.md)
### [Mobile Broadband Profile Schema v2](mobile-broadband-profile-schema-v2.md)
#### [Mobile Broadband Profile Schema v2 Elements](mobile-broadband-profile-schema-v2-elements.md)
##### [DisplayProviderName](element-displayprovidername.md)
##### [IsPurchaseProfile](element-ispurchaseprofile.md)
### [Mobile Broadband Profile Schema v3](mobile-broadband-profile-schema-v3.md)
#### [Mobile Broadband Profile Schema v3 Elements](mobile-broadband-profile-schema-v3-elements.md)
##### [IsAdditionalPdpContextProfile](element-isadditionalpdpcontextprofile.md)
### [Mobile Broadband Profile Schema v4](schema-root.md)
#### [Mobile Broadband Profile Schema v4 Elements](root-elements.md)
##### [MBNProfileExt](element-mbnprofileext.md)
###### [Name](element-name.md)
###### [Description](element-description.md)
###### [ICONFilePath](element-iconfilepath.md)
###### [IsDefault](element-isdefault.md)
###### [ProfileCreationType](element-profilecreationtype.md)
###### [SubscriberID](element-subscriberid.md)
###### [SimIccID](element-simiccid.md)
###### [HomeProviderName](element-homeprovidername.md)
###### [AutoConnectOnInternet](element-autoconnectoninternet.md)
###### [ConnectionMode](element-connectionmode.md)
###### [Context](element-context.md)
####### [AccessString](element-accessstring.md)
####### [UserLogonCred](element-userlogoncred.md)
######## [UserName](element-username.md)
######## [IgnorePassword](element-ignorepassword.md)
######## [Password](element-password.md)
####### [Compression](element-compression.md)
####### [AuthProtocol](element-authprotocol.md)
####### [IPType](element-iptype.md)
###### [DataRoamingPartners](element-dataroamingpartners.md)
####### [Provider](element-provider.md)
###### [PurposeGroups](element-purposegroups.md)
####### [PurposeGroupGuid](element-purposegroupguid.md)
###### [ProfileConditionedOn](element-profileconditionedon.md)
####### [CellularClass](element-cellularclass.md)
####### [RATApplicability](element-ratapplicability.md)
####### [RoamApplicability](element-roamapplicability.md)
####### [IMSI](element-imsi.md)
####### [IwlanApplicability](element-iwlanapplicability.md)
###### [IsProvisioningProfile](element-isprovisioningprofile.md)
###### [ApnID](element-apnid.md)
###### [AdminEnable](element-adminenable.md)
###### [AdminRoamControl](element-adminroamcontrol.md)
###### [IsExclusiveToOther](element-isexclusivetoother.md)
###### [IsLongStandingAdditionalPdpContextProfile](element-islongstandingadditionalpdpcontextprofile.md)
###### [MmsConfiguration](element-mmsconfiguration.md)
####### [MmscUrl](element-mmscurl.md)
####### [MmscPort](element-mmscport.md)
####### [MmsMaximumMessageSize](element-mmsmaximummessagesize.md)
##### [ModemDMConfigProfile](element-modemdmconfigprofile.md)
###### [Name](element-1-name.md)
###### [SimIccID](element-1-simiccid.md)
###### [ApnID](element-1-apnid.md)
###### [OemConnectionId](element-oemconnectionid.md)
###### [RoamApplicability](element-1-roamapplicability.md)
###### [Context](element-1-context.md)
####### [AccessString](element-1-accessstring.md)
####### [UserLogonCred](element-1-userlogoncred.md)
######## [UserName](element-1-username.md)
######## [IgnorePassword](element-1-ignorepassword.md)
######## [Password](element-1-password.md)
####### [Compression](element-1-compression.md)
####### [AuthProtocol](element-1-authprotocol.md)
####### [IPType](element-1-iptype.md)
###### [AdminEnable](element-1-adminenable.md)
###### [AdminRoamControl](element-1-adminroamcontrol.md)
###### [ProfileCreationType](element-1-profilecreationtype.md)
#### [Mobile Broadband Profile Schema v4 Simple types](simple-types.md)
##### [guidType Simple Type](simpletype-guidtype.md)
##### [iwlanApplicabilityType Simple Type](simpletype-iwlanapplicabilitytype.md)
##### [roamApplicabilityType Simple Type](simpletype-roamapplicabilitytype.md)
##### [roamControlType Simple Type](simpletype-roamcontroltype.md)
