# SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Firewall policy violations ID. | [optional] 
**threshold** | **int** | Firewall policy violation threshold. | [optional] 
**src_ip** | **str** | Source IP (0&#x3D;all). | [optional] 
**dst_ip** | **str** | Destination IP (0&#x3D;all). | [optional] 
**src_port** | **int** | Source port (0&#x3D;all). | [optional] 
**dst_port** | **int** | Destination port (0&#x3D;all). | [optional] 

## Example

```python
from microlab_fortinet.models.system_alarm_get200_response_groups_inner_fw_policy_violations_inner import SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner from a JSON string
system_alarm_get200_response_groups_inner_fw_policy_violations_inner_instance = SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner.from_json(json)
# print the JSON string representation of the object
print(SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner.to_json())

# convert the object into a dict
system_alarm_get200_response_groups_inner_fw_policy_violations_inner_dict = system_alarm_get200_response_groups_inner_fw_policy_violations_inner_instance.to_dict()
# create an instance of SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner from a dict
system_alarm_get200_response_groups_inner_fw_policy_violations_inner_from_dict = SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner.from_dict(system_alarm_get200_response_groups_inner_fw_policy_violations_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


