# UserExchangeNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | MS Exchange server entry name. | [optional] 
**server_name** | **str** | MS Exchange server hostname. | [optional] 
**domain_name** | **str** | MS Exchange server fully qualified domain name. | [optional] 
**username** | **str** | User name used to sign in to the server. Must have proper permissions for service. | [optional] 
**password** | **str** | Password for the specified username. | [optional] 
**ip** | **str** | Server IPv4 address. | [optional] 
**connect_protocol** | **str** | Connection protocol used to connect to MS Exchange service.    rpc-over-tcp:Connect using RPC-over-TCP. Use for MS Exchange 2010 and earlier versions. Supported in MS Exchange 2013.    rpc-over-http:Connect using RPC-over-HTTP. Use for MS Exchange 2016 and later versions. Supported in MS Exchange 2013.    rpc-over-https:Connect using RPC-over-HTTPS. Use for MS Exchange 2016 and later versions. Supported in MS Exchange 2013. | [optional] 
**validate_server_certificate** | **str** | Enable/disable exchange server certificate validation.    disable:Disable validation of server certificate.    enable:Enable validation of server certificate. | [optional] 
**auth_type** | **str** | Authentication security type used for the RPC protocol layer.    spnego:Negotiate authentication.    ntlm:NTLM authentication.    kerberos:Kerberos authentication. | [optional] 
**auth_level** | **str** | Authentication security level used for the RPC protocol layer.    connect:RPC authentication level &#39;connect&#39;.    call:RPC authentication level &#39;call&#39;.    packet:RPC authentication level &#39;packet&#39;.    integrity:RPC authentication level &#39;integrity&#39;.    privacy:RPC authentication level &#39;privacy&#39;. | [optional] 
**http_auth_type** | **str** | Authentication security type used for the HTTP transport.    basic:Basic HTTP authentication.    ntlm:NTLM HTTP authentication. | [optional] 
**ssl_min_proto_version** | **str** | Minimum SSL/TLS protocol version for HTTPS transport (default is to follow system global setting).    default:Follow system global setting.    SSLv3:SSLv3.    TLSv1:TLSv1.    TLSv1-1:TLSv1.1.    TLSv1-2:TLSv1.2.    TLSv1-3:TLSv1.3. | [optional] 
**auto_discover_kdc** | **str** | Enable/disable automatic discovery of KDC IP addresses.    enable:Enable automatic discovery of KDC IP addresses.    disable:Disable automatic discovery of KDC IP addresses. | [optional] 
**kdc_ip** | [**List[UserExchangeNameGet200ResponseKdcIpInner]**](UserExchangeNameGet200ResponseKdcIpInner.md) | KDC IPv4 addresses for Kerberos authentication. | [optional] 

## Example

```python
from microlab_fortinet.models.user_exchange_name_get200_response import UserExchangeNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserExchangeNameGet200Response from a JSON string
user_exchange_name_get200_response_instance = UserExchangeNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserExchangeNameGet200Response.to_json())

# convert the object into a dict
user_exchange_name_get200_response_dict = user_exchange_name_get200_response_instance.to_dict()
# create an instance of UserExchangeNameGet200Response from a dict
user_exchange_name_get200_response_from_dict = UserExchangeNameGet200Response.from_dict(user_exchange_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


