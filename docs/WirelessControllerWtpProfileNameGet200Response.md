# WirelessControllerWtpProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | WTP (or FortiAP or AP) profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**platform** | [**List[WirelessControllerWtpProfileNameGet200ResponsePlatformInner]**](WirelessControllerWtpProfileNameGet200ResponsePlatformInner.md) | WTP, FortiAP, or AP platform. | [optional] 
**control_message_offload** | **str** | Enable/disable CAPWAP control message data channel offload.    ebp-frame:Ekahau blink protocol (EBP) frames.    aeroscout-tag:AeroScout tag.    ap-list:Rogue AP list.    sta-list:Rogue STA list.    sta-cap-list:STA capability list.    stats:WTP, radio, VAP, and STA statistics.    aeroscout-mu:AeroScout Mobile Unit (MU) report.    sta-health:STA health log.    spectral-analysis:Spectral analysis report. | [optional] 
**bonjour_profile** | **str** | Bonjour profile name. | [optional] 
**apcfg_profile** | **str** | AP local configuration profile name. | [optional] 
**apcfg_mesh** | **str** | Enable/disable AP local mesh configuration (default &#x3D; disable).    enable:Enable AP local mesh configuration.    disable:Disable AP local mesh configuration. | [optional] 
**apcfg_mesh_ap_type** | **str** | Mesh AP Type (default &#x3D; ethernet).    ethernet:Use ethernet uplink.    mesh:Use mesh uplink.    auto:Ethernet with mesh backup support. | [optional] 
**apcfg_mesh_ssid** | **str** |  Mesh SSID (default &#x3D; none). | [optional] 
**apcfg_mesh_eth_bridge** | **str** | Enable/disable mesh ethernet bridge (default &#x3D; disable).    enable:Enable AP local mesh eth bridge configuration.    disable:Disable AP local mesh eth bridge configuration. | [optional] 
**ble_profile** | **str** | Bluetooth Low Energy profile name. | [optional] 
**lw_profile** | **str** | LoRaWAN profile name. | [optional] 
**syslog_profile** | **str** | System log server configuration profile name. | [optional] 
**wan_port_mode** | **str** | Enable/disable using a WAN port as a LAN port.    wan-lan:Enable using a WAN port as a LAN port.    wan-only:Disable using a WAN port as a LAN port. | [optional] 
**lan** | [**List[WirelessControllerWtpWtpIdGet200ResponseLanInner]**](WirelessControllerWtpWtpIdGet200ResponseLanInner.md) | WTP LAN port mapping. | [optional] 
**energy_efficient_ethernet** | **str** | Enable/disable use of energy efficient Ethernet on WTP.    enable:Enable use of energy efficient Ethernet on WTP.    disable:Disable use of energy efficient Ethernet on WTP. | [optional] 
**led_state** | **str** | Enable/disable use of LEDs on WTP (default &#x3D; enable).    enable:Enable use of LEDs on WTP.    disable:Disable use of LEDs on WTP. | [optional] 
**led_schedules** | [**List[WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner]**](WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner.md) | Recurring firewall schedules for illuminating LEDs on the FortiAP. If led-state is enabled, LEDs will be visible when at least one of the schedules is valid. Separate multiple schedule names with a space. | [optional] 
**dtls_policy** | **str** | WTP data channel DTLS policy (default &#x3D; clear-text).    clear-text:Clear Text Data Channel.    dtls-enabled:DTLS Enabled Data Channel.    ipsec-vpn:IPsec VPN Data Channel.    ipsec-sn-vpn:IPsec VPN Data Channel with FortiAP&#39;s SN in the first IKE messages. | [optional] 
**dtls_in_kernel** | **str** | Enable/disable data channel DTLS in kernel.    enable:Enable data channel DTLS in kernel.    disable:Disable data channel DTLS in kernel. | [optional] 
**max_clients** | **int** | Maximum number of stations (STAs) supported by the WTP (default &#x3D; 0, meaning no client limitation). | [optional] 
**handoff_rssi** | **int** | Minimum received signal strength indicator (RSSI) value for handoff (20 - 30, default &#x3D; 25). | [optional] 
**handoff_sta_thresh** | **int** | Threshold value for AP handoff. | [optional] 
**handoff_roaming** | **str** | Enable/disable client load balancing during roaming to avoid roaming delay (default &#x3D; enable).    enable:Enable handoff roaming.    disable:Disable handoff roaming. | [optional] 
**deny_mac_list** | [**List[WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner]**](WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner.md) | List of MAC addresses that are denied access to this WTP, FortiAP, or AP. | [optional] 
**ap_country** | **str** | Country in which this WTP, FortiAP, or AP will operate (default &#x3D; NA, automatically use the country configured for the current VDOM).    --:NO_COUNTRY_SET    AF:AFGHANISTAN    AL:ALBANIA    DZ:ALGERIA    AS:AMERICAN SAMOA    AO:ANGOLA    AR:ARGENTINA    AM:ARMENIA    AU:AUSTRALIA    AT:AUSTRIA    AZ:AZERBAIJAN    BS:BAHAMAS    BH:BAHRAIN    BD:BANGLADESH    BB:BARBADOS    BY:BELARUS    BE:BELGIUM    BZ:BELIZE    BJ:BENIN    BM:BERMUDA    BT:BHUTAN    BO:BOLIVIA    BA:BOSNIA AND HERZEGOVINA    BW:BOTSWANA    BR:BRAZIL    BN:BRUNEI DARUSSALAM    BG:BULGARIA    BF:BURKINA-FASO    KH:CAMBODIA    CM:CAMEROON    KY:CAYMAN ISLANDS    CF:CENTRAL AFRICA REPUBLIC    TD:CHAD      CL:CHILE    CN:CHINA    CX:CHRISTMAS ISLAND    CO:COLOMBIA    CG:CONGO REPUBLIC    CD:DEMOCRATIC REPUBLIC OF CONGO    CR:COSTA RICA    HR:CROATIA    CY:CYPRUS    CZ:CZECH REPUBLIC    DK:DENMARK    DJ:DJIBOUTI    DM:DOMINICA    DO:DOMINICAN REPUBLIC    EC:ECUADOR    EG:EGYPT    SV:EL SALVADOR    ET:ETHIOPIA    EE:ESTONIA    GF:FRENCH GUIANA    PF:FRENCH POLYNESIA    FO:FAEROE ISLANDS    FJ:FIJI    FI:FINLAND    FR:FRANCE    GA:GABON    GE:GEORGIA    GM:GAMBIA    DE:GERMANY    GH:GHANA    GI:GIBRALTAR    GR:GREECE    GL:GREENLAND    GD:GRENADA    GP:GUADELOUPE    GU:GUAM    GT:GUATEMALA    GY:GUYANA    HT:HAITI    HN:HONDURAS    HK:HONG KONG    HU:HUNGARY    IS:ICELAND    IN:INDIA    ID:INDONESIA    IQ:IRAQ    IE:IRELAND    IM:ISLE OF MAN    IL:ISRAEL    IT:ITALY    CI:COTE_D_IVOIRE    JM:JAMAICA    JO:JORDAN    KZ:KAZAKHSTAN    KE:KENYA    KR:KOREA REPUBLIC    KW:KUWAIT    LA:LAOS    LV:LATVIA    LB:LEBANON    LS:LESOTHO    LR:LIBERIA    LY:LIBYA    LI:LIECHTENSTEIN    LT:LITHUANIA    LU:LUXEMBOURG    MO:MACAU SAR    MK:MACEDONIA, FYRO    MG:MADAGASCAR    MW:MALAWI    MY:MALAYSIA    MV:MALDIVES    ML:MALI    MT:MALTA    MH:MARSHALL ISLANDS    MQ:MARTINIQUE    MR:MAURITANIA    MU:MAURITIUS    YT:MAYOTTE    MX:MEXICO    FM:MICRONESIA    MD:REPUBLIC OF MOLDOVA    MC:MONACO    MN:MONGOLIA    MA:MOROCCO    MZ:MOZAMBIQUE    MM:MYANMAR    NA:NAMIBIA    NP:NEPAL    NL:NETHERLANDS    AN:NETHERLANDS ANTILLES    AW:ARUBA    NZ:NEW ZEALAND    NI:NICARAGUA    NE:NIGER    NG:NIGERIA    NO:NORWAY    MP:NORTHERN MARIANA ISLANDS    OM:OMAN    PK:PAKISTAN    PW:PALAU    PA:PANAMA    PG:PAPUA NEW GUINEA    PY:PARAGUAY    PE:PERU    PH:PHILIPPINES    PL:POLAND    PT:PORTUGAL    PR:PUERTO RICO    QA:QATAR    RE:REUNION    RO:ROMANIA    RU:RUSSIA    RW:RWANDA    BL:SAINT BARTHELEMY    KN:SAINT KITTS AND NEVIS    LC:SAINT LUCIA    MF:SAINT MARTIN    PM:SAINT PIERRE AND MIQUELON    VC:SAINT VINCENT AND GRENADIENS    SA:SAUDI ARABIA    SN:SENEGAL    RS:REPUBLIC OF SERBIA    ME:MONTENEGRO    SL:SIERRA LEONE    SG:SINGAPORE    SK:SLOVAKIA    SI:SLOVENIA    SO:SOMALIA    ZA:SOUTH AFRICA    ES:SPAIN    LK:SRI LANKA    SR:SURINAME    SZ:SWAZILAND    SE:SWEDEN    CH:SWITZERLAND    TW:TAIWAN    TZ:TANZANIA    TH:THAILAND    TL:TIMOR-LESTE    TG:TOGO    TT:TRINIDAD AND TOBAGO    TN:TUNISIA    TR:TURKEY    TM:TURKMENISTAN    AE:UNITED ARAB EMIRATES    TC:TURKS AND CAICOS    UG:UGANDA    UA:UKRAINE    GB:UNITED KINGDOM    US:UNITED STATES    PS:UNITED STATES (PUBLIC SAFETY)    UY:URUGUAY    UZ:UZBEKISTAN    VU:VANUATU    VE:VENEZUELA    VN:VIET NAM    VI:VIRGIN ISLANDS    WF:WALLIS AND FUTUNA    YE:YEMEN    ZM:ZAMBIA    ZW:ZIMBABWE    JP:JAPAN    CA:CANADA | [optional] 
**ip_fragment_preventing** | **str** | Method(s) by which IP fragmentation is prevented for control and data packets through CAPWAP tunnel (default &#x3D; tcp-mss-adjust).    tcp-mss-adjust:TCP maximum segment size adjustment.    icmp-unreachable:Drop packet and send ICMP Destination Unreachable | [optional] 
**tun_mtu_uplink** | **int** | The maximum transmission unit (MTU) of uplink CAPWAP tunnel (576 - 1500 bytes or 0; 0 means the local MTU of FortiAP; default &#x3D; 0). | [optional] 
**tun_mtu_downlink** | **int** | The MTU of downlink CAPWAP tunnel (576 - 1500 bytes or 0; 0 means the local MTU of FortiAP; default &#x3D; 0). | [optional] 
**split_tunneling_acl_path** | **str** | Split tunneling ACL path is local/tunnel.    tunnel:Split tunneling ACL list traffic will be tunnel.    local:Split tunneling ACL list traffic will be local NATed. | [optional] 
**split_tunneling_acl_local_ap_subnet** | **str** | Enable/disable automatically adding local subnetwork of FortiAP to split-tunneling ACL (default &#x3D; disable).    enable:Enable automatically adding local subnetwork of FortiAP to split-tunneling ACL.    disable:Disable automatically adding local subnetwork of FortiAP to split-tunneling ACL. | [optional] 
**split_tunneling_acl** | [**List[WirelessControllerWtpWtpIdGet200ResponseSplitTunnelingAclInner]**](WirelessControllerWtpWtpIdGet200ResponseSplitTunnelingAclInner.md) | Split tunneling ACL filter list. | [optional] 
**allowaccess** | **str** | Control management access to the managed WTP, FortiAP, or AP. Separate entries with a space.    https:HTTPS access.    ssh:SSH access.    snmp:SNMP access. | [optional] 
**login_passwd_change** | **str** | Change or reset the administrator password of a managed WTP, FortiAP or AP (yes, default, or no, default &#x3D; no).    yes:Change the managed WTP, FortiAP or AP&#39;s administrator password. Use the login-password option to set the password.    default:Keep the managed WTP, FortiAP or AP&#39;s administrator password set to the factory default.    no:Do not change the managed WTP, FortiAP or AP&#39;s administrator password. | [optional] 
**login_passwd** | **str** | Set the managed WTP, FortiAP, or AP&#39;s administrator password. | [optional] 
**lldp** | **str** | Enable/disable Link Layer Discovery Protocol (LLDP) for the WTP, FortiAP, or AP (default &#x3D; enable).    enable:Enable LLDP.    disable:Disable LLDP. | [optional] 
**poe_mode** | **str** | Set the WTP, FortiAP, or AP&#39;s PoE mode.    auto:Automatically detect the PoE mode.    8023af:Use 802.3af PoE mode.    8023at:Use 802.3at PoE mode.    power-adapter:Use the power adapter to control the PoE mode.    full:Use full power mode.    high:Use high power mode.    low:Use low power mode. | [optional] 
**usb_port** | **str** | Enable/disable USB port of the WTP (default &#x3D; enable).    enable:Enable USB port.    disable:Disable USB port. | [optional] 
**frequency_handoff** | **str** | Enable/disable frequency handoff of clients to other channels (default &#x3D; disable).    enable:Enable frequency handoff.    disable:Disable frequency handoff. | [optional] 
**ap_handoff** | **str** | Enable/disable AP handoff of clients to other APs (default &#x3D; disable).    enable:Enable AP handoff.    disable:Disable AP handoff. | [optional] 
**default_mesh_root** | **str** | Configure default mesh root SSID when it is not included by radio&#39;s SSID configuration.    enable:Enable default mesh root SSID if it is not included by radio&#39;s SSID configuration.    disable:Do not enable default mesh root SSID if it is not included by radio&#39;s SSID configuration. | [optional] 
**radio_1** | [**List[WirelessControllerWtpProfileNameGet200ResponseRadio1Inner]**](WirelessControllerWtpProfileNameGet200ResponseRadio1Inner.md) | Configuration options for radio 1. | [optional] 
**radio_2** | [**List[WirelessControllerWtpProfileNameGet200ResponseRadio2Inner]**](WirelessControllerWtpProfileNameGet200ResponseRadio2Inner.md) | Configuration options for radio 2. | [optional] 
**radio_3** | [**List[WirelessControllerWtpProfileNameGet200ResponseRadio3Inner]**](WirelessControllerWtpProfileNameGet200ResponseRadio3Inner.md) | Configuration options for radio 3. | [optional] 
**radio_4** | [**List[WirelessControllerWtpProfileNameGet200ResponseRadio4Inner]**](WirelessControllerWtpProfileNameGet200ResponseRadio4Inner.md) | Configuration options for radio 4. | [optional] 
**lbs** | [**List[WirelessControllerWtpProfileNameGet200ResponseLbsInner]**](WirelessControllerWtpProfileNameGet200ResponseLbsInner.md) | Set various location based service (LBS) options. | [optional] 
**ext_info_enable** | **str** | Enable/disable station/VAP/radio extension information.    enable:Enable station/VAP/radio extension information.    disable:Disable station/VAP/radio extension information. | [optional] 
**indoor_outdoor_deployment** | **str** | Set to allow indoor/outdoor-only channels under regulatory rules (default &#x3D; platform-determined).    platform-determined:Set AP deployment type based on its platform.    outdoor:Set AP deployment type to outdoor.    indoor:Set AP deployment type to indoor. | [optional] 
**esl_ses_dongle** | [**List[WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner]**](WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner.md) | ESL SES-imagotag dongle configuration. | [optional] 
**console_login** | **str** | Enable/disable FortiAP console login access (default &#x3D; enable).    enable:Enable FAP console login access.    disable:Disable FAP console login access. | [optional] 
**wan_port_auth** | **str** | Set WAN port authentication mode (default &#x3D; none).    none:Disable WAN port authentication.    802.1x:Enable WAN port 802.1x authentication. | [optional] 
**wan_port_auth_usrname** | **str** | Set WAN port 802.1x supplicant user name. | [optional] 
**wan_port_auth_password** | **str** | Set WAN port 802.1x supplicant password. | [optional] 
**wan_port_auth_methods** | **str** | WAN port 802.1x supplicant EAP methods (default &#x3D; all).    all:Do not specify any EAP methods.    EAP-FAST:Enable EAP-FAST.    EAP-TLS:Enable EAP-TLS.    EAP-PEAP:Enable EAP-PEAP. | [optional] 
**wan_port_auth_macsec** | **str** | Enable/disable WAN port 802.1x supplicant MACsec policy (default &#x3D; disable).    enable:Enable WAN port 802.1x supplicant MACsec policy.    disable:Disable WAN port 802.1x supplicant MACsec policy. | [optional] 
**apcfg_auto_cert** | **str** | Enable/disable AP local auto cert configuration (default &#x3D; disable).    enable:Enable AP local auto cert configuration.    disable:Disable AP local auto cert configuration. | [optional] 
**apcfg_auto_cert_enroll_protocol** | **str** | Certificate enrollment protocol (default &#x3D; none)    none:None (default).    est:Enrollment over Secure Transport.    scep:Simple Certificate Enrollment Protocol. | [optional] 
**apcfg_auto_cert_crypto_algo** | **str** | Cryptography algorithm: rsa-1024, rsa-1536, rsa-2048, rsa-4096, ec-secp256r1, ec-secp384r1, ec-secp521r1 (default &#x3D; ec-secp256r1)    rsa-1024:Cryptography algorithm rsa-1024.    rsa-1536:Cryptography algorithm rsa-1536.    rsa-2048:Cryptography algorithm rsa-2048.    rsa-4096:Cryptography algorithm rsa-4096.    ec-secp256r1:Cryptography algorithm ec-secp256r1.    ec-secp384r1:Cryptography algorithm ec-secp384r1.    ec-secp521r1:Cryptography algorithm ec-secp521r1. | [optional] 
**apcfg_auto_cert_est_server** | **str** | Address and port for EST server (e.g. https://example.com:1234). | [optional] 
**apcfg_auto_cert_est_ca_id** | **str** | CA identifier of the CA server for signing via EST. | [optional] 
**apcfg_auto_cert_est_http_username** | **str** | HTTP Authentication username for signing via EST. | [optional] 
**apcfg_auto_cert_est_http_password** | **str** | HTTP Authentication password for signing via EST. | [optional] 
**apcfg_auto_cert_est_subject** | **str** | Subject e.g. \&quot;CN&#x3D;User,DC&#x3D;example,DC&#x3D;COM\&quot; (default &#x3D; CN&#x3D;FortiAP,DC&#x3D;local,DC&#x3D;COM) | [optional] 
**apcfg_auto_cert_est_subject_alt_name** | **str** | Subject alternative name (optional, e.g. \&quot;DNS:dns1.com,IP:192.168.1.99\&quot;) | [optional] 
**apcfg_auto_cert_auto_regen_days** | **int** | Number of days to wait before expiry of an updated local certificate is requested (0 &#x3D; disabled) (default &#x3D; 30). | [optional] 
**apcfg_auto_cert_est_https_ca** | **str** | PEM format https CA Certificate. | [optional] 
**apcfg_auto_cert_scep_keytype** | **str** | Key type (default &#x3D; rsa)    rsa:Generate a RSA certificate request.    ec:Generate an elliptic curve certificate request. | [optional] 
**apcfg_auto_cert_scep_keysize** | **str** | Key size: 1024, 1536, 2048, 4096 (default 2048).    1024:keysize 1024.    1536:keysize 1536.    2048:keysize 2048.    4096:keysize 4096. | [optional] 
**apcfg_auto_cert_scep_ec_name** | **str** | Elliptic curve name: secp256r1, secp384r1 and secp521r1. (default secp256r1).    secp256r1:Elliptic curve name secp256r1.    secp384r1:Elliptic curve name secp384r1.    secp521r1:Elliptic curve name secp521r1. | [optional] 
**apcfg_auto_cert_scep_sub_fully_dn** | **str** | Full DN of the subject (e.g C&#x3D;US,ST&#x3D;CA,L&#x3D;Sunnyvale,O&#x3D;Fortinet,OU&#x3D;Dep1,emailAddress&#x3D;test@example.com). There should be no space in between the attributes. Supported DN attributes (case-sensitive) are:C,ST,L,O,OU,emailAddress. The CN defaults to the device’s SN and cannot be changed. | [optional] 
**apcfg_auto_cert_scep_url** | **str** | SCEP server URL. | [optional] 
**apcfg_auto_cert_scep_password** | **str** | SCEP server challenge password for auto-regeneration. | [optional] 
**apcfg_auto_cert_scep_ca_id** | **str** | CA identifier of the CA server for signing via SCEP. | [optional] 
**apcfg_auto_cert_scep_subject_alt_name** | **str** | Subject alternative name (optional, e.g. \&quot;DNS:dns1.com,IP:192.168.1.99\&quot;) | [optional] 
**apcfg_auto_cert_scep_https_ca** | **str** | PEM format https CA Certificate. | [optional] 
**unii_4_5ghz_band** | **str** | Enable/disable UNII-4 5Ghz band channels (default &#x3D; disable).    enable:Enable UNII-4 5Ghz band channels.    disable:Disable UNII-4 5Ghz band channels. | [optional] 
**admin_auth_tacacs** | **str** | Remote authentication server for admin user. | [optional] 
**admin_restrict_local** | **str** | Enable/disable local admin authentication restriction when remote authenticator is up and running (default &#x3D; disable).    enable:Enable local admin authentication restriction.    disable:Diable local admin authentication restriction. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_profile_name_get200_response import WirelessControllerWtpProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpProfileNameGet200Response from a JSON string
wireless_controller_wtp_profile_name_get200_response_instance = WirelessControllerWtpProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_wtp_profile_name_get200_response_dict = wireless_controller_wtp_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerWtpProfileNameGet200Response from a dict
wireless_controller_wtp_profile_name_get200_response_from_dict = WirelessControllerWtpProfileNameGet200Response.from_dict(wireless_controller_wtp_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


