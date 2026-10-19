# SystemInterfaceNameGet200ResponseIpv6Inner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip6_mode** | **str** | Addressing mode (static, DHCP, delegated).    static:Static setting.    dhcp:DHCPv6 client mode.    pppoe:IPv6 over PPPoE mode.    delegated:IPv6 address with delegated prefix. | [optional] 
**client_options** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner]**](SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner.md) | DHCP6 client options. | [optional] 
**nd_mode** | **str** | Neighbor discovery mode.    basic:Do not support SEND.    SEND-compatible:Support SEND. | [optional] 
**nd_cert** | **str** | Neighbor discovery certificate. | [optional] 
**nd_security_level** | **int** | Neighbor discovery security level (0 - 7; 0 &#x3D; least secure, default &#x3D; 0). | [optional] 
**nd_timestamp_delta** | **int** | Neighbor discovery timestamp delta value (1 - 3600 sec; default &#x3D; 300). | [optional] 
**nd_timestamp_fuzz** | **int** | Neighbor discovery timestamp fuzz factor (1 - 60 sec; default &#x3D; 1). | [optional] 
**nd_cga_modifier** | **str** | Neighbor discovery CGA modifier. | [optional] 
**ip6_dns_server_override** | **str** | Enable/disable using the DNS server acquired by DHCP.    enable:Enable using the DNS server acquired by DHCP.    disable:Disable using the DNS server acquired by DHCP. | [optional] 
**ip6_address** | **str** | Primary IPv6 address prefix. Syntax: xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx/xxx. | [optional] 
**ip6_extra_addr** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerIp6ExtraAddrInner]**](SystemInterfaceNameGet200ResponseIpv6InnerIp6ExtraAddrInner.md) | Extra IPv6 address prefixes of interface. | [optional] 
**ip6_allowaccess** | **str** | Allow management access to the interface.    ping:PING access.    https:HTTPS access.    ssh:SSH access.    snmp:SNMP access.    http:HTTP access.    telnet:TELNET access.    fgfm:FortiManager access.    fabric:Security Fabric access.    scim:System for Cross-domain Identity Management (SCIM) access.    probe-response:Probe access. | [optional] 
**ip6_send_adv** | **str** | Enable/disable sending advertisements about the interface.    enable:Enable sending advertisements about this interface.    disable:Disable sending advertisements about this interface. | [optional] 
**icmp6_send_redirect** | **str** | Enable/disable sending of ICMPv6 redirects.    enable:Enable sending of ICMPv6 redirects.    disable:Disable sending of ICMPv6 redirects. | [optional] 
**ip6_manage_flag** | **str** | Enable/disable the managed flag.    enable:Enable the managed IPv6 flag.    disable:Disable the managed IPv6 flag. | [optional] 
**ip6_other_flag** | **str** | Enable/disable the other IPv6 flag.    enable:Enable the other IPv6 flag.    disable:Disable the other IPv6 flag. | [optional] 
**ip6_max_interval** | **int** | IPv6 maximum interval (4 to 1800 sec). | [optional] 
**ip6_min_interval** | **int** | IPv6 minimum interval (3 to 1350 sec). | [optional] 
**ip6_link_mtu** | **int** | IPv6 link MTU. | [optional] 
**ra_send_mtu** | **str** | Enable/disable sending link MTU in RA packet.    enable:Enable sending link MTU in RA packet.    disable:Disable sending link MTU in RA packet. | [optional] 
**ip6_reachable_time** | **int** | IPv6 reachable time (milliseconds; 0 means unspecified). | [optional] 
**ip6_retrans_time** | **int** | IPv6 retransmit time (milliseconds; 0 means unspecified). | [optional] 
**ip6_default_life** | **int** | Default life (sec). | [optional] 
**ip6_hop_limit** | **int** | Hop limit (0 means unspecified). | [optional] 
**ip6_adv_rio** | **str** | Enable/disable sending advertisements with route information option.    enable:Enable sending advertisements with route information option.    disable:Disable sending advertisements with route information option. | [optional] 
**ip6_route_pref** | **str** | Set route preference to the interface (default &#x3D; medium).    medium:Medium route preferences in RA packet.    high:High route preferences in RA packet.    low:Low route preferences in RA packet. | [optional] 
**ip6_route_list** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner]**](SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner.md) | Advertised route list. | [optional] 
**autoconf** | **str** | Enable/disable address auto config.    enable:Enable auto-configuration.    disable:Disable auto-configuration. | [optional] 
**unique_autoconf_addr** | **str** | Enable/disable unique auto config address.    enable:Enable unique auto-configuration address.    disable:Disable unique auto-configuration address. | [optional] 
**interface_identifier** | **str** | IPv6 interface identifier. | [optional] 
**ip6_prefix_mode** | **str** | Assigning a prefix from DHCP or RA.    dhcp6:Use delegated prefix from a DHCPv6 client to form a delegated IPv6 address.    ra:Use prefix from RA to form a delegated IPv6 address. | [optional] 
**ip6_delegated_prefix_iaid** | **int** | IAID of obtained delegated-prefix from the upstream interface. | [optional] 
**ip6_upstream_interface** | **str** | Interface name providing delegated information. | [optional] 
**ip6_subnet** | **str** | Subnet to routing prefix. Syntax: xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx/xxx. | [optional] 
**ip6_prefix_list** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner]**](SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner.md) | Advertised prefix list. | [optional] 
**ip6_rdnss_list** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner]**](SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner.md) | Advertised IPv6 RDNSS list. | [optional] 
**ip6_dnssl_list** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner]**](SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner.md) | Advertised IPv6 DNSS list. | [optional] 
**ip6_delegated_prefix_list** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner]**](SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner.md) | Advertised IPv6 delegated prefix list. | [optional] 
**dhcp6_relay_service** | **str** | Enable/disable DHCPv6 relay.    disable:Disable DHCPv6 relay    enable:Enable DHCPv6 relay. | [optional] 
**dhcp6_relay_type** | **str** | DHCPv6 relay type.    regular:Regular DHCP relay. | [optional] 
**dhcp6_relay_source_interface** | **str** | Enable/disable use of address on this interface as the source address of the relay message.    disable:Use address of the egress interface as source address of the relay message.    enable:Use address of this interface as source address of the relay message. | [optional] 
**dhcp6_relay_ip** | **str** | DHCPv6 relay IP address. | [optional] 
**dhcp6_relay_source_ip** | **str** | IPv6 address used by the DHCP6 relay as its source IP. | [optional] 
**dhcp6_relay_interface_id** | **str** | DHCP6 relay interface ID. | [optional] 
**dhcp6_client_options** | **str** | DHCPv6 client options.    rapid:Send rapid commit option.    iapd:Send including IA-PD option.    iana:Send including IA-NA option. | [optional] 
**dhcp6_prefix_delegation** | **str** | Enable/disable DHCPv6 prefix delegation.    enable:Enable DHCPv6 prefix delegation.    disable:Disable DHCPv6 prefix delegation. | [optional] 
**dhcp6_information_request** | **str** | Enable/disable DHCPv6 information request.    enable:Enable DHCPv6 information request.    disable:Disable DHCPv6 information request. | [optional] 
**dhcp6_iapd_list** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner]**](SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner.md) | DHCPv6 IA-PD list. | [optional] 
**cli_conn6_status** | **int** | CLI IPv6 connection status. | [optional] 
**vrrp_virtual_mac6** | **str** | Enable/disable virtual MAC for VRRP.    enable:Enable virtual MAC for VRRP.    disable:Disable virtual MAC for VRRP. | [optional] 
**vrip6_link_local** | **str** | Link-local IPv6 address of virtual router. | [optional] 
**vrrp6** | [**List[SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner]**](SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner.md) | IPv6 VRRP configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner import SystemInterfaceNameGet200ResponseIpv6Inner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6Inner from a JSON string
system_interface_name_get200_response_ipv6_inner_instance = SystemInterfaceNameGet200ResponseIpv6Inner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6Inner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_dict = system_interface_name_get200_response_ipv6_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6Inner from a dict
system_interface_name_get200_response_ipv6_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6Inner.from_dict(system_interface_name_get200_response_ipv6_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


