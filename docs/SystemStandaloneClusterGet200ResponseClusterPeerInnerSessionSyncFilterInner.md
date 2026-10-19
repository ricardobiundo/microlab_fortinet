# SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**srcintf** | **str** | Only sessions from this interface are synchronized. | [optional] 
**dstintf** | **str** | Only sessions to this interface are synchronized. | [optional] 
**srcaddr** | **str** | Only sessions from this IPv4 address are synchronized. | [optional] 
**dstaddr** | **str** | Only sessions to this IPv4 address are synchronized. | [optional] 
**srcaddr6** | **str** | Only sessions from this IPv6 address are synchronized. | [optional] 
**dstaddr6** | **str** | Only sessions to this IPv6 address are synchronized. | [optional] 
**custom_service** | [**List[SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInnerCustomServiceInner]**](SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInnerCustomServiceInner.md) | Only sessions using these custom services are synchronized. Use source and destination port ranges to define these custom services. | [optional] 

## Example

```python
from microlab_fortinet.models.system_standalone_cluster_get200_response_cluster_peer_inner_session_sync_filter_inner import SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner from a JSON string
system_standalone_cluster_get200_response_cluster_peer_inner_session_sync_filter_inner_instance = SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner.from_json(json)
# print the JSON string representation of the object
print(SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner.to_json())

# convert the object into a dict
system_standalone_cluster_get200_response_cluster_peer_inner_session_sync_filter_inner_dict = system_standalone_cluster_get200_response_cluster_peer_inner_session_sync_filter_inner_instance.to_dict()
# create an instance of SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner from a dict
system_standalone_cluster_get200_response_cluster_peer_inner_session_sync_filter_inner_from_dict = SystemStandaloneClusterGet200ResponseClusterPeerInnerSessionSyncFilterInner.from_dict(system_standalone_cluster_get200_response_cluster_peer_inner_session_sync_filter_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


