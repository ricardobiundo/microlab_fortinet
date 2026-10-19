# microlab_fortinet.SystemIpsApi

All URIs are relative to *https://172.16.177.65/api/v2/cmdb*

Method | HTTP request | Description
------------- | ------------- | -------------
[**system_ips_get**](SystemIpsApi.md#system_ips_get) | **GET** /system/ips | Select all entries in a CLI table.  Access Group: sysgrp
[**system_ips_put**](SystemIpsApi.md#system_ips_put) | **PUT** /system/ips | Update this specific resource.  Access Group: sysgrp


# **system_ips_get**
> SystemIpsGet200Response system_ips_get()

Select all entries in a CLI table.  Access Group: sysgrp

### Example

* Api Key Authentication (APIKeyQueryParam):

```python
import microlab_fortinet
from microlab_fortinet.models.system_ips_get200_response import SystemIpsGet200Response
from microlab_fortinet.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://172.16.177.65/api/v2/cmdb
# See configuration.py for a list of all supported configuration parameters.
configuration = microlab_fortinet.Configuration(
    host = "https://172.16.177.65/api/v2/cmdb"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: APIKeyQueryParam
configuration.api_key['APIKeyQueryParam'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['APIKeyQueryParam'] = 'Bearer'

# Enter a context with an instance of the API client
async with microlab_fortinet.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = microlab_fortinet.SystemIpsApi(api_client)

    try:
        # Select all entries in a CLI table.  Access Group: sysgrp
        api_response = await api_instance.system_ips_get()
        print("The response of SystemIpsApi->system_ips_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SystemIpsApi->system_ips_get: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**SystemIpsGet200Response**](SystemIpsGet200Response.md)

### Authorization

[APIKeyQueryParam](../README.md#APIKeyQueryParam)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | OK: Request returns successful |  -  |
**400** | Bad Request: Request cannot be processed by the API |  -  |
**401** | Not Authorized: Request without successful login session |  -  |
**403** | Forbidden: Request is missing CSRF token or administrator is missing access profile permissions. |  -  |
**404** | Resource Not Found: Unable to find the specified resource. |  -  |
**405** | Method Not Allowed: Specified HTTP method is not allowed for this resource.  |  -  |
**413** | Request Entity Too Large: Request cannot be processed due to large entity  |  -  |
**424** | Failed Dependency: Fail dependency can be duplicate resource, missing required parameter, missing required attribute, invalid attribute value |  -  |
**429** | Access temporarily blocked: Maximum failed authentications reached. The offended source is temporarily blocked for certain amount of time. |  -  |
**500** | Internal Server Error: Internal error when processing the request  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **system_ips_put**
> system_ips_put(body, vdom=vdom, action=action, before=before, after=after, scope=scope)

Update this specific resource.  Access Group: sysgrp

### Example

* Api Key Authentication (APIKeyQueryParam):

```python
import microlab_fortinet
from microlab_fortinet.models.system_ips_get200_response import SystemIpsGet200Response
from microlab_fortinet.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://172.16.177.65/api/v2/cmdb
# See configuration.py for a list of all supported configuration parameters.
configuration = microlab_fortinet.Configuration(
    host = "https://172.16.177.65/api/v2/cmdb"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: APIKeyQueryParam
configuration.api_key['APIKeyQueryParam'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['APIKeyQueryParam'] = 'Bearer'

# Enter a context with an instance of the API client
async with microlab_fortinet.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = microlab_fortinet.SystemIpsApi(api_client)
    body = microlab_fortinet.SystemIpsGet200Response() # SystemIpsGet200Response | Possible parameters to go in the body for the request
    vdom = ['vdom_example'] # List[str] | Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom=root (Single VDOM) vdom=vdom1,vdom2 (Multiple VDOMs) vdom=* (All VDOMs)  (optional)
    action = 'action_example' # str | If supported, an action can be specified. _move_: Move this specific resource. When *action=move* is set, one of the extra parameters (*before*, *after*) must be provided. __*Note:*__ If this parameter is provided when not supported, the action will be ignored and an “invalid request” error will be returned.  (optional)
    before = 'before_example' # str | If *action=move*, use *before* to specify the ID of the resource that this resource will be moved before. For example, to move `object 1` to before `object 2`, use: __action=move&before=2__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *move*.  (optional)
    after = 'after_example' # str | If *action=move*, use *after* to specify the ID of the resource that this resource will be moved after. For example, to move `object 1` to after `object 3`, use: __action=move&after=3__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *move*.  (optional)
    scope = 'scope_example' # str | Specify the Scope from which results are returned or changes are applied to. Objects are only existed in VDOMs scope. scope=vdom (optional)

    try:
        # Update this specific resource.  Access Group: sysgrp
        await api_instance.system_ips_put(body, vdom=vdom, action=action, before=before, after=after, scope=scope)
    except Exception as e:
        print("Exception when calling SystemIpsApi->system_ips_put: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**SystemIpsGet200Response**](SystemIpsGet200Response.md)| Possible parameters to go in the body for the request | 
 **vdom** | [**List[str]**](str.md)| Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom&#x3D;root (Single VDOM) vdom&#x3D;vdom1,vdom2 (Multiple VDOMs) vdom&#x3D;* (All VDOMs)  | [optional] 
 **action** | **str**| If supported, an action can be specified. _move_: Move this specific resource. When *action&#x3D;move* is set, one of the extra parameters (*before*, *after*) must be provided. __*Note:*__ If this parameter is provided when not supported, the action will be ignored and an “invalid request” error will be returned.  | [optional] 
 **before** | **str**| If *action&#x3D;move*, use *before* to specify the ID of the resource that this resource will be moved before. For example, to move &#x60;object 1&#x60; to before &#x60;object 2&#x60;, use: __action&#x3D;move&amp;before&#x3D;2__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *move*.  | [optional] 
 **after** | **str**| If *action&#x3D;move*, use *after* to specify the ID of the resource that this resource will be moved after. For example, to move &#x60;object 1&#x60; to after &#x60;object 3&#x60;, use: __action&#x3D;move&amp;after&#x3D;3__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *move*.  | [optional] 
 **scope** | **str**| Specify the Scope from which results are returned or changes are applied to. Objects are only existed in VDOMs scope. scope&#x3D;vdom | [optional] 

### Return type

void (empty response body)

### Authorization

[APIKeyQueryParam](../README.md#APIKeyQueryParam)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | OK: Request returns successful |  -  |
**400** | Bad Request: Request cannot be processed by the API |  -  |
**401** | Not Authorized: Request without successful login session |  -  |
**403** | Forbidden: Request is missing CSRF token or administrator is missing access profile permissions. |  -  |
**404** | Resource Not Found: Unable to find the specified resource. |  -  |
**405** | Method Not Allowed: Specified HTTP method is not allowed for this resource.  |  -  |
**413** | Request Entity Too Large: Request cannot be processed due to large entity  |  -  |
**424** | Failed Dependency: Fail dependency can be duplicate resource, missing required parameter, missing required attribute, invalid attribute value |  -  |
**429** | Access temporarily blocked: Maximum failed authentications reached. The offended source is temporarily blocked for certain amount of time. |  -  |
**500** | Internal Server Error: Internal error when processing the request  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

