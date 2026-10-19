# SwitchControllerPtpProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Profile name. | [optional] 
**description** | **str** | Description. | [optional] 
**mode** | **str** | Select PTP mode.    transparent-e2e:End-to-end transparent clock.    transparent-p2p:Peer-to-peer transparent clock. | [optional] 
**ptp_profile** | **str** | Configure PTP power profile.    C37.238-2017:C37.238-2017 power profile. | [optional] 
**transport** | **str** | Configure PTP transport mode.    l2-mcast:L2 multicast. | [optional] 
**domain** | **int** | Configure PTP domain value (0 - 255, default &#x3D; 254). | [optional] 
**pdelay_req_interval** | **str** | Configure PTP peer delay request interval.    1sec:1 sec.    2sec:2 sec.    4sec:4 sec.    8sec:8 sec.    16sec:16 sec.    32sec:32 sec. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_ptp_profile_name_get200_response import SwitchControllerPtpProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerPtpProfileNameGet200Response from a JSON string
switch_controller_ptp_profile_name_get200_response_instance = SwitchControllerPtpProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerPtpProfileNameGet200Response.to_json())

# convert the object into a dict
switch_controller_ptp_profile_name_get200_response_dict = switch_controller_ptp_profile_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerPtpProfileNameGet200Response from a dict
switch_controller_ptp_profile_name_get200_response_from_dict = SwitchControllerPtpProfileNameGet200Response.from_dict(switch_controller_ptp_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


