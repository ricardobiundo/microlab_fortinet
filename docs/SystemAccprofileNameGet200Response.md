# SystemAccprofileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Profile name. | [optional] 
**scope** | **str** | Scope of admin access: global or specific VDOM(s).    vdom:VDOM access.    global:Global access. | [optional] 
**comments** | **str** | Comment. | [optional] 
**secfabgrp** | **str** | Security Fabric.    none:No access.    read:Read access.    read-write:Read/write access.    custom:Customized access. | [optional] 
**ftviewgrp** | **str** | FortiView.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**authgrp** | **str** | Administrator access to Users and Devices.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**sysgrp** | **str** | System Configuration.    none:No access.    read:Read access.    read-write:Read/write access.    custom:Customized access. | [optional] 
**netgrp** | **str** | Network Configuration.    none:No access.    read:Read access.    read-write:Read/write access.    custom:Customized access. | [optional] 
**loggrp** | **str** | Administrator access to Logging and Reporting including viewing log messages.    none:No access.    read:Read access.    read-write:Read/write access.    custom:Customized access. | [optional] 
**fwgrp** | **str** | Administrator access to the Firewall configuration.    none:No access.    read:Read access.    read-write:Read/write access.    custom:Customized access. | [optional] 
**vpngrp** | **str** | Administrator access to IPsec, SSL, PPTP, and L2TP VPN.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**utmgrp** | **str** | Administrator access to Security Profiles.    none:No access.    read:Read access.    read-write:Read/write access.    custom:Customized access. | [optional] 
**wanoptgrp** | **str** | Administrator access to WAN Opt &amp; Cache.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**wifi** | **str** | Administrator access to the WiFi controller and Switch controller.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**netgrp_permission** | [**List[SystemAccprofileNameGet200ResponseNetgrpPermissionInner]**](SystemAccprofileNameGet200ResponseNetgrpPermissionInner.md) | Custom network permission. | [optional] 
**sysgrp_permission** | [**List[SystemAccprofileNameGet200ResponseSysgrpPermissionInner]**](SystemAccprofileNameGet200ResponseSysgrpPermissionInner.md) | Custom system permission. | [optional] 
**fwgrp_permission** | [**List[SystemAccprofileNameGet200ResponseFwgrpPermissionInner]**](SystemAccprofileNameGet200ResponseFwgrpPermissionInner.md) | Custom firewall permission. | [optional] 
**loggrp_permission** | [**List[SystemAccprofileNameGet200ResponseLoggrpPermissionInner]**](SystemAccprofileNameGet200ResponseLoggrpPermissionInner.md) | Custom Log &amp; Report permission. | [optional] 
**utmgrp_permission** | [**List[SystemAccprofileNameGet200ResponseUtmgrpPermissionInner]**](SystemAccprofileNameGet200ResponseUtmgrpPermissionInner.md) | Custom Security Profile permissions. | [optional] 
**secfabgrp_permission** | [**List[SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner]**](SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner.md) | Custom Security Fabric permissions. | [optional] 
**admintimeout_override** | **str** | Enable/disable overriding the global administrator idle timeout.    enable:Enable overriding the global administrator idle timeout.    disable:Disable overriding the global administrator idle timeout. | [optional] 
**admintimeout** | **int** | Administrator timeout for this access profile (0 - 480 min, default &#x3D; 10, 0 means never timeout). | [optional] 
**cli_diagnose** | **str** | Enable/disable permission to run diagnostic commands.    enable:Enable permission to run diagnostic commands.    disable:Disable permission to run diagnostic commands. | [optional] 
**cli_get** | **str** | Enable/disable permission to run get commands.    enable:Enable permission to run get commands.    disable:Disable permission to run get commands. | [optional] 
**cli_show** | **str** | Enable/disable permission to run show commands.    enable:Enable permission to run show commands.    disable:Disable permission to run show commands. | [optional] 
**cli_exec** | **str** | Enable/disable permission to run execute commands.    enable:Enable permission to run execute commands.    disable:Disable permission to run execute commands. | [optional] 
**cli_config** | **str** | Enable/disable permission to run config commands.    enable:Enable permission to run config commands.    disable:Disable permission to run config commands. | [optional] 
**system_execute_ssh** | **str** | Enable/disable permission to execute SSH commands.    enable:Enable permission to execute SSH commands.    disable:Disable permission to execute SSH commands. | [optional] 
**system_execute_telnet** | **str** | Enable/disable permission to execute TELNET commands.    enable:Enable permission to execute TELNET commands.    disable:Disable permission to execute TELNET commands. | [optional] 

## Example

```python
from microlab_fortinet.models.system_accprofile_name_get200_response import SystemAccprofileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAccprofileNameGet200Response from a JSON string
system_accprofile_name_get200_response_instance = SystemAccprofileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAccprofileNameGet200Response.to_json())

# convert the object into a dict
system_accprofile_name_get200_response_dict = system_accprofile_name_get200_response_instance.to_dict()
# create an instance of SystemAccprofileNameGet200Response from a dict
system_accprofile_name_get200_response_from_dict = SystemAccprofileNameGet200Response.from_dict(system_accprofile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


