# UserDomainControllerNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Domain controller entry name. | [optional] 
**ad_mode** | **str** | Set Active Directory mode.    none:The server is not configured as an Active Directory Domain Server (AD DS).    ds:The server is configured as an Active Directory Domain Server (AD DS).    lds:The server is an Active Directory Lightweight Domain Server (AD LDS). | [optional] 
**hostname** | **str** | Hostname of the server to connect to. | [optional] 
**username** | **str** | User name to sign in with. Must have proper permissions for service. | [optional] 
**password** | **str** | Password for specified username. | [optional] 
**ip_address** | **str** | Domain controller IPv4 address. | [optional] 
**ip6** | **str** | Domain controller IPv6 address. | [optional] 
**port** | **int** | Port to be used for communication with the domain controller (default &#x3D; 445). | [optional] 
**source_ip_address** | **str** | FortiGate IPv4 address to be used for communication with the domain controller. | [optional] 
**source_ip6** | **str** | FortiGate IPv6 address to be used for communication with the domain controller. | [optional] 
**source_port** | **int** | Source port to be used for communication with the domain controller. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**extra_server** | [**List[UserDomainControllerNameGet200ResponseExtraServerInner]**](UserDomainControllerNameGet200ResponseExtraServerInner.md) | Extra servers. | [optional] 
**domain_name** | **str** | Domain DNS name. | [optional] 
**replication_port** | **int** | Port to be used for communication with the domain controller for replication service. Port number 0 indicates automatic discovery. | [optional] 
**ldap_server** | [**List[UserDomainControllerNameGet200ResponseLdapServerInner]**](UserDomainControllerNameGet200ResponseLdapServerInner.md) | LDAP server name(s). | [optional] 
**change_detection** | **str** | Enable/disable detection of a configuration change in the Active Directory server.    enable:Enable detection of a configuration change in the Active Directory server.    disable:Disable detection of a configuration change in the Active Directory server. | [optional] 
**change_detection_period** | **int** | Minutes to detect a configuration change in the Active Directory server (5 - 10080 minutes (7 days), default &#x3D; 60). | [optional] 
**dns_srv_lookup** | **str** | Enable/disable DNS service lookup.    enable:Enable DNS service lookup.    disable:Disable DNS service lookup. | [optional] 
**adlds_dn** | **str** | AD LDS distinguished name. | [optional] 
**adlds_ip_address** | **str** | AD LDS IPv4 address. | [optional] 
**adlds_ip6** | **str** | AD LDS IPv6 address. | [optional] 
**adlds_port** | **int** | Port number of AD LDS service (default &#x3D; 389). | [optional] 

## Example

```python
from microlab_fortinet.models.user_domain_controller_name_get200_response import UserDomainControllerNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserDomainControllerNameGet200Response from a JSON string
user_domain_controller_name_get200_response_instance = UserDomainControllerNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserDomainControllerNameGet200Response.to_json())

# convert the object into a dict
user_domain_controller_name_get200_response_dict = user_domain_controller_name_get200_response_instance.to_dict()
# create an instance of UserDomainControllerNameGet200Response from a dict
user_domain_controller_name_get200_response_from_dict = UserDomainControllerNameGet200Response.from_dict(user_domain_controller_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


