# SystemDeviceUpgradeExemptionsIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Device upgrade exemption ID (0 - 65535). | [optional] 
**fortinet_device** | **str** | Fortinet extension device (FortiAP, FortiSwitch, FortiExtender). | [optional] 
**version** | **str** | Highest version of Fortinet firmware to exempt (format in Major.minor.patch, such as 7.6.4). | [optional] 

## Example

```python
from microlab_fortinet.models.system_device_upgrade_exemptions_id_get200_response import SystemDeviceUpgradeExemptionsIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDeviceUpgradeExemptionsIdGet200Response from a JSON string
system_device_upgrade_exemptions_id_get200_response_instance = SystemDeviceUpgradeExemptionsIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDeviceUpgradeExemptionsIdGet200Response.to_json())

# convert the object into a dict
system_device_upgrade_exemptions_id_get200_response_dict = system_device_upgrade_exemptions_id_get200_response_instance.to_dict()
# create an instance of SystemDeviceUpgradeExemptionsIdGet200Response from a dict
system_device_upgrade_exemptions_id_get200_response_from_dict = SystemDeviceUpgradeExemptionsIdGet200Response.from_dict(system_device_upgrade_exemptions_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


