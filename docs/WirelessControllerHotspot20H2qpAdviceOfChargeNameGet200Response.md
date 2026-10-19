# WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Plan name. | [optional] 
**aoc_list** | [**List[WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner]**](WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner.md) | AOC list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response import WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200Response from a JSON string
wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_instance = WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_dict = wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200Response from a dict
wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_from_dict = WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200Response.from_dict(wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


