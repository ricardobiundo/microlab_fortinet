# UserFortitokenSerialNumberGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**serial_number** | **str** | Serial number. | [optional] 
**status** | **str** | Status.    active:Activate FortiToken.    lock:Lock FortiToken. | [optional] 
**seed** | **str** | Token seed. | [optional] 
**comments** | **str** | Comment. | [optional] 
**license** | **str** | Mobile token license. | [optional] 
**activation_code** | **str** | Mobile token user activation-code. | [optional] 
**activation_expire** | **int** | Mobile token user activation-code expire time. | [optional] 
**reg_id** | **str** | Device Reg ID. | [optional] 
**os_ver** | **str** | Device Mobile Version. | [optional] 

## Example

```python
from microlab_fortinet.models.user_fortitoken_serial_number_get200_response import UserFortitokenSerialNumberGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserFortitokenSerialNumberGet200Response from a JSON string
user_fortitoken_serial_number_get200_response_instance = UserFortitokenSerialNumberGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserFortitokenSerialNumberGet200Response.to_json())

# convert the object into a dict
user_fortitoken_serial_number_get200_response_dict = user_fortitoken_serial_number_get200_response_instance.to_dict()
# create an instance of UserFortitokenSerialNumberGet200Response from a dict
user_fortitoken_serial_number_get200_response_from_dict = UserFortitokenSerialNumberGet200Response.from_dict(user_fortitoken_serial_number_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


