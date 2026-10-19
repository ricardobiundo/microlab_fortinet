# SystemMobileTunnelNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Tunnel name. | [optional] 
**status** | **str** | Enable/disable this mobile tunnel.    disable:Disable this mobile tunnel.    enable:Enable this mobile tunnel. | [optional] 
**roaming_interface** | **str** | Select the associated interface name from available options. | [optional] 
**home_agent** | **str** | IPv4 address of the NEMO HA (Format: xxx.xxx.xxx.xxx). | [optional] 
**home_address** | **str** | Home IP address (Format: xxx.xxx.xxx.xxx). | [optional] 
**renew_interval** | **int** | Time before lifetime expiration to send NMMO HA re-registration (5 - 60, default &#x3D; 60). | [optional] 
**lifetime** | **int** | NMMO HA registration request lifetime (180 - 65535 sec, default &#x3D; 65535). | [optional] 
**reg_interval** | **int** | NMMO HA registration interval (5 - 300, default &#x3D; 5). | [optional] 
**reg_retry** | **int** | Maximum number of NMMO HA registration retries (1 to 30, default &#x3D; 3). | [optional] 
**n_mhae_spi** | **int** | NEMO authentication SPI (default: 256). | [optional] 
**n_mhae_key_type** | **str** | NEMO authentication key type (ASCII or base64).    ascii:The authentication key is an ASCII string.    base64:The authentication key is Base64 encoded. | [optional] 
**n_mhae_key** | **str** | NEMO authentication key. | [optional] 
**hash_algorithm** | **str** | Hash Algorithm (Keyed MD5).    hmac-md5:Keyed MD5. | [optional] 
**tunnel_mode** | **str** | NEMO tunnel mode (GRE tunnel).    gre:GRE tunnel. | [optional] 
**network** | [**List[SystemMobileTunnelNameGet200ResponseNetworkInner]**](SystemMobileTunnelNameGet200ResponseNetworkInner.md) | NEMO network configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.system_mobile_tunnel_name_get200_response import SystemMobileTunnelNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemMobileTunnelNameGet200Response from a JSON string
system_mobile_tunnel_name_get200_response_instance = SystemMobileTunnelNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemMobileTunnelNameGet200Response.to_json())

# convert the object into a dict
system_mobile_tunnel_name_get200_response_dict = system_mobile_tunnel_name_get200_response_instance.to_dict()
# create an instance of SystemMobileTunnelNameGet200Response from a dict
system_mobile_tunnel_name_get200_response_from_dict = SystemMobileTunnelNameGet200Response.from_dict(system_mobile_tunnel_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


