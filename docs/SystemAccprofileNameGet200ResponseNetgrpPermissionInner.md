# SystemAccprofileNameGet200ResponseNetgrpPermissionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cfg** | **str** | Network Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**packet_capture** | **str** | Packet Capture Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**route_cfg** | **str** | Router Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 

## Example

```python
from microlab_fortinet.models.system_accprofile_name_get200_response_netgrp_permission_inner import SystemAccprofileNameGet200ResponseNetgrpPermissionInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAccprofileNameGet200ResponseNetgrpPermissionInner from a JSON string
system_accprofile_name_get200_response_netgrp_permission_inner_instance = SystemAccprofileNameGet200ResponseNetgrpPermissionInner.from_json(json)
# print the JSON string representation of the object
print(SystemAccprofileNameGet200ResponseNetgrpPermissionInner.to_json())

# convert the object into a dict
system_accprofile_name_get200_response_netgrp_permission_inner_dict = system_accprofile_name_get200_response_netgrp_permission_inner_instance.to_dict()
# create an instance of SystemAccprofileNameGet200ResponseNetgrpPermissionInner from a dict
system_accprofile_name_get200_response_netgrp_permission_inner_from_dict = SystemAccprofileNameGet200ResponseNetgrpPermissionInner.from_dict(system_accprofile_name_get200_response_netgrp_permission_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


