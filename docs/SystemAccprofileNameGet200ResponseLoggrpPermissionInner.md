# SystemAccprofileNameGet200ResponseLoggrpPermissionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**config** | **str** | Log &amp; Report configuration.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**data_access** | **str** | Log &amp; Report Data Access.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**report_access** | **str** | Log &amp; Report Report Access.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**threat_weight** | **str** | Log &amp; Report Threat Weight.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 

## Example

```python
from microlab_fortinet.models.system_accprofile_name_get200_response_loggrp_permission_inner import SystemAccprofileNameGet200ResponseLoggrpPermissionInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAccprofileNameGet200ResponseLoggrpPermissionInner from a JSON string
system_accprofile_name_get200_response_loggrp_permission_inner_instance = SystemAccprofileNameGet200ResponseLoggrpPermissionInner.from_json(json)
# print the JSON string representation of the object
print(SystemAccprofileNameGet200ResponseLoggrpPermissionInner.to_json())

# convert the object into a dict
system_accprofile_name_get200_response_loggrp_permission_inner_dict = system_accprofile_name_get200_response_loggrp_permission_inner_instance.to_dict()
# create an instance of SystemAccprofileNameGet200ResponseLoggrpPermissionInner from a dict
system_accprofile_name_get200_response_loggrp_permission_inner_from_dict = SystemAccprofileNameGet200ResponseLoggrpPermissionInner.from_dict(system_accprofile_name_get200_response_loggrp_permission_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


