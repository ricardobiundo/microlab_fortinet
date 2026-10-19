# SystemSecurityRatingControlsNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Security Rating control name. | [optional] 
**display_report** | **str** | Enable/disable displaying the Security Rating control in the default report.    enable:Enable displaying the Security Rating control in the default report.    disable:Disable displaying the Security Rating control in the default report. | [optional] 
**display_insight** | **str** | Enable/disable displaying the Security Rating control as an insight across the GUI.    enable:Enable displaying the Security Rating control as an insight across the GUI.    disable:Disable displaying the Security Rating control as an insight across the GUI. | [optional] 

## Example

```python
from microlab_fortinet.models.system_security_rating_controls_name_get200_response import SystemSecurityRatingControlsNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSecurityRatingControlsNameGet200Response from a JSON string
system_security_rating_controls_name_get200_response_instance = SystemSecurityRatingControlsNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSecurityRatingControlsNameGet200Response.to_json())

# convert the object into a dict
system_security_rating_controls_name_get200_response_dict = system_security_rating_controls_name_get200_response_instance.to_dict()
# create an instance of SystemSecurityRatingControlsNameGet200Response from a dict
system_security_rating_controls_name_get200_response_from_dict = SystemSecurityRatingControlsNameGet200Response.from_dict(system_security_rating_controls_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


