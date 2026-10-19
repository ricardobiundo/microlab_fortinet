# WirelessControllerSettingGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **str** | FortiCloud customer account ID. | [optional] 
**country** | **str** | Country or region in which the FortiGate is located. The country determines the 802.11 bands and channels that are available.    --:NO_COUNTRY_SET    AF:AFGHANISTAN    AL:ALBANIA    DZ:ALGERIA    AS:AMERICAN SAMOA    AO:ANGOLA    AR:ARGENTINA    AM:ARMENIA    AU:AUSTRALIA    AT:AUSTRIA    AZ:AZERBAIJAN    BS:BAHAMAS    BH:BAHRAIN    BD:BANGLADESH    BB:BARBADOS    BY:BELARUS    BE:BELGIUM    BZ:BELIZE    BJ:BENIN    BM:BERMUDA    BT:BHUTAN    BO:BOLIVIA    BA:BOSNIA AND HERZEGOVINA    BW:BOTSWANA    BR:BRAZIL    BN:BRUNEI DARUSSALAM    BG:BULGARIA    BF:BURKINA-FASO    KH:CAMBODIA    CM:CAMEROON    KY:CAYMAN ISLANDS    CF:CENTRAL AFRICA REPUBLIC    TD:CHAD      CL:CHILE    CN:CHINA    CX:CHRISTMAS ISLAND    CO:COLOMBIA    CG:CONGO REPUBLIC    CD:DEMOCRATIC REPUBLIC OF CONGO    CR:COSTA RICA    HR:CROATIA    CY:CYPRUS    CZ:CZECH REPUBLIC    DK:DENMARK    DJ:DJIBOUTI    DM:DOMINICA    DO:DOMINICAN REPUBLIC    EC:ECUADOR    EG:EGYPT    SV:EL SALVADOR    ET:ETHIOPIA    EE:ESTONIA    GF:FRENCH GUIANA    PF:FRENCH POLYNESIA    FO:FAEROE ISLANDS    FJ:FIJI    FI:FINLAND    FR:FRANCE    GA:GABON    GE:GEORGIA    GM:GAMBIA    DE:GERMANY    GH:GHANA    GI:GIBRALTAR    GR:GREECE    GL:GREENLAND    GD:GRENADA    GP:GUADELOUPE    GU:GUAM    GT:GUATEMALA    GY:GUYANA    HT:HAITI    HN:HONDURAS    HK:HONG KONG    HU:HUNGARY    IS:ICELAND    IN:INDIA    ID:INDONESIA    IQ:IRAQ    IE:IRELAND    IM:ISLE OF MAN    IL:ISRAEL    IT:ITALY    CI:COTE_D_IVOIRE    JM:JAMAICA    JO:JORDAN    KZ:KAZAKHSTAN    KE:KENYA    KR:KOREA REPUBLIC    KW:KUWAIT    LA:LAOS    LV:LATVIA    LB:LEBANON    LS:LESOTHO    LR:LIBERIA    LY:LIBYA    LI:LIECHTENSTEIN    LT:LITHUANIA    LU:LUXEMBOURG    MO:MACAU SAR    MK:MACEDONIA, FYRO    MG:MADAGASCAR    MW:MALAWI    MY:MALAYSIA    MV:MALDIVES    ML:MALI    MT:MALTA    MH:MARSHALL ISLANDS    MQ:MARTINIQUE    MR:MAURITANIA    MU:MAURITIUS    YT:MAYOTTE    MX:MEXICO    FM:MICRONESIA    MD:REPUBLIC OF MOLDOVA    MC:MONACO    MN:MONGOLIA    MA:MOROCCO    MZ:MOZAMBIQUE    MM:MYANMAR    NA:NAMIBIA    NP:NEPAL    NL:NETHERLANDS    AN:NETHERLANDS ANTILLES    AW:ARUBA    NZ:NEW ZEALAND    NI:NICARAGUA    NE:NIGER    NG:NIGERIA    NO:NORWAY    MP:NORTHERN MARIANA ISLANDS    OM:OMAN    PK:PAKISTAN    PW:PALAU    PA:PANAMA    PG:PAPUA NEW GUINEA    PY:PARAGUAY    PE:PERU    PH:PHILIPPINES    PL:POLAND    PT:PORTUGAL    PR:PUERTO RICO    QA:QATAR    RE:REUNION    RO:ROMANIA    RU:RUSSIA    RW:RWANDA    BL:SAINT BARTHELEMY    KN:SAINT KITTS AND NEVIS    LC:SAINT LUCIA    MF:SAINT MARTIN    PM:SAINT PIERRE AND MIQUELON    VC:SAINT VINCENT AND GRENADIENS    SA:SAUDI ARABIA    SN:SENEGAL    RS:REPUBLIC OF SERBIA    ME:MONTENEGRO    SL:SIERRA LEONE    SG:SINGAPORE    SK:SLOVAKIA    SI:SLOVENIA    SO:SOMALIA    ZA:SOUTH AFRICA    ES:SPAIN    LK:SRI LANKA    SR:SURINAME    SZ:SWAZILAND    SE:SWEDEN    CH:SWITZERLAND    TW:TAIWAN    TZ:TANZANIA    TH:THAILAND    TL:TIMOR-LESTE    TG:TOGO    TT:TRINIDAD AND TOBAGO    TN:TUNISIA    TR:TURKEY    TM:TURKMENISTAN    AE:UNITED ARAB EMIRATES    TC:TURKS AND CAICOS    UG:UGANDA    UA:UKRAINE    GB:UNITED KINGDOM    US:UNITED STATES    PS:UNITED STATES (PUBLIC SAFETY)    UY:URUGUAY    UZ:UZBEKISTAN    VU:VANUATU    VE:VENEZUELA    VN:VIET NAM    VI:VIRGIN ISLANDS    WF:WALLIS AND FUTUNA    YE:YEMEN    ZM:ZAMBIA    ZW:ZIMBABWE    JP:JAPAN    CA:CANADA | [optional] 
**duplicate_ssid** | **str** | Enable/disable allowing Virtual Access Points (VAPs) to use the same SSID name in the same VDOM.    enable:Allow VAPs to use the same SSID name in the same VDOM.    disable:Do not allow VAPs to use the same SSID name in the same VDOM. | [optional] 
**fapc_compatibility** | **str** | Enable/disable FAP-C series compatibility.    enable:Enable FAP-C series compatibility.    disable:Disable FAP-C series compatibility. | [optional] 
**wfa_compatibility** | **str** | Enable/disable WFA compatibility.    enable:Enable Wi-Fi Alliance Certification compatibility.    disable:Disable Wi-Fi Alliance Certification compatibility. | [optional] 
**phishing_ssid_detect** | **str** | Enable/disable phishing SSID detection.    enable:Enable phishing SSID detection.    disable:Disable phishing SSID detection. | [optional] 
**fake_ssid_action** | **str** | Actions taken for detected fake SSID.    log:Write logs for detected fake SSID.    suppress:Suppress detected fake SSID. | [optional] 
**offending_ssid** | [**List[WirelessControllerSettingGet200ResponseOffendingSsidInner]**](WirelessControllerSettingGet200ResponseOffendingSsidInner.md) | Configure offending SSID. | [optional] 
**device_weight** | **int** | Upper limit of confidence of device for identification (0 - 255, default &#x3D; 1, 0 &#x3D; disable). | [optional] 
**device_holdoff** | **int** | Lower limit of creation time of device for identification in minutes (0 - 60, default &#x3D; 5). | [optional] 
**device_idle** | **int** | Upper limit of idle time of device for identification in minutes (0 - 14400, default &#x3D; 1440). | [optional] 
**firmware_provision_on_authorization** | **str** | Enable/disable automatic provisioning of latest firmware on authorization.    enable:Enable firmware provision on authorization.    disable:Disable firmware provision on authorization. | [optional] 
**rolling_wtp_upgrade** | **str** | Enable/disable rolling WTP upgrade (default &#x3D; disable).    enable:Enable rolling WTP upgrade.    disable:Disable rolling WTP upgrade. | [optional] 
**darrp_optimize** | **int** | Time for running Distributed Automatic Radio Resource Provisioning (DARRP) optimizations (0 - 86400 sec, default &#x3D; 86400, 0 &#x3D; disable). | [optional] 
**darrp_optimize_schedules** | [**List[WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner]**](WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner.md) | Firewall schedules for DARRP running time. DARRP will run periodically based on darrp-optimize within the schedules. Separate multiple schedule names with a space. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_setting_get200_response import WirelessControllerSettingGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerSettingGet200Response from a JSON string
wireless_controller_setting_get200_response_instance = WirelessControllerSettingGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerSettingGet200Response.to_json())

# convert the object into a dict
wireless_controller_setting_get200_response_dict = wireless_controller_setting_get200_response_instance.to_dict()
# create an instance of WirelessControllerSettingGet200Response from a dict
wireless_controller_setting_get200_response_from_dict = WirelessControllerSettingGet200Response.from_dict(wireless_controller_setting_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


