# SystemVdomLinkNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | VDOM link name (maximum &#x3D; 11 characters). | [optional] 
**vcluster** | **str** | Virtual cluster.    vcluster1:Virtual cluster 1.    vcluster2:Virtual cluster 2. | [optional] 
**type** | **str** | VDOM link type: PPP or Ethernet.    ppp:PPP VDOM link.    ethernet:Ethernet VDOM link. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vdom_link_name_get200_response import SystemVdomLinkNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVdomLinkNameGet200Response from a JSON string
system_vdom_link_name_get200_response_instance = SystemVdomLinkNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVdomLinkNameGet200Response.to_json())

# convert the object into a dict
system_vdom_link_name_get200_response_dict = system_vdom_link_name_get200_response_instance.to_dict()
# create an instance of SystemVdomLinkNameGet200Response from a dict
system_vdom_link_name_get200_response_from_dict = SystemVdomLinkNameGet200Response.from_dict(system_vdom_link_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


