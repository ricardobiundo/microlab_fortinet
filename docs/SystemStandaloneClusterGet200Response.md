# SystemStandaloneClusterGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**standalone_group_id** | **int** | Cluster group ID (0 - 255). Must be the same for all members. | [optional] 
**group_member_id** | **int** | Cluster member ID (0 - 15). | [optional] 
**layer2_connection** | **str** | Indicate whether layer 2 connections are present among FGSP members.    available:There exist layer 2 connections among FGSP members.    unavailable:There does not exist layer 2 connection among FGSP members. | [optional] 
**session_sync_dev** | **str** | Offload session-sync process to kernel and sync sessions using connected interface(s) directly. | [optional] 
**encryption** | **str** | Enable/disable encryption when synchronizing sessions.    enable:Enable encryption when synchronizing sessions.    disable:Disable encryption when synchronizing sessions. | [optional] 
**psksecret** | **str** | Pre-shared secret for session synchronization (ASCII string or hexadecimal encoded with a leading 0x). | [optional] 
**asymmetric_traffic_control** | **str** | Asymmetric traffic control mode.    cps-preferred:Connection per second (CPS) preferred.    strict-anti-replay:Strict anti-replay check. | [optional] 
**cluster_peer** | [**List[SystemStandaloneClusterGet200ResponseClusterPeerInner]**](SystemStandaloneClusterGet200ResponseClusterPeerInner.md) | Configure FortiGate Session Life Support Protocol (FGSP) session synchronization. | [optional] 
**monitor_interface** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | Configure a list of interfaces on which to monitor itself. Monitoring is performed on the status of the interface. | [optional] 
**pingsvr_monitor_interface** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | List of pingsvr monitor interface to check for remote IP monitoring. | [optional] 
**monitor_prefix** | [**List[SystemStandaloneClusterGet200ResponseMonitorPrefixInner]**](SystemStandaloneClusterGet200ResponseMonitorPrefixInner.md) | Configure a list of routing prefixes to monitor. | [optional] 
**helper_traffic_bounce** | **str** | Enable/disable helper related traffic bounce.    enable:Enable helper related traffic bounce.    disable:Disable helper related traffic bounce. | [optional] 
**utm_traffic_bounce** | **str** | Enable/disable UTM related traffic bounce.    enable:Enable UTM related traffic bounce.    disable:Disable UTM related traffic bounce. | [optional] 

## Example

```python
from microlab_fortinet.models.system_standalone_cluster_get200_response import SystemStandaloneClusterGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStandaloneClusterGet200Response from a JSON string
system_standalone_cluster_get200_response_instance = SystemStandaloneClusterGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemStandaloneClusterGet200Response.to_json())

# convert the object into a dict
system_standalone_cluster_get200_response_dict = system_standalone_cluster_get200_response_instance.to_dict()
# create an instance of SystemStandaloneClusterGet200Response from a dict
system_standalone_cluster_get200_response_from_dict = SystemStandaloneClusterGet200Response.from_dict(system_standalone_cluster_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


