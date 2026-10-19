# UserQuarantineGet200ResponseTargetsInnerMacsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mac** | **str** | Quarantine MAC. | [optional] 
**description** | **str** | Description for the quarantine MAC. | [optional] 
**drop** | **str** | Enable/disable dropping of quarantined device traffic.    disable:Sends quarantined device traffic to FortiGate.    enable:Blocks quarantined device traffic to FortiGate. | [optional] 
**parent** | **str** | Parent entry name. | [optional] 

## Example

```python
from microlab_fortinet.models.user_quarantine_get200_response_targets_inner_macs_inner import UserQuarantineGet200ResponseTargetsInnerMacsInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserQuarantineGet200ResponseTargetsInnerMacsInner from a JSON string
user_quarantine_get200_response_targets_inner_macs_inner_instance = UserQuarantineGet200ResponseTargetsInnerMacsInner.from_json(json)
# print the JSON string representation of the object
print(UserQuarantineGet200ResponseTargetsInnerMacsInner.to_json())

# convert the object into a dict
user_quarantine_get200_response_targets_inner_macs_inner_dict = user_quarantine_get200_response_targets_inner_macs_inner_instance.to_dict()
# create an instance of UserQuarantineGet200ResponseTargetsInnerMacsInner from a dict
user_quarantine_get200_response_targets_inner_macs_inner_from_dict = UserQuarantineGet200ResponseTargetsInnerMacsInner.from_dict(user_quarantine_get200_response_targets_inner_macs_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


