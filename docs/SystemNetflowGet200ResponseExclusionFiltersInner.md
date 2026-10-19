# SystemNetflowGet200ResponseExclusionFiltersInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Filter ID. | [optional] 
**source_ip** | **str** | Session source address. | [optional] 
**destination_ip** | **str** | Session destination address. | [optional] 
**source_port** | **str** | Session source port number or range. | [optional] 
**destination_port** | **str** | Session destination port number or range. | [optional] 
**protocol** | **int** | Session IP protocol (0 - 255, default &#x3D; 255, meaning any). | [optional] 

## Example

```python
from microlab_fortinet.models.system_netflow_get200_response_exclusion_filters_inner import SystemNetflowGet200ResponseExclusionFiltersInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetflowGet200ResponseExclusionFiltersInner from a JSON string
system_netflow_get200_response_exclusion_filters_inner_instance = SystemNetflowGet200ResponseExclusionFiltersInner.from_json(json)
# print the JSON string representation of the object
print(SystemNetflowGet200ResponseExclusionFiltersInner.to_json())

# convert the object into a dict
system_netflow_get200_response_exclusion_filters_inner_dict = system_netflow_get200_response_exclusion_filters_inner_instance.to_dict()
# create an instance of SystemNetflowGet200ResponseExclusionFiltersInner from a dict
system_netflow_get200_response_exclusion_filters_inner_from_dict = SystemNetflowGet200ResponseExclusionFiltersInner.from_dict(system_netflow_get200_response_exclusion_filters_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


