# SystemSpeedTestScheduleInterfaceGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interface** | **str** | Interface name. | [optional] 
**status** | **str** | Enable/disable scheduled speed test.    disable:Disable scheduled speed test.    enable:Enable scheduled speed test. | [optional] 
**diffserv** | **str** | DSCP used for speed test. | [optional] 
**server_name** | **str** | Speed test server name in system.speed-test-server list or leave it as empty to choose default server \&quot;FTNT_Auto\&quot;. | [optional] 
**mode** | **str** | Protocol Auto(default), TCP or UDP used for speed test.    UDP:Protocol UDP for speed test.    TCP:Protocol TCP for speed test.    Auto:Dynamically selects TCP or UDP based on the speed test setting | [optional] 
**schedules** | [**List[SystemSpeedTestScheduleInterfaceGet200ResponseSchedulesInner]**](SystemSpeedTestScheduleInterfaceGet200ResponseSchedulesInner.md) | Schedules for the interface. | [optional] 
**dynamic_server** | **str** | Enable/disable dynamic server option.    disable:Disable dynamic server.    enable:Enable dynamic server.The speed test server will be found automatically. | [optional] 
**ctrl_port** | **int** | Port of the controller to get access token. | [optional] 
**server_port** | **int** | Port of the server to run speed test. | [optional] 
**update_shaper** | **str** | Set egress shaper based on the test result.    disable:Disable updating egress shaper.    local:Update local-side egress shaper.    remote:Update remote-side egress shaper.    both:Update both local-side and remote-side egress shaper. | [optional] 
**update_inbandwidth** | **str** | Enable/disable bypassing interface&#39;s inbound bandwidth setting.    disable:Honor interface&#39;s inbandwidth shaping.    enable:Ignore interface&#39;s inbandwidth shaping. | [optional] 
**update_outbandwidth** | **str** | Enable/disable bypassing interface&#39;s outbound bandwidth setting.    disable:Honor interface&#39;s outbandwidth shaping.    enable:Ignore updating interface&#39;s outbandwidth shaping. | [optional] 
**update_interface_shaping** | **str** | Enable/disable using the speedtest results as reference for interface shaping (overriding configured in/outbandwidth).    disable:Disable updating interface shaping.    enable:Enable updating interface shaping. | [optional] 
**update_inbandwidth_maximum** | **int** | Maximum downloading bandwidth (kbps) to be used in a speed test. | [optional] 
**update_inbandwidth_minimum** | **int** | Minimum downloading bandwidth (kbps) to be considered effective. | [optional] 
**update_outbandwidth_maximum** | **int** | Maximum uploading bandwidth (kbps) to be used in a speed test. | [optional] 
**update_outbandwidth_minimum** | **int** | Minimum uploading bandwidth (kbps) to be considered effective. | [optional] 
**expected_inbandwidth_minimum** | **int** | Set the minimum inbandwidth threshold for applying speedtest results on shaping-profile. | [optional] 
**expected_inbandwidth_maximum** | **int** | Set the maximum inbandwidth threshold for applying speedtest results on shaping-profile. | [optional] 
**expected_outbandwidth_minimum** | **int** | Set the minimum outbandwidth threshold for applying speedtest results on shaping-profile. | [optional] 
**expected_outbandwidth_maximum** | **int** | Set the maximum outbandwidth threshold for applying speedtest results on shaping-profile. | [optional] 
**retries** | **int** | Maximum number of times the FortiGate unit will attempt to contact the same server before considering the speed test has failed (1 - 10, default &#x3D; 5). | [optional] 
**retry_pause** | **int** | Number of seconds the FortiGate pauses between successive speed tests before trying a different server (60 - 3600, default &#x3D; 300). | [optional] 

## Example

```python
from microlab_fortinet.models.system_speed_test_schedule_interface_get200_response import SystemSpeedTestScheduleInterfaceGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSpeedTestScheduleInterfaceGet200Response from a JSON string
system_speed_test_schedule_interface_get200_response_instance = SystemSpeedTestScheduleInterfaceGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSpeedTestScheduleInterfaceGet200Response.to_json())

# convert the object into a dict
system_speed_test_schedule_interface_get200_response_dict = system_speed_test_schedule_interface_get200_response_instance.to_dict()
# create an instance of SystemSpeedTestScheduleInterfaceGet200Response from a dict
system_speed_test_schedule_interface_get200_response_from_dict = SystemSpeedTestScheduleInterfaceGet200Response.from_dict(system_speed_test_schedule_interface_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


