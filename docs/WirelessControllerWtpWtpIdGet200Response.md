# WirelessControllerWtpWtpIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**wtp_id** | **str** | WTP ID. | [optional] 
**index** | **int** | Index (0 - 4294967295). | [optional] 
**uuid** | **UUID** | Universally Unique Identifier (UUID; automatically assigned but can be manually reset). | [optional] 
**admin** | **str** | Configure how the FortiGate operating as a wireless controller discovers and manages this WTP, AP or FortiAP.    discovered:FortiGate wireless controller discovers the WTP, AP, or FortiAP though discovery or join request messages.    disable:FortiGate wireless controller is configured to not provide service to this WTP.    enable:FortiGate wireless controller is configured to provide service to this WTP. | [optional] 
**name** | **str** | WTP, AP or FortiAP configuration name. | [optional] 
**location** | **str** | Field for describing the physical location of the WTP, AP or FortiAP. | [optional] 
**comment** | **str** | Comment. | [optional] 
**region** | **str** | Region name WTP is associated with. | [optional] 
**region_x** | **str** | Relative horizontal region coordinate (between 0 and 1). | [optional] 
**region_y** | **str** | Relative vertical region coordinate (between 0 and 1). | [optional] 
**firmware_provision** | **str** | Firmware version to provision to this FortiAP on bootup (major.minor.build, i.e. 6.2.1234). | [optional] 
**firmware_provision_latest** | **str** | Enable/disable one-time automatic provisioning of the latest firmware version.    disable:Do not automatically provision the latest available firmware.    once:Automatically attempt a one-time upgrade to the latest available firmware version. | [optional] 
**wtp_profile** | **str** | WTP profile name to apply to this WTP, AP or FortiAP. | [optional] 
**apcfg_profile** | **str** | AP local configuration profile name. | [optional] 
**bonjour_profile** | **str** | Bonjour profile name. | [optional] 
**ble_major_id** | **int** | Override BLE Major ID. | [optional] 
**ble_minor_id** | **int** | Override BLE Minor ID. | [optional] 
**override_led_state** | **str** | Enable to override the profile LED state setting for this FortiAP. You must enable this option to use the led-state command to turn off the FortiAP&#39;s LEDs.    enable:Override the WTP profile LED state.    disable:Use the WTP profile LED state. | [optional] 
**led_state** | **str** | Enable to allow the FortiAPs LEDs to light. Disable to keep the LEDs off. You may want to keep the LEDs off so they are not distracting in low light areas etc.    enable:Allow the LEDs on this FortiAP to light.    disable:Keep the LEDs on this FortiAP off. | [optional] 
**override_wan_port_mode** | **str** | Enable/disable overriding the wan-port-mode in the WTP profile.    enable:Override the WTP profile wan-port-mode.    disable:Use the wan-port-mode in the WTP profile. | [optional] 
**wan_port_mode** | **str** | Enable/disable using the FortiAP WAN port as a LAN port.    wan-lan:Use the FortiAP WAN port as a LAN port.    wan-only:Do not use the WAN port as a LAN port. | [optional] 
**override_ip_fragment** | **str** | Enable/disable overriding the WTP profile IP fragment prevention setting.    enable:Override the WTP profile IP fragment prevention setting.    disable:Use the WTP profile IP fragment prevention setting. | [optional] 
**ip_fragment_preventing** | **str** | Method(s) by which IP fragmentation is prevented for control and data packets through CAPWAP tunnel (default &#x3D; tcp-mss-adjust).    tcp-mss-adjust:TCP maximum segment size adjustment.    icmp-unreachable:Drop packet and send ICMP Destination Unreachable | [optional] 
**tun_mtu_uplink** | **int** | The maximum transmission unit (MTU) of uplink CAPWAP tunnel (576 - 1500 bytes or 0; 0 means the local MTU of FortiAP; default &#x3D; 0). | [optional] 
**tun_mtu_downlink** | **int** | The MTU of downlink CAPWAP tunnel (576 - 1500 bytes or 0; 0 means the local MTU of FortiAP; default &#x3D; 0). | [optional] 
**override_split_tunnel** | **str** | Enable/disable overriding the WTP profile split tunneling setting.    enable:Override the WTP profile split tunneling setting.    disable:Use the WTP profile split tunneling setting. | [optional] 
**split_tunneling_acl_path** | **str** | Split tunneling ACL path is local/tunnel.    tunnel:Split tunneling ACL list traffic will be tunnel.    local:Split tunneling ACL list traffic will be local NATed. | [optional] 
**split_tunneling_acl_local_ap_subnet** | **str** | Enable/disable automatically adding local subnetwork of FortiAP to split-tunneling ACL (default &#x3D; disable).    enable:Enable automatically adding local subnetwork of FortiAP to split-tunneling ACL.    disable:Disable automatically adding local subnetwork of FortiAP to split-tunneling ACL. | [optional] 
**split_tunneling_acl** | [**List[WirelessControllerWtpWtpIdGet200ResponseSplitTunnelingAclInner]**](WirelessControllerWtpWtpIdGet200ResponseSplitTunnelingAclInner.md) | Split tunneling ACL filter list. | [optional] 
**override_lan** | **str** | Enable to override the WTP profile LAN port setting.    enable:Override the WTP profile LAN port setting.    disable:Use the WTP profile LAN port setting. | [optional] 
**lan** | [**List[WirelessControllerWtpWtpIdGet200ResponseLanInner]**](WirelessControllerWtpWtpIdGet200ResponseLanInner.md) | WTP LAN port mapping. | [optional] 
**override_allowaccess** | **str** | Enable to override the WTP profile management access configuration.    enable:Override the WTP profile management access configuration.    disable:Use the WTP profile management access configuration. | [optional] 
**allowaccess** | **str** | Control management access to the managed WTP, FortiAP, or AP. Separate entries with a space.    https:HTTPS access.    ssh:SSH access.    snmp:SNMP access. | [optional] 
**override_login_passwd_change** | **str** | Enable to override the WTP profile login-password (administrator password) setting.    enable:Override the WTP profile login-password (administrator password) setting.    disable:Use the the WTP profile login-password (administrator password) setting. | [optional] 
**login_passwd_change** | **str** | Change or reset the administrator password of a managed WTP, FortiAP or AP (yes, default, or no, default &#x3D; no).    yes:Change the managed WTP, FortiAP or AP&#39;s administrator password. Use the login-password option to set the password.    default:Keep the managed WTP, FortiAP or AP&#39;s administrator password set to the factory default.    no:Do not change the managed WTP, FortiAP or AP&#39;s administrator password. | [optional] 
**login_passwd** | **str** | Set the managed WTP, FortiAP, or AP&#39;s administrator password. | [optional] 
**override_default_mesh_root** | **str** | Enable to override the WTP profile default mesh root SSID setting.    enable:Override the WTP profile default mesh root SSID setting.    disable:Use the WTP profile default mesh root SSID setting. | [optional] 
**default_mesh_root** | **str** | Configure default mesh root SSID when it is not included by radio&#39;s SSID configuration.    enable:Enable default mesh root SSID if it is not included by radio&#39;s SSID configuration.    disable:Do not enable default mesh root SSID if it is not included by radio&#39;s SSID configuration. | [optional] 
**radio_1** | [**List[WirelessControllerWtpWtpIdGet200ResponseRadio1Inner]**](WirelessControllerWtpWtpIdGet200ResponseRadio1Inner.md) | Configuration options for radio 1. | [optional] 
**radio_2** | [**List[WirelessControllerWtpWtpIdGet200ResponseRadio2Inner]**](WirelessControllerWtpWtpIdGet200ResponseRadio2Inner.md) | Configuration options for radio 2. | [optional] 
**radio_3** | [**List[WirelessControllerWtpWtpIdGet200ResponseRadio3Inner]**](WirelessControllerWtpWtpIdGet200ResponseRadio3Inner.md) | Configuration options for radio 3. | [optional] 
**radio_4** | [**List[WirelessControllerWtpWtpIdGet200ResponseRadio4Inner]**](WirelessControllerWtpWtpIdGet200ResponseRadio4Inner.md) | Configuration options for radio 4. | [optional] 
**image_download** | **str** | Enable/disable WTP image download.    enable:Enable WTP image download at join time.    disable:Disable WTP image download at join time. | [optional] 
**mesh_bridge_enable** | **str** | Enable/disable mesh Ethernet bridge when WTP is configured as a mesh branch/leaf AP.    default:Use mesh Ethernet bridge local setting on the WTP.    enable:Turn on mesh Ethernet bridge on the WTP.    disable:Turn off mesh Ethernet bridge on the WTP. | [optional] 
**purdue_level** | **str** | Purdue Level of this WTP.    1:Level 1 - Basic Control    1.5:Level 1.5    2:Level 2 - Area Supervisory Control    2.5:Level 2.5    3:Level 3 - Operations &amp; Control    3.5:Level 3.5    4:Level 4 - Business Planning &amp; Logistics    5:Level 5 - Enterprise Network    5.5:Level 5.5 | [optional] 
**coordinate_latitude** | **str** | WTP latitude coordinate. | [optional] 
**coordinate_longitude** | **str** | WTP longitude coordinate. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_wtp_id_get200_response import WirelessControllerWtpWtpIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpWtpIdGet200Response from a JSON string
wireless_controller_wtp_wtp_id_get200_response_instance = WirelessControllerWtpWtpIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpWtpIdGet200Response.to_json())

# convert the object into a dict
wireless_controller_wtp_wtp_id_get200_response_dict = wireless_controller_wtp_wtp_id_get200_response_instance.to_dict()
# create an instance of WirelessControllerWtpWtpIdGet200Response from a dict
wireless_controller_wtp_wtp_id_get200_response_from_dict = WirelessControllerWtpWtpIdGet200Response.from_dict(wireless_controller_wtp_wtp_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


