# SystemAccprofileNameGet200ResponseFwgrpPermissionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy** | **str** | Policy Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**address** | **str** | Address Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**service** | **str** | Service Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**schedule** | **str** | Schedule Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**others** | **str** | Other Firewall Configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 

## Example

```python
from microlab_fortinet.models.system_accprofile_name_get200_response_fwgrp_permission_inner import SystemAccprofileNameGet200ResponseFwgrpPermissionInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAccprofileNameGet200ResponseFwgrpPermissionInner from a JSON string
system_accprofile_name_get200_response_fwgrp_permission_inner_instance = SystemAccprofileNameGet200ResponseFwgrpPermissionInner.from_json(json)
# print the JSON string representation of the object
print(SystemAccprofileNameGet200ResponseFwgrpPermissionInner.to_json())

# convert the object into a dict
system_accprofile_name_get200_response_fwgrp_permission_inner_dict = system_accprofile_name_get200_response_fwgrp_permission_inner_instance.to_dict()
# create an instance of SystemAccprofileNameGet200ResponseFwgrpPermissionInner from a dict
system_accprofile_name_get200_response_fwgrp_permission_inner_from_dict = SystemAccprofileNameGet200ResponseFwgrpPermissionInner.from_dict(system_accprofile_name_get200_response_fwgrp_permission_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


