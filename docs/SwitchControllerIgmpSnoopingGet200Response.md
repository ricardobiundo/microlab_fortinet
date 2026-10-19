# SwitchControllerIgmpSnoopingGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**aging_time** | **int** | Maximum number of seconds to retain a multicast snooping entry for which no packets have been seen (15 - 3600 sec, default &#x3D; 300). | [optional] 
**flood_unknown_multicast** | **str** | Enable/disable unknown multicast flooding.    enable:Enable unknown multicast flooding.    disable:Disable unknown multicast flooding. | [optional] 
**query_interval** | **int** | Maximum time after which IGMP query will be sent (10 - 1200 sec, default &#x3D; 125). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_igmp_snooping_get200_response import SwitchControllerIgmpSnoopingGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerIgmpSnoopingGet200Response from a JSON string
switch_controller_igmp_snooping_get200_response_instance = SwitchControllerIgmpSnoopingGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerIgmpSnoopingGet200Response.to_json())

# convert the object into a dict
switch_controller_igmp_snooping_get200_response_dict = switch_controller_igmp_snooping_get200_response_instance.to_dict()
# create an instance of SwitchControllerIgmpSnoopingGet200Response from a dict
switch_controller_igmp_snooping_get200_response_from_dict = SwitchControllerIgmpSnoopingGet200Response.from_dict(switch_controller_igmp_snooping_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


