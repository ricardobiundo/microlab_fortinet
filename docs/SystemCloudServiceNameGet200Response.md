# SystemCloudServiceNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**vendor** | **str** | Cloud service vendor.    unknown:Unknown type of cloud service vendor.    google-cloud-kms:Google Cloud KMS service. | [optional] 
**traffic_vdom** | **str** | Vdom used to communicate with cloud service. | [optional] 
**gck_service_account** | **str** | Service account (e.g. \&quot;account-id@sampledomain.com\&quot;). | [optional] 
**gck_private_key** | **str** | Service account private key in PEM format (e.g. \&quot;-----BEGIN PRIVATE KEY-----\\ ...\&quot;). | [optional] 
**gck_keyid** | **str** | Key id, also referred as \&quot;kid\&quot;. | [optional] 
**gck_access_token_lifetime** | **int** | Lifetime of automatically generated access tokens in minutes (default is 60 minutes). | [optional] 

## Example

```python
from microlab_fortinet.models.system_cloud_service_name_get200_response import SystemCloudServiceNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemCloudServiceNameGet200Response from a JSON string
system_cloud_service_name_get200_response_instance = SystemCloudServiceNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemCloudServiceNameGet200Response.to_json())

# convert the object into a dict
system_cloud_service_name_get200_response_dict = system_cloud_service_name_get200_response_instance.to_dict()
# create an instance of SystemCloudServiceNameGet200Response from a dict
system_cloud_service_name_get200_response_from_dict = SystemCloudServiceNameGet200Response.from_dict(system_cloud_service_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


