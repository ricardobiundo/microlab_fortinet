# SystemAutomationActionNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**description** | **str** | Description. | [optional] 
**action_type** | **str** | Action type.    email:Send notification email.    fortiexplorer-notification:Send push notification to FortiExplorer.    alert:Generate FortiOS dashboard alert.    disable-ssid:Disable interface.    system-actions:Perform immediate system operations on this FortiGate unit.    quarantine:Quarantine host.    quarantine-forticlient:Quarantine FortiClient by EMS.    quarantine-nsx:Quarantine NSX instance.    quarantine-fortinac:Quarantine host by FortiNAC.    ban-ip:Ban IP address.    aws-lambda:Send log data to integrated AWS service.    azure-function:Send log data to an Azure function.    google-cloud-function:Send log data to a Google Cloud function.    alicloud-function:Send log data to an AliCloud function.    webhook:Send an HTTP request.    cli-script:Run CLI script.    diagnose-script:Run diagnose script.    regular-expression:Match pattern on input text.    slack-notification:Send a notification message to a Slack incoming webhook.    microsoft-teams-notification:Send a notification message to a Microsoft Teams incoming webhook. | [optional] 
**system_action** | **str** | System action type.    reboot:Reboot this FortiGate unit.    shutdown:Shutdown this FortiGate unit.    backup-config:Backup current configuration to the disk revisions. | [optional] 
**tls_certificate** | **str** | Custom TLS certificate for API request. | [optional] 
**forticare_email** | **str** | Enable/disable use of your FortiCare email address as the email-to address.    enable:Enable use of your FortiCare email address as the email-to address.    disable:Disable use of your FortiCare email address as the email-to address. | [optional] 
**email_to** | [**List[SystemAutomationActionNameGet200ResponseEmailToInner]**](SystemAutomationActionNameGet200ResponseEmailToInner.md) | Email addresses. | [optional] 
**email_from** | **str** | Email sender name. | [optional] 
**email_subject** | **str** | Email subject. | [optional] 
**minimum_interval** | **int** | Limit execution to no more than once in this interval (in seconds). | [optional] 
**aws_api_key** | **str** | AWS API Gateway API key. | [optional] 
**azure_function_authorization** | **str** | Azure function authorization level.    anonymous:Anonymous authorization level (No authorization required).    function:Function authorization level (Function or Host Key required).    admin:Admin authorization level (Master Host Key required). | [optional] 
**azure_api_key** | **str** | Azure function API key. | [optional] 
**alicloud_function_authorization** | **str** | AliCloud function authorization type.    anonymous:Anonymous authorization (No authorization required).    function:Function authorization (Authorization required). | [optional] 
**alicloud_access_key_id** | **str** | AliCloud AccessKey ID. | [optional] 
**alicloud_access_key_secret** | **str** | AliCloud AccessKey secret. | [optional] 
**message_type** | **str** | Message type.    text:Plaintext.    json:Custom JSON.    form-data:Multipart/form-data | [optional] 
**message** | **str** | Message content. | [optional] 
**replacement_message** | **str** | Enable/disable replacement message.    enable:Enable replacement message.    disable:Disable replacement message. | [optional] 
**replacemsg_group** | **str** | Replacement message group. | [optional] 
**protocol** | **str** | Request protocol.    http:HTTP.    https:HTTPS. | [optional] 
**method** | **str** | Request method (POST, PUT, GET, PATCH or DELETE).    post:POST.    put:PUT.    get:GET.    patch:PATCH.    delete:DELETE. | [optional] 
**uri** | **str** | Request API URI. | [optional] 
**http_body** | **str** | Request body (if necessary). Should be serialized json string. | [optional] 
**port** | **int** | Protocol port. | [optional] 
**http_headers** | [**List[SystemAutomationActionNameGet200ResponseHttpHeadersInner]**](SystemAutomationActionNameGet200ResponseHttpHeadersInner.md) | Request headers. | [optional] 
**form_data** | [**List[SystemAutomationActionNameGet200ResponseFormDataInner]**](SystemAutomationActionNameGet200ResponseFormDataInner.md) | Form data parts for content type multipart/form-data. | [optional] 
**verify_host_cert** | **str** | Enable/disable verification of the remote host certificate.    enable:Enable verification of the remote host certificate.    disable:Disable verification of the remote host certificate. | [optional] 
**script** | **str** | CLI script. | [optional] 
**output_size** | **int** | Number of megabytes to limit script output to (1 - 1024, default &#x3D; 10). | [optional] 
**timeout** | **int** | Maximum running time for this script in seconds (0 &#x3D; no timeout). | [optional] 
**duration** | **int** | Maximum running time for this script in seconds. | [optional] 
**output_interval** | **int** | Collect the outputs for each output-interval in seconds (0 &#x3D; no intermediate output). | [optional] 
**file_only** | **str** | Enable/disable the output in files only.    enable:The output of the diag CLI will only be files.    disable:The output of the diag CLI will be in raw text, output larger than 64KB will be in files. | [optional] 
**execute_security_fabric** | **str** | Enable/disable execution of CLI script on all or only one FortiGate unit in the Security Fabric.    enable:CLI script executes on all FortiGate units in the Security Fabric.    disable:CLI script executes only on the FortiGate unit that the stitch is triggered. | [optional] 
**accprofile** | **str** | Access profile for CLI script action to access FortiGate features. | [optional] 
**regular_expression** | **str** | Regular expression string. | [optional] 
**log_debug_print** | **str** | Enable/disable logging debug print output from diagnose action.    enable:Enable logging debug print output from diagnose action.    disable:Disable logging debug print output from diagnose action. | [optional] 
**security_tag** | **str** | NSX security tag. | [optional] 
**sdn_connector** | [**List[SystemAutomationActionNameGet200ResponseSdnConnectorInner]**](SystemAutomationActionNameGet200ResponseSdnConnectorInner.md) | NSX SDN connector names. | [optional] 

## Example

```python
from microlab_fortinet.models.system_automation_action_name_get200_response import SystemAutomationActionNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutomationActionNameGet200Response from a JSON string
system_automation_action_name_get200_response_instance = SystemAutomationActionNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAutomationActionNameGet200Response.to_json())

# convert the object into a dict
system_automation_action_name_get200_response_dict = system_automation_action_name_get200_response_instance.to_dict()
# create an instance of SystemAutomationActionNameGet200Response from a dict
system_automation_action_name_get200_response_from_dict = SystemAutomationActionNameGet200Response.from_dict(system_automation_action_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


