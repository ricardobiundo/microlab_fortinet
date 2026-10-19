# SystemWccpServiceIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**service_id** | **str** | Service ID. | [optional] 
**router_id** | **str** | IP address known to all cache engines. If all cache engines connect to the same FortiGate interface, use the default 0.0.0.0. | [optional] 
**cache_id** | **str** | IP address known to all routers. If the addresses are the same, use the default 0.0.0.0. | [optional] 
**group_address** | **str** | IP multicast address used by the cache routers. For the FortiGate to ignore multicast WCCP traffic, use the default 0.0.0.0. | [optional] 
**server_list** | **str** | IP addresses and netmasks for up to four cache servers. | [optional] 
**router_list** | **str** | IP addresses of one or more WCCP routers. | [optional] 
**ports_defined** | **str** | Match method.    source:Source port match.    destination:Destination port match. | [optional] 
**server_type** | **str** | Cache server type.    forward:Forward server.    proxy:Proxy server. | [optional] 
**ports** | **str** | Service ports. | [optional] 
**authentication** | **str** | Enable/disable MD5 authentication.    enable:Enable MD5 authentication.    disable:Disable MD5 authentication. | [optional] 
**password** | **str** | Password for MD5 authentication. | [optional] 
**forward_method** | **str** | Method used to forward traffic to the cache servers.    GRE:GRE encapsulation.    L2:L2 rewrite.    any:GRE or L2. | [optional] 
**cache_engine_method** | **str** | Method used to forward traffic to the routers or to return to the cache engine.    GRE:GRE encapsulation.    L2:L2 rewrite. | [optional] 
**service_type** | **str** | WCCP service type used by the cache server for logical interception and redirection of traffic.    auto:auto    standard:Standard service.    dynamic:Dynamic service. | [optional] 
**primary_hash** | **str** | Hash method.    src-ip:Source IP hash.    dst-ip:Destination IP hash.    src-port:Source port hash.    dst-port:Destination port hash. | [optional] 
**priority** | **int** | Service priority. | [optional] 
**protocol** | **int** | Service protocol. | [optional] 
**assignment_weight** | **int** | Assignment of hash weight/ratio for the WCCP cache engine. | [optional] 
**assignment_bucket_format** | **str** | Assignment bucket format for the WCCP cache engine.    wccp-v2:WCCP-v2 bucket format.    cisco-implementation:Cisco bucket format. | [optional] 
**return_method** | **str** | Method used to decline a redirected packet and return it to the FortiGate unit.    GRE:GRE encapsulation.    L2:L2 rewrite.    any:GRE or L2. | [optional] 
**assignment_method** | **str** | Hash key assignment preference.    HASH:HASH assignment method.    MASK:MASK assignment method.    any:HASH or MASK. | [optional] 
**assignment_srcaddr_mask** | **str** | Assignment source address mask. | [optional] 
**assignment_dstaddr_mask** | **str** | Assignment destination address mask. | [optional] 

## Example

```python
from microlab_fortinet.models.system_wccp_service_id_get200_response import SystemWccpServiceIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemWccpServiceIdGet200Response from a JSON string
system_wccp_service_id_get200_response_instance = SystemWccpServiceIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemWccpServiceIdGet200Response.to_json())

# convert the object into a dict
system_wccp_service_id_get200_response_dict = system_wccp_service_id_get200_response_instance.to_dict()
# create an instance of SystemWccpServiceIdGet200Response from a dict
system_wccp_service_id_get200_response_from_dict = SystemWccpServiceIdGet200Response.from_dict(system_wccp_service_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


