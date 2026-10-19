# SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**type** | **str** | Type.    username:User Name.    email:Email Address.    profile-name:Profile Name. | [optional] 

## Example

```python
from microlab_fortinet.models.system_saml_get200_response_service_providers_inner_assertion_attributes_inner import SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner from a JSON string
system_saml_get200_response_service_providers_inner_assertion_attributes_inner_instance = SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner.from_json(json)
# print the JSON string representation of the object
print(SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner.to_json())

# convert the object into a dict
system_saml_get200_response_service_providers_inner_assertion_attributes_inner_dict = system_saml_get200_response_service_providers_inner_assertion_attributes_inner_instance.to_dict()
# create an instance of SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner from a dict
system_saml_get200_response_service_providers_inner_assertion_attributes_inner_from_dict = SystemSamlGet200ResponseServiceProvidersInnerAssertionAttributesInner.from_dict(system_saml_get200_response_service_providers_inner_assertion_attributes_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


