# UserRadiusNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | RADIUS server entry name. | [optional] 
**server** | **str** | Primary RADIUS server CN domain name or IP address. | [optional] 
**secret** | **str** | Pre-shared secret key used to access the primary RADIUS server. | [optional] 
**secondary_server** | **str** | Secondary RADIUS CN domain name or IP address. | [optional] 
**secondary_secret** | **str** | Secret key to access the secondary server. | [optional] 
**tertiary_server** | **str** | Tertiary RADIUS CN domain name or IP address. | [optional] 
**tertiary_secret** | **str** | Secret key to access the tertiary server. | [optional] 
**timeout** | **int** | Time in seconds to retry connecting server. | [optional] 
**status_ttl** | **int** | Time for which server reachability is cached so that when a server is unreachable, it will not be retried for at least this period of time (0 &#x3D; cache disabled, default &#x3D; 300). | [optional] 
**all_usergroup** | **str** | Enable/disable automatically including this RADIUS server in all user groups.    disable:Do not automatically include this server in a user group.    enable:Include this RADIUS server in every user group. | [optional] 
**use_management_vdom** | **str** | Enable/disable using management VDOM to send requests.    enable:Send requests using the management VDOM.    disable:Send requests using the current VDOM. | [optional] 
**switch_controller_nas_ip_dynamic** | **str** | Enable/Disable switch-controller nas-ip dynamic to dynamically set nas-ip.    enable:Enable dynamic NAS-IP setting.    disable:Disable dynamic NAS-IP setting. | [optional] 
**nas_ip** | **str** | IP address used to communicate with the RADIUS server and used as NAS-IP-Address and Called-Station-ID attributes. | [optional] 
**nas_id_type** | **str** | NAS identifier type configuration (default &#x3D; legacy).    legacy:NAS-ID value is the value previously used by each daemon.    custom:NAS-ID value is customized.    hostname:NAS-ID value is hostname or HA group name if applicable. | [optional] 
**call_station_id_type** | **str** | Calling &amp; Called station identifier type configuration (default &#x3D; legacy), this option is not available for 802.1x authentication.     legacy:Calling &amp; Called station identifier is the value previously used by each daemon.    IP:Calling &amp; Called station identifier is the value of IP address.     MAC:Calling &amp; Called station identifier is the value of MAC address.  | [optional] 
**nas_id** | **str** | Custom NAS identifier. | [optional] 
**acct_interim_interval** | **int** | Time in seconds between each accounting interim update message. | [optional] 
**radius_coa** | **str** | Enable to allow a mechanism to change the attributes of an authentication, authorization, and accounting session after it is authenticated.    enable:Enable RADIUS CoA.    disable:Disable RADIUS CoA. | [optional] 
**radius_port** | **int** | RADIUS service port number. | [optional] 
**h3c_compatibility** | **str** | Enable/disable compatibility with the H3C, a mechanism that performs security checking for authentication.    enable:Enable H3C compatibility.    disable:Disable H3C compatibility. | [optional] 
**auth_type** | **str** | Authentication methods/protocols permitted for this RADIUS server.    auto:Use PAP, MSCHAP_v2, and CHAP (in that order).    ms_chap_v2:Microsoft Challenge Handshake Authentication Protocol version 2.    ms_chap:Microsoft Challenge Handshake Authentication Protocol.    chap:Challenge Handshake Authentication Protocol.    pap:Password Authentication Protocol. | [optional] 
**source_ip** | **str** | Source IP address for communications to the RADIUS server. | [optional] 
**source_ip_interface** | **str** | Source interface for communication with the RADIUS server. | [optional] 
**username_case_sensitive** | **str** | Enable/disable case sensitive user names.    enable:Enable username case-sensitive.    disable:Disable username case-sensitive. | [optional] 
**group_override_attr_type** | **str** | RADIUS attribute type to override user group information.    filter-Id:Filter-Id    class:Class | [optional] 
**var_class** | [**List[UserRadiusNameGet200ResponseClassInner]**](UserRadiusNameGet200ResponseClassInner.md) | Class attribute name(s). | [optional] 
**password_renewal** | **str** | Enable/disable password renewal.    enable:Enable password renewal.    disable:Disable password renewal. | [optional] 
**require_message_authenticator** | **str** | Require message authenticator in authentication response.    enable:Make the validation of message authenticator mandatory in authentication response.    disable:Make the validation of message authenticator optional in authentication response. | [optional] 
**password_encoding** | **str** | Password encoding.    auto:Use original password encoding.    ISO-8859-1:Use ISO-8859-1 password encoding. | [optional] 
**mac_username_delimiter** | **str** | MAC authentication username delimiter (default &#x3D; hyphen).    hyphen:Use hyphen as delimiter for MAC authentication username.    single-hyphen:Use single hyphen as delimiter for MAC authentication username.    colon:Use colon as delimiter for MAC authentication username.    none:No delimiter for MAC authentication username. | [optional] 
**mac_password_delimiter** | **str** | MAC authentication password delimiter (default &#x3D; hyphen).    hyphen:Use hyphen as delimiter for MAC authentication password.    single-hyphen:Use single hyphen as delimiter for MAC authentication password.    colon:Use colon as delimiter for MAC authentication password.    none:No delimiter for MAC authentication password. | [optional] 
**mac_case** | **str** | MAC authentication case (default &#x3D; lowercase).    uppercase:Use uppercase MAC.    lowercase:Use lowercase MAC. | [optional] 
**acct_all_servers** | **str** | Enable/disable sending of accounting messages to all configured servers (default &#x3D; disable).    enable:Send accounting messages to all configured servers.    disable:Send accounting message only to servers that are confirmed to be reachable. | [optional] 
**switch_controller_acct_fast_framedip_detect** | **int** | Switch controller accounting message Framed-IP detection from DHCP snooping (seconds, default&#x3D;2). | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 
**switch_controller_service_type** | **str** | RADIUS service type.    login:User should be connected to a host.    framed:User use Framed Protocol.    callback-login:User disconnected and called back.    callback-framed:User disconnected and called back, then a Framed Protocol.    outbound:User granted access to outgoing devices.    administrative:User granted access to the administrative unsigned interface.    nas-prompt:User provided a command prompt on the NAS.    authenticate-only:Authentication requested, and no auth info needs to be returned.    callback-nas-prompt:User disconnected and called back, then provided a command prompt.    call-check:Used by the NAS in an Access-Request packet, Access-Accept to answer the call.    callback-administrative:User disconnected and called back, granted access to the admin unsigned interface. | [optional] 
**transport_protocol** | **str** | Transport protocol to be used (default &#x3D; udp).    udp:UDP.    tcp:TCP.    tls:TLS over TCP. | [optional] 
**tls_min_proto_version** | **str** | Minimum supported protocol version for TLS connections (default is to follow system global setting).    default:Follow system global setting.    SSLv3:SSLv3.    TLSv1:TLSv1.    TLSv1-1:TLSv1.1.    TLSv1-2:TLSv1.2.    TLSv1-3:TLSv1.3. | [optional] 
**ca_cert** | **str** | CA of server to trust under TLS. | [optional] 
**client_cert** | **str** | Client certificate to use under TLS. | [optional] 
**server_identity_check** | **str** | Enable/disable RADIUS server identity check (verify server domain name/IP address against the server certificate).    enable:Enable server identity check.    disable:Disable server identity check. | [optional] 
**account_key_processing** | **str** | Account key processing operation. The FortiGate will keep either the whole domain or strip the domain from the subject identity.    same:Same as subject identity field.    strip:Strip domain string from subject identity field. | [optional] 
**account_key_cert_field** | **str** | Define subject identity field in certificate for user access right checking.    othername:Other name in SAN.    rfc822name:RFC822 email address in SAN.    dnsname:DNS name in SAN.    cn:CN in subject. | [optional] 
**rsso** | **str** | Enable/disable RADIUS based single sign on feature.    enable:Enable RADIUS based single sign on feature.    disable:Disable RADIUS based single sign on feature. | [optional] 
**rsso_radius_server_port** | **int** | UDP port to listen on for RADIUS Start and Stop records. | [optional] 
**rsso_radius_response** | **str** | Enable/disable sending RADIUS response packets after receiving Start and Stop records.    enable:Enable sending RADIUS response packets.    disable:Disable sending RADIUS response packets. | [optional] 
**rsso_validate_request_secret** | **str** | Enable/disable validating the RADIUS request shared secret in the Start or End record.    enable:Enable validating RADIUS request shared secret.    disable:Disable validating RADIUS request shared secret. | [optional] 
**rsso_secret** | **str** | RADIUS secret used by the RADIUS accounting server. | [optional] 
**rsso_endpoint_attribute** | **str** | RADIUS attributes used to extract the user end point identifier from the RADIUS Start record.    User-Name:Use this attribute.    NAS-IP-Address:Use this attribute.    Framed-IP-Address:Use this attribute.    Framed-IP-Netmask:Use this attribute.    Filter-Id:Use this attribute.    Login-IP-Host:Use this attribute.    Reply-Message:Use this attribute.    Callback-Number:Use this attribute.    Callback-Id:Use this attribute.    Framed-Route:Use this attribute.    Framed-IPX-Network:Use this attribute.    Class:Use this attribute.    Called-Station-Id:Use this attribute.    Calling-Station-Id:Use this attribute.    NAS-Identifier:Use this attribute.    Proxy-State:Use this attribute.    Login-LAT-Service:Use this attribute.    Login-LAT-Node:Use this attribute.    Login-LAT-Group:Use this attribute.    Framed-AppleTalk-Zone:Use this attribute.    Acct-Session-Id:Use this attribute.    Acct-Multi-Session-Id:Use this attribute. | [optional] 
**rsso_endpoint_block_attribute** | **str** | RADIUS attributes used to block a user.    User-Name:Use this attribute.    NAS-IP-Address:Use this attribute.    Framed-IP-Address:Use this attribute.    Framed-IP-Netmask:Use this attribute.    Filter-Id:Use this attribute.    Login-IP-Host:Use this attribute.    Reply-Message:Use this attribute.    Callback-Number:Use this attribute.    Callback-Id:Use this attribute.    Framed-Route:Use this attribute.    Framed-IPX-Network:Use this attribute.    Class:Use this attribute.    Called-Station-Id:Use this attribute.    Calling-Station-Id:Use this attribute.    NAS-Identifier:Use this attribute.    Proxy-State:Use this attribute.    Login-LAT-Service:Use this attribute.    Login-LAT-Node:Use this attribute.    Login-LAT-Group:Use this attribute.    Framed-AppleTalk-Zone:Use this attribute.    Acct-Session-Id:Use this attribute.    Acct-Multi-Session-Id:Use this attribute. | [optional] 
**sso_attribute** | **str** | RADIUS attribute that contains the profile group name to be extracted from the RADIUS Start record.    User-Name:Use this attribute.    NAS-IP-Address:Use this attribute.    Framed-IP-Address:Use this attribute.    Framed-IP-Netmask:Use this attribute.    Filter-Id:Use this attribute.    Login-IP-Host:Use this attribute.    Reply-Message:Use this attribute.    Callback-Number:Use this attribute.    Callback-Id:Use this attribute.    Framed-Route:Use this attribute.    Framed-IPX-Network:Use this attribute.    Class:Use this attribute.    Called-Station-Id:Use this attribute.    Calling-Station-Id:Use this attribute.    NAS-Identifier:Use this attribute.    Proxy-State:Use this attribute.    Login-LAT-Service:Use this attribute.    Login-LAT-Node:Use this attribute.    Login-LAT-Group:Use this attribute.    Framed-AppleTalk-Zone:Use this attribute.    Acct-Session-Id:Use this attribute.    Acct-Multi-Session-Id:Use this attribute. | [optional] 
**sso_attribute_key** | **str** | Key prefix for SSO group value in the SSO attribute. | [optional] 
**sso_attribute_value_override** | **str** | Enable/disable override old attribute value with new value for the same endpoint.    enable:Enable override old attribute value with new value for the same endpoint.    disable:Disable override old attribute value with new value for the same endpoint. | [optional] 
**rsso_context_timeout** | **int** | Time in seconds before the logged out user is removed from the \&quot;user context list\&quot; of logged on users. | [optional] 
**rsso_log_period** | **int** | Time interval in seconds that group event log messages will be generated for dynamic profile events. | [optional] 
**rsso_log_flags** | **str** | Events to log.    protocol-error:Enable this log type.    profile-missing:Enable this log type.    accounting-stop-missed:Enable this log type.    accounting-event:Enable this log type.    endpoint-block:Enable this log type.    radiusd-other:Enable this log type.    none:Disable all logging. | [optional] 
**rsso_flush_ip_session** | **str** | Enable/disable flushing user IP sessions on RADIUS accounting Stop messages.    enable:Enable flush user IP sessions on RADIUS accounting stop.    disable:Disable flush user IP sessions on RADIUS accounting stop. | [optional] 
**rsso_ep_one_ip_only** | **str** | Enable/disable the replacement of old IP addresses with new ones for the same endpoint on RADIUS accounting Start messages.    enable:Enable replacement of old IP address with new IP address for the same endpoint on RADIUS accounting start.    disable:Disable replacement of old IP address with new IP address for the same endpoint on RADIUS accounting start. | [optional] 
**delimiter** | **str** | Configure delimiter to be used for separating profile group names in the SSO attribute (default &#x3D; plus character \&quot;+\&quot;).    plus:Plus character \&quot;+\&quot;.    comma:Comma character \&quot;,\&quot;. | [optional] 
**accounting_server** | [**List[UserRadiusNameGet200ResponseAccountingServerInner]**](UserRadiusNameGet200ResponseAccountingServerInner.md) | Additional accounting servers. | [optional] 

## Example

```python
from microlab_fortinet.models.user_radius_name_get200_response import UserRadiusNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserRadiusNameGet200Response from a JSON string
user_radius_name_get200_response_instance = UserRadiusNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserRadiusNameGet200Response.to_json())

# convert the object into a dict
user_radius_name_get200_response_dict = user_radius_name_get200_response_instance.to_dict()
# create an instance of UserRadiusNameGet200Response from a dict
user_radius_name_get200_response_from_dict = UserRadiusNameGet200Response.from_dict(user_radius_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


