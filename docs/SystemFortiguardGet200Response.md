# SystemFortiguardGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**fortiguard_anycast** | **str** | Enable/disable use of FortiGuard&#39;s Anycast network.    enable:Enable use of FortiGuard&#39;s Anycast network.    disable:Disable use of FortiGuard&#39;s Anycast network. | [optional] 
**fortiguard_anycast_source** | **str** | Configure which of Fortinet&#39;s servers to provide FortiGuard services in FortiGuard&#39;s anycast network. Default is Fortinet.    fortinet:Use Fortinet&#39;s servers to provide FortiGuard services in FortiGuard&#39;s anycast network.    aws:Use Fortinet&#39;s AWS servers to provide FortiGuard services in FortiGuard&#39;s anycast network.    debug:Use Fortinet&#39;s internal test servers to provide FortiGuard services in FortiGuard&#39;s anycast network. | [optional] 
**protocol** | **str** | Protocol used to communicate with the FortiGuard servers.    udp:UDP for server communication (for use by FortiGuard or FortiManager).    http:HTTP for server communication (for use only by FortiManager).    https:HTTPS for server communication (for use by FortiGuard or FortiManager). | [optional] 
**port** | **str** | Port used to communicate with the FortiGuard servers.    8888:port 8888 for server communication.    53:port 53 for server communication.    80:port 80 for server communication.    443:port 443 for server communication. | [optional] 
**service_account_id** | **str** | Service account ID. | [optional] 
**load_balance_servers** | **int** | Number of servers to alternate between as first FortiGuard option. | [optional] 
**auto_join_forticloud** | **str** | Automatically connect to and login to FortiCloud.    enable:Enable automatic connection and login to FortiCloud.    disable:Disable automatic connection and login to FortiCloud. | [optional] 
**update_server_location** | **str** | Location from which to receive FortiGuard updates.    automatic:FortiGuard servers chosen based on closest proximity to FortiGate unit.    usa:FortiGuard servers in United States.    eu:FortiGuard servers in the European Union. | [optional] 
**sandbox_region** | **str** | FortiCloud Sandbox region. | [optional] 
**sandbox_inline_scan** | **str** | Enable/disable FortiCloud Sandbox inline-scan.    enable:Enable FortiCloud Sandbox inline scan.    disable:Disable FortiCloud Sandbox inline scan. | [optional] 
**update_ffdb** | **str** | Enable/disable Internet Service Database update.    enable:Enable Internet Service Database update.    disable:Disable Internet Service Database update. | [optional] 
**update_uwdb** | **str** | Enable/disable allowlist update.    enable:Enable allowlist update.    disable:Disable allowlist update. | [optional] 
**update_dldb** | **str** | Enable/disable DLP signature update.    enable:Enable DLP signature update.    disable:Disable DLP signature update. | [optional] 
**update_extdb** | **str** | Enable/disable external resource update.    enable:Enable external resource update.    disable:Disable external resource update. | [optional] 
**update_build_proxy** | **str** | Enable/disable proxy dictionary rebuild.    enable:Enable proxy dictionary rebuild.    disable:Disable proxy dictionary rebuild. | [optional] 
**persistent_connection** | **str** | Enable/disable use of persistent connection to receive update notification from FortiGuard.    enable:Enable persistent connection to receive update notification from FortiGuard.    disable:Disable persistent connection to receive update notification from FortiGuard. | [optional] 
**vdom** | **str** | FortiGuard Service virtual domain name. | [optional] 
**auto_firmware_upgrade** | **str** | Enable/disable automatic patch-level firmware upgrade from FortiGuard. The FortiGate unit searches for new patches only in the same major and minor version.    enable:Enable automatic patch-level firmware upgrade to latest version from FortiGuard.    disable:Disable automatic patch-level firmware upgrade to latest version from FortiGuard. | [optional] 
**auto_firmware_upgrade_day** | **str** | Allowed day(s) of the week to install an automatic patch-level firmware upgrade from FortiGuard (default is none). Disallow any day of the week to use auto-firmware-upgrade-delay instead, which waits for designated days before installing an automatic patch-level firmware upgrade.    sunday:Sunday.    monday:Monday.    tuesday:Tuesday.    wednesday:Wednesday.    thursday:Thursday.    friday:Friday.    saturday:Saturday. | [optional] 
**auto_firmware_upgrade_delay** | **int** | Delay of day(s) before installing an automatic patch-level firmware upgrade from FortiGuard (default &#x3D; 3). Set it 0 to use auto-firmware-upgrade-day instead, which selects allowed day(s) of the week for installing an automatic patch-level firmware upgrade. | [optional] 
**auto_firmware_upgrade_start_hour** | **int** | Start time in the designated time window for automatic patch-level firmware upgrade from FortiGuard in 24 hour time (0 ~ 23, default &#x3D; 2). The actual upgrade time is selected randomly within the time window. | [optional] 
**auto_firmware_upgrade_end_hour** | **int** | End time in the designated time window for automatic patch-level firmware upgrade from FortiGuard in 24 hour time (0 ~ 23, default &#x3D; 4). When the end time is smaller than the start time, the end time is interpreted as the next day. The actual upgrade time is selected randomly within the time window. | [optional] 
**fds_license_expiring_days** | **int** | Threshold for number of days before FortiGuard license expiration to generate license expiring event log (1 - 100 days, default &#x3D; 15). | [optional] 
**subscribe_update_notification** | **str** | Enable/disable subscription to receive update notification from FortiGuard.    enable:Enable subscription to receive update notification from FortiGuard.    disable:Disable subscription to receive update notification from FortiGuard. | [optional] 
**antispam_force_off** | **str** | Enable/disable turning off the FortiGuard antispam service.    enable:Turn off the FortiGuard antispam service.    disable:Allow the FortiGuard antispam service. | [optional] 
**antispam_cache** | **str** | Enable/disable FortiGuard antispam request caching. Uses a small amount of memory but improves performance.    enable:Enable FortiGuard antispam request caching.    disable:Disable FortiGuard antispam request caching. | [optional] 
**antispam_cache_ttl** | **int** | Time-to-live for antispam cache entries in seconds (300 - 86400). Lower times reduce the cache size. Higher times may improve performance since the cache will have more entries. | [optional] 
**antispam_cache_mpermille** | **int** | Maximum permille of FortiGate memory the antispam cache is allowed to use (1 - 150). | [optional] 
**antispam_license** | **int** | Interval of time between license checks for the FortiGuard antispam contract. | [optional] 
**antispam_expiration** | **int** | Expiration date of the FortiGuard antispam contract. | [optional] 
**antispam_timeout** | **int** | Antispam query time out (1 - 30 sec, default &#x3D; 7). | [optional] 
**outbreak_prevention_force_off** | **str** | Turn off FortiGuard Virus Outbreak Prevention service.    enable:Turn off FortiGuard antivirus service.    disable:Allow the FortiGuard antivirus service. | [optional] 
**outbreak_prevention_cache** | **str** | Enable/disable FortiGuard Virus Outbreak Prevention cache.    enable:Enable FortiGuard antivirus caching.    disable:Disable FortiGuard antivirus caching. | [optional] 
**outbreak_prevention_cache_ttl** | **int** | Time-to-live for FortiGuard Virus Outbreak Prevention cache entries (300 - 86400 sec, default &#x3D; 300). | [optional] 
**outbreak_prevention_cache_mpermille** | **int** | Maximum permille of memory FortiGuard Virus Outbreak Prevention cache can use (1 - 150 permille, default &#x3D; 1). | [optional] 
**outbreak_prevention_license** | **int** | Interval of time between license checks for FortiGuard Virus Outbreak Prevention contract. | [optional] 
**outbreak_prevention_expiration** | **int** | Expiration date of FortiGuard Virus Outbreak Prevention contract. | [optional] 
**outbreak_prevention_timeout** | **int** | FortiGuard Virus Outbreak Prevention time out (1 - 30 sec, default &#x3D; 7). | [optional] 
**webfilter_force_off** | **str** | Enable/disable turning off the FortiGuard web filtering service.    enable:Turn off the FortiGuard web filtering service.    disable:Allow the FortiGuard web filtering service to operate. | [optional] 
**webfilter_cache** | **str** | Enable/disable FortiGuard web filter caching.    enable:Enable FortiGuard web filter caching.    disable:Disable FortiGuard web filter caching. | [optional] 
**webfilter_cache_ttl** | **int** | Time-to-live for web filter cache entries in seconds (300 - 86400). | [optional] 
**webfilter_license** | **int** | Interval of time between license checks for the FortiGuard web filter contract. | [optional] 
**webfilter_expiration** | **int** | Expiration date of the FortiGuard web filter contract. | [optional] 
**webfilter_timeout** | **int** | Web filter query time out (1 - 30 sec, default &#x3D; 15). | [optional] 
**sdns_server_ip** | **str** | IP address of the FortiGuard DNS rating server. | [optional] 
**sdns_server_port** | **int** | Port to connect to on the FortiGuard DNS rating server. | [optional] 
**anycast_sdns_server_ip** | **str** | IP address of the FortiGuard anycast DNS rating server. | [optional] 
**anycast_sdns_server_port** | **int** | Port to connect to on the FortiGuard anycast DNS rating server. | [optional] 
**sdns_options** | **str** | Customization options for the FortiGuard DNS service.    include-question-section:Include DNS question section in the FortiGuard DNS setup message. | [optional] 
**source_ip** | **str** | Source IPv4 address used to communicate with FortiGuard. | [optional] 
**source_ip6** | **str** | Source IPv6 address used to communicate with FortiGuard. | [optional] 
**proxy_server_ip** | **str** | Hostname or IPv4 address of the proxy server. | [optional] 
**proxy_server_port** | **int** | Port used to communicate with the proxy server. | [optional] 
**proxy_username** | **str** | Proxy user name. | [optional] 
**proxy_password** | **str** | Proxy user password. | [optional] 
**ddns_server_ip** | **str** | IP address of the FortiDDNS server. | [optional] 
**ddns_server_ip6** | **str** | IPv6 address of the FortiDDNS server. | [optional] 
**ddns_server_port** | **int** | Port used to communicate with FortiDDNS servers. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fortiguard_get200_response import SystemFortiguardGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFortiguardGet200Response from a JSON string
system_fortiguard_get200_response_instance = SystemFortiguardGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFortiguardGet200Response.to_json())

# convert the object into a dict
system_fortiguard_get200_response_dict = system_fortiguard_get200_response_instance.to_dict()
# create an instance of SystemFortiguardGet200Response from a dict
system_fortiguard_get200_response_from_dict = SystemFortiguardGet200Response.from_dict(system_fortiguard_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


