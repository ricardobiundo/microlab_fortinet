# WirelessControllerBleProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Bluetooth Low Energy profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**advertising** | **str** | Advertising type.    ibeacon:iBeacon advertising.    eddystone-uid:Eddystone UID advertising.    eddystone-url:Eddystone URL advertising. | [optional] 
**ibeacon_uuid** | **str** | Universally Unique Identifier (UUID; automatically assigned but can be manually reset). | [optional] 
**major_id** | **int** | Major ID. | [optional] 
**minor_id** | **int** | Minor ID. | [optional] 
**eddystone_namespace** | **str** | Eddystone namespace ID. | [optional] 
**eddystone_instance** | **str** | Eddystone instance ID. | [optional] 
**eddystone_url** | **str** | Eddystone URL. | [optional] 
**txpower** | **str** | Transmit power level (default &#x3D; 0).    0:Transmit power level 0 (-21 dBm)    1:Transmit power level 1 (-18 dBm)    2:Transmit power level 2 (-15 dBm)    3:Transmit power level 3 (-12 dBm)    4:Transmit power level 4 (-9 dBm)    5:Transmit power level 5 (-6 dBm)    6:Transmit power level 6 (-3 dBm)    7:Transmit power level 7 (0 dBm)    8:Transmit power level 8 (1 dBm)    9:Transmit power level 9 (2 dBm)    10:Transmit power level 10 (3 dBm)    11:Transmit power level 11 (4 dBm)    12:Transmit power level 12 (5 dBm)    13:Transmit power level 13 (8 dBm)    14:Transmit power level 14 (11 dBm)    15:Transmit power level 15 (14 dBm)    16:Transmit power level 16 (17 dBm)    17:Transmit power level 17 (20 dBm) | [optional] 
**beacon_interval** | **int** | Beacon interval (default &#x3D; 100 msec). | [optional] 
**ble_scanning** | **str** | Enable/disable Bluetooth Low Energy (BLE) scanning.    enable:Enable BLE scanning.    disable:Disable BLE scanning. | [optional] 
**scan_type** | **str** | Scan Type (default &#x3D; active).    active:Active BLE scanning.    passive:Passive BLE scanning. | [optional] 
**scan_threshold** | **str** | Minimum signal level/threshold in dBm required for the AP to report detected BLE device (-95 to -20, default &#x3D; -90). | [optional] 
**scan_period** | **int** | Scan Period (default &#x3D; 4000 msec). | [optional] 
**scan_time** | **int** | Scan Time (default &#x3D; 1000 msec). | [optional] 
**scan_interval** | **int** | Scan Interval (default &#x3D; 50 msec). | [optional] 
**scan_window** | **int** | Scan Windows (default &#x3D; 50 msec). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_ble_profile_name_get200_response import WirelessControllerBleProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerBleProfileNameGet200Response from a JSON string
wireless_controller_ble_profile_name_get200_response_instance = WirelessControllerBleProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerBleProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_ble_profile_name_get200_response_dict = wireless_controller_ble_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerBleProfileNameGet200Response from a dict
wireless_controller_ble_profile_name_get200_response_from_dict = WirelessControllerBleProfileNameGet200Response.from_dict(wireless_controller_ble_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


