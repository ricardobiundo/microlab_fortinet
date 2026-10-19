# SystemSamlGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable SAML authentication (default &#x3D; disable).    enable:Enable SAML authentication.    disable:Disable SAML authentication. | [optional] 
**role** | **str** | SAML role.    identity-provider:Identity Provider.    service-provider:Service Provider. | [optional] 
**default_login_page** | **str** | Choose default login page.    normal:Use local login page as default.    sso:Use IdP&#39;s Single Sign-On page as default. | [optional] 
**default_profile** | **str** | Default profile for new SSO admin. | [optional] 
**cert** | **str** | Certificate to sign SAML messages. | [optional] 
**binding_protocol** | **str** | IdP Binding protocol.    post:HTTP POST binding.    redirect:HTTP Redirect binding. | [optional] 
**portal_url** | **str** | SP portal URL. | [optional] 
**entity_id** | **str** | SP entity ID. | [optional] 
**single_sign_on_url** | **str** | SP single sign-on URL. | [optional] 
**single_logout_url** | **str** | SP single logout URL. | [optional] 
**idp_entity_id** | **str** | IDP entity ID. | [optional] 
**idp_single_sign_on_url** | **str** | IDP single sign-on URL. | [optional] 
**idp_single_logout_url** | **str** | IDP single logout URL. | [optional] 
**idp_cert** | **str** | IDP certificate name. | [optional] 
**server_address** | **str** | Server address. | [optional] 
**require_signed_resp_and_asrt** | **str** | Require both response and assertion from IDP to be signed when FGT acts as SP (default &#x3D; disable).    enable:Both response and assertion must be signed and valid.    disable:At least one of response or assertion must be signed and valid. | [optional] 
**tolerance** | **int** | Tolerance to the range of time when the assertion is valid (in minutes). | [optional] 
**life** | **int** | Length of the range of time when the assertion is valid (in minutes). | [optional] 
**service_providers** | [**List[SystemSamlGet200ResponseServiceProvidersInner]**](SystemSamlGet200ResponseServiceProvidersInner.md) | Authorized service providers. | [optional] 

## Example

```python
from microlab_fortinet.models.system_saml_get200_response import SystemSamlGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSamlGet200Response from a JSON string
system_saml_get200_response_instance = SystemSamlGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSamlGet200Response.to_json())

# convert the object into a dict
system_saml_get200_response_dict = system_saml_get200_response_instance.to_dict()
# create an instance of SystemSamlGet200Response from a dict
system_saml_get200_response_from_dict = SystemSamlGet200Response.from_dict(system_saml_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


