# UserAdgrpNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**server_name** | **str** | FSSO agent name. | [optional] 
**connector_source** | **str** | FSSO connector source. | [optional] 
**id** | **int** | Group ID. | [optional] 

## Example

```python
from microlab_fortinet.models.user_adgrp_name_get200_response import UserAdgrpNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserAdgrpNameGet200Response from a JSON string
user_adgrp_name_get200_response_instance = UserAdgrpNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserAdgrpNameGet200Response.to_json())

# convert the object into a dict
user_adgrp_name_get200_response_dict = user_adgrp_name_get200_response_instance.to_dict()
# create an instance of UserAdgrpNameGet200Response from a dict
user_adgrp_name_get200_response_from_dict = UserAdgrpNameGet200Response.from_dict(user_adgrp_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


