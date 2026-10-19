# WirelessControllerInterControllerGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inter_controller_mode** | **str** | Configure inter-controller mode (disable, l2-roaming, 1+1, default &#x3D; disable).    disable:Disable inter-controller mode.    l2-roaming:Enable layer 2 roaming support between inter-controllers.    1+1:Enable 1+1 fast failover mode. | [optional] 
**l3_roaming** | **str** | Enable/disable layer 3 roaming (default &#x3D; disable).    enable:Enable layer 3 roaming.    disable:Disable layer 3 roaming. | [optional] 
**inter_controller_key** | **str** | Secret key for inter-controller communications. | [optional] 
**inter_controller_pri** | **str** | Configure inter-controller&#39;s priority (primary or secondary, default &#x3D; primary).    primary:Primary fast failover mode.    secondary:Secondary fast failover mode. | [optional] 
**fast_failover_max** | **int** | Maximum number of retransmissions for fast failover HA messages between peer wireless controllers (3 - 64, default &#x3D; 10). | [optional] 
**fast_failover_wait** | **int** | Minimum wait time before an AP transitions from secondary controller to primary controller (10 - 86400 sec, default &#x3D; 10). | [optional] 
**inter_controller_peer** | [**List[WirelessControllerInterControllerGet200ResponseInterControllerPeerInner]**](WirelessControllerInterControllerGet200ResponseInterControllerPeerInner.md) | Fast failover peer wireless controller list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_inter_controller_get200_response import WirelessControllerInterControllerGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerInterControllerGet200Response from a JSON string
wireless_controller_inter_controller_get200_response_instance = WirelessControllerInterControllerGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerInterControllerGet200Response.to_json())

# convert the object into a dict
wireless_controller_inter_controller_get200_response_dict = wireless_controller_inter_controller_get200_response_instance.to_dict()
# create an instance of WirelessControllerInterControllerGet200Response from a dict
wireless_controller_inter_controller_get200_response_from_dict = WirelessControllerInterControllerGet200Response.from_dict(wireless_controller_inter_controller_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


