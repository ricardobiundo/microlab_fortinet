# SystemEmailServerGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Use FortiGuard Message service or custom email server.    custom:Use custom email server. | [optional] 
**server** | **str** | SMTP server IP address or hostname. | [optional] 
**port** | **int** | SMTP server port. | [optional] 
**source_ip** | **str** | SMTP server IPv4 source IP. | [optional] 
**source_ip6** | **str** | SMTP server IPv6 source IP. | [optional] 
**authenticate** | **str** | Enable/disable authentication.    enable:Enable authentication.    disable:Disable authentication. | [optional] 
**validate_server** | **str** | Enable/disable validation of server certificate.    enable:Enable validation of server certificate.    disable:Disable validation of server certificate. | [optional] 
**username** | **str** | SMTP server user name for authentication. | [optional] 
**password** | **str** | SMTP server user password for authentication. | [optional] 
**security** | **str** | Connection security used by the email server.    none:None.    starttls:STARTTLS.    smtps:SSL/TLS. | [optional] 
**ssl_min_proto_version** | **str** | Minimum supported protocol version for SSL/TLS connections (default is to follow system global setting).    default:Follow system global setting.    SSLv3:SSLv3.    TLSv1:TLSv1.    TLSv1-1:TLSv1.1.    TLSv1-2:TLSv1.2.    TLSv1-3:TLSv1.3. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_email_server_get200_response import SystemEmailServerGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemEmailServerGet200Response from a JSON string
system_email_server_get200_response_instance = SystemEmailServerGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemEmailServerGet200Response.to_json())

# convert the object into a dict
system_email_server_get200_response_dict = system_email_server_get200_response_instance.to_dict()
# create an instance of SystemEmailServerGet200Response from a dict
system_email_server_get200_response_from_dict = SystemEmailServerGet200Response.from_dict(system_email_server_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


