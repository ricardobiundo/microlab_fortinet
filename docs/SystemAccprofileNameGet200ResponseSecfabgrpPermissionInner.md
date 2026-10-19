# SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**csfsys** | **str** | Security Fabric system profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**csffoo** | **str** | Fabric Overlay Orchestrator profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 

## Example

```python
from microlab_fortinet.models.system_accprofile_name_get200_response_secfabgrp_permission_inner import SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner from a JSON string
system_accprofile_name_get200_response_secfabgrp_permission_inner_instance = SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner.from_json(json)
# print the JSON string representation of the object
print(SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner.to_json())

# convert the object into a dict
system_accprofile_name_get200_response_secfabgrp_permission_inner_dict = system_accprofile_name_get200_response_secfabgrp_permission_inner_instance.to_dict()
# create an instance of SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner from a dict
system_accprofile_name_get200_response_secfabgrp_permission_inner_from_dict = SystemAccprofileNameGet200ResponseSecfabgrpPermissionInner.from_dict(system_accprofile_name_get200_response_secfabgrp_permission_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


