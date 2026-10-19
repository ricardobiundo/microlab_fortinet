# SystemDdnsDdnsidGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ddnsid** | **int** | DDNS ID. | [optional] 
**ddns_server** | **str** | Select a DDNS service provider.    dyndns.org:members.dyndns.org and dnsalias.com    dyns.net:www.dyns.net    tzo.com:rh.tzo.com    vavic.com:Peanut Hull    dipdns.net:dipdnsserver.dipdns.com    now.net.cn:ip.todayisp.com    dhs.org:members.dhs.org    easydns.com:members.easydns.com    genericDDNS:Generic DDNS based on RFC2136.    FortiGuardDDNS:FortiGuard DDNS service.    noip.com:dynupdate.no-ip.com | [optional] 
**addr_type** | **str** | Address type of interface address in DDNS update.    ipv4:Use IPv4 address of the interface.    ipv6:Use IPv6 address of the interface. | [optional] 
**server_type** | **str** | Address type of the DDNS server.    ipv4:Use IPv4 addressing.    ipv6:Use IPv6 addressing. | [optional] 
**ddns_server_addr** | [**List[SystemDdnsDdnsidGet200ResponseDdnsServerAddrInner]**](SystemDdnsDdnsidGet200ResponseDdnsServerAddrInner.md) | Generic DDNS server IP/FQDN list. | [optional] 
**ddns_zone** | **str** | Zone of your domain name (for example, DDNS.com). | [optional] 
**ddns_ttl** | **int** | Time-to-live for DDNS packets. | [optional] 
**ddns_auth** | **str** | Enable/disable TSIG authentication for your DDNS server.    disable:Disable DDNS authentication.    tsig:Enable TSIG authentication based on RFC2845. | [optional] 
**ddns_keyname** | **str** | DDNS update key name. | [optional] 
**ddns_key** | **str** | DDNS update key (base 64 encoding). | [optional] 
**ddns_domain** | **str** | Your fully qualified domain name. For example, yourname.ddns.com. | [optional] 
**ddns_username** | **str** | DDNS user name. | [optional] 
**ddns_sn** | **str** | DDNS Serial Number. | [optional] 
**ddns_password** | **str** | DDNS password. | [optional] 
**use_public_ip** | **str** | Enable/disable use of public IP address.    disable:Disable use of public IP address.    enable:Enable use of public IP address. | [optional] 
**update_interval** | **int** | DDNS update interval (60 - 2592000 sec, 0 means default). | [optional] 
**clear_text** | **str** | Enable/disable use of clear text connections.    disable:Disable use of clear text connections.    enable:Enable use of clear text connections. | [optional] 
**ssl_certificate** | **str** | Name of local certificate for SSL connections. | [optional] 
**bound_ip** | **str** | Bound IP address. | [optional] 
**monitor_interface** | [**List[SystemAcmeGet200ResponseInterfaceInner]**](SystemAcmeGet200ResponseInterfaceInner.md) | Monitored interface. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ddns_ddnsid_get200_response import SystemDdnsDdnsidGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDdnsDdnsidGet200Response from a JSON string
system_ddns_ddnsid_get200_response_instance = SystemDdnsDdnsidGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDdnsDdnsidGet200Response.to_json())

# convert the object into a dict
system_ddns_ddnsid_get200_response_dict = system_ddns_ddnsid_get200_response_instance.to_dict()
# create an instance of SystemDdnsDdnsidGet200Response from a dict
system_ddns_ddnsid_get200_response_from_dict = SystemDdnsDdnsidGet200Response.from_dict(system_ddns_ddnsid_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


