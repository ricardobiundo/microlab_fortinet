# SwitchControllerLldpProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Profile name. | [optional] 
**med_tlvs** | **str** | Transmitted LLDP-MED TLVs (type-length-value descriptions).    inventory-management:Inventory management TLVs.    network-policy:Network policy TLVs.    power-management:Power manangement TLVs.    location-identification:Location identificaion TLVs. | [optional] 
**var_802_1_tlvs** | **str** | Transmitted IEEE 802.1 TLVs.    port-vlan-id:Port native VLAN TLV. | [optional] 
**var_802_3_tlvs** | **str** | Transmitted IEEE 802.3 TLVs.    max-frame-size:Maximum frame size TLV.    power-negotiation:PoE+ classification TLV. | [optional] 
**auto_isl** | **str** | Enable/disable auto inter-switch LAG.    disable:Disable automatic MCLAG inter chassis link.    enable:Enable automatic MCLAG inter chassis link. | [optional] 
**auto_isl_hello_timer** | **int** | Auto inter-switch LAG hello timer duration (1 - 30 sec, default &#x3D; 3). | [optional] 
**auto_isl_receive_timeout** | **int** | Auto inter-switch LAG timeout if no response is received (3 - 90 sec, default &#x3D; 9). | [optional] 
**auto_isl_port_group** | **int** | Auto inter-switch LAG port group ID (0 - 9). | [optional] 
**auto_mclag_icl** | **str** | Enable/disable MCLAG inter chassis link.    disable:Disable auto inter-switch-LAG.    enable:Enable auto inter-switch-LAG. | [optional] 
**auto_isl_auth** | **str** | Auto inter-switch LAG authentication mode.    legacy:No auto inter-switch-LAG authentication.    strict:Strict auto inter-switch-LAG authentication.    relax:Relax auto inter-switch-LAG authentication. | [optional] 
**auto_isl_auth_user** | **str** | Auto inter-switch LAG authentication user certificate. | [optional] 
**auto_isl_auth_identity** | **str** | Auto inter-switch LAG authentication identity. | [optional] 
**auto_isl_auth_reauth** | **int** | Auto inter-switch LAG authentication reauth period in seconds(10 - 3600, default &#x3D; 3600). | [optional] 
**auto_isl_auth_encrypt** | **str** | Auto inter-switch LAG encryption mode.    none:No auto inter-switch-LAG encryption.    mixed:Mixed auto inter-switch-LAG encryption.    must:Must auto inter-switch-LAG encryption. | [optional] 
**auto_isl_auth_macsec_profile** | **str** | Auto inter-switch LAG macsec profile for encryption. | [optional] 
**med_network_policy** | [**List[SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner]**](SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner.md) | Configuration method to edit Media Endpoint Discovery (MED) network policy type-length-value (TLV) categories. | [optional] 
**med_location_service** | [**List[SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner]**](SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner.md) | Configuration method to edit Media Endpoint Discovery (MED) location service type-length-value (TLV) categories. | [optional] 
**custom_tlvs** | [**List[SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner]**](SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner.md) | Configuration method to edit custom TLV entries. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_lldp_profile_name_get200_response import SwitchControllerLldpProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerLldpProfileNameGet200Response from a JSON string
switch_controller_lldp_profile_name_get200_response_instance = SwitchControllerLldpProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerLldpProfileNameGet200Response.to_json())

# convert the object into a dict
switch_controller_lldp_profile_name_get200_response_dict = switch_controller_lldp_profile_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerLldpProfileNameGet200Response from a dict
switch_controller_lldp_profile_name_get200_response_from_dict = SwitchControllerLldpProfileNameGet200Response.from_dict(switch_controller_lldp_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


