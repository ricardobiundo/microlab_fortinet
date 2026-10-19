# SystemNetflowGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active_flow_timeout** | **int** | Timeout to report active flows (60 - 3600 sec, default &#x3D; 1800). | [optional] 
**inactive_flow_timeout** | **int** | Timeout for periodic report of finished flows (10 - 600 sec, default &#x3D; 15). | [optional] 
**template_tx_timeout** | **int** | Timeout for periodic template flowset transmission (60 - 86400 sec, default &#x3D; 1800). | [optional] 
**template_tx_counter** | **int** | Counter of flowset records before resending a template flowset record. | [optional] 
**session_cache_size** | **str** | Maximum RAM usage allowed for Netflow session cache.    min:Up to 0.5% of system RAM.    default:Up to 1% of system RAM.    max:Up to 2% of system RAM. | [optional] 
**exclusion_filters** | [**List[SystemNetflowGet200ResponseExclusionFiltersInner]**](SystemNetflowGet200ResponseExclusionFiltersInner.md) | Exclusion filters | [optional] 
**collectors** | [**List[SystemNetflowGet200ResponseCollectorsInner]**](SystemNetflowGet200ResponseCollectorsInner.md) | Netflow collectors. | [optional] 

## Example

```python
from microlab_fortinet.models.system_netflow_get200_response import SystemNetflowGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetflowGet200Response from a JSON string
system_netflow_get200_response_instance = SystemNetflowGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemNetflowGet200Response.to_json())

# convert the object into a dict
system_netflow_get200_response_dict = system_netflow_get200_response_instance.to_dict()
# create an instance of SystemNetflowGet200Response from a dict
system_netflow_get200_response_from_dict = SystemNetflowGet200Response.from_dict(system_netflow_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


