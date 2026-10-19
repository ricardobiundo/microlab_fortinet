# WirelessControllerSnmpGet200ResponseUserInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | SNMP user name. | [optional] 
**status** | **str** | SNMP user enable.    enable:Enable setting.    disable:Disable setting. | [optional] 
**queries** | **str** | Enable/disable SNMP queries for this user.    enable:Enable setting.    disable:Disable setting. | [optional] 
**trap_status** | **str** | Enable/disable traps for this SNMP user.    enable:Enable setting.    disable:Disable setting. | [optional] 
**security_level** | **str** | Security level for message authentication and encryption.    no-auth-no-priv:Message with no authentication and no privacy (encryption).    auth-no-priv:Message with authentication but no privacy (encryption).    auth-priv:Message with authentication and privacy (encryption). | [optional] 
**auth_proto** | **str** | Authentication protocol.    md5:HMAC-MD5-96 authentication protocol.    sha:HMAC-SHA-96 authentication protocol.    sha224:HMAC-SHA224 authentication protocol.    sha256:HMAC-SHA256 authentication protocol.    sha384:HMAC-SHA384 authentication protocol.    sha512:HMAC-SHA512 authentication protocol. | [optional] 
**auth_pwd** | **str** | Password for authentication protocol. | [optional] 
**priv_proto** | **str** | Privacy (encryption) protocol.    aes:CFB128-AES-128 symmetric encryption protocol.    des:CBC-DES symmetric encryption protocol.    aes256:CFB128-AES-256 symmetric encryption protocol.    aes256cisco:CFB128-AES-256 symmetric encryption protocol compatible with CISCO. | [optional] 
**priv_pwd** | **str** | Password for privacy (encryption) protocol. | [optional] 
**notify_hosts** | **str** | Configure SNMP User Notify Hosts. | [optional] 
**notify_hosts6** | **str** | Configure IPv6 SNMP User Notify Hosts. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_snmp_get200_response_user_inner import WirelessControllerSnmpGet200ResponseUserInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerSnmpGet200ResponseUserInner from a JSON string
wireless_controller_snmp_get200_response_user_inner_instance = WirelessControllerSnmpGet200ResponseUserInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerSnmpGet200ResponseUserInner.to_json())

# convert the object into a dict
wireless_controller_snmp_get200_response_user_inner_dict = wireless_controller_snmp_get200_response_user_inner_instance.to_dict()
# create an instance of WirelessControllerSnmpGet200ResponseUserInner from a dict
wireless_controller_snmp_get200_response_user_inner_from_dict = WirelessControllerSnmpGet200ResponseUserInner.from_dict(wireless_controller_snmp_get200_response_user_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


