# WirelessControllerRegionNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | FortiAP region name. | [optional] 
**comments** | **str** | Comments. | [optional] 
**grayscale** | **str** | Region image grayscale.    enable:Enable region image grayscale.    disable:Disable region image grayscale. | [optional] 
**opacity** | **int** | Region image opacity (0 - 100). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_region_name_get200_response import WirelessControllerRegionNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerRegionNameGet200Response from a JSON string
wireless_controller_region_name_get200_response_instance = WirelessControllerRegionNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerRegionNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_region_name_get200_response_dict = wireless_controller_region_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerRegionNameGet200Response from a dict
wireless_controller_region_name_get200_response_from_dict = WirelessControllerRegionNameGet200Response.from_dict(wireless_controller_region_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


