# UserPasswordPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Password policy name. | [optional] 
**expire_status** | **str** | Enable/disable password expiration.    enable:Passwords expire after expire-day days.    disable:Passwords do not expire. | [optional] 
**expire_days** | **int** | Time in days before the user&#39;s password expires. | [optional] 
**warn_days** | **int** | Time in days before a password expiration warning message is displayed to the user upon login. | [optional] 
**expired_password_renewal** | **str** | Enable/disable renewal of a password that already is expired.    enable:Enable renewal of a password that already is expired.    disable:Disable renewal of a password that already is expired. | [optional] 
**minimum_length** | **int** | Minimum password length (8 - 128, default &#x3D; 8). | [optional] 
**min_lower_case_letter** | **int** | Minimum number of lowercase characters in password (0 - 128, default &#x3D; 0). | [optional] 
**min_upper_case_letter** | **int** | Minimum number of uppercase characters in password (0 - 128, default &#x3D; 0). | [optional] 
**min_non_alphanumeric** | **int** | Minimum number of non-alphanumeric characters in password (0 - 128, default &#x3D; 0). | [optional] 
**min_number** | **int** | Minimum number of numeric characters in password (0 - 128, default &#x3D; 0). | [optional] 
**min_change_characters** | **int** | Minimum number of unique characters in new password which do not exist in old password (0 - 128, default &#x3D; 0. This attribute overrides reuse-password if both are enabled). | [optional] 
**reuse_password** | **str** | Enable/disable reuse of password. If both reuse-password and min-change-characters are enabled, min-change-characters overrides.    enable:Users are allowed to reuse the same password up to a limit.    disable:Users must create a new password. | [optional] 
**reuse_password_limit** | **int** | Number of times passwords can be reused (0 - 20, default &#x3D; 0. If set to 0, can reuse password an unlimited number of times.). | [optional] 

## Example

```python
from microlab_fortinet.models.user_password_policy_name_get200_response import UserPasswordPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserPasswordPolicyNameGet200Response from a JSON string
user_password_policy_name_get200_response_instance = UserPasswordPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserPasswordPolicyNameGet200Response.to_json())

# convert the object into a dict
user_password_policy_name_get200_response_dict = user_password_policy_name_get200_response_instance.to_dict()
# create an instance of UserPasswordPolicyNameGet200Response from a dict
user_password_policy_name_get200_response_from_dict = UserPasswordPolicyNameGet200Response.from_dict(user_password_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


