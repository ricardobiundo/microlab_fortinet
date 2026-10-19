# SystemAccprofileNameGet200ResponseSysgrpPermissionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin** | **str** | Administrator Users.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**upd** | **str** | FortiGuard Updates.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**cfg** | **str** | System Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**mnt** | **str** | Maintenance.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 

## Example

```python
from microlab_fortinet.models.system_accprofile_name_get200_response_sysgrp_permission_inner import SystemAccprofileNameGet200ResponseSysgrpPermissionInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAccprofileNameGet200ResponseSysgrpPermissionInner from a JSON string
system_accprofile_name_get200_response_sysgrp_permission_inner_instance = SystemAccprofileNameGet200ResponseSysgrpPermissionInner.from_json(json)
# print the JSON string representation of the object
print(SystemAccprofileNameGet200ResponseSysgrpPermissionInner.to_json())

# convert the object into a dict
system_accprofile_name_get200_response_sysgrp_permission_inner_dict = system_accprofile_name_get200_response_sysgrp_permission_inner_instance.to_dict()
# create an instance of SystemAccprofileNameGet200ResponseSysgrpPermissionInner from a dict
system_accprofile_name_get200_response_sysgrp_permission_inner_from_dict = SystemAccprofileNameGet200ResponseSysgrpPermissionInner.from_dict(system_accprofile_name_get200_response_sysgrp_permission_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


