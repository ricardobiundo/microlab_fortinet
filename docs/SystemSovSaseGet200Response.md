# SystemSovSaseGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable Sovereign SASE.    enable:Enable Sovereign SASE.    disable:Disable Sovereign SASE. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sov_sase_get200_response import SystemSovSaseGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSovSaseGet200Response from a JSON string
system_sov_sase_get200_response_instance = SystemSovSaseGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSovSaseGet200Response.to_json())

# convert the object into a dict
system_sov_sase_get200_response_dict = system_sov_sase_get200_response_instance.to_dict()
# create an instance of SystemSovSaseGet200Response from a dict
system_sov_sase_get200_response_from_dict = SystemSovSaseGet200Response.from_dict(system_sov_sase_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


