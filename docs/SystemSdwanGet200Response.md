# SystemSdwanGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable SD-WAN.    disable:Disable SD-WAN.    enable:Enable SD-WAN. | [optional] 
**load_balance_mode** | **str** | Algorithm or mode to use for load balancing Internet traffic to SD-WAN members.    source-ip-based:Source IP load balancing. All traffic from a source IP is sent to the same interface.    weight-based:Weight-based load balancing. Interfaces with higher weights have higher priority and get more traffic.    usage-based:Usage-based load balancing. All traffic is sent to the first interface on the list. When the bandwidth on that interface exceeds the spill-over limit new traffic is sent to the next interface.    source-dest-ip-based:Source and destination IP load balancing. All traffic from a source IP to a destination IP is sent to the same interface.    measured-volume-based:Volume-based load balancing. Traffic is load balanced based on traffic volume (in bytes). More traffic is sent to interfaces with higher volume ratios. | [optional] 
**speedtest_bypass_routing** | **str** | Enable/disable bypass routing when speedtest on a SD-WAN member.    disable:Disable SD-WAN.    enable:Enable SD-WAN. | [optional] 
**duplication_max_num** | **int** | Maximum number of interface members a packet is duplicated in the SD-WAN zone (2 - 4, default &#x3D; 2; if set to 3, the original packet plus 2 more copies are created). | [optional] 
**duplication_max_discrepancy** | **int** | Maximum discrepancy between two packets for deduplication in milliseconds (250 - 1000, default &#x3D; 250). | [optional] 
**neighbor_hold_down** | **str** | Enable/disable hold switching from the secondary neighbor to the primary neighbor.    enable:Enable hold switching from the secondary neighbor to the primary neighbor.    disable:Disable hold switching from the secondary neighbor to the primary neighbor. | [optional] 
**neighbor_hold_down_time** | **int** | Waiting period in seconds when switching from the secondary neighbor to the primary neighbor when hold-down is disabled. (0 - 10000000, default &#x3D; 0). | [optional] 
**app_perf_log_period** | **int** | Time interval in seconds that application performance logs are generated (0 - 3600, default &#x3D; 0). | [optional] 
**neighbor_hold_boot_time** | **int** | Waiting period in seconds when switching from the primary neighbor to the secondary neighbor from the neighbor start. (0 - 10000000, default &#x3D; 0). | [optional] 
**fail_detect** | **str** | Enable/disable SD-WAN Internet connection status checking (failure detection).    enable:Enable status checking.    disable:Disable status checking. | [optional] 
**fail_alert_interfaces** | [**List[SystemSdwanGet200ResponseFailAlertInterfacesInner]**](SystemSdwanGet200ResponseFailAlertInterfacesInner.md) | Physical interfaces that will be alerted. | [optional] 
**zone** | [**List[SystemSdwanGet200ResponseZoneInner]**](SystemSdwanGet200ResponseZoneInner.md) | Configure SD-WAN zones. | [optional] 
**members** | [**List[SystemSdwanGet200ResponseMembersInner]**](SystemSdwanGet200ResponseMembersInner.md) | FortiGate interfaces added to the SD-WAN. | [optional] 
**health_check** | [**List[SystemSdwanGet200ResponseHealthCheckInner]**](SystemSdwanGet200ResponseHealthCheckInner.md) | SD-WAN status checking or health checking. Identify a server on the Internet and determine how SD-WAN verifies that the FortiGate can communicate with it. | [optional] 
**service** | [**List[SystemSdwanGet200ResponseServiceInner]**](SystemSdwanGet200ResponseServiceInner.md) | Create SD-WAN rules (also called services) to control how sessions are distributed to interfaces in the SD-WAN. | [optional] 
**neighbor** | [**List[SystemSdwanGet200ResponseNeighborInner]**](SystemSdwanGet200ResponseNeighborInner.md) | Create SD-WAN neighbor from BGP neighbor table to control route advertisements according to SLA status. | [optional] 
**duplication** | [**List[SystemSdwanGet200ResponseDuplicationInner]**](SystemSdwanGet200ResponseDuplicationInner.md) | Create SD-WAN duplication rule. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdwan_get200_response import SystemSdwanGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdwanGet200Response from a JSON string
system_sdwan_get200_response_instance = SystemSdwanGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSdwanGet200Response.to_json())

# convert the object into a dict
system_sdwan_get200_response_dict = system_sdwan_get200_response_instance.to_dict()
# create an instance of SystemSdwanGet200Response from a dict
system_sdwan_get200_response_from_dict = SystemSdwanGet200Response.from_dict(system_sdwan_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


