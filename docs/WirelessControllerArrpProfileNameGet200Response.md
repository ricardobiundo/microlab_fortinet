# WirelessControllerArrpProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | WiFi ARRP profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**selection_period** | **int** | Period in seconds to measure average channel load, noise floor, spectral RSSI (default &#x3D; 3600). | [optional] 
**monitor_period** | **int** | Period in seconds to measure average transmit retries and receive errors (default &#x3D; 300). | [optional] 
**weight_managed_ap** | **int** | Weight in DARRP channel score calculation for managed APs (0 - 2000, default &#x3D; 50). | [optional] 
**weight_rogue_ap** | **int** | Weight in DARRP channel score calculation for rogue APs (0 - 2000, default &#x3D; 10). | [optional] 
**weight_noise_floor** | **int** | Weight in DARRP channel score calculation for noise floor (0 - 2000, default &#x3D; 40). | [optional] 
**weight_channel_load** | **int** | Weight in DARRP channel score calculation for channel load (0 - 2000, default &#x3D; 20). | [optional] 
**weight_spectral_rssi** | **int** | Weight in DARRP channel score calculation for spectral RSSI (0 - 2000, default &#x3D; 40). | [optional] 
**weight_weather_channel** | **int** | Weight in DARRP channel score calculation for weather channel (0 - 2000, default &#x3D; 0). | [optional] 
**weight_dfs_channel** | **int** | Weight in DARRP channel score calculation for DFS channel (0 - 2000, default &#x3D; 0). | [optional] 
**threshold_ap** | **int** | Threshold to reject channel in DARRP channel selection phase 1 due to surrounding APs (0 - 500, default &#x3D; 250). | [optional] 
**threshold_noise_floor** | **str** | Threshold in dBm to reject channel in DARRP channel selection phase 1 due to noise floor (-95 to -20, default &#x3D; -85). | [optional] 
**threshold_channel_load** | **int** | Threshold in percentage to reject channel in DARRP channel selection phase 1 due to channel load (0 - 100, default &#x3D; 60). | [optional] 
**threshold_spectral_rssi** | **str** | Threshold in dBm to reject channel in DARRP channel selection phase 1 due to spectral RSSI (-95 to -20, default &#x3D; -65). | [optional] 
**threshold_tx_retries** | **int** | Threshold in percentage for transmit retries to trigger channel reselection in DARRP monitor stage (0 - 1000, default &#x3D; 300). | [optional] 
**threshold_rx_errors** | **int** | Threshold in percentage for receive errors to trigger channel reselection in DARRP monitor stage (0 - 100, default &#x3D; 50). | [optional] 
**include_weather_channel** | **str** | Enable/disable use of weather channel in DARRP channel selection phase 1 (default &#x3D; enable).    enable:Include weather channel in darrp channel selection phase 1.    disable:Exclude weather channel in darrp channel selection phase 1. | [optional] 
**include_dfs_channel** | **str** | Enable/disable use of DFS channel in DARRP channel selection phase 1 (default &#x3D; enable).    enable:Include DFS channel in darrp channel selection phase 1.    disable:Exclude DFS channel in darrp channel selection phase 1. | [optional] 
**override_darrp_optimize** | **str** | Enable to override setting darrp-optimize and darrp-optimize-schedules (default &#x3D; disable).    enable:Override setting darrp-optimize and darrp-optimize-schedules.    disable:Use setting darrp-optimize and darrp-optimize-schedules. | [optional] 
**darrp_optimize** | **int** | Time for running Distributed Automatic Radio Resource Provisioning (DARRP) optimizations (0 - 86400 sec, default &#x3D; 86400, 0 &#x3D; disable). | [optional] 
**darrp_optimize_schedules** | [**List[WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner]**](WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner.md) | Firewall schedules for DARRP running time. DARRP will run periodically based on darrp-optimize within the schedules. Separate multiple schedule names with a space. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_arrp_profile_name_get200_response import WirelessControllerArrpProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerArrpProfileNameGet200Response from a JSON string
wireless_controller_arrp_profile_name_get200_response_instance = WirelessControllerArrpProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerArrpProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_arrp_profile_name_get200_response_dict = wireless_controller_arrp_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerArrpProfileNameGet200Response from a dict
wireless_controller_arrp_profile_name_get200_response_from_dict = WirelessControllerArrpProfileNameGet200Response.from_dict(wireless_controller_arrp_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


