# WirelessControllerInterControllerGet200ResponseInterControllerPeerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**peer_ip** | **str** | Peer wireless controller&#39;s IP address. | [optional] 
**peer_port** | **int** | Port used by the wireless controller&#39;s for inter-controller communications (1024 - 49150, default &#x3D; 5246). | [optional] 
**peer_priority** | **str** | Peer wireless controller&#39;s priority (primary or secondary, default &#x3D; primary).    primary:Primary fast failover mode.    secondary:Secondary fast failover mode. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_inter_controller_get200_response_inter_controller_peer_inner import WirelessControllerInterControllerGet200ResponseInterControllerPeerInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerInterControllerGet200ResponseInterControllerPeerInner from a JSON string
wireless_controller_inter_controller_get200_response_inter_controller_peer_inner_instance = WirelessControllerInterControllerGet200ResponseInterControllerPeerInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerInterControllerGet200ResponseInterControllerPeerInner.to_json())

# convert the object into a dict
wireless_controller_inter_controller_get200_response_inter_controller_peer_inner_dict = wireless_controller_inter_controller_get200_response_inter_controller_peer_inner_instance.to_dict()
# create an instance of WirelessControllerInterControllerGet200ResponseInterControllerPeerInner from a dict
wireless_controller_inter_controller_get200_response_inter_controller_peer_inner_from_dict = WirelessControllerInterControllerGet200ResponseInterControllerPeerInner.from_dict(wireless_controller_inter_controller_get200_response_inter_controller_peer_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


