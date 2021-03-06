
 | Name | RequiredServices | CanPauseAndContinue | CanShutdown | CanStop | Container | DependentServices | DisplayName | MachineName | ServiceHandle | ServiceName | ServicesDependedOn | ServiceType | Site | StartType | Status |
 |-----|-----------------|--------------------|------------|--------|----------|------------------|------------|------------|--------------|------------|-------------------|------------|-----|----------|-------|
 | AJRouter |  | False | False | False |  |  | AllJoyn Router Service | . | SafeServiceHandle | AJRouter |  | Win32ShareProcess |  | Manual | Stopped |
 | ALG |  | False | False | False |  |  | Application Layer Gateway Service | . | SafeServiceHandle | ALG |  | Win32OwnProcess |  | Manual | Stopped |
 | AppIDSvc | RpcSs CryptSvc AppID | False | False | False |  | applockerfltr | Application Identity | . | SafeServiceHandle | AppIDSvc | RpcSs CryptSvc AppID | Win32ShareProcess |  | Manual | Stopped |
 | Appinfo | RpcSs ProfSvc | False | False | True |  |  | Application Information | . | SafeServiceHandle | Appinfo | RpcSs ProfSvc | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | AppMgmt |  | False | False | False |  |  | Application Management | . | SafeServiceHandle | AppMgmt |  | Win32ShareProcess |  | Manual | Stopped |
 | AppReadiness |  | False | False | False |  |  | App Readiness | . | SafeServiceHandle | AppReadiness |  | Win32ShareProcess |  | Manual | Stopped |
 | AppVClient | AppvVfs RpcSS AppvStrm netprofm | False | True | True |  |  | Microsoft App-V Client | . | SafeServiceHandle | AppVClient | AppvVfs RpcSS AppvStrm netprofm | Win32OwnProcess |  | Automatic | Running |
 | AppXSvc | rpcss staterepository | False | True | True |  |  | AppX Deployment Service (AppXSVC) | . | SafeServiceHandle | AppXSvc | rpcss staterepository | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | aspnet_state |  | False | False | False |  |  | ASP.NET State Service | . | SafeServiceHandle | aspnet_state |  | Win32OwnProcess |  | Manual | Stopped |
 | AssignedAccessManagerSvc |  | False | False | False |  |  | AssignedAccessManager Service | . | SafeServiceHandle | AssignedAccessManagerSvc |  | Win32ShareProcess |  | Manual | Stopped |
 | AudioEndpointBuilder |  | False | False | True |  | Audiosrv | Windows Audio Endpoint Builder | . | SafeServiceHandle | AudioEndpointBuilder |  | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | Audiosrv | AudioEndpointBuilder RpcSs | False | False | True |  |  | Windows Audio | . | SafeServiceHandle | Audiosrv | AudioEndpointBuilder RpcSs | Win32OwnProcess |  | Automatic | Running |
 | AxInstSV | rpcss | False | False | False |  |  | ActiveX Installer (AxInstSV) | . | SafeServiceHandle | AxInstSV | rpcss | Win32ShareProcess |  | Manual | Stopped |
 | BDESVC |  | False | False | True |  |  | BitLocker Drive Encryption Service | . |  | BDESVC |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | BFE | RpcSs | False | False | True |  | SharedAccess XboxNetApiSvc WdNisSvc WdNisDrv RemoteAccess PolicyAgent NcaSvc MpsSvc IKEEXT | Base Filtering Engine | . |  | BFE | RpcSs | Win32ShareProcess |  | Automatic | Running |
 | BITS | RpcSs | False | False | False |  |  | Background Intelligent Transfer Service | . | SafeServiceHandle | BITS | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | BrokerInfrastructure | DcomLaunch RpcSs RpcEptMapper | False | False | False |  | embeddedmode | Background Tasks Infrastructure Service | . |  | BrokerInfrastructure | DcomLaunch RpcSs RpcEptMapper | Win32ShareProcess |  | Automatic | Running |
 | Browser | LanmanServer LanmanWorkstation | False | False | False |  |  | Computer Browser | . | SafeServiceHandle | Browser | LanmanServer LanmanWorkstation | Win32ShareProcess |  | Disabled | Stopped |
 | BthHFSrv | bthserv | False | False | False |  |  | Bluetooth Handsfree Service | . | SafeServiceHandle | BthHFSrv | bthserv | Win32ShareProcess |  | Manual | Stopped |
 | bthserv |  | False | True | True |  | BthHFSrv | Bluetooth Support Service | . | SafeServiceHandle | bthserv |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | camsvc |  | False | False | False |  |  | Capability Access Manager Service | . | SafeServiceHandle | camsvc |  | Win32ShareProcess |  | Manual | Stopped |
 | CcmExec | winmgmt | False | True | True |  |  | SMS Agent Host | . | SafeServiceHandle | CcmExec | winmgmt | Win32OwnProcess |  | Automatic | Running |
 | CDPSvc | Tcpip ncbservice RpcSS | False | False | True |  |  | Connected Devices Platform Service | . | SafeServiceHandle | CDPSvc | Tcpip ncbservice RpcSS | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | CDPUserSvc_16f456 |  | False | False | True |  |  | Connected Devices Platform User Service_16f456 | . | SafeServiceHandle | CDPUserSvc_16f456 |  | 240 |  | Automatic | Running |
 | CertPropSvc | RpcSs | False | True | True |  |  | Certificate Propagation | . |  | CertPropSvc | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | ClickToRunSvc |  | False | True | True |  |  | Microsoft Office Click-to-Run Service | . | SafeServiceHandle | ClickToRunSvc |  | Win32OwnProcess |  | Automatic | Running |
 | ClientMgmtSrv |  | True | True | True |  |  | Swisscom Client Management Service | . | SafeServiceHandle | ClientMgmtSrv |  | Win32OwnProcess |  | Automatic | Running |
 | ClipSVC | rpcss | False | False | False |  |  | Client License Service (ClipSVC) | . |  | ClipSVC | rpcss | Win32OwnProcess, Win32ShareProcess |  | Manual | Stopped |
 | CmRcService |  | False | True | True |  |  | Configuration Manager Remote Control | . | SafeServiceHandle | CmRcService |  | Win32OwnProcess |  | Automatic | Running |
 | COMSysApp | EventSystem SENS RpcSs | False | False | False |  |  | COM+ System Application | . | SafeServiceHandle | COMSysApp | EventSystem SENS RpcSs | Win32OwnProcess |  | Manual | Stopped |
 | CoreMessagingRegistrar | rpcss | False | False | False |  |  | CoreMessaging | . |  | CoreMessagingRegistrar | rpcss | Win32ShareProcess |  | Automatic | Running |
 | cphs | RPCSS | False | False | True |  |  | Intel(R) Content Protection HECI Service | . | SafeServiceHandle | cphs | RPCSS | Win32OwnProcess |  | Manual | Running |
 | cplspcon |  | False | False | True |  |  | Intel(R) Content Protection HDCP Service | . | SafeServiceHandle | cplspcon |  | Win32OwnProcess |  | Automatic | Running |
 | CryptSvc | RpcSs | False | True | True |  | applockerfltr AppIDSvc | Cryptographic Services | . | SafeServiceHandle | CryptSvc | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | CscService | RpcSs | False | False | True |  |  | Offline Files | . | SafeServiceHandle | CscService | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | CxMonSvc |  | False | True | True |  |  | CxMonSvc | . | SafeServiceHandle | CxMonSvc |  | Win32OwnProcess |  | Automatic | Running |
 | CxUtilSvc | RPCSS | False | False | True |  |  | CxUtilSvc | . | SafeServiceHandle | CxUtilSvc | RPCSS | Win32OwnProcess |  | Automatic | Running |
 | DcomLaunch |  | False | False | False |  | PrintWorkflowUserSvc_16f456 DevicesFlowUserSvc_16f456 ZeroConfigService XblGameSave xbgm XblAuthManager wlpasvc WwanSvc wuauserv workfolderssvc WMPNetworkSvc WSearch wscsvc WpnService WPDBusEnum wlidsvc WlanSvc wisvc WinRM vmms smstsmgr NcaSvc iphlpsvc HgClientService CcmExec Winmgmt WinDefend WiaRpc WFDSConMgrSvc WEPHOSTSVC wcncsvc icssvc Wcmsvc WbioSrvc VSS vmcompute vds VaultSvc UsoSvc TokenBroker UserManager TrkWks tiledatamodelsvc UmRdpService TermService Fax TapiSrv TabletInputService NaturalAuthentication Schedule SystemEventsBroker SysMain swprv stisvc AppXSvc StateRepository sppsvc Spooler spectrum SmsRouter smphost shpamsvc ShellHWDetection SharedRealitySvc SessionEnv SEMgrSvc SecurityHealthService SDRSVC SCPolicySvc MSDTC Browser LanmanServer KtmRm SamSs RmSvc RemoteRegistry RemoteAccess RegSrvc QWAVE PushToInstall Appinfo ProfSvc PrintWorkflowUserSvc PrintNotify pla PhoneSvc PerfHost PcaSvc NcdAutoSetup HomeGroupProvider AppVClient netprofm NlaSvc Netman Netlogon LanmanWorkstation IpxlatCfgSvc XboxNetApiSvc IKEEXT hns Dnscache WinHttpAutoProxySvc Dhcp nsi NgcSvc NgcCtnrSvc NetSetupSvc CDPSvc NcbService MyWiFiDHCPDNS msiserver MapsBroker LSM lltdsvc LicenseManager lfsvc dot3svc Eaphost KeyIso InstallService hpqwmiex HP Hotkey Service gupdatem gupdate gpsvc FrameServer fhsvc FDResPub fdPHost igfxCUIService2.0.0.0 COMSysApp SENS EventSystem EntAppSvc EFS DusmSvc DsmSvc DoSvc dmwappushservice DmEnrollmentSvc DiagTrack diagsvc DevicesFlowUserSvc defragsvc CxUtilSvc CscService applockerfltr AppIDSvc CryptSvc cphs CoreMessagingRegistrar ClipSVC CertPropSvc embeddedmode BrokerInfrastructure BITS SharedAccess WdNisSvc WdNisDrv PolicyAgent MpsSvc BFE AxInstSV Audiosrv RpcSs | DCOM Server Process Launcher | . |  | DcomLaunch |  | Win32ShareProcess |  | Automatic | Running |
 | defragsvc | RPCSS | False | False | False |  |  | Optimize drives | . | SafeServiceHandle | defragsvc | RPCSS | Win32OwnProcess |  | Manual | Stopped |
 | DeviceAssociationService |  | False | True | True |  |  | Device Association Service | . | SafeServiceHandle | DeviceAssociationService |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | DeviceInstall |  | False | False | False |  |  | Device Install Service | . | SafeServiceHandle | DeviceInstall |  | Win32ShareProcess |  | Manual | Stopped |
 | DevicesFlowUserSvc_16f456 |  | False | False | False |  |  | DevicesFlow_16f456 | . |  | DevicesFlowUserSvc_16f456 |  | 224 |  | Manual | Stopped |
 | DevQueryBroker |  | False | False | False |  |  | DevQuery Background Discovery Broker | . | SafeServiceHandle | DevQueryBroker |  | Win32ShareProcess |  | Manual | Stopped |
 | Dhcp | Afd NSI Tdx | False | True | True |  | NcaSvc iphlpsvc WinHttpAutoProxySvc NcdAutoSetup HomeGroupProvider AppVClient netprofm NlaSvc | DHCP Client | . | SafeServiceHandle | Dhcp | Afd NSI Tdx | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | diagnosticshub.standardcollector.service |  | False | False | False |  |  | Microsoft (R) Diagnostics Hub Standard Collector Service | . | SafeServiceHandle | diagnosticshub.standardcollector.service |  | Win32OwnProcess |  | Manual | Stopped |
 | diagsvc | RpcSs | False | False | False |  |  | Diagnostic Execution Service | . | SafeServiceHandle | diagsvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | DiagTrack | RpcSs | False | True | True |  |  | Connected User Experiences and Telemetry | . | SafeServiceHandle | DiagTrack | RpcSs | Win32OwnProcess |  | Automatic | Running |
 | DmEnrollmentSvc | rpcss | False | False | False |  |  | Device Management Enrollment Service | . | SafeServiceHandle | DmEnrollmentSvc | rpcss | Win32OwnProcess |  | Manual | Stopped |
 | dmwappushservice | rpcss | False | False | False |  |  | dmwappushsvc | . | SafeServiceHandle | dmwappushservice | rpcss | Win32OwnProcess, Win32ShareProcess |  | Automatic | Stopped |
 | Dnscache | nsi Tdx | False | False | False |  | NcaSvc | DNS Client | . |  | Dnscache | nsi Tdx | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | DoSvc | rpcss | False | False | False |  |  | Delivery Optimization | . | SafeServiceHandle | DoSvc | rpcss | Win32OwnProcess, Win32ShareProcess |  | Automatic | Stopped |
 | dot3svc | RpcSs Eaphost Ndisuio | False | True | True |  |  | Wired AutoConfig | . | SafeServiceHandle | dot3svc | RpcSs Eaphost Ndisuio | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | DPS |  | False | True | True |  |  | Diagnostic Policy Service | . |  | DPS |  | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | DsmSvc | RpcSs | False | False | False |  |  | Device Setup Manager | . | SafeServiceHandle | DsmSvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | DsSvc |  | False | False | True |  |  | Data Sharing Service | . | SafeServiceHandle | DsSvc |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | DusmSvc | RpcSs | False | False | True |  |  | Data Usage | . | SafeServiceHandle | DusmSvc | RpcSs | Win32OwnProcess |  | Automatic | Running |
 | Eaphost | RPCSS KeyIso | False | True | True |  | dot3svc | Extensible Authentication Protocol | . | SafeServiceHandle | Eaphost | RPCSS KeyIso | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | EFS | RPCSS | False | False | False |  |  | Encrypting File System (EFS) | . |  | EFS | RPCSS | Win32ShareProcess |  | Manual | Stopped |
 | embeddedmode | BrokerInfrastructure | False | False | False |  |  | Embedded Mode | . | SafeServiceHandle | embeddedmode | BrokerInfrastructure | Win32ShareProcess |  | Manual | Stopped |
 | EntAppSvc | rpcss | False | False | False |  |  | Enterprise App Management Service | . | SafeServiceHandle | EntAppSvc | rpcss | Win32ShareProcess |  | Manual | Stopped |
 | EventLog |  | False | True | True |  | Wecsvc NcdAutoSetup HomeGroupProvider AppVClient netprofm NlaSvc | Windows Event Log | . | SafeServiceHandle | EventLog |  | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | EventSystem | rpcss | False | False | True |  | igfxCUIService2.0.0.0 COMSysApp SENS | COM+ Event System | . | SafeServiceHandle | EventSystem | rpcss | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | EvtEng |  | False | False | True |  |  | Intel(R) PROSet/Wireless Event Log | . | SafeServiceHandle | EvtEng |  | Win32OwnProcess |  | Automatic | Running |
 | Fax | RpcSs TapiSrv Spooler | False | False | False |  |  | Fax | . | SafeServiceHandle | Fax | RpcSs TapiSrv Spooler | Win32OwnProcess |  | Disabled | Stopped |
 | fdPHost | RpcSs http | False | False | False |  | HomeGroupProvider | Function Discovery Provider Host | . | SafeServiceHandle | fdPHost | RpcSs http | Win32ShareProcess |  | Manual | Stopped |
 | FDResPub | RpcSs http | False | False | False |  | HomeGroupProvider | Function Discovery Resource Publication | . | SafeServiceHandle | FDResPub | RpcSs http | Win32ShareProcess |  | Manual | Stopped |
 | fhsvc | RpcSs | False | False | False |  |  | File History Service | . | SafeServiceHandle | fhsvc | RpcSs | Win32ShareProcess |  | Disabled | Stopped |
 | FontCache |  | False | True | True |  |  | Windows Font Cache Service | . | SafeServiceHandle | FontCache |  | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | FontCache3.0.0.0 |  | False | True | True |  |  | Windows Presentation Foundation Font Cache 3.0.0.0 | . | SafeServiceHandle | FontCache3.0.0.0 |  | Win32OwnProcess |  | Manual | Running |
 | FrameServer | rpcss | False | False | False |  |  | Windows Camera Frame Server | . | SafeServiceHandle | FrameServer | rpcss | Win32OwnProcess, Win32ShareProcess |  | Manual | Stopped |
 | gpsvc | RPCSS Mup | False | False | False |  |  | Group Policy Client | . |  | gpsvc | RPCSS Mup | Win32OwnProcess |  | Automatic | Stopped |
 | GraphicsPerfSvc |  | False | False | False |  |  | GraphicsPerfSvc | . | SafeServiceHandle | GraphicsPerfSvc |  | Win32ShareProcess |  | Manual | Stopped |
 | GRR Monitor |  | False | False | True |  |  | GRR Monitor | . | SafeServiceHandle | GRR Monitor |  | Win32OwnProcess |  | Automatic | Running |
 | gupdate | RPCSS | False | False | False |  |  | Google Update-Dienst (gupdate) | . | SafeServiceHandle | gupdate | RPCSS | Win32OwnProcess |  | Automatic | Stopped |
 | gupdatem | RPCSS | False | False | False |  |  | Google Update-Dienst (gupdatem) | . | SafeServiceHandle | gupdatem | RPCSS | Win32OwnProcess |  | Manual | Stopped |
 | HgClientService | Winmgmt | False | False | False |  |  | Host Guardian Client Service | . | SafeServiceHandle | HgClientService | Winmgmt | Win32ShareProcess |  | Manual | Stopped |
 | hidserv |  | False | True | True |  |  | Human Interface Device Service | . | SafeServiceHandle | hidserv |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | hns | RpcSs nsi | False | False | True |  |  | Host Network Service | . | SafeServiceHandle | hns | RpcSs nsi | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | HomeGroupListener |  | False | False | False |  |  | HomeGroup Listener | . | SafeServiceHandle | HomeGroupListener |  | Win32ShareProcess |  | Manual | Stopped |
 | HomeGroupProvider | fdrespub fdphost netprofm | False | False | False |  |  | HomeGroup Provider | . | SafeServiceHandle | HomeGroupProvider | fdrespub fdphost netprofm | Win32ShareProcess |  | Manual | Stopped |
 | HP Hotkey Service | RPCSS | False | True | True |  |  | HP Hotkey Service | . | SafeServiceHandle | HP Hotkey Service | RPCSS | Win32OwnProcess |  | Automatic | Running |
 | hpqwmiex | RPCSS | True | True | True |  |  | HP Software Framework Service | . | SafeServiceHandle | hpqwmiex | RPCSS | Win32OwnProcess |  | Manual | Running |
 | hpsrv |  | False | False | True |  |  | HP Service | . | SafeServiceHandle | hpsrv |  | Win32OwnProcess |  | Automatic | Running |
 | HvHost | hvservice | False | True | True |  |  | HV Host Service | . | SafeServiceHandle | HvHost | hvservice | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | ibtsiva |  | False | True | True |  |  | Intel Bluetooth Service | . | SafeServiceHandle | ibtsiva |  | Win32OwnProcess |  | Automatic | Running |
 | icssvc | RpcSs wcmsvc | False | False | False |  |  | Windows Mobile Hotspot Service | . | SafeServiceHandle | icssvc | RpcSs wcmsvc | Win32ShareProcess |  | Manual | Stopped |
 | igfxCUIService2.0.0.0 | SENS | False | False | True |  |  | Intel(R) HD Graphics Control Panel Service | . | SafeServiceHandle | igfxCUIService2.0.0.0 | SENS | Win32OwnProcess |  | Automatic | Running |
 | IKEEXT | nsi BFE | False | True | True |  | XboxNetApiSvc | IKE and AuthIP IPsec Keying Modules | . | SafeServiceHandle | IKEEXT | nsi BFE | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | InstallService | rpcss | False | False | False |  |  | Windows Store Install Service | . | SafeServiceHandle | InstallService | rpcss | Win32OwnProcess |  | Manual | Stopped |
 | IntelAudioService |  | False | True | True |  |  | Intel(R) Audio Service | . | SafeServiceHandle | IntelAudioService |  | Win32OwnProcess |  | Automatic | Running |
 | iphlpsvc | nsi RpcSS winmgmt Tdx tcpip WinHttpAutoProxySvc | False | False | False |  | NcaSvc | IP Helper | . | SafeServiceHandle | iphlpsvc | nsi RpcSS winmgmt Tdx tcpip WinHttpAutoProxySvc | Win32ShareProcess |  | Disabled | Stopped |
 | IpxlatCfgSvc | nsi | False | False | False |  |  | IP Translation Configuration Service | . | SafeServiceHandle | IpxlatCfgSvc | nsi | Win32ShareProcess |  | Manual | Stopped |
 | irmon | irda | False | False | False |  |  | Infrared monitor service | . | SafeServiceHandle | irmon | irda | Win32ShareProcess |  | Manual | Stopped |
 | KeyIso | RpcSs | False | False | True |  | XboxNetApiSvc dot3svc Eaphost | CNG Key Isolation | . | SafeServiceHandle | KeyIso | RpcSs | Win32ShareProcess |  | Manual | Running |
 | KtmRm | RPCSS SamSS | False | False | False |  |  | KtmRm for Distributed Transaction Coordinator | . | SafeServiceHandle | KtmRm | RPCSS SamSS | Win32ShareProcess |  | Manual | Stopped |
 | LanmanServer | SamSS Srv2 | False | False | True |  | Browser | Server | . | SafeServiceHandle | LanmanServer | SamSS Srv2 | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | LanmanWorkstation | NSI MRxSmb20 Bowser | True | False | True |  | SessionEnv Netlogon Browser | Workstation | . | SafeServiceHandle | LanmanWorkstation | NSI MRxSmb20 Bowser | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | lfsvc | RpcSs | False | False | True |  |  | Geolocation Service | . | SafeServiceHandle | lfsvc | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | LicenseManager | rpcss | False | False | True |  |  | Windows License Manager Service | . | SafeServiceHandle | LicenseManager | rpcss | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | lltdsvc | rpcss lltdio | False | False | False |  |  | Link-Layer Topology Discovery Mapper | . | SafeServiceHandle | lltdsvc | rpcss lltdio | Win32ShareProcess |  | Manual | Stopped |
 | lmhosts | Afd | False | False | True |  |  | TCP/IP NetBIOS Helper | . | SafeServiceHandle | lmhosts | Afd | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | lpasvc |  | False | False | False |  |  | Microsoft Policy Platform Local Authority | . | SafeServiceHandle | lpasvc |  | Win32ShareProcess |  | Manual | Stopped |
 | lppsvc |  | False | False | False |  |  | Microsoft Policy Platform Processor | . | SafeServiceHandle | lppsvc |  | Win32ShareProcess |  | Manual | Stopped |
 | LSM | DcomLaunch RpcSs RpcEptMapper | False | False | False |  |  | Local Session Manager | . |  | LSM | DcomLaunch RpcSs RpcEptMapper | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | macmnsvc |  | False | True | True |  |  | McAfee Agent Common Services | . |  | macmnsvc |  | Win32OwnProcess |  | Automatic | Running |
 | MapsBroker | rpcss | False | False | False |  |  | Downloaded Maps Manager | . | SafeServiceHandle | MapsBroker | rpcss | Win32OwnProcess |  | Automatic | Stopped |
 | masvc |  | False | True | True |  |  | McAfee Agent Service | . |  | masvc |  | Win32OwnProcess |  | Automatic | Running |
 | McAfeeFramework |  | False | True | True |  |  | McAfee Agent Backwards Compatibility Service | . |  | McAfeeFramework |  | Win32OwnProcess |  | Manual | Running |
 | MessagingService_16f456 |  | False | False | False |  |  | MessagingService_16f456 | . | SafeServiceHandle | MessagingService_16f456 |  | 240 |  | Automatic | Stopped |
 | mfefire | mfevtp | False | False | False |  |  | McAfee Firewall Core Service | . |  | mfefire | mfevtp | Win32OwnProcess |  | Manual | Stopped |
 | mfemms |  | False | True | True |  |  | McAfee Service Controller | . |  | mfemms |  | Win32OwnProcess |  | Automatic | Running |
 | mfevtp | mfehidk | False | True | True |  | mfefire | McAfee Validation Trust Protection Service | . |  | mfevtp | mfehidk | Win32OwnProcess |  | Automatic | Running |
 | MpsSvc | mpsdrv bfe | False | False | False |  | XboxNetApiSvc | Windows Defender Firewall | . |  | MpsSvc | mpsdrv bfe | Win32ShareProcess |  | Automatic | Running |
 | MSDTC | RPCSS SamSS | False | False | False |  |  | Distributed Transaction Coordinator | . |  | MSDTC | RPCSS SamSS | Win32OwnProcess |  | Manual | Stopped |
 | MSiSCSI |  | False | False | False |  |  | Microsoft iSCSI Initiator Service | . | SafeServiceHandle | MSiSCSI |  | Win32ShareProcess |  | Disabled | Stopped |
 | msiserver | rpcss | False | False | False |  |  | Windows Installer | . | SafeServiceHandle | msiserver | rpcss | Win32OwnProcess |  | Manual | Stopped |
 | MyWiFiDHCPDNS | RPCSS | False | False | False |  |  | Wireless PAN DHCP Server | . | SafeServiceHandle | MyWiFiDHCPDNS | RPCSS | Win32OwnProcess |  | Manual | Stopped |
 | NaturalAuthentication | RpcSs Schedule ProfSvc | False | False | False |  |  | Natural Authentication | . | SafeServiceHandle | NaturalAuthentication | RpcSs Schedule ProfSvc | Win32ShareProcess |  | Manual | Stopped |
 | NcaSvc | NSI dnscache iphlpsvc BFE | False | False | False |  |  | Network Connectivity Assistant | . | SafeServiceHandle | NcaSvc | NSI dnscache iphlpsvc BFE | Win32ShareProcess |  | Manual | Stopped |
 | NcbService | RpcSS tcpip | False | False | True |  | CDPSvc | Network Connection Broker | . | SafeServiceHandle | NcbService | RpcSS tcpip | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | NcdAutoSetup | netprofm | False | False | False |  |  | Network Connected Devices Auto-Setup | . | SafeServiceHandle | NcdAutoSetup | netprofm | Win32ShareProcess |  | Disabled | Stopped |
 | Net Driver HPZ12 |  | False | True | True |  |  | Net Driver HPZ12 | . | SafeServiceHandle | Net Driver HPZ12 |  | Win32OwnProcess |  | Automatic | Running |
 | Netlogon | LanmanWorkstation | True | False | True |  |  | Netlogon | . | SafeServiceHandle | Netlogon | LanmanWorkstation | Win32ShareProcess |  | Automatic | Running |
 | Netman | RpcSs nsi | False | False | True |  |  | Network Connections | . | SafeServiceHandle | Netman | RpcSs nsi | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | netprofm | RpcSs nlasvc | False | False | True |  | NcdAutoSetup HomeGroupProvider AppVClient | Network List Service | . | SafeServiceHandle | netprofm | RpcSs nlasvc | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | NetSetupSvc | RpcSs | False | False | False |  |  | Network Setup Service | . | SafeServiceHandle | NetSetupSvc | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Manual | Stopped |
 | NetTcpPortSharing |  | False | False | False |  |  | Net.Tcp Port Sharing Service | . | SafeServiceHandle | NetTcpPortSharing |  | Win32ShareProcess |  | Disabled | Stopped |
 | NgcCtnrSvc | RpcSs | False | False | False |  |  | Microsoft Passport Container | . |  | NgcCtnrSvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | NgcSvc | RpcSs | False | False | False |  |  | Microsoft Passport | . |  | NgcSvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | NlaSvc | NSI RpcSs Eventlog Dhcp TcpIp | False | False | True |  | NcdAutoSetup HomeGroupProvider AppVClient netprofm | Network Location Awareness | . | SafeServiceHandle | NlaSvc | NSI RpcSs Eventlog Dhcp TcpIp | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | nsi | rpcss nsiproxy | False | False | True |  | WlanSvc icssvc Wcmsvc NcdAutoSetup HomeGroupProvider AppVClient netprofm NlaSvc Netman NcaSvc SessionEnv Netlogon Browser LanmanWorkstation IpxlatCfgSvc iphlpsvc XboxNetApiSvc IKEEXT hns Dnscache WinHttpAutoProxySvc Dhcp | Network Store Interface Service | . | SafeServiceHandle | nsi | rpcss nsiproxy | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | OneSyncSvc_16f456 |  | False | False | True |  |  | Sync Host_16f456 | . | SafeServiceHandle | OneSyncSvc_16f456 |  | 224 |  | Automatic | Running |
 | ose |  | False | False | False |  |  | Office  Source Engine | . | SafeServiceHandle | ose |  | Win32OwnProcess |  | Manual | Stopped |
 | p2pimsvc |  | False | False | False |  | PNRPAutoReg p2psvc PNRPsvc | Peer Networking Identity Manager | . | SafeServiceHandle | p2pimsvc |  | Win32ShareProcess |  | Manual | Stopped |
 | p2psvc | PNRPSvc p2pimsvc | False | False | False |  |  | Peer Networking Grouping | . | SafeServiceHandle | p2psvc | PNRPSvc p2pimsvc | Win32ShareProcess |  | Manual | Stopped |
 | PcaSvc | RpcSs | False | True | True |  |  | Program Compatibility Assistant Service | . | SafeServiceHandle | PcaSvc | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | PeerDistSvc | http | False | True | True |  |  | BranchCache | . | SafeServiceHandle | PeerDistSvc | http | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | PerfHost | RPCSS | False | False | False |  |  | Performance Counter DLL Host | . | SafeServiceHandle | PerfHost | RPCSS | Win32OwnProcess |  | Manual | Stopped |
 | PhoneSvc | RpcSs | False | False | False |  |  | Phone Service | . | SafeServiceHandle | PhoneSvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | PimIndexMaintenanceSvc_16f456 |  | False | False | True |  |  | Contact Data_16f456 | . |  | PimIndexMaintenanceSvc_16f456 |  | 224 |  | Manual | Running |
 | pla | RPCSS | False | False | False |  |  | Performance Logs & Alerts | . | SafeServiceHandle | pla | RPCSS | Win32ShareProcess |  | Manual | Stopped |
 | PlugPlay |  | False | True | True |  |  | Plug and Play | . | SafeServiceHandle | PlugPlay |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | Pml Driver HPZ12 |  | False | True | True |  |  | Pml Driver HPZ12 | . | SafeServiceHandle | Pml Driver HPZ12 |  | Win32OwnProcess |  | Automatic | Running |
 | PNRPAutoReg | pnrpsvc | False | False | False |  |  | PNRP Machine Name Publication Service | . | SafeServiceHandle | PNRPAutoReg | pnrpsvc | Win32ShareProcess |  | Manual | Stopped |
 | PNRPsvc | p2pimsvc | False | False | False |  | PNRPAutoReg p2psvc | Peer Name Resolution Protocol | . | SafeServiceHandle | PNRPsvc | p2pimsvc | Win32ShareProcess |  | Manual | Stopped |
 | PolicyAgent | Tcpip bfe | False | True | True |  |  | IPsec Policy Agent | . | SafeServiceHandle | PolicyAgent | Tcpip bfe | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | Power |  | False | False | False |  |  | Power | . | SafeServiceHandle | Power |  | Win32ShareProcess |  | Automatic | Running |
 | PrintNotify | RpcSs | False | False | False |  |  | Printer Extensions and Notifications | . | SafeServiceHandle | PrintNotify | RpcSs | Win32ShareProcess, InteractiveProcess |  | Manual | Stopped |
 | PrintWorkflowUserSvc_16f456 |  | False | False | False |  |  | PrintWorkflow_16f456 | . |  | PrintWorkflowUserSvc_16f456 |  | 224 |  | Manual | Stopped |
 | ProfSvc | RpcSs | False | True | True |  | XblGameSave xbgm TokenBroker UserManager shpamsvc NaturalAuthentication Appinfo | User Profile Service | . | SafeServiceHandle | ProfSvc | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | PushToInstall | rpcss | False | False | False |  |  | Windows PushToInstall Service | . | SafeServiceHandle | PushToInstall | rpcss | Win32OwnProcess, Win32ShareProcess |  | Manual | Stopped |
 | QWAVE | QWAVEdrv rpcss LLTDIO psched | False | False | False |  |  | Quality Windows Audio Video Experience | . | SafeServiceHandle | QWAVE | QWAVEdrv rpcss LLTDIO psched | Win32ShareProcess |  | Manual | Stopped |
 | RasAuto | RasAcd | False | False | False |  |  | Remote Access Auto Connection Manager | . | SafeServiceHandle | RasAuto | RasAcd | Win32ShareProcess |  | Manual | Stopped |
 | RasMan | SstpSvc | False | True | True |  | RemoteAccess | Remote Access Connection Manager | . | SafeServiceHandle | RasMan | SstpSvc | Win32ShareProcess |  | Automatic | Running |
 | RegSrvc | RPCSS | False | False | True |  |  | Intel(R) PROSet/Wireless Registry Service | . | SafeServiceHandle | RegSrvc | RPCSS | Win32OwnProcess |  | Automatic | Running |
 | RemoteAccess | Http RasMan RpcSS Bfe | False | False | False |  |  | Routing and Remote Access | . | SafeServiceHandle | RemoteAccess | Http RasMan RpcSS Bfe | Win32ShareProcess |  | Disabled | Stopped |
 | RemoteRegistry | RPCSS | False | False | False |  |  | Remote Registry | . | SafeServiceHandle | RemoteRegistry | RPCSS | Win32ShareProcess |  | Manual | Stopped |
 | RetailDemo |  | False | False | False |  |  | Retail Demo Service | . | SafeServiceHandle | RetailDemo |  | Win32ShareProcess |  | Manual | Stopped |
 | RmSvc | RpcSs | False | False | False |  |  | Radio Management Service | . |  | RmSvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | RpcEptMapper |  | False | False | False |  | NaturalAuthentication Schedule SystemEventsBroker PrintWorkflowUserSvc_16f456 DevicesFlowUserSvc_16f456 ZeroConfigService XblGameSave xbgm XblAuthManager wlpasvc WwanSvc wuauserv workfolderssvc WMPNetworkSvc WSearch wscsvc WpnService WPDBusEnum wlidsvc WlanSvc wisvc WinRM vmms smstsmgr NcaSvc iphlpsvc HgClientService CcmExec Winmgmt WinDefend WiaRpc WFDSConMgrSvc WEPHOSTSVC wcncsvc icssvc Wcmsvc WbioSrvc VSS vmcompute vds VaultSvc UsoSvc TokenBroker UserManager TrkWks tiledatamodelsvc UmRdpService TermService Fax TapiSrv TabletInputService SysMain swprv stisvc AppXSvc StateRepository sppsvc Spooler spectrum SmsRouter smphost shpamsvc ShellHWDetection SharedRealitySvc SessionEnv SEMgrSvc SecurityHealthService SDRSVC SCPolicySvc MSDTC Browser LanmanServer KtmRm SamSs RmSvc RemoteRegistry RemoteAccess RegSrvc QWAVE PushToInstall Appinfo ProfSvc PrintWorkflowUserSvc PrintNotify pla PhoneSvc PerfHost PcaSvc NcdAutoSetup HomeGroupProvider AppVClient netprofm NlaSvc Netman Netlogon LanmanWorkstation IpxlatCfgSvc XboxNetApiSvc IKEEXT hns Dnscache WinHttpAutoProxySvc Dhcp nsi NgcSvc NgcCtnrSvc NetSetupSvc CDPSvc NcbService MyWiFiDHCPDNS msiserver MapsBroker LSM lltdsvc LicenseManager lfsvc dot3svc Eaphost KeyIso InstallService hpqwmiex HP Hotkey Service gupdatem gupdate gpsvc FrameServer fhsvc FDResPub fdPHost igfxCUIService2.0.0.0 COMSysApp SENS EventSystem EntAppSvc EFS DusmSvc DsmSvc DoSvc dmwappushservice DmEnrollmentSvc DiagTrack diagsvc DevicesFlowUserSvc defragsvc CxUtilSvc CscService applockerfltr AppIDSvc CryptSvc cphs CoreMessagingRegistrar ClipSVC CertPropSvc embeddedmode BrokerInfrastructure BITS SharedAccess WdNisSvc WdNisDrv PolicyAgent MpsSvc BFE AxInstSV Audiosrv RpcSs | RPC Endpoint Mapper | . |  | RpcEptMapper |  | Win32ShareProcess |  | Automatic | Running |
 | RpcLocator |  | False | False | False |  |  | Remote Procedure Call (RPC) Locator | . | SafeServiceHandle | RpcLocator |  | Win32OwnProcess |  | Manual | Stopped |
 | RpcSs | DcomLaunch RpcEptMapper | False | False | False |  | PrintWorkflowUserSvc_16f456 DevicesFlowUserSvc_16f456 ZeroConfigService XblGameSave xbgm XblAuthManager wlpasvc WwanSvc wuauserv workfolderssvc WMPNetworkSvc WSearch wscsvc WpnService WPDBusEnum wlidsvc WlanSvc wisvc WinRM vmms smstsmgr NcaSvc iphlpsvc HgClientService CcmExec Winmgmt WinDefend WiaRpc WFDSConMgrSvc WEPHOSTSVC wcncsvc icssvc Wcmsvc WbioSrvc VSS vmcompute vds VaultSvc UsoSvc TokenBroker UserManager TrkWks tiledatamodelsvc UmRdpService TermService Fax TapiSrv TabletInputService NaturalAuthentication Schedule SystemEventsBroker SysMain swprv stisvc AppXSvc StateRepository sppsvc Spooler spectrum SmsRouter smphost shpamsvc ShellHWDetection SharedRealitySvc SessionEnv SEMgrSvc SecurityHealthService SDRSVC SCPolicySvc MSDTC Browser LanmanServer KtmRm SamSs RmSvc RemoteRegistry RemoteAccess RegSrvc QWAVE PushToInstall Appinfo ProfSvc PrintWorkflowUserSvc PrintNotify pla PhoneSvc PerfHost PcaSvc NcdAutoSetup HomeGroupProvider AppVClient netprofm NlaSvc Netman Netlogon LanmanWorkstation IpxlatCfgSvc XboxNetApiSvc IKEEXT hns Dnscache WinHttpAutoProxySvc Dhcp nsi NgcSvc NgcCtnrSvc NetSetupSvc CDPSvc NcbService MyWiFiDHCPDNS msiserver MapsBroker LSM lltdsvc LicenseManager lfsvc dot3svc Eaphost KeyIso InstallService hpqwmiex HP Hotkey Service gupdatem gupdate gpsvc FrameServer fhsvc FDResPub fdPHost igfxCUIService2.0.0.0 COMSysApp SENS EventSystem EntAppSvc EFS DusmSvc DsmSvc DoSvc dmwappushservice DmEnrollmentSvc DiagTrack diagsvc DevicesFlowUserSvc defragsvc CxUtilSvc CscService applockerfltr AppIDSvc CryptSvc cphs CoreMessagingRegistrar ClipSVC CertPropSvc embeddedmode BrokerInfrastructure BITS SharedAccess WdNisSvc WdNisDrv PolicyAgent MpsSvc BFE AxInstSV Audiosrv | Remote Procedure Call (RPC) | . |  | RpcSs | DcomLaunch RpcEptMapper | Win32ShareProcess |  | Automatic | Running |
 | SamSs | RPCSS | False | False | False |  | MSDTC Browser LanmanServer KtmRm | Security Accounts Manager | . | SafeServiceHandle | SamSs | RPCSS | Win32ShareProcess |  | Automatic | Running |
 | SCardSvr |  | False | False | False |  |  | Smart Card | . |  | SCardSvr |  | Win32ShareProcess |  | Disabled | Stopped |
 | ScDeviceEnum |  | False | False | False |  |  | Smart Card Device Enumeration Service | . |  | ScDeviceEnum |  | Win32ShareProcess |  | Manual | Stopped |
 | Schedule | RPCSS SystemEventsBroker | False | True | True |  | NaturalAuthentication | Task Scheduler | . |  | Schedule | RPCSS SystemEventsBroker | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | SCPolicySvc | RpcSs | False | False | False |  |  | Smart Card Removal Policy | . |  | SCPolicySvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | SDRSVC | RPCSS | False | False | False |  |  | Windows Backup | . | SafeServiceHandle | SDRSVC | RPCSS | Win32OwnProcess |  | Manual | Stopped |
 | seclogon |  | False | False | False |  |  | Secondary Logon | . | SafeServiceHandle | seclogon |  | Win32ShareProcess |  | Manual | Stopped |
 | SecurityHealthService | RpcSs | False | False | True |  |  | Windows Defender Security Center Service | . |  | SecurityHealthService | RpcSs | Win32OwnProcess |  | Automatic | Running |
 | SEMgrSvc | RpcSs | False | False | True |  |  | Payments and NFC/SE Manager | . | SafeServiceHandle | SEMgrSvc | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | SENS | EventSystem | False | False | True |  | igfxCUIService2.0.0.0 COMSysApp | System Event Notification Service | . | SafeServiceHandle | SENS | EventSystem | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | Sense |  | False | False | False |  |  | Windows Defender Advanced Threat Protection Service | . |  | Sense |  | Win32OwnProcess |  | Manual | Stopped |
 | SensorDataService |  | False | False | False |  |  | Sensor Data Service | . | SafeServiceHandle | SensorDataService |  | Win32OwnProcess |  | Manual | Stopped |
 | SensorService |  | False | False | False |  |  | Sensor Service | . | SafeServiceHandle | SensorService |  | Win32ShareProcess |  | Manual | Stopped |
 | SensrSvc |  | False | False | False |  |  | Sensor Monitoring Service | . | SafeServiceHandle | SensrSvc |  | Win32ShareProcess |  | Manual | Stopped |
 | SessionEnv | RPCSS LanmanWorkstation | False | False | True |  |  | Remote Desktop Configuration | . | SafeServiceHandle | SessionEnv | RPCSS LanmanWorkstation | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | SharedAccess | BFE | False | False | False |  |  | Internet Connection Sharing (ICS) | . | SafeServiceHandle | SharedAccess | BFE | Win32ShareProcess |  | Disabled | Stopped |
 | SharedRealitySvc | RpcSS | False | False | False |  |  | Spatial Data Service | . | SafeServiceHandle | SharedRealitySvc | RpcSS | Win32ShareProcess |  | Manual | Stopped |
 | ShellHWDetection | RpcSs | False | False | True |  |  | Shell Hardware Detection | . | SafeServiceHandle | ShellHWDetection | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | shpamsvc | RpcSs ProfSvc | False | False | False |  |  | Shared PC Account Manager | . | SafeServiceHandle | shpamsvc | RpcSs ProfSvc | Win32ShareProcess |  | Disabled | Stopped |
 | smphost | RPCSS | False | False | False |  |  | Microsoft Storage Spaces SMP | . | SafeServiceHandle | smphost | RPCSS | Win32OwnProcess |  | Manual | Stopped |
 | SmsRouter | RpcSs NdisUio | False | True | True |  |  | Microsoft Windows SMS Router Service. | . |  | SmsRouter | RpcSs NdisUio | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | smstsmgr | winmgmt | False | False | False |  |  | ConfigMgr Task Sequence Agent | . | SafeServiceHandle | smstsmgr | winmgmt | Win32OwnProcess |  | Disabled | Stopped |
 | SNMPTRAP |  | False | False | False |  |  | SNMP Trap | . | SafeServiceHandle | SNMPTRAP |  | Win32OwnProcess |  | Disabled | Stopped |
 | spectrum | rpcss | False | False | False |  |  | Windows Perception Service | . | SafeServiceHandle | spectrum | rpcss | Win32OwnProcess |  | Manual | Stopped |
 | Spooler | RPCSS http | False | False | True |  | Fax | Print Spooler | . | SafeServiceHandle | Spooler | RPCSS http | Win32OwnProcess, InteractiveProcess |  | Automatic | Running |
 | sppsvc | RpcSs | False | False | False |  |  | Software Protection | . |  | sppsvc | RpcSs | Win32OwnProcess |  | Automatic | Stopped |
 | SQLWriter |  | False | True | True |  |  | SQL Server VSS Writer | . | SafeServiceHandle | SQLWriter |  | Win32OwnProcess |  | Automatic | Running |
 | SSDPSRV | HTTP | False | False | False |  | upnphost | SSDP Discovery | . | SafeServiceHandle | SSDPSRV | HTTP | Win32ShareProcess |  | Disabled | Stopped |
 | SstpSvc |  | False | True | True |  | RemoteAccess RasMan | Secure Socket Tunneling Protocol Service | . | SafeServiceHandle | SstpSvc |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | StateRepository | rpcss | False | True | True |  | tiledatamodelsvc AppXSvc | State Repository Service | . | SafeServiceHandle | StateRepository | rpcss | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | stisvc | RpcSs | False | False | False |  |  | Windows Image Acquisition (WIA) | . | SafeServiceHandle | stisvc | RpcSs | Win32OwnProcess |  | Manual | Stopped |
 | StorSvc |  | False | False | True |  |  | Storage Service | . | SafeServiceHandle | StorSvc |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | svsvc |  | False | False | False |  |  | Spot Verifier | . | SafeServiceHandle | svsvc |  | Win32ShareProcess |  | Manual | Stopped |
 | SwisscomWorkplaceService |  | False | True | True |  |  | Swisscom Workplace Service | . | SafeServiceHandle | SwisscomWorkplaceService |  | Win32OwnProcess |  | Automatic | Running |
 | swprv | RPCSS | False | False | False |  |  | Microsoft Software Shadow Copy Provider | . | SafeServiceHandle | swprv | RPCSS | Win32OwnProcess |  | Manual | Stopped |
 | SynTPEnhService |  | False | True | True |  |  | SynTPEnh Caller Service | . | SafeServiceHandle | SynTPEnhService |  | Win32OwnProcess |  | Automatic | Running |
 | SysMain | rpcss fileinfo | False | True | True |  |  | Superfetch | . | SafeServiceHandle | SysMain | rpcss fileinfo | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | Sysmon |  | False | False | True |  |  | Sysmon | . | SafeServiceHandle | Sysmon |  | Win32OwnProcess |  | Automatic | Running |
 | SystemEventsBroker | RpcSs RpcEptMapper | False | False | True |  | NaturalAuthentication Schedule | System Events Broker | . |  | SystemEventsBroker | RpcSs RpcEptMapper | Win32ShareProcess |  | Automatic | Running |
 | TabletInputService | RpcSs | False | False | True |  |  | Touch Keyboard and Handwriting Panel Service | . | SafeServiceHandle | TabletInputService | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | TapiSrv | RpcSs | False | False | False |  | Fax | Telephony | . | SafeServiceHandle | TapiSrv | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | TechSmith Uploader Service |  | True | False | True |  |  | TechSmith Uploader Service | . | SafeServiceHandle | TechSmith Uploader Service |  | Win32OwnProcess |  | Automatic | Running |
 | TermService | RPCSS | False | True | True |  | UmRdpService | Remote Desktop Services | . | SafeServiceHandle | TermService | RPCSS | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | Themes |  | False | False | True |  |  | Themes | . | SafeServiceHandle | Themes |  | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | TieringEngineService |  | False | False | False |  |  | Storage Tiers Management | . | SafeServiceHandle | TieringEngineService |  | Win32OwnProcess |  | Manual | Stopped |
 | tiledatamodelsvc | rpcss staterepository | False | False | False |  |  | Tile Data model server | . | SafeServiceHandle | tiledatamodelsvc | rpcss staterepository | Win32OwnProcess, Win32ShareProcess |  | Manual | Stopped |
 | TimeBrokerSvc |  | False | False | True |  |  | Time Broker | . |  | TimeBrokerSvc |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | TokenBroker | UserManager | False | False | True |  |  | Web Account Manager | . | SafeServiceHandle | TokenBroker | UserManager | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | TrkWks | RpcSs | False | False | False |  |  | Distributed Link Tracking Client | . | SafeServiceHandle | TrkWks | RpcSs | Win32ShareProcess |  | Disabled | Stopped |
 | TrustedInstaller |  | False | False | False |  |  | Windows Modules Installer | . |  | TrustedInstaller |  | Win32OwnProcess |  | Manual | Stopped |
 | tzautoupdate |  | False | False | False |  |  | Auto Time Zone Updater | . | SafeServiceHandle | tzautoupdate |  | Win32ShareProcess |  | Disabled | Stopped |
 | UevAgentService |  | False | True | True |  |  | User Experience Virtualization Service | . | SafeServiceHandle | UevAgentService |  | Win32OwnProcess |  | Automatic | Running |
 | UI0Detect |  | False | False | False |  |  | Interactive Services Detection | . | SafeServiceHandle | UI0Detect |  | Win32OwnProcess, InteractiveProcess |  | Manual | Stopped |
 | UIUService |  | False | False | False |  |  | Conexant UIU Service | . | SafeServiceHandle | UIUService |  | Win32OwnProcess |  | Automatic | Stopped |
 | UmRdpService | RDPDR TermService | False | True | True |  |  | Remote Desktop Services UserMode Port Redirector | . | SafeServiceHandle | UmRdpService | RDPDR TermService | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | UnistoreSvc_16f456 |  | False | False | True |  | UserDataSvc_16f456 PimIndexMaintenanceSvc_16f456 | User Data Storage_16f456 | . |  | UnistoreSvc_16f456 |  | 224 |  | Manual | Running |
 | upnphost | HTTP SSDPSRV | False | False | False |  |  | UPnP Device Host | . | SafeServiceHandle | upnphost | HTTP SSDPSRV | Win32ShareProcess |  | Disabled | Stopped |
 | UserDataSvc_16f456 |  | False | False | True |  |  | User Data Access_16f456 | . |  | UserDataSvc_16f456 |  | 224 |  | Manual | Running |
 | UserManager | RpcSs ProfSvc | False | False | True |  | XblGameSave xbgm TokenBroker | User Manager | . | SafeServiceHandle | UserManager | RpcSs ProfSvc | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | UsoSvc | rpcss | False | False | False |  |  | Update Orchestrator Service | . | SafeServiceHandle | UsoSvc | rpcss | Win32ShareProcess |  | Manual | Stopped |
 | VaultSvc | rpcss | False | True | True |  |  | Credential Manager | . | SafeServiceHandle | VaultSvc | rpcss | Win32ShareProcess |  | Manual | Running |
 | vds | RpcSs | False | False | False |  |  | Virtual Disk | . | SafeServiceHandle | vds | RpcSs | Win32OwnProcess |  | Manual | Stopped |
 | vmcompute | rpcss wcifs condrv hvsocketcontrol | False | False | True |  |  | Hyper-V Host Compute Service | . | SafeServiceHandle | vmcompute | rpcss wcifs condrv hvsocketcontrol | Win32OwnProcess |  | Manual | Running |
 | vmicguestinterface |  | False | False | False |  |  | Hyper-V Guest Service Interface | . | SafeServiceHandle | vmicguestinterface |  | Win32ShareProcess |  | Disabled | Stopped |
 | vmicheartbeat |  | False | False | False |  |  | Hyper-V Heartbeat Service | . | SafeServiceHandle | vmicheartbeat |  | Win32ShareProcess |  | Disabled | Stopped |
 | vmickvpexchange |  | False | False | False |  |  | Hyper-V Data Exchange Service | . | SafeServiceHandle | vmickvpexchange |  | Win32ShareProcess |  | Disabled | Stopped |
 | vmicrdv |  | False | False | False |  |  | Hyper-V Remote Desktop Virtualization Service | . | SafeServiceHandle | vmicrdv |  | Win32ShareProcess |  | Disabled | Stopped |
 | vmicshutdown |  | False | False | False |  |  | Hyper-V Guest Shutdown Service | . | SafeServiceHandle | vmicshutdown |  | Win32ShareProcess |  | Disabled | Stopped |
 | vmictimesync | VmGid | False | False | False |  |  | Hyper-V Time Synchronization Service | . | SafeServiceHandle | vmictimesync | VmGid | Win32ShareProcess |  | Disabled | Stopped |
 | vmicvmsession |  | False | False | False |  |  | Hyper-V PowerShell Direct Service | . | SafeServiceHandle | vmicvmsession |  | Win32ShareProcess |  | Manual | Stopped |
 | vmicvss |  | False | False | False |  |  | Hyper-V Volume Shadow Copy Requestor | . | SafeServiceHandle | vmicvss |  | Win32ShareProcess |  | Disabled | Stopped |
 | vmms | RPCSS WINMGMT | False | False | True |  |  | Hyper-V Virtual Machine Management | . | SafeServiceHandle | vmms | RPCSS WINMGMT | Win32OwnProcess |  | Automatic | Running |
 | vpnagent | Tcpip | True | True | True |  |  | Cisco AnyConnect Secure Mobility Agent | . | SafeServiceHandle | vpnagent | Tcpip | Win32OwnProcess |  | Automatic | Running |
 | VSS | RPCSS | False | False | False |  |  | Volume Shadow Copy | . | SafeServiceHandle | VSS | RPCSS | Win32OwnProcess |  | Manual | Stopped |
 | VSStandardCollectorService140 |  | False | False | False |  |  | Visual Studio Standard Collector Service | . | SafeServiceHandle | VSStandardCollectorService140 |  | Win32OwnProcess |  | Manual | Stopped |
 | VSStandardCollectorService150 |  | False | False | False |  |  | Visual Studio Standard Collector Service 150 | . | SafeServiceHandle | VSStandardCollectorService150 |  | Win32OwnProcess |  | Manual | Stopped |
 | W32Time |  | False | True | True |  |  | Windows Time | . | SafeServiceHandle | W32Time |  | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | WalletService |  | False | False | False |  |  | WalletService | . | SafeServiceHandle | WalletService |  | Win32ShareProcess |  | Manual | Stopped |
 | WarpJITSvc |  | False | False | False |  |  | WarpJITSvc | . | SafeServiceHandle | WarpJITSvc |  | Win32OwnProcess |  | Manual | Stopped |
 | wbengine |  | False | False | False |  |  | Block Level Backup Engine Service | . | SafeServiceHandle | wbengine |  | Win32OwnProcess |  | Manual | Stopped |
 | WbioSrvc | RpcSs | False | False | False |  |  | Windows Biometric Service | . | SafeServiceHandle | WbioSrvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | Wcmsvc | RpcSs NSI | False | True | True |  | WlanSvc icssvc | Windows Connection Manager | . | SafeServiceHandle | Wcmsvc | RpcSs NSI | Win32OwnProcess |  | Automatic | Running |
 | wcncsvc | rpcss | False | False | False |  |  | Windows Connect Now - Config Registrar | . | SafeServiceHandle | wcncsvc | rpcss | Win32ShareProcess |  | Manual | Stopped |
 | WdiServiceHost |  | False | True | True |  |  | Diagnostic Service Host | . |  | WdiServiceHost |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | WdiSystemHost |  | False | False | False |  |  | Diagnostic System Host | . |  | WdiSystemHost |  | Win32OwnProcess, Win32ShareProcess |  | Manual | Stopped |
 | WdNisSvc | WdNisDrv | False | False | False |  |  | Windows Defender Antivirus Network Inspection Service | . |  | WdNisSvc | WdNisDrv | Win32OwnProcess |  | Manual | Stopped |
 | WebClient | MRxDAV | False | False | True |  |  | WebClient | . | SafeServiceHandle | WebClient | MRxDAV | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | Wecsvc | Eventlog HTTP | False | False | False |  |  | Windows Event Collector | . | SafeServiceHandle | Wecsvc | Eventlog HTTP | Win32ShareProcess |  | Manual | Stopped |
 | WEPHOSTSVC | rpcss | False | False | False |  |  | Windows Encryption Provider Host Service | . | SafeServiceHandle | WEPHOSTSVC | rpcss | Win32ShareProcess |  | Manual | Stopped |
 | wercplsupport |  | False | False | False |  |  | Problem Reports and Solutions Control Panel Support | . | SafeServiceHandle | wercplsupport |  | Win32ShareProcess |  | Manual | Stopped |
 | WerSvc |  | False | False | False |  |  | Windows Error Reporting Service | . | SafeServiceHandle | WerSvc |  | Win32OwnProcess |  | Disabled | Stopped |
 | WFDSConMgrSvc | RpcSs | False | False | False |  |  | Wi-Fi Direct Services Connection Manager Service | . | SafeServiceHandle | WFDSConMgrSvc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | WiaRpc | RpcSs | False | False | False |  |  | Still Image Acquisition Events | . | SafeServiceHandle | WiaRpc | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | WinDefend | RpcSs | False | False | False |  |  | Windows Defender Antivirus Service | . |  | WinDefend | RpcSs | Win32OwnProcess |  | Manual | Stopped |
 | WinHttpAutoProxySvc | Dhcp | False | False | False |  | NcaSvc iphlpsvc | WinHTTP Web Proxy Auto-Discovery Service | . |  | WinHttpAutoProxySvc | Dhcp | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | Winmgmt | RPCSS | True | True | True |  | wscsvc vmms smstsmgr NcaSvc iphlpsvc HgClientService CcmExec | Windows Management Instrumentation | . | SafeServiceHandle | Winmgmt | RPCSS | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | WinRM | RPCSS HTTP | False | True | True |  |  | Windows Remote Management (WS-Management) | . | SafeServiceHandle | WinRM | RPCSS HTTP | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | wisvc | rpcss | False | False | False |  |  | Windows Insider Service | . | SafeServiceHandle | wisvc | rpcss | Win32OwnProcess, Win32ShareProcess |  | Manual | Stopped |
 | WlanSvc | wcmsvc RpcSs nativewifip Ndisuio | False | True | True |  |  | WLAN AutoConfig | . | SafeServiceHandle | WlanSvc | wcmsvc RpcSs nativewifip Ndisuio | Win32OwnProcess |  | Automatic | Running |
 | wlidsvc | RpcSs | False | False | True |  |  | Microsoft Account Sign-in Assistant | . | SafeServiceHandle | wlidsvc | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Manual | Running |
 | wlpasvc | RpcSs WwanSvc | False | False | False |  |  | Local Profile Assistant Service | . | SafeServiceHandle | wlpasvc | RpcSs WwanSvc | Win32ShareProcess |  | Manual | Stopped |
 | wmiApSrv |  | False | False | False |  |  | WMI Performance Adapter | . | SafeServiceHandle | wmiApSrv |  | Win32OwnProcess |  | Manual | Stopped |
 | WMPNetworkSvc | WSearch http | False | False | False |  |  | Windows Media Player Network Sharing Service | . | SafeServiceHandle | WMPNetworkSvc | WSearch http | Win32OwnProcess |  | Disabled | Stopped |
 | workfolderssvc | RpcSs wsearch | False | False | False |  |  | Work Folders | . | SafeServiceHandle | workfolderssvc | RpcSs wsearch | Win32ShareProcess |  | Manual | Stopped |
 | WPDBusEnum | RpcSs | False | False | False |  |  | Portable Device Enumerator Service | . | SafeServiceHandle | WPDBusEnum | RpcSs | Win32OwnProcess, Win32ShareProcess |  | Manual | Stopped |
 | WpnService | rpcss | False | False | True |  |  | Windows Push Notifications System Service | . | SafeServiceHandle | WpnService | rpcss | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | WpnUserService_16f456 |  | False | False | True |  |  | Windows Push Notifications User Service_16f456 | . |  | WpnUserService_16f456 |  | 240 |  | Automatic | Running |
 | wscsvc | RpcSs WinMgmt | False | False | False |  |  | Security Center | . | SafeServiceHandle | wscsvc | RpcSs WinMgmt | Win32ShareProcess |  | Disabled | Stopped |
 | WSearch | RPCSS | False | True | True |  | workfolderssvc WMPNetworkSvc | Windows Search | . | SafeServiceHandle | WSearch | RPCSS | Win32OwnProcess |  | Automatic | Running |
 | wuauserv | rpcss | False | False | False |  |  | Windows Update | . | SafeServiceHandle | wuauserv | rpcss | Win32ShareProcess |  | Manual | Stopped |
 | WwanSvc | RpcSs NdisUio | False | False | True |  | wlpasvc | WWAN AutoConfig | . | SafeServiceHandle | WwanSvc | RpcSs NdisUio | Win32OwnProcess, Win32ShareProcess |  | Automatic | Running |
 | xbgm | XblAuthManager UserManager | False | False | False |  |  | Xbox Game Monitoring | . | SafeServiceHandle | xbgm | XblAuthManager UserManager | Win32OwnProcess |  | Manual | Stopped |
 | XblAuthManager | RpcSs | False | False | False |  | XblGameSave xbgm | Xbox Live Auth Manager | . | SafeServiceHandle | XblAuthManager | RpcSs | Win32ShareProcess |  | Manual | Stopped |
 | XblGameSave | XblAuthManager UserManager | False | False | False |  |  | Xbox Live Game Save | . | SafeServiceHandle | XblGameSave | XblAuthManager UserManager | Win32ShareProcess |  | Manual | Stopped |
 | XboxGipSvc |  | False | False | False |  |  | Xbox Accessory Management Service | . | SafeServiceHandle | XboxGipSvc |  | Win32ShareProcess |  | Manual | Stopped |
 | XboxNetApiSvc | KeyIso IKEEXT mpssvc BFE | False | False | False |  |  | Xbox Live Networking Service | . | SafeServiceHandle | XboxNetApiSvc | KeyIso IKEEXT mpssvc BFE | Win32ShareProcess |  | Manual | Stopped |
 | ZeroConfigService | RPCSS | False | False | True |  |  | Intel(R) PROSet/Wireless Zero Configuration Service | . | SafeServiceHandle | ZeroConfigService | RPCSS | Win32OwnProcess |  | Automatic | Running |

