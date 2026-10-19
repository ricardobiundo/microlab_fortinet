# SystemExternalResourceNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | External resource name. | [optional] 
**uuid** | **UUID** | Universally Unique Identifier (UUID; automatically assigned but can be manually reset). | [optional] 
**status** | **str** | Enable/disable user resource.    enable:Enable user resource.    disable:Disable user resource. | [optional] 
**type** | **str** | User resource type.    category:FortiGuard category.    domain:Domain Name.    malware:Malware hash.    address:Firewall IP address.    mac-address:Firewall MAC address.    data:Data file.    generic-address:Generic addresses. | [optional] 
**namespace** | **str** | Generic external connector address namespace. | [optional] 
**object_array_path** | **str** | JSON Path to array of generic addresses in resource. | [optional] 
**address_name_field** | **str** | JSON Path to address name in generic address entry. | [optional] 
**address_data_field** | **str** | JSON Path to address data in generic address entry. | [optional] 
**address_comment_field** | **str** | JSON Path to address description in generic address entry. | [optional] 
**update_method** | **str** | External resource update method.    feed:FortiGate unit will pull update from the external resource.    push:External Resource update is pushed to the FortiGate unit through the FortiGate unit&#39;s RESTAPI/CLI. | [optional] 
**category** | **int** | User resource category. | [optional] 
**username** | **str** | HTTP basic authentication user name. | [optional] 
**password** | **str** | HTTP basic authentication password. | [optional] 
**client_cert_auth** | **str** | Enable/disable using client certificate for TLS authentication.    enable:Enable using client certificate for TLS authentication.    disable:Disable using client certificate for TLS authentication. | [optional] 
**client_cert** | **str** | Client certificate name. | [optional] 
**comments** | **str** | Comment. | [optional] 
**resource** | **str** | URL of external resource. | [optional] 
**user_agent** | **str** | HTTP User-Agent header (default &#x3D; &#39;curl/7.58.0&#39;). | [optional] 
**server_identity_check** | **str** | Certificate verification option.    none:No certificate verification.    basic:Check server certifcate only.    full:Check server certificate and verify the domain matches in the server certificate. | [optional] 
**refresh_rate** | **int** | Time interval to refresh external resource (1 - 43200 min, default &#x3D; 5 min). | [optional] 
**source_ip** | **str** | Source IPv4 address used to communicate with server. | [optional] 
**source_ip_interface** | **str** | IPv4 Source interface for communication with the server. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_external_resource_name_get200_response import SystemExternalResourceNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemExternalResourceNameGet200Response from a JSON string
system_external_resource_name_get200_response_instance = SystemExternalResourceNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemExternalResourceNameGet200Response.to_json())

# convert the object into a dict
system_external_resource_name_get200_response_dict = system_external_resource_name_get200_response_instance.to_dict()
# create an instance of SystemExternalResourceNameGet200Response from a dict
system_external_resource_name_get200_response_from_dict = SystemExternalResourceNameGet200Response.from_dict(system_external_resource_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


