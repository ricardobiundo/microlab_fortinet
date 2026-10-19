# WirelessControllerApcfgProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | AP local configuration profile name. | [optional] 
**ap_family** | **str** | FortiAP family type (default &#x3D; fap).    fap:FortiAP Family.    fap-u:FortiAP-U Family.    fap-c:FortiAP-C Family. | [optional] 
**comment** | **str** | Comment. | [optional] 
**ac_type** | **str** | Validation controller type (default &#x3D; default).    default:This controller is the one and only controller that the AP could join after applying AP local configuration.    specify:Specified controller is the one and only controller that the AP could join after applying AP local configuration.    apcfg:Any controller defined by AP local configuration after applying AP local configuration. | [optional] 
**ac_timer** | **int** | Maximum waiting time for the AP to join the validation controller after applying AP local configuration (3 - 30 min, default &#x3D; 10). | [optional] 
**ac_ip** | **str** | IP address of the validation controller that AP must be able to join after applying AP local configuration. | [optional] 
**ac_port** | **int** | Port of the validation controller that AP must be able to join after applying AP local configuration (1024 - 49150, default &#x3D; 5246). | [optional] 
**command_list** | [**List[WirelessControllerApcfgProfileNameGet200ResponseCommandListInner]**](WirelessControllerApcfgProfileNameGet200ResponseCommandListInner.md) | AP local configuration command list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_apcfg_profile_name_get200_response import WirelessControllerApcfgProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerApcfgProfileNameGet200Response from a JSON string
wireless_controller_apcfg_profile_name_get200_response_instance = WirelessControllerApcfgProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerApcfgProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_apcfg_profile_name_get200_response_dict = wireless_controller_apcfg_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerApcfgProfileNameGet200Response from a dict
wireless_controller_apcfg_profile_name_get200_response_from_dict = WirelessControllerApcfgProfileNameGet200Response.from_dict(wireless_controller_apcfg_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


