# WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Advice of charge ID. | [optional] 
**type** | **str** | Usage charge type.    time-based:Time based usage charge.    volume-based:Volume based usage charge.    time-and-volume-based:Time and volume based usage charge.    unlimited:Unlimited usage. | [optional] 
**nai_realm_encoding** | **str** | NAI realm encoding. | [optional] 
**nai_realm** | **str** | NAI realm list name. | [optional] 
**plan_info** | [**List[WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInnerPlanInfoInner]**](WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInnerPlanInfoInner.md) | Plan info. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_aoc_list_inner import WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner from a JSON string
wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_aoc_list_inner_instance = WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner.to_json())

# convert the object into a dict
wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_aoc_list_inner_dict = wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_aoc_list_inner_instance.to_dict()
# create an instance of WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner from a dict
wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_aoc_list_inner_from_dict = WirelessControllerHotspot20H2qpAdviceOfChargeNameGet200ResponseAocListInner.from_dict(wireless_controller_hotspot20_h2qp_advice_of_charge_name_get200_response_aoc_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


