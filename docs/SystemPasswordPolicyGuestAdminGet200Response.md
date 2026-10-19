# SystemPasswordPolicyGuestAdminGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable setting a password policy for locally defined administrator passwords and IPsec VPN pre-shared keys.    enable:Enable password policy.    disable:Disable password policy. | [optional] 
**apply_to** | **str** | Guest administrator to which this password policy applies.    guest-admin-password:Apply to guest administrator password. | [optional] 
**minimum_length** | **int** | Minimum password length (12 - 128, default &#x3D; 12). | [optional] 
**min_lower_case_letter** | **int** | Minimum number of lowercase characters in password (0 - 128, default &#x3D; 1). | [optional] 
**min_upper_case_letter** | **int** | Minimum number of uppercase characters in password (0 - 128, default &#x3D; 1). | [optional] 
**min_non_alphanumeric** | **int** | Minimum number of non-alphanumeric characters in password (0 - 128, default &#x3D; 1). | [optional] 
**min_number** | **int** | Minimum number of numeric characters in password (0 - 128, default &#x3D; 1). | [optional] 
**expire_status** | **str** | Enable/disable password expiration.    enable:Passwords expire after expire-day days.    disable:Passwords do not expire. | [optional] 
**expire_day** | **int** | Number of days after which passwords expire (1 - 999 days, default &#x3D; 90). | [optional] 
**reuse_password** | **str** | Enable/disable reuse of password.    enable:Administrators are allowed to reuse the same password up to a limit.    disable:Administrators must create a new password. | [optional] 
**reuse_password_limit** | **int** | Number of times passwords can be reused (0 - 20, default &#x3D; 0. If set to 0, can reuse password an unlimited number of times.). | [optional] 

## Example

```python
from microlab_fortinet.models.system_password_policy_guest_admin_get200_response import SystemPasswordPolicyGuestAdminGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPasswordPolicyGuestAdminGet200Response from a JSON string
system_password_policy_guest_admin_get200_response_instance = SystemPasswordPolicyGuestAdminGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemPasswordPolicyGuestAdminGet200Response.to_json())

# convert the object into a dict
system_password_policy_guest_admin_get200_response_dict = system_password_policy_guest_admin_get200_response_instance.to_dict()
# create an instance of SystemPasswordPolicyGuestAdminGet200Response from a dict
system_password_policy_guest_admin_get200_response_from_dict = SystemPasswordPolicyGuestAdminGet200Response.from_dict(system_password_policy_guest_admin_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


