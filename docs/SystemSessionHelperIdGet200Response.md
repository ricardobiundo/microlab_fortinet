# SystemSessionHelperIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Session helper ID. | [optional] 
**name** | **str** | Helper name.    ftp:FTP.    tftp:TFTP.    ras:RAS.    h323:H323.    tns:TNS.    mms:MMS.    sip:SIP.    pptp:PPTP.    rtsp:RTSP.    dns-udp:DNS UDP.    dns-tcp:DNS TCP.    pmap:PMAP.    rsh:RSH.    dcerpc:DCERPC.    mgcp:MGCP. | [optional] 
**protocol** | **int** | Protocol number. | [optional] 
**port** | **int** | Protocol port. | [optional] 

## Example

```python
from microlab_fortinet.models.system_session_helper_id_get200_response import SystemSessionHelperIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSessionHelperIdGet200Response from a JSON string
system_session_helper_id_get200_response_instance = SystemSessionHelperIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSessionHelperIdGet200Response.to_json())

# convert the object into a dict
system_session_helper_id_get200_response_dict = system_session_helper_id_get200_response_instance.to_dict()
# create an instance of SystemSessionHelperIdGet200Response from a dict
system_session_helper_id_get200_response_from_dict = SystemSessionHelperIdGet200Response.from_dict(system_session_helper_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


