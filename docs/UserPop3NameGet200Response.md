# UserPop3NameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | POP3 server entry name. | [optional] 
**server** | **str** | Server domain name or IP address. | [optional] 
**port** | **int** | POP3 service port number. | [optional] 
**secure** | **str** | SSL connection.    none:None.    starttls:Use StartTLS.    pop3s:Use POP3 over SSL. | [optional] 
**ssl_min_proto_version** | **str** | Minimum supported protocol version for SSL/TLS connections (default is to follow system global setting).    default:Follow system global setting.    SSLv3:SSLv3.    TLSv1:TLSv1.    TLSv1-1:TLSv1.1.    TLSv1-2:TLSv1.2.    TLSv1-3:TLSv1.3. | [optional] 

## Example

```python
from microlab_fortinet.models.user_pop3_name_get200_response import UserPop3NameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserPop3NameGet200Response from a JSON string
user_pop3_name_get200_response_instance = UserPop3NameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserPop3NameGet200Response.to_json())

# convert the object into a dict
user_pop3_name_get200_response_dict = user_pop3_name_get200_response_instance.to_dict()
# create an instance of UserPop3NameGet200Response from a dict
user_pop3_name_get200_response_from_dict = UserPop3NameGet200Response.from_dict(user_pop3_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


