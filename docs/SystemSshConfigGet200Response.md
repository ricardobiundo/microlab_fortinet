# SystemSshConfigGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ssh_kex_algo** | **str** | Select one or more SSH kex algorithms.    diffie-hellman-group1-sha1:diffie-hellman-group1-sha1    diffie-hellman-group14-sha1:diffie-hellman-group14-sha1    diffie-hellman-group14-sha256:diffie-hellman-group14-sha256    diffie-hellman-group16-sha512:diffie-hellman-group16-sha512    diffie-hellman-group18-sha512:diffie-hellman-group18-sha512    diffie-hellman-group-exchange-sha1:diffie-hellman-group-exchange-sha1    diffie-hellman-group-exchange-sha256:diffie-hellman-group-exchange-sha256    curve25519-sha256@libssh.org:curve25519-sha256@libssh.org    ecdh-sha2-nistp256:ecdh-sha2-nistp256    ecdh-sha2-nistp384:ecdh-sha2-nistp384    ecdh-sha2-nistp521:ecdh-sha2-nistp521 | [optional] 
**ssh_enc_algo** | **str** | Select one or more SSH ciphers.    chacha20-poly1305@openssh.com:chacha20-poly1305@openssh.com    aes128-ctr:aes128-ctr    aes192-ctr:aes192-ctr    aes256-ctr:aes256-ctr    arcfour256:arcfour256    arcfour128:arcfour128    aes128-cbc:aes128-cbc    3des-cbc:3des-cbc    blowfish-cbc:blowfish-cbc    cast128-cbc:cast128-cbc    aes192-cbc:aes192-cbc    aes256-cbc:aes256-cbc    arcfour:arcfour    rijndael-cbc@lysator.liu.se:rijndael-cbc@lysator.liu.se    aes128-gcm@openssh.com:aes128-gcm@openssh.com    aes256-gcm@openssh.com:aes256-gcm@openssh.com | [optional] 
**ssh_mac_algo** | **str** | Select one or more SSH MAC algorithms.    hmac-md5:hmac-md5    hmac-md5-etm@openssh.com:hmac-md5-etm@openssh.com    hmac-md5-96:hmac-md5-96    hmac-md5-96-etm@openssh.com:hmac-md5-96-etm@openssh.com    hmac-sha1:hmac-sha1    hmac-sha1-etm@openssh.com:hmac-sha1-etm@openssh.com    hmac-sha2-256:hmac-sha2-256    hmac-sha2-256-etm@openssh.com:hmac-sha2-256-etm@openssh.com    hmac-sha2-512:hmac-sha2-512    hmac-sha2-512-etm@openssh.com:hmac-sha2-512-etm@openssh.com    hmac-ripemd160:hmac-ripemd160    hmac-ripemd160@openssh.com:hmac-ripemd160@openssh.com    hmac-ripemd160-etm@openssh.com:hmac-ripemd160-etm@openssh.com    umac-64@openssh.com:umac-64@openssh.com    umac-128@openssh.com:umac-128@openssh.com    umac-64-etm@openssh.com:umac-64-etm@openssh.com    umac-128-etm@openssh.com:umac-128-etm@openssh.com | [optional] 
**ssh_hsk_algo** | **str** | Select one or more SSH hostkey algorithms.    ssh-rsa:ssh-rsa    ecdsa-sha2-nistp521:ecdsa-sha2-nistp521    ecdsa-sha2-nistp384:ecdsa-sha2-nistp384    ecdsa-sha2-nistp256:ecdsa-sha2-nistp256    rsa-sha2-256:rsa-sha2-256    rsa-sha2-512:rsa-sha2-512    ssh-ed25519:ssh-ed25519 | [optional] 
**ssh_hsk_override** | **str** | Enable/disable SSH host key override in SSH daemon.    disable:Disable SSH host key override in SSH daemon.    enable:Enable SSH host key override in SSH daemon. | [optional] 
**ssh_hsk_password** | **str** | Password for ssh-hostkey. | [optional] 
**ssh_hsk** | **str** | Config SSH host key. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ssh_config_get200_response import SystemSshConfigGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSshConfigGet200Response from a JSON string
system_ssh_config_get200_response_instance = SystemSshConfigGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSshConfigGet200Response.to_json())

# convert the object into a dict
system_ssh_config_get200_response_dict = system_ssh_config_get200_response_instance.to_dict()
# create an instance of SystemSshConfigGet200Response from a dict
system_ssh_config_get200_response_from_dict = SystemSshConfigGet200Response.from_dict(system_ssh_config_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


