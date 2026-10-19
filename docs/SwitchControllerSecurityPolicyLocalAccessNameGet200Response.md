# SwitchControllerSecurityPolicyLocalAccessNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Policy name. | [optional] 
**mgmt_allowaccess** | **str** | Allowed access on the switch management interface.    https:HTTPS access.    ping:PING access.    ssh:SSH access.    snmp:SNMP access.    http:HTTP access.    telnet:TELNET access.    radius-acct:RADIUS accounting access. | [optional] 
**internal_allowaccess** | **str** | Allowed access on the switch internal interface.    https:HTTPS access.    ping:PING access.    ssh:SSH access.    snmp:SNMP access.    http:HTTP access.    telnet:TELNET access.    radius-acct:RADIUS accounting access. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_security_policy_local_access_name_get200_response import SwitchControllerSecurityPolicyLocalAccessNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerSecurityPolicyLocalAccessNameGet200Response from a JSON string
switch_controller_security_policy_local_access_name_get200_response_instance = SwitchControllerSecurityPolicyLocalAccessNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerSecurityPolicyLocalAccessNameGet200Response.to_json())

# convert the object into a dict
switch_controller_security_policy_local_access_name_get200_response_dict = switch_controller_security_policy_local_access_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerSecurityPolicyLocalAccessNameGet200Response from a dict
switch_controller_security_policy_local_access_name_get200_response_from_dict = SwitchControllerSecurityPolicyLocalAccessNameGet200Response.from_dict(switch_controller_security_policy_local_access_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


