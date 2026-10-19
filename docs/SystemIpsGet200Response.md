# SystemIpsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**signature_hold_time** | **str** | Time to hold and monitor IPS signatures. Format &lt;#d##h&gt; (day range: 0 - 21, hour range: 0 - 23, max hold time: 21d0h, default hold time: 0d0h). | [optional] 
**override_signature_hold_by_id** | **str** | Enable/disable override of hold of triggering signatures that are specified by IDs regardless of hold.    enable:Allow the signatures specified by IDs to be triggered even if they are on hold.    disable:Do not trigger the signatures that are on hold. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ips_get200_response import SystemIpsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpsGet200Response from a JSON string
system_ips_get200_response_instance = SystemIpsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIpsGet200Response.to_json())

# convert the object into a dict
system_ips_get200_response_dict = system_ips_get200_response_instance.to_dict()
# create an instance of SystemIpsGet200Response from a dict
system_ips_get200_response_from_dict = SystemIpsGet200Response.from_dict(system_ips_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


