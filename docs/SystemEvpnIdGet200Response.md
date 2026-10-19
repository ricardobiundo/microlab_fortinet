# SystemEvpnIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**rd** | **str** | Route Distinguisher: AA:NN|A.B.C.D:NN. | [optional] 
**import_rt** | [**List[SystemEvpnIdGet200ResponseImportRtInner]**](SystemEvpnIdGet200ResponseImportRtInner.md) | List of import route targets. | [optional] 
**export_rt** | [**List[SystemEvpnIdGet200ResponseImportRtInner]**](SystemEvpnIdGet200ResponseImportRtInner.md) | List of export route targets. | [optional] 
**ip_local_learning** | **str** | Enable/disable IP address local learning.    enable:Enable IP address local learning.    disable:Disable IP address local learning. | [optional] 
**arp_suppression** | **str** | Enable/disable ARP suppression.    enable:Enable ARP suppression.    disable:Disable ARP suppression. | [optional] 

## Example

```python
from microlab_fortinet.models.system_evpn_id_get200_response import SystemEvpnIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemEvpnIdGet200Response from a JSON string
system_evpn_id_get200_response_instance = SystemEvpnIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemEvpnIdGet200Response.to_json())

# convert the object into a dict
system_evpn_id_get200_response_dict = system_evpn_id_get200_response_instance.to_dict()
# create an instance of SystemEvpnIdGet200Response from a dict
system_evpn_id_get200_response_from_dict = SystemEvpnIdGet200Response.from_dict(system_evpn_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


