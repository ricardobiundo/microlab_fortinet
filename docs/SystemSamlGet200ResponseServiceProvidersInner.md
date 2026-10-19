# SystemSamlGet200ResponseServiceProvidersInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**prefix** | **str** | Prefix. | [optional] 
**sp_binding_protocol** | **str** | SP binding protocol.    post:HTTP POST binding.    redirect:HTTP Redirect binding. | [optional] 
**sp_cert** | **str** | SP certificate name. | [optional] 
**sp_entity_id** | **str** | SP entity ID. | [optional] 
**sp_single_sign_on_url** | **str** | SP single sign-on URL. | [optional] 
**sp_single_logout_url** | **str** | SP single logout URL. | [optional] 
**sp_portal_url** | **str** | SP portal URL. | [optional] 
**idp_entity_id** | **str** | IDP entity ID. | [optional] 
**idp_single_sign_on_url** | **str** | IDP single sign-on URL. | [optional] 
**idp_single_logout_url** | **str** | IDP single logout URL. | [optional] 
**assertion_attributes** | [**List[SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner]**](SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner.md) | Customized SAML attributes to send along with assertion. | [optional] 

## Example

```python
from microlab_fortinet.models.system_saml_get200_response_service_providers_inner import SystemSamlGet200ResponseServiceProvidersInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSamlGet200ResponseServiceProvidersInner from a JSON string
system_saml_get200_response_service_providers_inner_instance = SystemSamlGet200ResponseServiceProvidersInner.from_json(json)
# print the JSON string representation of the object
print(SystemSamlGet200ResponseServiceProvidersInner.to_json())

# convert the object into a dict
system_saml_get200_response_service_providers_inner_dict = system_saml_get200_response_service_providers_inner_instance.to_dict()
# create an instance of SystemSamlGet200ResponseServiceProvidersInner from a dict
system_saml_get200_response_service_providers_inner_from_dict = SystemSamlGet200ResponseServiceProvidersInner.from_dict(system_saml_get200_response_service_providers_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


