# WirelessControllerHotspot20IconNameGet200ResponseIconListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Icon name. | [optional] 
**lang** | **str** | Language code. | [optional] 
**file** | **str** | Icon file. | [optional] 
**type** | **str** | Icon type.    bmp:BMP image.    gif:GIF image.    jpeg:JPEG image.    png:PNG image.    tiff:TIFF image. | [optional] 
**width** | **int** | Icon width. | [optional] 
**height** | **int** | Icon height. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_icon_name_get200_response_icon_list_inner import WirelessControllerHotspot20IconNameGet200ResponseIconListInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20IconNameGet200ResponseIconListInner from a JSON string
wireless_controller_hotspot20_icon_name_get200_response_icon_list_inner_instance = WirelessControllerHotspot20IconNameGet200ResponseIconListInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20IconNameGet200ResponseIconListInner.to_json())

# convert the object into a dict
wireless_controller_hotspot20_icon_name_get200_response_icon_list_inner_dict = wireless_controller_hotspot20_icon_name_get200_response_icon_list_inner_instance.to_dict()
# create an instance of WirelessControllerHotspot20IconNameGet200ResponseIconListInner from a dict
wireless_controller_hotspot20_icon_name_get200_response_icon_list_inner_from_dict = WirelessControllerHotspot20IconNameGet200ResponseIconListInner.from_dict(wireless_controller_hotspot20_icon_name_get200_response_icon_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


