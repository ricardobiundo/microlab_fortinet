# SystemVneInterfaceNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | VNE tunnel name. | [optional] 
**interface** | **str** | Interface name. | [optional] 
**ssl_certificate** | **str** | Name of local certificate for SSL connections. | [optional] 
**bmr_hostname** | **str** | BMR hostname. | [optional] 
**auto_asic_offload** | **str** | Enable/disable tunnel ASIC offloading.    enable:Enable auto ASIC offloading.    disable:Disable ASIC offloading. | [optional] 
**ipv4_address** | **str** | Tunnel IPv4 address and netmask. | [optional] 
**br** | **str** | IPv6 address or FQDN of the border relay. | [optional] 
**update_url** | **str** | URL of provisioning server. | [optional] 
**mode** | **str** | VNE tunnel mode.    map-e:Map-e mode.    fixed-ip:Fixed-ip mode.    ds-lite:DS-Lite mode. | [optional] 
**http_username** | **str** | HTTP authentication user name. | [optional] 
**http_password** | **str** | HTTP authentication password. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vne_interface_name_get200_response import SystemVneInterfaceNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVneInterfaceNameGet200Response from a JSON string
system_vne_interface_name_get200_response_instance = SystemVneInterfaceNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVneInterfaceNameGet200Response.to_json())

# convert the object into a dict
system_vne_interface_name_get200_response_dict = system_vne_interface_name_get200_response_instance.to_dict()
# create an instance of SystemVneInterfaceNameGet200Response from a dict
system_vne_interface_name_get200_response_from_dict = SystemVneInterfaceNameGet200Response.from_dict(system_vne_interface_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


