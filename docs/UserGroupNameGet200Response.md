# UserGroupNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Group name. | [optional] 
**id** | **int** | Group ID. | [optional] 
**group_type** | **str** | Set the group to be for firewall authentication, FSSO, RSSO, SCIM, or guest users.    firewall:Firewall.    fsso-service:Fortinet Single Sign-On Service.    rsso:RADIUS based Single Sign-On Service.    guest:Guest.    scim:SCIM based Authorization. | [optional] 
**authtimeout** | **int** | Authentication timeout in minutes for this user group. 0 to use the global user setting auth-timeout. | [optional] 
**auth_concurrent_override** | **str** | Enable/disable overriding the global number of concurrent authentication sessions for this user group.    enable:Enable auth-concurrent-override.    disable:Disable auth-concurrent-override. | [optional] 
**auth_concurrent_value** | **int** | Maximum number of concurrent authenticated connections per user (0 - 100). | [optional] 
**http_digest_realm** | **str** | Realm attribute for MD5-digest authentication. | [optional] 
**sso_attribute_value** | **str** | RADIUS attribute value. | [optional] 
**member** | [**List[UserGroupNameGet200ResponseMemberInner]**](UserGroupNameGet200ResponseMemberInner.md) | Names of users, peers, LDAP severs, RADIUS servers, SCIM client or external idp servers to add to the user group. | [optional] 
**match** | [**List[UserGroupNameGet200ResponseMatchInner]**](UserGroupNameGet200ResponseMatchInner.md) | Group matches. | [optional] 
**user_id** | **str** | Guest user ID type.    email:Email address.    auto-generate:Automatically generate.    specify:Specify. | [optional] 
**password** | **str** | Guest user password type.    auto-generate:Automatically generate.    specify:Specify.    disable:Disable. | [optional] 
**user_name** | **str** | Enable/disable the guest user name entry.    disable:Disable setting.    enable:Enable setting. | [optional] 
**sponsor** | **str** | Set the action for the sponsor guest user field.    optional:Optional.    mandatory:Mandatory.    disabled:Disabled. | [optional] 
**company** | **str** | Set the action for the company guest user field.    optional:Optional.    mandatory:Mandatory.    disabled:Disabled. | [optional] 
**email** | **str** | Enable/disable the guest user email address field.    disable:Disable setting.    enable:Enable setting. | [optional] 
**mobile_phone** | **str** | Enable/disable the guest user mobile phone number field.    disable:Disable setting.    enable:Enable setting. | [optional] 
**sms_server** | **str** | Send SMS through FortiGuard or other external server.    fortiguard:Send SMS by FortiGuard.    custom:Send SMS by custom server. | [optional] 
**sms_custom_server** | **str** | SMS server. | [optional] 
**expire_type** | **str** | Determine when the expiration countdown begins.    immediately:Immediately.    first-successful-login:First successful login. | [optional] 
**expire** | **int** | Time in seconds before guest user accounts expire (1 - 31536000). | [optional] 
**max_accounts** | **int** | Maximum number of guest accounts that can be created for this group (0 means unlimited). | [optional] 
**multiple_guest_add** | **str** | Enable/disable addition of multiple guests.    disable:Disable setting.    enable:Enable setting. | [optional] 
**guest** | [**List[UserGroupNameGet200ResponseGuestInner]**](UserGroupNameGet200ResponseGuestInner.md) | Guest User. | [optional] 
**scim_user_attr_type** | **str** | User attribute type used to match SCIM users (default &#x3D; user-name).    user-name:User name.    display-name:Display name.    external-id:External ID.    email:Email. | [optional] 
**scim_group_attr_type** | **str** | Group attribute type used to match SCIM groups (default &#x3D; display-name).    display-name:Display name.    external-id:External ID. | [optional] 
**scim_users** | [**List[UserGroupNameGet200ResponseScimUsersInner]**](UserGroupNameGet200ResponseScimUsersInner.md) | Names of SCIM users. | [optional] 
**scim_groups** | [**List[UserGroupNameGet200ResponseScimGroupsInner]**](UserGroupNameGet200ResponseScimGroupsInner.md) | Names of SCIM groups. | [optional] 

## Example

```python
from microlab_fortinet.models.user_group_name_get200_response import UserGroupNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserGroupNameGet200Response from a JSON string
user_group_name_get200_response_instance = UserGroupNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserGroupNameGet200Response.to_json())

# convert the object into a dict
user_group_name_get200_response_dict = user_group_name_get200_response_instance.to_dict()
# create an instance of UserGroupNameGet200Response from a dict
user_group_name_get200_response_from_dict = UserGroupNameGet200Response.from_dict(user_group_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


