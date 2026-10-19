# SwitchControllerInitialConfigTemplateNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Initial config template name. | [optional] 
**vlanid** | **int** | Unique VLAN ID. | [optional] 
**ip** | **str** | Interface IPv4 address and subnet mask. | [optional] 
**allowaccess** | **str** | Permitted types of management access to this interface.    ping:PING access.    https:HTTPS access.    ssh:SSH access.    snmp:SNMP access.    http:HTTP access.    telnet:TELNET access.    fgfm:FortiManager access.    radius-acct:RADIUS accounting access.    probe-response:Probe access.    fabric:Security Fabric access.    ftm:FTM access. | [optional] 
**auto_ip** | **str** | Automatically allocate interface address and subnet block.    enable:Enable auto-ip status.    disable:Disable auto-ip status. | [optional] 
**dhcp_server** | **str** | Enable/disable a DHCP server on this interface.    enable:Enable DHCP server.    disable:Disable DHCP server. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_initial_config_template_name_get200_response import SwitchControllerInitialConfigTemplateNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerInitialConfigTemplateNameGet200Response from a JSON string
switch_controller_initial_config_template_name_get200_response_instance = SwitchControllerInitialConfigTemplateNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerInitialConfigTemplateNameGet200Response.to_json())

# convert the object into a dict
switch_controller_initial_config_template_name_get200_response_dict = switch_controller_initial_config_template_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerInitialConfigTemplateNameGet200Response from a dict
switch_controller_initial_config_template_name_get200_response_from_dict = SwitchControllerInitialConfigTemplateNameGet200Response.from_dict(switch_controller_initial_config_template_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


