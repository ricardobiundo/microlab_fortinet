# WirelessControllerQosProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | WiFi QoS profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**uplink** | **int** | Maximum uplink bandwidth for Virtual Access Points (VAPs) (0 - 2097152 Kbps, default &#x3D; 0, 0 means no limit). | [optional] 
**downlink** | **int** | Maximum downlink bandwidth for Virtual Access Points (VAPs) (0 - 2097152 Kbps, default &#x3D; 0, 0 means no limit). | [optional] 
**uplink_sta** | **int** | Maximum uplink bandwidth for clients (0 - 2097152 Kbps, default &#x3D; 0, 0 means no limit). | [optional] 
**downlink_sta** | **int** | Maximum downlink bandwidth for clients (0 - 2097152 Kbps, default &#x3D; 0, 0 means no limit). | [optional] 
**burst** | **str** | Enable/disable client rate burst.    enable:Enable client rate burst.    disable:Disable client rate burst. | [optional] 
**wmm** | **str** | Enable/disable WiFi multi-media (WMM) control.    enable:Enable WiFi multi-media (WMM) control.    disable:Disable WiFi multi-media (WMM) control. | [optional] 
**wmm_uapsd** | **str** | Enable/disable WMM Unscheduled Automatic Power Save Delivery (U-APSD) power save mode.    enable:Enable WMM Unscheduled Automatic Power Save Delivery (U-APSD) power save mode.    disable:Disable WMM Unscheduled Automatic Power Save Delivery (U-APSD) power save mode. | [optional] 
**call_admission_control** | **str** | Enable/disable WMM call admission control.    enable:Enable WMM call admission control.    disable:Disable WMM call admission control. | [optional] 
**call_capacity** | **int** | Maximum number of Voice over WLAN (VoWLAN) phones allowed (0 - 60, default &#x3D; 10). | [optional] 
**bandwidth_admission_control** | **str** | Enable/disable WMM bandwidth admission control.    enable:Enable WMM bandwidth admission control.    disable:Disable WMM bandwidth admission control. | [optional] 
**bandwidth_capacity** | **int** | Maximum bandwidth capacity allowed (1 - 600000 Kbps, default &#x3D; 2000). | [optional] 
**dscp_wmm_mapping** | **str** | Enable/disable Differentiated Services Code Point (DSCP) mapping.    enable:Enable Differentiated Services Code Point (DSCP) mapping.    disable:Disable Differentiated Services Code Point (DSCP) mapping. | [optional] 
**dscp_wmm_vo** | [**List[WirelessControllerQosProfileNameGet200ResponseDscpWmmVoInner]**](WirelessControllerQosProfileNameGet200ResponseDscpWmmVoInner.md) | DSCP mapping for voice access (default &#x3D; 48 56). | [optional] 
**dscp_wmm_vi** | [**List[WirelessControllerQosProfileNameGet200ResponseDscpWmmVoInner]**](WirelessControllerQosProfileNameGet200ResponseDscpWmmVoInner.md) | DSCP mapping for video access (default &#x3D; 32 40). | [optional] 
**dscp_wmm_be** | [**List[WirelessControllerQosProfileNameGet200ResponseDscpWmmVoInner]**](WirelessControllerQosProfileNameGet200ResponseDscpWmmVoInner.md) | DSCP mapping for best effort access (default &#x3D; 0 24). | [optional] 
**dscp_wmm_bk** | [**List[WirelessControllerQosProfileNameGet200ResponseDscpWmmVoInner]**](WirelessControllerQosProfileNameGet200ResponseDscpWmmVoInner.md) | DSCP mapping for background access (default &#x3D; 8 16). | [optional] 
**wmm_dscp_marking** | **str** | Enable/disable WMM Differentiated Services Code Point (DSCP) marking.    enable:Enable WMM Differentiated Services Code Point (DSCP) marking.    disable:Disable WMM Differentiated Services Code Point (DSCP) marking. | [optional] 
**wmm_vo_dscp** | **int** | DSCP marking for voice access (default &#x3D; 48). | [optional] 
**wmm_vi_dscp** | **int** | DSCP marking for video access (default &#x3D; 32). | [optional] 
**wmm_be_dscp** | **int** | DSCP marking for best effort access (default &#x3D; 0). | [optional] 
**wmm_bk_dscp** | **int** | DSCP marking for background access (default &#x3D; 8). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_qos_profile_name_get200_response import WirelessControllerQosProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerQosProfileNameGet200Response from a JSON string
wireless_controller_qos_profile_name_get200_response_instance = WirelessControllerQosProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerQosProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_qos_profile_name_get200_response_dict = wireless_controller_qos_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerQosProfileNameGet200Response from a dict
wireless_controller_qos_profile_name_get200_response_from_dict = WirelessControllerQosProfileNameGet200Response.from_dict(wireless_controller_qos_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


