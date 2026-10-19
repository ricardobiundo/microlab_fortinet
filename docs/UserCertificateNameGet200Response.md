# UserCertificateNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | User name. | [optional] 
**id** | **int** | User ID. | [optional] 
**status** | **str** | Enable/disable allowing the certificate user to authenticate with the FortiGate unit.    enable:Enable user.    disable:Disable user. | [optional] 
**type** | **str** | Type of certificate authentication method.    single-certificate:Single certificate.    trusted-issuer:Trusted CA issuer. | [optional] 
**common_name** | **str** | Certificate common name. | [optional] 
**issuer** | **str** | CA certificate used for client certificate verification. | [optional] 

## Example

```python
from microlab_fortinet.models.user_certificate_name_get200_response import UserCertificateNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserCertificateNameGet200Response from a JSON string
user_certificate_name_get200_response_instance = UserCertificateNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserCertificateNameGet200Response.to_json())

# convert the object into a dict
user_certificate_name_get200_response_dict = user_certificate_name_get200_response_instance.to_dict()
# create an instance of UserCertificateNameGet200Response from a dict
user_certificate_name_get200_response_from_dict = UserCertificateNameGet200Response.from_dict(user_certificate_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


