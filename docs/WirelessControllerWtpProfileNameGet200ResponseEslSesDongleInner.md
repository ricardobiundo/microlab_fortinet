# WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**compliance_level** | **str** | Compliance levels for the ESL solution integration (default &#x3D; compliance-level-2).    compliance-level-2:Compliance Level 2 - Full Cloud Support, IoT and Fast-Response. | [optional] 
**scd_enable** | **str** | Enable/disable ESL SES-imagotag Serial Communication Daemon (SCD) (default &#x3D; disable).    enable:Enable ESL SES-imagotag SCD.    disable:Disable ESL SES-imagotag SCD. | [optional] 
**esl_channel** | **str** | ESL SES-imagotag dongle channel (default &#x3D; 127).    -1:No esl-channel is set.    0:ESL channel 0.    1:ESL channel 1.    2:ESL channel 2.    3:ESL channel 3.    4:ESL channel 4.    5:ESL channel 5.    6:ESL channel 6.    7:ESL channel 7.    8:ESL channel 8.    9:ESL channel 9.    10:ESL channel 10.    127:Managed channel enabled, indicates that the APC (server) is setting the esl-channel via the slot channel | [optional] 
**output_power** | **str** | ESL SES-imagotag dongle output power (default &#x3D; A).    a:About 15mW.    b:About 7mW.    c:About 5mW.    d:About 1mW.    e:About 13mW.    f:About 10mW.    g:About 3mW.    h:About 2mW. | [optional] 
**apc_addr_type** | **str** | ESL SES-imagotag APC address type (default &#x3D; fqdn).    fqdn:Fully Qualified Domain Name address.    ip:IPv4 address. | [optional] 
**apc_fqdn** | **str** | FQDN of ESL SES-imagotag Access Point Controller (APC). | [optional] 
**apc_ip** | **str** | IP address of ESL SES-imagotag Access Point Controller (APC). | [optional] 
**apc_port** | **int** | Port of ESL SES-imagotag Access Point Controller (APC). | [optional] 
**coex_level** | **str** | ESL SES-imagotag dongle coexistence level (default &#x3D; none).    none:No support for coexistence of USB-Dongle with WiFi AP. | [optional] 
**tls_cert_verification** | **str** | Enable/disable TLS certificate verification (default &#x3D; enable).    enable:Enable TLS Certificate verification.    disable:Disable TLS Certificate verification. | [optional] 
**tls_fqdn_verification** | **str** | Enable/disable TLS FQDN verification (default &#x3D; disable).    enable:Enable TLS FQDN verification.    disable:Disable TLS FQDN verification. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_profile_name_get200_response_esl_ses_dongle_inner import WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner from a JSON string
wireless_controller_wtp_profile_name_get200_response_esl_ses_dongle_inner_instance = WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner.to_json())

# convert the object into a dict
wireless_controller_wtp_profile_name_get200_response_esl_ses_dongle_inner_dict = wireless_controller_wtp_profile_name_get200_response_esl_ses_dongle_inner_instance.to_dict()
# create an instance of WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner from a dict
wireless_controller_wtp_profile_name_get200_response_esl_ses_dongle_inner_from_dict = WirelessControllerWtpProfileNameGet200ResponseEslSesDongleInner.from_dict(wireless_controller_wtp_profile_name_get200_response_esl_ses_dongle_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


