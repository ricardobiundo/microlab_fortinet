# UserQuarantineGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**quarantine** | **str** | Enable/disable quarantine.    enable:Enable quarantine.    disable:Disable quarantine. | [optional] 
**traffic_policy** | **str** | Traffic policy for quarantined MACs. | [optional] 
**firewall_groups** | **str** | Firewall address group which includes all quarantine MAC address. | [optional] 
**targets** | [**List[UserQuarantineGet200ResponseTargetsInner]**](UserQuarantineGet200ResponseTargetsInner.md) | Quarantine entry to hold multiple MACs. | [optional] 

## Example

```python
from microlab_fortinet.models.user_quarantine_get200_response import UserQuarantineGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserQuarantineGet200Response from a JSON string
user_quarantine_get200_response_instance = UserQuarantineGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserQuarantineGet200Response.to_json())

# convert the object into a dict
user_quarantine_get200_response_dict = user_quarantine_get200_response_instance.to_dict()
# create an instance of UserQuarantineGet200Response from a dict
user_quarantine_get200_response_from_dict = UserQuarantineGet200Response.from_dict(user_quarantine_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


