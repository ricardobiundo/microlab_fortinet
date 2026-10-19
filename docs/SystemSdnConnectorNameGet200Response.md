# SystemSdnConnectorNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | SDN connector name. | [optional] 
**status** | **str** | Enable/disable connection to the remote SDN connector.    disable:Disable connection to this SDN Connector.    enable:Enable connection to this SDN Connector. | [optional] 
**type** | **str** | Type of SDN connector.    aci:Application Centric Infrastructure (ACI).    alicloud:AliCloud Service (ACS).    aws:Amazon Web Services (AWS).    azure:Microsoft Azure.    gcp:Google Cloud Platform (GCP).    nsx:VMware NSX.    nuage:Nuage VSP.    oci:Oracle Cloud Infrastructure.    openstack:OpenStack.    kubernetes:Kubernetes.    vmware:VMware vSphere (vCenter &amp; ESXi).    sepm:Symantec Endpoint Protection Manager.    aci-direct:Application Centric Infrastructure (ACI Direct Connection).    ibm:IBM Cloud Infrastructure.    nutanix:Nutanix Prism Central.    sap:SAP Control. | [optional] 
**proxy** | **str** | SDN proxy. | [optional] 
**use_metadata_iam** | **str** | Enable/disable use of IAM role from metadata to call API.    disable:Disable using IAM role to call API.    enable:Enable using IAM role to call API. | [optional] 
**microsoft_365** | **str** | Enable to use as Microsoft 365 connector.    disable:Azure SDN connector    enable:Microsoft 365 SDN connector | [optional] 
**ha_status** | **str** | Enable/disable use for FortiGate HA service.    disable:Disable use for FortiGate HA service.    enable:Enable use for FortiGate HA service. | [optional] 
**verify_certificate** | **str** | Enable/disable server certificate verification.    disable:Disable server certificate verification.    enable:Enable server certificate verification. | [optional] 
**vdom** | **str** | Virtual domain name of the remote SDN connector. | [optional] 
**server** | **str** | Server address of the remote SDN connector. | [optional] 
**server_list** | [**List[SystemSdnConnectorNameGet200ResponseServerListInner]**](SystemSdnConnectorNameGet200ResponseServerListInner.md) | Server address list of the remote SDN connector. | [optional] 
**server_port** | **int** | Port number of the remote SDN connector. | [optional] 
**message_server_port** | **int** | HTTP port number of the SAP message server. | [optional] 
**username** | **str** | Username of the remote SDN connector as login credentials. | [optional] 
**password** | **str** | Password of the remote SDN connector as login credentials. | [optional] 
**vcenter_server** | **str** | vCenter server address for NSX quarantine. | [optional] 
**vcenter_username** | **str** | vCenter server username for NSX quarantine. | [optional] 
**vcenter_password** | **str** | vCenter server password for NSX quarantine. | [optional] 
**access_key** | **str** | AWS / ACS access key ID. | [optional] 
**secret_key** | **str** | AWS / ACS secret access key. | [optional] 
**region** | **str** | AWS / ACS region name. | [optional] 
**vpc_id** | **str** | AWS VPC ID. | [optional] 
**alt_resource_ip** | **str** | Enable/disable AWS alternative resource IP.    disable:Disable AWS alternative resource IP.    enable:Enable AWS alternative resource IP. | [optional] 
**external_account_list** | [**List[SystemSdnConnectorNameGet200ResponseExternalAccountListInner]**](SystemSdnConnectorNameGet200ResponseExternalAccountListInner.md) | Configure AWS external account list. | [optional] 
**tenant_id** | **str** | Tenant ID (directory ID). | [optional] 
**client_id** | **str** | Azure client ID (application ID). | [optional] 
**client_secret** | **str** | Azure client secret (application key). | [optional] 
**subscription_id** | **str** | Azure subscription ID. | [optional] 
**resource_group** | **str** | Azure resource group. | [optional] 
**login_endpoint** | **str** | Azure Stack login endpoint. | [optional] 
**resource_url** | **str** | Azure Stack resource URL. | [optional] 
**azure_region** | **str** | Azure server region.    global:Global Azure Server.    china:China Azure Server.    germany:Germany Azure Server.    usgov:US Government Azure Server.    local:Azure Stack Local Server. | [optional] 
**nic** | [**List[SystemSdnConnectorNameGet200ResponseNicInner]**](SystemSdnConnectorNameGet200ResponseNicInner.md) | Configure Azure network interface. | [optional] 
**route_table** | [**List[SystemSdnConnectorNameGet200ResponseRouteTableInner]**](SystemSdnConnectorNameGet200ResponseRouteTableInner.md) | Configure Azure route table. | [optional] 
**user_id** | **str** | User ID. | [optional] 
**compartment_list** | [**List[SystemSdnConnectorNameGet200ResponseCompartmentListInner]**](SystemSdnConnectorNameGet200ResponseCompartmentListInner.md) | Configure OCI compartment list. | [optional] 
**oci_region_list** | [**List[SystemSdnConnectorNameGet200ResponseOciRegionListInner]**](SystemSdnConnectorNameGet200ResponseOciRegionListInner.md) | Configure OCI region list. | [optional] 
**oci_region_type** | **str** | OCI region type.    commercial:Commercial region.    government:Government region. | [optional] 
**oci_cert** | **str** | OCI certificate. | [optional] 
**oci_fingerprint** | **str** | OCI pubkey fingerprint. | [optional] 
**external_ip** | [**List[SystemSdnConnectorNameGet200ResponseExternalIpInner]**](SystemSdnConnectorNameGet200ResponseExternalIpInner.md) | Configure GCP external IP. | [optional] 
**route** | [**List[SystemSdnConnectorNameGet200ResponseRouteInner]**](SystemSdnConnectorNameGet200ResponseRouteInner.md) | Configure GCP route. | [optional] 
**gcp_project_list** | [**List[SystemSdnConnectorNameGet200ResponseGcpProjectListInner]**](SystemSdnConnectorNameGet200ResponseGcpProjectListInner.md) | Configure GCP project list. | [optional] 
**forwarding_rule** | [**List[SystemSdnConnectorNameGet200ResponseForwardingRuleInner]**](SystemSdnConnectorNameGet200ResponseForwardingRuleInner.md) | Configure GCP forwarding rule. | [optional] 
**service_account** | **str** | GCP service account email. | [optional] 
**private_key** | **str** | Private key of GCP service account. | [optional] 
**secret_token** | **str** | Secret token of Kubernetes service account. | [optional] 
**domain** | **str** | Domain name. | [optional] 
**group_name** | **str** | Full path group name of computers. | [optional] 
**server_cert** | **str** | Trust servers that contain this certificate only. | [optional] 
**server_ca_cert** | **str** | Trust only those servers whose certificate is directly/indirectly signed by this certificate. | [optional] 
**api_key** | **str** | IBM cloud API key or service ID API key. | [optional] 
**ibm_region** | **str** | IBM cloud region name.    dallas:US South (Dallas) Public Endpoint.    washington-dc:US East (Washington DC) Public Endpoint.    london:United Kingdom (London) Public Endpoint.    frankfurt:Germany (Frankfurt) Public Endpoint.    sydney:Australia (Sydney) Public Endpoint.    tokyo:Japan (Tokyo) Public Endpoint.    osaka:Japan (Osaka) Public Endpoint.    toronto:Canada (Toronto) Public Endpoint.    sao-paulo:Brazil (Sao Paulo) Public Endpoint.    madrid:Spain (Madrid) Public Endpoint. | [optional] 
**par_id** | **str** | Public address range ID. | [optional] 
**update_interval** | **int** | Dynamic object update interval (30 - 3600 sec, default &#x3D; 60, 0 &#x3D; disabled). | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_connector_name_get200_response import SystemSdnConnectorNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnConnectorNameGet200Response from a JSON string
system_sdn_connector_name_get200_response_instance = SystemSdnConnectorNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSdnConnectorNameGet200Response.to_json())

# convert the object into a dict
system_sdn_connector_name_get200_response_dict = system_sdn_connector_name_get200_response_instance.to_dict()
# create an instance of SystemSdnConnectorNameGet200Response from a dict
system_sdn_connector_name_get200_response_from_dict = SystemSdnConnectorNameGet200Response.from_dict(system_sdn_connector_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


