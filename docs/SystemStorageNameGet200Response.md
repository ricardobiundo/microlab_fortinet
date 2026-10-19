# SystemStorageNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Storage name. | [optional] 
**status** | **str** | Enable/disable storage.    enable:Enable setting.    disable:Disable setting. | [optional] 
**media_status** | **str** | The physical status of current media.    enable:Storage is enabled.    disable:Storage is disabled.    fail:Storage have some fail sector. | [optional] 
**order** | **int** | Set storage order. | [optional] 
**partition** | **str** | Label of underlying partition. | [optional] 
**device** | **str** | Partition device. | [optional] 
**size** | **int** | Partition size. | [optional] 
**usage** | **str** | Use hard disk for logging or WAN Optimization (default &#x3D; log).    log:Use hard disk for logging.    wanopt:Use hard disk for WAN Optimization. | [optional] 
**wanopt_mode** | **str** | WAN Optimization mode (default &#x3D; mix).    mix:Use hard disk for WAN Optimization mix mode.    wanopt:Use hard disk for WAN Optimization wanopt mode.    webcache:Use hard disk for WAN Optimization webcache mode. | [optional] 

## Example

```python
from microlab_fortinet.models.system_storage_name_get200_response import SystemStorageNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStorageNameGet200Response from a JSON string
system_storage_name_get200_response_instance = SystemStorageNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemStorageNameGet200Response.to_json())

# convert the object into a dict
system_storage_name_get200_response_dict = system_storage_name_get200_response_instance.to_dict()
# create an instance of SystemStorageNameGet200Response from a dict
system_storage_name_get200_response_from_dict = SystemStorageNameGet200Response.from_dict(system_storage_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


