# SystemAlarmGet200ResponseGroupsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Group ID. | [optional] 
**period** | **int** | Time period in seconds (0 &#x3D; from start up). | [optional] 
**admin_auth_failure_threshold** | **int** | Admin authentication failure threshold. | [optional] 
**admin_auth_lockout_threshold** | **int** | Admin authentication lockout threshold. | [optional] 
**user_auth_failure_threshold** | **int** | User authentication failure threshold. | [optional] 
**user_auth_lockout_threshold** | **int** | User authentication lockout threshold. | [optional] 
**replay_attempt_threshold** | **int** | Replay attempt threshold. | [optional] 
**self_test_failure_threshold** | **int** | Self-test failure threshold. | [optional] 
**log_full_warning_threshold** | **int** | Log full warning threshold. | [optional] 
**encryption_failure_threshold** | **int** | Encryption failure threshold. | [optional] 
**decryption_failure_threshold** | **int** | Decryption failure threshold. | [optional] 
**fw_policy_violations** | [**List[SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner]**](SystemAlarmGet200ResponseGroupsInnerFwPolicyViolationsInner.md) | Firewall policy violations. | [optional] 
**fw_policy_id** | **int** | Firewall policy ID. | [optional] 
**fw_policy_id_threshold** | **int** | Firewall policy ID threshold. | [optional] 

## Example

```python
from microlab_fortinet.models.system_alarm_get200_response_groups_inner import SystemAlarmGet200ResponseGroupsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAlarmGet200ResponseGroupsInner from a JSON string
system_alarm_get200_response_groups_inner_instance = SystemAlarmGet200ResponseGroupsInner.from_json(json)
# print the JSON string representation of the object
print(SystemAlarmGet200ResponseGroupsInner.to_json())

# convert the object into a dict
system_alarm_get200_response_groups_inner_dict = system_alarm_get200_response_groups_inner_instance.to_dict()
# create an instance of SystemAlarmGet200ResponseGroupsInner from a dict
system_alarm_get200_response_groups_inner_from_dict = SystemAlarmGet200ResponseGroupsInner.from_dict(system_alarm_get200_response_groups_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


