# SystemCentralManagementGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mode** | **str** | Central management mode.    normal:Manage and configure this FortiGate from FortiManager.    backup:Manage and configure this FortiGate locally and back up its configuration to FortiManager. | [optional] 
**type** | **str** | Central management type.    fortimanager:FortiManager.    fortiguard:Central management of this FortiGate using FortiCloud.    none:No central management. | [optional] 
**fortigate_cloud_sso_default_profile** | **str** | Override access profile. Permission is set to read-only without a FortiGate Cloud Central Management license. | [optional] 
**schedule_config_restore** | **str** | Enable/disable allowing the central management server to restore the configuration of this FortiGate.    enable:Enable scheduled configuration restore.    disable:Disable scheduled configuration restore. | [optional] 
**schedule_script_restore** | **str** | Enable/disable allowing the central management server to restore the scripts stored on this FortiGate.    enable:Enable scheduled script restore.    disable:Disable scheduled script restore. | [optional] 
**allow_push_configuration** | **str** | Enable/disable allowing the central management server to push configuration changes to this FortiGate.    enable:Enable push configuration.    disable:Disable push configuration. | [optional] 
**allow_push_firmware** | **str** | Enable/disable allowing the central management server to push firmware updates to this FortiGate.    enable:Enable push firmware.    disable:Disable push firmware. | [optional] 
**allow_remote_firmware_upgrade** | **str** | Enable/disable remotely upgrading the firmware on this FortiGate from the central management server.    enable:Enable remote firmware upgrade.    disable:Disable remote firmware upgrade. | [optional] 
**allow_monitor** | **str** | Enable/disable allowing the central management server to remotely monitor this FortiGate unit.    enable:Enable remote monitoring of device.    disable:Disable remote monitoring of device. | [optional] 
**serial_number** | **str** | Serial number. | [optional] 
**fmg** | **str** | IP address or FQDN of the FortiManager. | [optional] 
**fmg_source_ip** | **str** | IPv4 source address that this FortiGate uses when communicating with FortiManager. | [optional] 
**fmg_source_ip6** | **str** | IPv6 source address that this FortiGate uses when communicating with FortiManager. | [optional] 
**local_cert** | **str** | Certificate to be used by FGFM protocol. | [optional] 
**ca_cert** | **str** | CA certificate to be used by FGFM protocol. | [optional] 
**vdom** | **str** | Virtual domain (VDOM) name to use when communicating with FortiManager. | [optional] 
**server_list** | [**List[SystemCentralManagementGet200ResponseServerListInner]**](SystemCentralManagementGet200ResponseServerListInner.md) | Additional severs that the FortiGate can use for updates (for AV, IPS, updates) and ratings (for web filter and antispam ratings) servers. | [optional] 
**fmg_update_port** | **str** | Port used to communicate with FortiManager that is acting as a FortiGuard update server.    8890:Use port 8890 to communicate with FortiManager that is acting as a FortiGuard update server.    443:Use port 443 to communicate with FortiManager that is acting as a FortiGuard update server. | [optional] 
**fmg_update_http_header** | **str** | Enable/disable inclusion of HTTP header in update request.    enable:Enable inclusion of HTTP header in update request.    disable:Disable inclusion of HTTP header in update request. | [optional] 
**include_default_servers** | **str** | Enable/disable inclusion of public FortiGuard servers in the override server list.    enable:Enable inclusion of public FortiGuard servers in the override server list.    disable:Disable inclusion of public FortiGuard servers in the override server list. | [optional] 
**enc_algorithm** | **str** | Encryption strength for communications between the FortiGate and central management.    default:High strength algorithms and medium-strength 128-bit key length algorithms.    high:128-bit and larger key length algorithms.    low:64-bit or 56-bit key length algorithms without export restrictions. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_central_management_get200_response import SystemCentralManagementGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemCentralManagementGet200Response from a JSON string
system_central_management_get200_response_instance = SystemCentralManagementGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemCentralManagementGet200Response.to_json())

# convert the object into a dict
system_central_management_get200_response_dict = system_central_management_get200_response_instance.to_dict()
# create an instance of SystemCentralManagementGet200Response from a dict
system_central_management_get200_response_from_dict = SystemCentralManagementGet200Response.from_dict(system_central_management_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


