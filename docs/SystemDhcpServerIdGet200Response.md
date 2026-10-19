# SystemDhcpServerIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**status** | **str** | Enable/disable this DHCP configuration.    disable:Do not use this DHCP server configuration.    enable:Use this DHCP server configuration. | [optional] 
**lease_time** | **int** | Lease time in seconds, 0 means unlimited. | [optional] 
**mac_acl_default_action** | **str** | MAC access control default action (allow or block assigning IP settings).    assign:Allow the DHCP server to assign IP settings to clients on the MAC access control list.    block:Block the DHCP server from assigning IP settings to clients on the MAC access control list. | [optional] 
**forticlient_on_net_status** | **str** | Enable/disable FortiClient-On-Net service for this DHCP server.    disable:Disable FortiClient On-Net Status.    enable:Enable FortiClient On-Net Status. | [optional] 
**dns_service** | **str** | Options for assigning DNS servers to DHCP clients.    local:IP address of the interface the DHCP server is added to becomes the client&#39;s DNS server IP address.    default:Clients are assigned the FortiGate&#39;s configured DNS servers.    specify:Specify up to 3 DNS servers in the DHCP server configuration. | [optional] 
**dns_server1** | **str** | DNS server 1. | [optional] 
**dns_server2** | **str** | DNS server 2. | [optional] 
**dns_server3** | **str** | DNS server 3. | [optional] 
**dns_server4** | **str** | DNS server 4. | [optional] 
**wifi_ac_service** | **str** | Options for assigning WiFi access controllers to DHCP clients.    specify:Specify up to 3 WiFi Access Controllers in the DHCP server configuration.    local:IP address of the interface the DHCP server is added to becomes the client&#39;s WiFi Access Controller IP address. | [optional] 
**wifi_ac1** | **str** | WiFi Access Controller 1 IP address (DHCP option 138, RFC 5417). | [optional] 
**wifi_ac2** | **str** | WiFi Access Controller 2 IP address (DHCP option 138, RFC 5417). | [optional] 
**wifi_ac3** | **str** | WiFi Access Controller 3 IP address (DHCP option 138, RFC 5417). | [optional] 
**ntp_service** | **str** | Options for assigning Network Time Protocol (NTP) servers to DHCP clients.    local:IP address of the interface the DHCP server is added to becomes the client&#39;s NTP server IP address.    default:Clients are assigned the FortiGate&#39;s configured NTP servers.    specify:Specify up to 3 NTP servers in the DHCP server configuration. | [optional] 
**ntp_server1** | **str** | NTP server 1. | [optional] 
**ntp_server2** | **str** | NTP server 2. | [optional] 
**ntp_server3** | **str** | NTP server 3. | [optional] 
**domain** | **str** | Domain name suffix for the IP addresses that the DHCP server assigns to clients. | [optional] 
**wins_server1** | **str** | WINS server 1. | [optional] 
**wins_server2** | **str** | WINS server 2. | [optional] 
**default_gateway** | **str** | Default gateway IP address assigned by the DHCP server. | [optional] 
**next_server** | **str** | IP address of a server (for example, a TFTP sever) that DHCP clients can download a boot file from. | [optional] 
**netmask** | **str** | Netmask assigned by the DHCP server. | [optional] 
**interface** | **str** | DHCP server can assign IP configurations to clients connected to this interface. | [optional] 
**ip_range** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInner]**](SystemDhcpServerIdGet200ResponseIpRangeInner.md) | DHCP IP range configuration. | [optional] 
**timezone_option** | **str** | Options for the DHCP server to set the client&#39;s time zone.    disable:Do not set the client&#39;s time zone.    default:Clients are assigned the FortiGate&#39;s configured time zone.    specify:Specify the time zone to be assigned to DHCP clients. | [optional] 
**timezone** | **str** | Select the time zone to be assigned to DHCP clients. | [optional] 
**tftp_server** | [**List[SystemDhcpServerIdGet200ResponseTftpServerInner]**](SystemDhcpServerIdGet200ResponseTftpServerInner.md) | One or more hostnames or IP addresses of the TFTP servers in quotes separated by spaces. | [optional] 
**filename** | **str** | Name of the boot file on the TFTP server. | [optional] 
**options** | [**List[SystemDhcpServerIdGet200ResponseOptionsInner]**](SystemDhcpServerIdGet200ResponseOptionsInner.md) | DHCP options. | [optional] 
**server_type** | **str** | DHCP server can be a normal DHCP server or an IPsec DHCP server.    regular:Regular DHCP service.    ipsec:DHCP over IPsec service. | [optional] 
**ip_mode** | **str** | Method used to assign client IP.    range:Use range defined by start-ip/end-ip to assign client IP.    usrgrp:Use user-group defined method to assign client IP. | [optional] 
**conflicted_ip_timeout** | **int** | Time in seconds to wait after a conflicted IP address is removed from the DHCP range before it can be reused. | [optional] 
**ipsec_lease_hold** | **int** | DHCP over IPsec leases expire this many seconds after tunnel down (0 to disable forced-expiry). | [optional] 
**auto_configuration** | **str** | Enable/disable auto configuration.    disable:Disable auto configuration.    enable:Enable auto configuration. | [optional] 
**dhcp_settings_from_fortiipam** | **str** | Enable/disable populating of DHCP server settings from FortiIPAM.    disable:Disable populating of DHCP server settings from FortiIPAM.    enable:Enable populating of DHCP server settings from FortiIPAM. | [optional] 
**auto_managed_status** | **str** | Enable/disable use of this DHCP server once this interface has been assigned an IP address from FortiIPAM.    disable:Disable use of this DHCP server once this interface has been assigned an IP address from FortiIPAM.    enable:Enable use of this DHCP server once this interface has been assigned an IP address from FortiIPAM. | [optional] 
**ddns_update** | **str** | Enable/disable DDNS update for DHCP.    disable:Disable DDNS update for DHCP.    enable:Enable DDNS update for DHCP. | [optional] 
**ddns_update_override** | **str** | Enable/disable DDNS update override for DHCP.    disable:Disable DDNS update override for DHCP.    enable:Enable DDNS update override for DHCP. | [optional] 
**ddns_server_ip** | **str** | DDNS server IP. | [optional] 
**ddns_zone** | **str** | Zone of your domain name (ex. DDNS.com). | [optional] 
**ddns_auth** | **str** | DDNS authentication mode.    disable:Disable DDNS authentication.    tsig:TSIG based on RFC2845. | [optional] 
**ddns_keyname** | **str** | DDNS update key name. | [optional] 
**ddns_key** | **str** | DDNS update key (base 64 encoding). | [optional] 
**ddns_ttl** | **int** | TTL. | [optional] 
**vci_match** | **str** | Enable/disable vendor class identifier (VCI) matching. When enabled only DHCP requests with a matching VCI are served.    disable:Disable VCI matching.    enable:Enable VCI matching. | [optional] 
**vci_string** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner]**](SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner.md) | One or more VCI strings in quotes separated by spaces. | [optional] 
**exclude_range** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInner]**](SystemDhcpServerIdGet200ResponseIpRangeInner.md) | Exclude one or more ranges of IP addresses from being assigned to clients. | [optional] 
**shared_subnet** | **str** | Enable/disable shared subnet.    disable:Disable shared subnet.    enable:Enable shared subnet. | [optional] 
**relay_agent** | **str** | Relay agent IP. | [optional] 
**reserved_address** | [**List[SystemDhcpServerIdGet200ResponseReservedAddressInner]**](SystemDhcpServerIdGet200ResponseReservedAddressInner.md) | Options for the DHCP server to assign IP settings to specific MAC addresses. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dhcp_server_id_get200_response import SystemDhcpServerIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDhcpServerIdGet200Response from a JSON string
system_dhcp_server_id_get200_response_instance = SystemDhcpServerIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDhcpServerIdGet200Response.to_json())

# convert the object into a dict
system_dhcp_server_id_get200_response_dict = system_dhcp_server_id_get200_response_instance.to_dict()
# create an instance of SystemDhcpServerIdGet200Response from a dict
system_dhcp_server_id_get200_response_from_dict = SystemDhcpServerIdGet200Response.from_dict(system_dhcp_server_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


