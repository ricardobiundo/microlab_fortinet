# SystemAccprofileNameGet200ResponseUtmgrpPermissionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**antivirus** | **str** | Antivirus profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**ips** | **str** | IPS profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**webfilter** | **str** | Web Filter profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**emailfilter** | **str** | Email Filter and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**dlp** | **str** | DLP profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**file_filter** | **str** | File-filter profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**application_control** | **str** | Application Control profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**icap** | **str** | ICAP profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**voip** | **str** | VoIP profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**waf** | **str** | Web Application Firewall profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**dnsfilter** | **str** | DNS Filter profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**endpoint_control** | **str** | FortiClient Profiles.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**videofilter** | **str** | Video filter profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**virtual_patch** | **str** | Virtual patch profiles and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**casb** | **str** | Inline CASB filter profile and settings    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 
**telemetry** | **str** | Telemetry profile and settings.    none:No access.    read:Read access.    read-write:Read/write access. | [optional] 

## Example

```python
from microlab_fortinet.models.system_accprofile_name_get200_response_utmgrp_permission_inner import SystemAccprofileNameGet200ResponseUtmgrpPermissionInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAccprofileNameGet200ResponseUtmgrpPermissionInner from a JSON string
system_accprofile_name_get200_response_utmgrp_permission_inner_instance = SystemAccprofileNameGet200ResponseUtmgrpPermissionInner.from_json(json)
# print the JSON string representation of the object
print(SystemAccprofileNameGet200ResponseUtmgrpPermissionInner.to_json())

# convert the object into a dict
system_accprofile_name_get200_response_utmgrp_permission_inner_dict = system_accprofile_name_get200_response_utmgrp_permission_inner_instance.to_dict()
# create an instance of SystemAccprofileNameGet200ResponseUtmgrpPermissionInner from a dict
system_accprofile_name_get200_response_utmgrp_permission_inner_from_dict = SystemAccprofileNameGet200ResponseUtmgrpPermissionInner.from_dict(system_accprofile_name_get200_response_utmgrp_permission_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


