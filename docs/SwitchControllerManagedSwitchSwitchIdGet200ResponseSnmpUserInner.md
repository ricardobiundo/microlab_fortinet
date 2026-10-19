# SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | SNMP user name. | [optional] 
**queries** | **str** | Enable/disable SNMP queries for this user.    disable:Disable SNMP queries for this user.    enable:Enable SNMP queries for this user. | [optional] 
**query_port** | **int** | SNMPv3 query port (default &#x3D; 161). | [optional] 
**security_level** | **str** | Security level for message authentication and encryption.    no-auth-no-priv:Message with no authentication and no privacy (encryption).    auth-no-priv:Message with authentication but no privacy (encryption).    auth-priv:Message with authentication and privacy (encryption). | [optional] 
**auth_proto** | **str** | Authentication protocol.    md5:HMAC-MD5-96 authentication protocol.    sha1:HMAC-SHA-1 authentication protocol.    sha224:HMAC-SHA-224 authentication protocol.    sha256:HMAC-SHA-256 authentication protocol.    sha384:HMAC-SHA-384 authentication protocol.    sha512:HMAC-SHA-512 authentication protocol. | [optional] 
**auth_pwd** | **str** | Password for authentication protocol. | [optional] 
**priv_proto** | **str** | Privacy (encryption) protocol.    aes128:CFB128-AES-128 symmetric encryption protocol.    aes192:CFB128-AES-192 symmetric encryption protocol.    aes192c:CFB128-AES-192-C symmetric encryption protocol.    aes256:CFB128-AES-256 symmetric encryption protocol.    aes256c:CFB128-AES-256-C symmetric encryption protocol.    des:CBC-DES symmetric encryption protocol. | [optional] 
**priv_pwd** | **str** | Password for privacy (encryption) protocol. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_snmp_user_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_snmp_user_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_snmp_user_inner_dict = switch_controller_managed_switch_switch_id_get200_response_snmp_user_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner from a dict
switch_controller_managed_switch_switch_id_get200_response_snmp_user_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_snmp_user_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


