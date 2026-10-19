# SystemFederatedUpgradeGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Current status of the upgrade.    disabled:No federated upgrade has been configured.    initialized:The upgrade has been configured.    downloading:The image is downloading in preparation for the upgrade.    device-disconnected:The image downloads are complete, but one or more devices have disconnected.    ready:The image download finished and the upgrade is pending.    coordinating:The upgrade is coordinating with other running upgrades.    staging:The upgrade is confirmed and images are being staged.    final-check:The upgrade is ready and final checks are in progress.    upgrade-devices:The upgrade is ready and devices are being rebooted.    cancelled:The upgrade was cancelled due to the tree not being ready.    confirmed:The upgrade was confirmed and reboots are running.    done:The upgrade completed successfully.    dry-run-done:The dry run finished.    failed:The upgrade failed due to a local issue. | [optional] 
**source** | **str** | Source that set up the federated upgrade config.    user:Upgrade configured based on user input.    auto-firmware-upgrade:Upgrade configured by the FortiGuard auto-firmware-upgrade feature.    forced-upgrade:Forced upgrade due to no support contract or end-of-life firmware. | [optional] 
**failure_reason** | **str** | Reason for upgrade failure.    none:No failure.    internal:An internal error occurred.    timeout:The upgrade timed out.    device-type-unsupported:The device type was not supported by the FortiGate.    download-failed:The image could not be downloaded.    device-missing:The device was disconnected from the FortiGate.    version-unavailable:An image matching the device and version could not be found.    staging-failed:The image could not be pushed to the device.    reboot-failed:The device could not be rebooted.    device-not-reconnected:The device did not reconnect after rebooting.    node-not-ready:A device in the Security Fabric tree was not ready.    no-final-confirmation:The coordinating FortiGate did not confirm the upgrade.    no-confirmation-query:A downstream FortiGate did not initiate final confirmation.    config-error-log-nonempty:Configuration errors encountered during the upgrade.    csf-tree-not-supported:The Security Fabric is disabled on the root FortiGate    firmware-changed:Firmware changed after the upgrade was set up.    node-failed:A device in the Security Fabric tree failed.    image-missing:The firmware image is missing and download is not allowed | [optional] 
**failure_device** | **str** | Serial number of the node to include. | [optional] 
**upgrade_id** | **int** | Unique identifier for this upgrade. | [optional] 
**next_path_index** | **int** | The index of the next image to upgrade to. | [optional] 
**ignore_signing_errors** | **str** | Allow/reject use of FortiGate firmware images that are unsigned.    enable:Allow use of FortiGate images that are unsigned.    disable:Reject use of FortiGate images that are unsigned. | [optional] 
**ha_reboot_controller** | **str** | Serial number of the FortiGate unit that will control the reboot process for the federated upgrade of the HA cluster. | [optional] 
**known_ha_members** | [**List[SystemDeviceUpgradeSerialGet200ResponseKnownHaMembersInner]**](SystemDeviceUpgradeSerialGet200ResponseKnownHaMembersInner.md) | Known members of the HA cluster. If a member is missing at upgrade time, the upgrade will be cancelled. | [optional] 
**initial_version** | **str** | Firmware version when the upgrade was set up. | [optional] 
**starter_admin** | **str** | Admin that started the upgrade. | [optional] 
**node_list** | [**List[SystemFederatedUpgradeGet200ResponseNodeListInner]**](SystemFederatedUpgradeGet200ResponseNodeListInner.md) | Nodes which will be included in the upgrade. | [optional] 

## Example

```python
from microlab_fortinet.models.system_federated_upgrade_get200_response import SystemFederatedUpgradeGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFederatedUpgradeGet200Response from a JSON string
system_federated_upgrade_get200_response_instance = SystemFederatedUpgradeGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFederatedUpgradeGet200Response.to_json())

# convert the object into a dict
system_federated_upgrade_get200_response_dict = system_federated_upgrade_get200_response_instance.to_dict()
# create an instance of SystemFederatedUpgradeGet200Response from a dict
system_federated_upgrade_get200_response_from_dict = SystemFederatedUpgradeGet200Response.from_dict(system_federated_upgrade_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


