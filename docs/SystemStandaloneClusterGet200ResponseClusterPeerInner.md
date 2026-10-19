# SystemStandaloneClusterGet200ResponseClusterPeerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sync_id** | **int** | Sync ID. | [optional] 
**peervd** | **str** | VDOM that contains the session synchronization link interface on the peer unit. Usually both peers would have the same peervd. | [optional] 
**peerip** | **str** | IP address of the interface on the peer unit that is used for the session synchronization link. | [optional] 
**syncvd** | [**List[SystemSnmpCommunityIdGet200ResponseVdomsInner]**](SystemSnmpCommunityIdGet200ResponseVdomsInner.md) | Sessions from these VDOMs are synchronized using this session synchronization configuration. | [optional] 
**down_intfs_before_sess_sync** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | List of interfaces to be turned down before session synchronization is complete. | [optional] 
**hb_interval** | **int** | Heartbeat interval (1 - 20 (100*ms). Increase to reduce false positives. | [optional] 
**hb_lost_threshold** | **int** | Lost heartbeat threshold (1 - 60). Increase to reduce false positives. | [optional] 
**ipsec_tunnel_sync** | **str** | Enable/disable IPsec tunnel synchronization.    enable:Enable IPsec tunnel synchronization.    disable:Disable IPsec tunnel synchronization. | [optional] 
**secondary_add_ipsec_routes** | **str** | Enable/disable IKE route announcement on the backup unit.    enable:Add IKE routes to the backup unit.    disable:Do not add IKE routes to the backup unit. | [optional] 
**session_sync_filter** | [**List[SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner]**](SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner.md) | Add one or more filters if you only want to synchronize some sessions. Use the filter to configure the types of sessions to synchronize. | [optional] 

## Example

```python
from microlab_fortinet.models.system_standalone_cluster_get200_response_cluster_peer_inner import SystemStandaloneClusterGet200ResponseClusterPeerInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStandaloneClusterGet200ResponseClusterPeerInner from a JSON string
system_standalone_cluster_get200_response_cluster_peer_inner_instance = SystemStandaloneClusterGet200ResponseClusterPeerInner.from_json(json)
# print the JSON string representation of the object
print(SystemStandaloneClusterGet200ResponseClusterPeerInner.to_json())

# convert the object into a dict
system_standalone_cluster_get200_response_cluster_peer_inner_dict = system_standalone_cluster_get200_response_cluster_peer_inner_instance.to_dict()
# create an instance of SystemStandaloneClusterGet200ResponseClusterPeerInner from a dict
system_standalone_cluster_get200_response_cluster_peer_inner_from_dict = SystemStandaloneClusterGet200ResponseClusterPeerInner.from_dict(system_standalone_cluster_get200_response_cluster_peer_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


