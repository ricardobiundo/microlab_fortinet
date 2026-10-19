# SystemFederatedUpgradeGet200ResponseNodeListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**serial** | **str** | Serial number of the node to include. | [optional] 
**timing** | **str** | Run immediately or at a scheduled time.    immediate:Begin the upgrade immediately.    scheduled:Begin the upgrade at a configured time. | [optional] 
**maximum_minutes** | **int** | Maximum number of minutes to allow for immediate upgrade preparation. | [optional] 
**time** | **str** | Scheduled upgrade execution time in UTC (hh:mm yyyy/mm/dd UTC). | [optional] 
**setup_time** | **str** | Upgrade preparation start time in UTC (hh:mm yyyy/mm/dd UTC). | [optional] 
**upgrade_path** | **str** | Fortinet OS image versions to upgrade through in major-minor-patch format, such as 7-0-4. | [optional] 
**device_type** | **str** | Fortinet device type.    fortigate:This device is a FortiGate.    fortiswitch:This device is a FortiSwitch.    fortiap:This device is a FortiAP.    fortiextender:This device is a FortiExtender. | [optional] 
**allow_download** | **str** | Enable/disable download firmware images.    enable:Allow download of images.    disable:Disable download of images. | [optional] 
**coordinating_fortigate** | **str** | Serial number of the FortiGate unit that controls this device. | [optional] 
**failure_reason** | **str** | Upgrade failure reason.    none:No failure.    internal:An internal error occurred.    timeout:The upgrade timed out.    device-type-unsupported:The device type was not supported by the FortiGate.    download-failed:The image could not be downloaded.    device-missing:The device was disconnected from the FortiGate.    version-unavailable:An image matching the device and version could not be found.    staging-failed:The image could not be pushed to the device.    reboot-failed:The device could not be rebooted.    device-not-reconnected:The device did not reconnect after rebooting.    node-not-ready:A device in the Security Fabric tree was not ready.    no-final-confirmation:The coordinating FortiGate did not confirm the upgrade.    no-confirmation-query:A downstream FortiGate did not initiate final confirmation.    config-error-log-nonempty:Configuration errors encountered during the upgrade.    csf-tree-not-supported:The Security Fabric is disabled on the root FortiGate    firmware-changed:Firmware changed after the upgrade was set up.    node-failed:A device in the Security Fabric tree failed.    image-missing:The firmware image is missing and download is not allowed | [optional] 

## Example

```python
from microlab_fortinet.models.system_federated_upgrade_get200_response_node_list_inner import SystemFederatedUpgradeGet200ResponseNodeListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFederatedUpgradeGet200ResponseNodeListInner from a JSON string
system_federated_upgrade_get200_response_node_list_inner_instance = SystemFederatedUpgradeGet200ResponseNodeListInner.from_json(json)
# print the JSON string representation of the object
print(SystemFederatedUpgradeGet200ResponseNodeListInner.to_json())

# convert the object into a dict
system_federated_upgrade_get200_response_node_list_inner_dict = system_federated_upgrade_get200_response_node_list_inner_instance.to_dict()
# create an instance of SystemFederatedUpgradeGet200ResponseNodeListInner from a dict
system_federated_upgrade_get200_response_node_list_inner_from_dict = SystemFederatedUpgradeGet200ResponseNodeListInner.from_dict(system_federated_upgrade_get200_response_node_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


