# WirelessControllerWtpGroupNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | WTP group name. | [optional] 
**platform_type** | **str** | FortiAP models to define the WTP group platform type.    AP-11N:Default 11n AP.    C24JE:FAPC24JE.    421E:FAP421E.    423E:FAP423E.    221E:FAP221E.    222E:FAP222E.    223E:FAP223E.    224E:FAP224E.    231E:FAP231E.    321E:FAP321E.    431F:FAP431F.    431FL:FAP431FL.    432F:FAP432F.    432FR:FAP432FR.    433F:FAP433F.    433FL:FAP433FL.    231F:FAP231F.    231FL:FAP231FL.    234F:FAP234F.    23JF:FAP23JF.    831F:FAP831F.    231G:FAP231G.    233G:FAP233G.    234G:FAP234G.    431G:FAP431G.    432G:FAP432G.    433G:FAP433G.    221K:FAP221K.    231K:FAP231K.    231KD:FAP231KD.    23JK:FAP23JK.    222KL:FAP222KL.    241K:FAP241K.    243K:FAP243K.    244K:FAP244K.    441K:FAP441K.    435K:FAP435K.    443K:FAP443K.    U421E:FAPU421EV.    U422EV:FAPU422EV.    U423E:FAPU423EV.    U221EV:FAPU221EV.    U223EV:FAPU223EV.    U24JEV:FAPU24JEV.    U321EV:FAPU321EV.    U323EV:FAPU323EV.    U431F:FAPU431F.    U433F:FAPU433F.    U231F:FAPU231F.    U234F:FAPU234F.    U432F:FAPU432F.    U231G:FAPU231G.    MVP:FAP MVP. | [optional] 
**ble_major_id** | **int** | Override BLE Major ID. | [optional] 
**wtps** | [**List[WirelessControllerWtpGroupNameGet200ResponseWtpsInner]**](WirelessControllerWtpGroupNameGet200ResponseWtpsInner.md) | WTP list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_group_name_get200_response import WirelessControllerWtpGroupNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpGroupNameGet200Response from a JSON string
wireless_controller_wtp_group_name_get200_response_instance = WirelessControllerWtpGroupNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpGroupNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_wtp_group_name_get200_response_dict = wireless_controller_wtp_group_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerWtpGroupNameGet200Response from a dict
wireless_controller_wtp_group_name_get200_response_from_dict = WirelessControllerWtpGroupNameGet200Response.from_dict(wireless_controller_wtp_group_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


