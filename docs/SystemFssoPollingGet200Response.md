# SystemFssoPollingGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable FSSO Polling Mode.    enable:Enable FSSO Polling Mode.    disable:Disable FSSO Polling Mode. | [optional] 
**listening_port** | **int** | Listening port to accept clients (1 - 65535). | [optional] 
**authentication** | **str** | Enable/disable FSSO Agent Authentication.    enable:Enable FSSO Agent Authentication.    disable:Disable FSSO Agent Authentication. | [optional] 
**auth_password** | **str** | Password to connect to FSSO Agent. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fsso_polling_get200_response import SystemFssoPollingGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFssoPollingGet200Response from a JSON string
system_fsso_polling_get200_response_instance = SystemFssoPollingGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFssoPollingGet200Response.to_json())

# convert the object into a dict
system_fsso_polling_get200_response_dict = system_fsso_polling_get200_response_instance.to_dict()
# create an instance of SystemFssoPollingGet200Response from a dict
system_fsso_polling_get200_response_from_dict = SystemFssoPollingGet200Response.from_dict(system_fsso_polling_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


