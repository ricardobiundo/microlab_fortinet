# WirelessControllerHotspot20HsProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Hotspot profile name. | [optional] 
**release** | **int** | Hotspot 2.0 Release number (1, 2, 3, default &#x3D; 2). | [optional] 
**access_network_type** | **str** | Access network type.    private-network:Private network.    private-network-with-guest-access:Private network with guest access.    chargeable-public-network:Chargeable public network.    free-public-network:Free public network.    personal-device-network:Personal devices network.    emergency-services-only-network:Emergency services only network.    test-or-experimental:Test or experimental.    wildcard:Wildcard. | [optional] 
**access_network_internet** | **str** | Enable/disable connectivity to the Internet.    enable:Enable connectivity to the Internet.    disable:Disable connectivity to the Internet. | [optional] 
**access_network_asra** | **str** | Enable/disable additional step required for access (ASRA).    enable:Enable additional step required for access (ASRA).    disable:Disable additional step required for access (ASRA). | [optional] 
**access_network_esr** | **str** | Enable/disable emergency services reachable (ESR).    enable:Enable emergency services reachable (ESR).    disable:Disable emergency services reachable (ESR). | [optional] 
**access_network_uesa** | **str** | Enable/disable unauthenticated emergency service accessible (UESA).    enable:Enable unauthenticated emergency service accessible (UESA).    disable:Disable unauthenticated emergency service accessible (UESA). | [optional] 
**venue_group** | **str** | Venue group.    unspecified:Unspecified.    assembly:Assembly.    business:Business.    educational:Educational.    factory:Factory and industrial.    institutional:Institutional.    mercantile:Mercantile.    residential:Residential.    storage:Storage.    utility:Utility and miscellaneous.    vehicular:Vehicular.    outdoor:Outdoor. | [optional] 
**venue_type** | **str** | Venue type.    unspecified:Unspecified.    arena:Arena.    stadium:Stadium.    passenger-terminal:Passenger terminal.    amphitheater:Amphitheater.    amusement-park:Amusement park.    place-of-worship:Place of worship.    convention-center:Convention center.    library:Library.    museum:Museum.    restaurant:Restaurant.    theater:Theater.    bar:Bar.    coffee-shop:Coffee shop.    zoo-or-aquarium:Zoo or aquarium.    emergency-center:Emergency coordination center.    doctor-office:Doctor or dentist office.    bank:Bank.    fire-station:Fire station.    police-station:Police station.    post-office:Post office.    professional-office:Professional office.    research-facility:Research and development facility.    attorney-office:Attorney office.    primary-school:Primary school.    secondary-school:Secondary school.    university-or-college:University or college.    factory:Factory.    hospital:Hospital.    long-term-care-facility:Long term care facility.    rehab-center:Alcohol and drug rehabilitation center.    group-home:Group home.    prison-or-jail:Prison or jail.    retail-store:Retail store.    grocery-market:Grocery market.    auto-service-station:Auto service station.    shopping-mall:Shopping mall.    gas-station:Gas station.    private:Private residence.    hotel-or-motel:Hotel or motel.    dormitory:Dormitory.    boarding-house:Boarding house.    automobile:Automobile or truck.    airplane:Airplane.    bus:Bus.    ferry:Ferry.    ship-or-boat:Ship or boat.    train:Train.    motor-bike:Motor bike.    muni-mesh-network:Muni mesh network.    city-park:City park.    rest-area:Rest area.    traffic-control:Traffic control.    bus-stop:Bus stop.    kiosk:Kiosk. | [optional] 
**hessid** | **str** | Homogeneous extended service set identifier (HESSID). | [optional] 
**proxy_arp** | **str** | Enable/disable Proxy ARP.    enable:Enable Proxy ARP.    disable:Disable Proxy ARP. | [optional] 
**l2tif** | **str** | Enable/disable Layer 2 traffic inspection and filtering.    enable:Enable Layer 2 traffic inspection and filtering.    disable:Disable Layer 2 traffic inspection and filtering. | [optional] 
**pame_bi** | **str** | Enable/disable Pre-Association Message Exchange BSSID Independent (PAME-BI).    disable:Disable Pre-Association Message Exchange BSSID Independent (PAME-BI).    enable:Enable Pre-Association Message Exchange BSSID Independent (PAME-BI). | [optional] 
**anqp_domain_id** | **int** | ANQP Domain ID (0-65535). | [optional] 
**domain_name** | **str** | Domain name. | [optional] 
**osu_ssid** | **str** | Online sign up (OSU) SSID. | [optional] 
**gas_comeback_delay** | **int** | GAS comeback delay (0 or 100 - 10000 milliseconds, default &#x3D; 500). | [optional] 
**gas_fragmentation_limit** | **int** | GAS fragmentation limit (512 - 4096, default &#x3D; 1024). | [optional] 
**dgaf** | **str** | Enable/disable downstream group-addressed forwarding (DGAF).    enable:Enable downstream group-addressed forwarding (DGAF).    disable:Disable downstream group-addressed forwarding (DGAF). | [optional] 
**deauth_request_timeout** | **int** | Deauthentication request timeout (in seconds). | [optional] 
**wnm_sleep_mode** | **str** | Enable/disable wireless network management (WNM) sleep mode.    enable:Enable wireless network management (WNM) sleep mode.    disable:Disable wireless network management (WNM) sleep mode. | [optional] 
**bss_transition** | **str** | Enable/disable basic service set (BSS) transition Support.    enable:Enable basic service set (BSS) transition support.    disable:Disable basic service set (BSS) transition support. | [optional] 
**venue_name** | **str** | Venue name. | [optional] 
**venue_url** | **str** | Venue name. | [optional] 
**roaming_consortium** | **str** | Roaming consortium list name. | [optional] 
**nai_realm** | **str** | NAI realm list name. | [optional] 
**oper_friendly_name** | **str** | Operator friendly name. | [optional] 
**oper_icon** | **str** | Operator icon. | [optional] 
**advice_of_charge** | **str** | Advice of charge. | [optional] 
**osu_provider_nai** | **str** | OSU Provider NAI. | [optional] 
**terms_and_conditions** | **str** | Terms and conditions. | [optional] 
**osu_provider** | [**List[WirelessControllerHotspot20HsProfileNameGet200ResponseOsuProviderInner]**](WirelessControllerHotspot20HsProfileNameGet200ResponseOsuProviderInner.md) | Manually selected list of OSU provider(s). | [optional] 
**wan_metrics** | **str** | WAN metric name. | [optional] 
**network_auth** | **str** | Network authentication name. | [optional] 
**var_3gpp_plmn** | **str** | 3GPP PLMN name. | [optional] 
**conn_cap** | **str** | Connection capability name. | [optional] 
**qos_map** | **str** | QoS MAP set ID. | [optional] 
**ip_addr_type** | **str** | IP address type name. | [optional] 
**wba_open_roaming** | **str** | Enable/disable WBA open roaming support.    disable:Disable WBA open roaming support.    enable:Enable WBA open roaming support. | [optional] 
**wba_financial_clearing_provider** | **str** | WBA ID of financial clearing provider. | [optional] 
**wba_data_clearing_provider** | **str** | WBA ID of data clearing provider. | [optional] 
**wba_charging_currency** | **str** | Three letter currency code. | [optional] 
**wba_charging_rate** | **int** | Number of currency units per kilobyte. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_hs_profile_name_get200_response import WirelessControllerHotspot20HsProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20HsProfileNameGet200Response from a JSON string
wireless_controller_hotspot20_hs_profile_name_get200_response_instance = WirelessControllerHotspot20HsProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20HsProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_hs_profile_name_get200_response_dict = wireless_controller_hotspot20_hs_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20HsProfileNameGet200Response from a dict
wireless_controller_hotspot20_hs_profile_name_get200_response_from_dict = WirelessControllerHotspot20HsProfileNameGet200Response.from_dict(wireless_controller_hotspot20_hs_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


