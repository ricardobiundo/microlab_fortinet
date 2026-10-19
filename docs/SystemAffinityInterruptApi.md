# microlab_fortinet.SystemAffinityInterruptApi

All URIs are relative to *https://172.16.177.65/api/v2/cmdb*

Method | HTTP request | Description
------------- | ------------- | -------------
[**system_affinity_interrupt_get**](SystemAffinityInterruptApi.md#system_affinity_interrupt_get) | **GET** /system/affinity-interrupt | Select all entries in a CLI table.  Access Group: sysgrp
[**system_affinity_interrupt_id_delete**](SystemAffinityInterruptApi.md#system_affinity_interrupt_id_delete) | **DELETE** /system/affinity-interrupt/{id} | Delete this specific resource.  Access Group: sysgrp
[**system_affinity_interrupt_id_get**](SystemAffinityInterruptApi.md#system_affinity_interrupt_id_get) | **GET** /system/affinity-interrupt/{id} | Select a specific entry from a CLI table.  Access Group: sysgrp
[**system_affinity_interrupt_id_put**](SystemAffinityInterruptApi.md#system_affinity_interrupt_id_put) | **PUT** /system/affinity-interrupt/{id} | Update this specific resource.  Access Group: sysgrp
[**system_affinity_interrupt_post**](SystemAffinityInterruptApi.md#system_affinity_interrupt_post) | **POST** /system/affinity-interrupt | Create object(s) in this table.  Access Group: sysgrp


# **system_affinity_interrupt_get**
> SystemAffinityInterruptIdGet200Response system_affinity_interrupt_get()

Select all entries in a CLI table.  Access Group: sysgrp

### Example

* Api Key Authentication (APIKeyQueryParam):

```python
import microlab_fortinet
from microlab_fortinet.models.system_affinity_interrupt_id_get200_response import SystemAffinityInterruptIdGet200Response
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
    api_instance = microlab_fortinet.SystemAffinityInterruptApi(api_client)

    try:
        # Select all entries in a CLI table.  Access Group: sysgrp
        api_response = await api_instance.system_affinity_interrupt_get()
        print("The response of SystemAffinityInterruptApi->system_affinity_interrupt_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SystemAffinityInterruptApi->system_affinity_interrupt_get: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**SystemAffinityInterruptIdGet200Response**](SystemAffinityInterruptIdGet200Response.md)

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

# **system_affinity_interrupt_id_delete**
> system_affinity_interrupt_id_delete(id, vdom=vdom, scope=scope)

Delete this specific resource.  Access Group: sysgrp

### Example

* Api Key Authentication (APIKeyQueryParam):

```python
import microlab_fortinet
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
    api_instance = microlab_fortinet.SystemAffinityInterruptApi(api_client)
    id = 56 # int | mkey
    vdom = ['vdom_example'] # List[str] | Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom=root (Single VDOM) vdom=vdom1,vdom2 (Multiple VDOMs) vdom=* (All VDOMs)  (optional)
    scope = 'scope_example' # str | Specify the Scope from which results are returned or changes are applied to. Objects are only existed in global scope. scope=global (optional)

    try:
        # Delete this specific resource.  Access Group: sysgrp
        await api_instance.system_affinity_interrupt_id_delete(id, vdom=vdom, scope=scope)
    except Exception as e:
        print("Exception when calling SystemAffinityInterruptApi->system_affinity_interrupt_id_delete: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**| mkey | 
 **vdom** | [**List[str]**](str.md)| Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom&#x3D;root (Single VDOM) vdom&#x3D;vdom1,vdom2 (Multiple VDOMs) vdom&#x3D;* (All VDOMs)  | [optional] 
 **scope** | **str**| Specify the Scope from which results are returned or changes are applied to. Objects are only existed in global scope. scope&#x3D;global | [optional] 

### Return type

void (empty response body)

### Authorization

[APIKeyQueryParam](../README.md#APIKeyQueryParam)

### HTTP request headers

 - **Content-Type**: Not defined
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

# **system_affinity_interrupt_id_get**
> SystemAffinityInterruptIdGet200Response system_affinity_interrupt_id_get(id, attr=attr, count=count, skip_to_datasource=skip_to_datasource, acs=acs, search=search, scope=scope, datasource=datasource, with_meta=with_meta, skip=skip, format=format, action=action, vdom=vdom)

Select a specific entry from a CLI table.  Access Group: sysgrp

### Example

* Api Key Authentication (APIKeyQueryParam):

```python
import microlab_fortinet
from microlab_fortinet.models.system_affinity_interrupt_id_get200_response import SystemAffinityInterruptIdGet200Response
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
    api_instance = microlab_fortinet.SystemAffinityInterruptApi(api_client)
    id = 56 # int | mkey
    attr = 'attr_example' # str | Attribute name that references other table (optional)
    count = 56 # int | Maximum number of entries to return. (optional)
    skip_to_datasource = None # object | Skip to provided table's Nth entry. E.g {datasource: 'firewall.address', pos: 10, global_entry: false} (optional)
    acs = 56 # int | If true, returned result are in ascending order. (optional)
    search = 'search_example' # str | If present, the objects will be filtered by the search value. (optional)
    scope = 'scope_example' # str | Scope [global|vdom|both*] (optional)
    datasource = True # bool | Enable to include datasource information for each linked object. (optional)
    with_meta = True # bool | Enable to include meta information about each object (type id, references, etc). (optional)
    skip = True # bool | Enable to call CLI skip operator to hide skipped properties. (optional)
    format = ['format_example'] # List[str] | List of property names to include in results, separated by | (i.e. policyid|srcintf). (optional)
    action = 'action_example' # str | datasource: Return all applicable datasource entries for a specific attribute based on simulate data. stats: Return CMDB aggregated statistics. find-index: Return indexes of provided primary keys with respect to filter. default: Return the CLI default values for this object type. json-schema: Return the JSON Schema for this object type. schema: Return the CLI schema for this object type. revision: Return the CMDB revision for this object type. transaction-list: List all configuration transaction(s). transaction-show: Show the content of the configuration transaction by transcation ID.  (optional)
    vdom = ['vdom_example'] # List[str] | Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom=root (Single VDOM) vdom=vdom1,vdom2 (Multiple VDOMs) vdom=* (All VDOMs)  (optional)

    try:
        # Select a specific entry from a CLI table.  Access Group: sysgrp
        api_response = await api_instance.system_affinity_interrupt_id_get(id, attr=attr, count=count, skip_to_datasource=skip_to_datasource, acs=acs, search=search, scope=scope, datasource=datasource, with_meta=with_meta, skip=skip, format=format, action=action, vdom=vdom)
        print("The response of SystemAffinityInterruptApi->system_affinity_interrupt_id_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SystemAffinityInterruptApi->system_affinity_interrupt_id_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**| mkey | 
 **attr** | **str**| Attribute name that references other table | [optional] 
 **count** | **int**| Maximum number of entries to return. | [optional] 
 **skip_to_datasource** | [**object**](.md)| Skip to provided table&#39;s Nth entry. E.g {datasource: &#39;firewall.address&#39;, pos: 10, global_entry: false} | [optional] 
 **acs** | **int**| If true, returned result are in ascending order. | [optional] 
 **search** | **str**| If present, the objects will be filtered by the search value. | [optional] 
 **scope** | **str**| Scope [global|vdom|both*] | [optional] 
 **datasource** | **bool**| Enable to include datasource information for each linked object. | [optional] 
 **with_meta** | **bool**| Enable to include meta information about each object (type id, references, etc). | [optional] 
 **skip** | **bool**| Enable to call CLI skip operator to hide skipped properties. | [optional] 
 **format** | [**List[str]**](str.md)| List of property names to include in results, separated by | (i.e. policyid|srcintf). | [optional] 
 **action** | **str**| datasource: Return all applicable datasource entries for a specific attribute based on simulate data. stats: Return CMDB aggregated statistics. find-index: Return indexes of provided primary keys with respect to filter. default: Return the CLI default values for this object type. json-schema: Return the JSON Schema for this object type. schema: Return the CLI schema for this object type. revision: Return the CMDB revision for this object type. transaction-list: List all configuration transaction(s). transaction-show: Show the content of the configuration transaction by transcation ID.  | [optional] 
 **vdom** | [**List[str]**](str.md)| Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom&#x3D;root (Single VDOM) vdom&#x3D;vdom1,vdom2 (Multiple VDOMs) vdom&#x3D;* (All VDOMs)  | [optional] 

### Return type

[**SystemAffinityInterruptIdGet200Response**](SystemAffinityInterruptIdGet200Response.md)

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

# **system_affinity_interrupt_id_put**
> system_affinity_interrupt_id_put(id, body, vdom=vdom, action=action, before=before, after=after, scope=scope)

Update this specific resource.  Access Group: sysgrp

### Example

* Api Key Authentication (APIKeyQueryParam):

```python
import microlab_fortinet
from microlab_fortinet.models.system_affinity_interrupt_id_get200_response import SystemAffinityInterruptIdGet200Response
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
    api_instance = microlab_fortinet.SystemAffinityInterruptApi(api_client)
    id = 56 # int | mkey
    body = microlab_fortinet.SystemAffinityInterruptIdGet200Response() # SystemAffinityInterruptIdGet200Response | Possible parameters to go in the body for the request
    vdom = ['vdom_example'] # List[str] | Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom=root (Single VDOM) vdom=vdom1,vdom2 (Multiple VDOMs) vdom=* (All VDOMs)  (optional)
    action = 'action_example' # str | If supported, an action can be specified. _move_: Move this specific resource. When *action=move* is set, one of the extra parameters (*before*, *after*) must be provided. __*Note:*__ If this parameter is provided when not supported, the action will be ignored and an “invalid request” error will be returned.  (optional)
    before = 'before_example' # str | If *action=move*, use *before* to specify the ID of the resource that this resource will be moved before. For example, to move `object 1` to before `object 2`, use: __action=move&before=2__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *move*.  (optional)
    after = 'after_example' # str | If *action=move*, use *after* to specify the ID of the resource that this resource will be moved after. For example, to move `object 1` to after `object 3`, use: __action=move&after=3__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *move*.  (optional)
    scope = 'scope_example' # str | Specify the Scope from which results are returned or changes are applied to. Objects are only existed in global scope. scope=global (optional)

    try:
        # Update this specific resource.  Access Group: sysgrp
        await api_instance.system_affinity_interrupt_id_put(id, body, vdom=vdom, action=action, before=before, after=after, scope=scope)
    except Exception as e:
        print("Exception when calling SystemAffinityInterruptApi->system_affinity_interrupt_id_put: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**| mkey | 
 **body** | [**SystemAffinityInterruptIdGet200Response**](SystemAffinityInterruptIdGet200Response.md)| Possible parameters to go in the body for the request | 
 **vdom** | [**List[str]**](str.md)| Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom&#x3D;root (Single VDOM) vdom&#x3D;vdom1,vdom2 (Multiple VDOMs) vdom&#x3D;* (All VDOMs)  | [optional] 
 **action** | **str**| If supported, an action can be specified. _move_: Move this specific resource. When *action&#x3D;move* is set, one of the extra parameters (*before*, *after*) must be provided. __*Note:*__ If this parameter is provided when not supported, the action will be ignored and an “invalid request” error will be returned.  | [optional] 
 **before** | **str**| If *action&#x3D;move*, use *before* to specify the ID of the resource that this resource will be moved before. For example, to move &#x60;object 1&#x60; to before &#x60;object 2&#x60;, use: __action&#x3D;move&amp;before&#x3D;2__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *move*.  | [optional] 
 **after** | **str**| If *action&#x3D;move*, use *after* to specify the ID of the resource that this resource will be moved after. For example, to move &#x60;object 1&#x60; to after &#x60;object 3&#x60;, use: __action&#x3D;move&amp;after&#x3D;3__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *move*.  | [optional] 
 **scope** | **str**| Specify the Scope from which results are returned or changes are applied to. Objects are only existed in global scope. scope&#x3D;global | [optional] 

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

# **system_affinity_interrupt_post**
> system_affinity_interrupt_post(body, vdom=vdom, action=action, nkey=nkey, scope=scope)

Create object(s) in this table.  Access Group: sysgrp

### Example

* Api Key Authentication (APIKeyQueryParam):

```python
import microlab_fortinet
from microlab_fortinet.models.system_affinity_interrupt_id_get200_response import SystemAffinityInterruptIdGet200Response
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
    api_instance = microlab_fortinet.SystemAffinityInterruptApi(api_client)
    body = microlab_fortinet.SystemAffinityInterruptIdGet200Response() # SystemAffinityInterruptIdGet200Response | Possible parameters to go in the body for the request
    vdom = ['vdom_example'] # List[str] | Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom=root (Single VDOM) vdom=vdom1,vdom2 (Multiple VDOMs) vdom=* (All VDOMs)  (optional)
    action = 'action_example' # str | If supported, an action can be specified. _clone_: Clone this specific resource. When *action=clone* is set, the extra parameters *nkey* must be provided. __*Note:*__ If this parameter is provided when not supported, the action will be ignored and an “invalid request” error will be returned.  (optional)
    nkey = 'nkey_example' # str |  If *action=clone*, use *nkey* to specify the ID for the new resource to be created. For example, to clone `address1` to `address1_clone`, use: __action=clone&nkey=address1_clone__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *clone*.  (optional)
    scope = 'scope_example' # str | Specify the Scope from which results are returned or changes are applied to. Objects are only existed in global scope. scope=global (optional)

    try:
        # Create object(s) in this table.  Access Group: sysgrp
        await api_instance.system_affinity_interrupt_post(body, vdom=vdom, action=action, nkey=nkey, scope=scope)
    except Exception as e:
        print("Exception when calling SystemAffinityInterruptApi->system_affinity_interrupt_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**SystemAffinityInterruptIdGet200Response**](SystemAffinityInterruptIdGet200Response.md)| Possible parameters to go in the body for the request | 
 **vdom** | [**List[str]**](str.md)| Specify the Virtual Domain(s) from which results are returned or changes are applied to. If this parameter is not provided, the management VDOM will be used. If the admin does not have access to the VDOM, a permission error will be returned. The URL parameter is one of: vdom&#x3D;root (Single VDOM) vdom&#x3D;vdom1,vdom2 (Multiple VDOMs) vdom&#x3D;* (All VDOMs)  | [optional] 
 **action** | **str**| If supported, an action can be specified. _clone_: Clone this specific resource. When *action&#x3D;clone* is set, the extra parameters *nkey* must be provided. __*Note:*__ If this parameter is provided when not supported, the action will be ignored and an “invalid request” error will be returned.  | [optional] 
 **nkey** | **str**|  If *action&#x3D;clone*, use *nkey* to specify the ID for the new resource to be created. For example, to clone &#x60;address1&#x60; to &#x60;address1_clone&#x60;, use: __action&#x3D;clone&amp;nkey&#x3D;address1_clone__ __*Note:*__ This parameter can only be used when the *action* parameter is set to *clone*.  | [optional] 
 **scope** | **str**| Specify the Scope from which results are returned or changes are applied to. Objects are only existed in global scope. scope&#x3D;global | [optional] 

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

