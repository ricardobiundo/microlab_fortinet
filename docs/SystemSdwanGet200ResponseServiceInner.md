# SystemSdwanGet200ResponseServiceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | SD-WAN rule ID (1 - 4000). | [optional] 
**name** | **str** | SD-WAN rule name. | [optional] 
**addr_mode** | **str** | Address mode (IPv4 or IPv6).    ipv4:IPv4 mode.    ipv6:IPv6 mode. | [optional] 
**load_balance** | **str** | Enable/disable load-balance.    enable:Enable load-balance.    disable:Disable load-balance. | [optional] 
**input_device** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | Source interface name. | [optional] 
**input_device_negate** | **str** | Enable/disable negation of input device match.    enable:Enable negation of input device match.    disable:Disable negation of input device match. | [optional] 
**input_zone** | [**List[SystemSdwanGet200ResponseServiceInnerInputZoneInner]**](SystemSdwanGet200ResponseServiceInnerInputZoneInner.md) | Source input-zone name. | [optional] 
**mode** | **str** | Control how the SD-WAN rule sets the priority of interfaces in the SD-WAN.    auto:Assign interfaces a priority based on quality.    manual:Assign interfaces a priority manually.    priority:Assign interfaces a priority based on the link-cost-factor quality of the interface.    sla:Assign interfaces a priority based on selected SLA settings. | [optional] 
**zone_mode** | **str** | Enable/disable zone mode.    enable:Traffic steered based on zone.    disable:Traffic steered based on member. | [optional] 
**minimum_sla_meet_members** | **int** | Minimum number of members which meet SLA. | [optional] 
**hash_mode** | **str** | Hash algorithm for selected priority members for load balance mode.    round-robin:All traffic are distributed to selected interfaces in equal portions and circular order.    source-ip-based:All traffic from a source IP is sent to the same interface.    source-dest-ip-based:All traffic from a source IP to a destination IP is sent to the same interface.    inbandwidth:All traffic are distributed to a selected interface with most available bandwidth for incoming traffic.    outbandwidth:All traffic are distributed to a selected interface with most available bandwidth for outgoing traffic.    bibandwidth:All traffic are distributed to a selected interface with most available bandwidth for both incoming and outgoing traffic. | [optional] 
**shortcut_priority** | **str** | High priority of ADVPN shortcut for this service.    enable:Enable a high priority of ADVPN shortcut for this service.    disable:Disable a high priority of ADVPN shortcut for this service.    auto:Auto enable a high priority of ADVPN shortcut for this service if ADVPN2.0 enabled. | [optional] 
**role** | **str** | Service role to work with neighbor.    standalone:Standalone service.    primary:Primary service for primary neighbor.    secondary:Secondary service for secondary neighbor. | [optional] 
**standalone_action** | **str** | Enable/disable service when selected neighbor role is standalone while service role is not standalone.    enable:Enable service when selected neighbor role is standalone.    disable:Disable service when selected neighbor role is standalone. | [optional] 
**quality_link** | **int** | Quality grade. | [optional] 
**tos** | **str** | Type of service bit pattern. | [optional] 
**tos_mask** | **str** | Type of service evaluated bits. | [optional] 
**protocol** | **int** | Protocol number. | [optional] 
**start_port** | **int** | Start destination port number. | [optional] 
**end_port** | **int** | End destination port number. | [optional] 
**start_src_port** | **int** | Start source port number. | [optional] 
**end_src_port** | **int** | End source port number. | [optional] 
**dst** | [**List[SystemSdwanGet200ResponseServiceInnerDstInner]**](SystemSdwanGet200ResponseServiceInnerDstInner.md) | Destination address name. | [optional] 
**dst_negate** | **str** | Enable/disable negation of destination address match.    enable:Enable destination address negation.    disable:Disable destination address negation. | [optional] 
**src** | [**List[SystemSdwanGet200ResponseServiceInnerDstInner]**](SystemSdwanGet200ResponseServiceInnerDstInner.md) | Source address name. | [optional] 
**dst6** | [**List[SystemSdwanGet200ResponseServiceInnerDst6Inner]**](SystemSdwanGet200ResponseServiceInnerDst6Inner.md) | Destination address6 name. | [optional] 
**src6** | [**List[SystemSdwanGet200ResponseServiceInnerDst6Inner]**](SystemSdwanGet200ResponseServiceInnerDst6Inner.md) | Source address6 name. | [optional] 
**src_negate** | **str** | Enable/disable negation of source address match.    enable:Enable source address negation.    disable:Disable source address negation. | [optional] 
**users** | [**List[SystemSdwanGet200ResponseServiceInnerUsersInner]**](SystemSdwanGet200ResponseServiceInnerUsersInner.md) | User name. | [optional] 
**groups** | [**List[SwitchControllerSecurityPolicy8021XNameGet200ResponseUserGroupInner]**](SwitchControllerSecurityPolicy8021XNameGet200ResponseUserGroupInner.md) | User groups. | [optional] 
**internet_service** | **str** | Enable/disable use of Internet service for application-based load balancing.    enable:Enable cloud service to support application-based load balancing.    disable:Disable cloud service to support application-based load balancing. | [optional] 
**internet_service_custom** | [**List[SystemSdwanGet200ResponseServiceInnerInternetServiceCustomInner]**](SystemSdwanGet200ResponseServiceInnerInternetServiceCustomInner.md) | Custom Internet service name list. | [optional] 
**internet_service_custom_group** | [**List[SystemSdwanGet200ResponseServiceInnerInternetServiceCustomGroupInner]**](SystemSdwanGet200ResponseServiceInnerInternetServiceCustomGroupInner.md) | Custom Internet Service group list. | [optional] 
**internet_service_fortiguard** | [**List[SystemSdwanGet200ResponseServiceInnerInternetServiceFortiguardInner]**](SystemSdwanGet200ResponseServiceInnerInternetServiceFortiguardInner.md) | FortiGuard Internet service name list. | [optional] 
**internet_service_name** | [**List[SystemSdwanGet200ResponseServiceInnerInternetServiceNameInner]**](SystemSdwanGet200ResponseServiceInnerInternetServiceNameInner.md) | Internet service name list. | [optional] 
**internet_service_group** | [**List[SystemSdwanGet200ResponseServiceInnerInternetServiceGroupInner]**](SystemSdwanGet200ResponseServiceInnerInternetServiceGroupInner.md) | Internet Service group list. | [optional] 
**internet_service_app_ctrl** | [**List[SystemSdwanGet200ResponseServiceInnerInternetServiceAppCtrlInner]**](SystemSdwanGet200ResponseServiceInnerInternetServiceAppCtrlInner.md) | Application control based Internet Service ID list. | [optional] 
**internet_service_app_ctrl_group** | [**List[SystemSdwanGet200ResponseServiceInnerInternetServiceAppCtrlGroupInner]**](SystemSdwanGet200ResponseServiceInnerInternetServiceAppCtrlGroupInner.md) | Application control based Internet Service group list. | [optional] 
**internet_service_app_ctrl_category** | [**List[SystemSdwanGet200ResponseServiceInnerInternetServiceAppCtrlCategoryInner]**](SystemSdwanGet200ResponseServiceInnerInternetServiceAppCtrlCategoryInner.md) | IDs of one or more application control categories. | [optional] 
**health_check** | [**List[SystemSdwanGet200ResponseServiceInnerHealthCheckInner]**](SystemSdwanGet200ResponseServiceInnerHealthCheckInner.md) | Health check list. | [optional] 
**link_cost_factor** | **str** | Link cost factor.    latency:Select link based on latency.    jitter:Select link based on jitter.    packet-loss:Select link based on packet loss.    inbandwidth:Select link based on available bandwidth of incoming traffic.    outbandwidth:Select link based on available bandwidth of outgoing traffic.    bibandwidth:Select link based on available bandwidth of bidirectional traffic.    custom-profile-1:Select link based on customized profile. | [optional] 
**packet_loss_weight** | **int** | Coefficient of packet-loss in the formula of custom-profile-1. | [optional] 
**latency_weight** | **int** | Coefficient of latency in the formula of custom-profile-1. | [optional] 
**jitter_weight** | **int** | Coefficient of jitter in the formula of custom-profile-1. | [optional] 
**bandwidth_weight** | **int** | Coefficient of reciprocal of available bidirectional bandwidth in the formula of custom-profile-1. | [optional] 
**link_cost_threshold** | **int** | Percentage threshold change of link cost values that will result in policy route regeneration (0 - 10000000, default &#x3D; 10). | [optional] 
**hold_down_time** | **int** | Waiting period in seconds when switching from the back-up member to the primary member (0 - 10000000, default &#x3D; 0). | [optional] 
**sla_stickiness** | **str** | Enable/disable SLA stickiness (default &#x3D; disable).    enable:Traffic remains in the original session path if the path is within the SLA.    disable:Traffic switches to the best path regardless of the SLA. | [optional] 
**dscp_forward** | **str** | Enable/disable forward traffic DSCP tag.    enable:Enable use of forward DSCP tag.    disable:Disable use of forward DSCP tag. | [optional] 
**dscp_reverse** | **str** | Enable/disable reverse traffic DSCP tag.    enable:Enable use of reverse DSCP tag.    disable:Disable use of reverse DSCP tag. | [optional] 
**dscp_forward_tag** | **str** | Forward traffic DSCP tag. | [optional] 
**dscp_reverse_tag** | **str** | Reverse traffic DSCP tag. | [optional] 
**sla** | [**List[SystemSdwanGet200ResponseServiceInnerSlaInner]**](SystemSdwanGet200ResponseServiceInnerSlaInner.md) | Service level agreement (SLA). | [optional] 
**priority_members** | [**List[SystemSdwanGet200ResponseHealthCheckInnerMembersInner]**](SystemSdwanGet200ResponseHealthCheckInnerMembersInner.md) | Member sequence number list. | [optional] 
**priority_zone** | [**List[SystemSdwanGet200ResponseServiceInnerPriorityZoneInner]**](SystemSdwanGet200ResponseServiceInnerPriorityZoneInner.md) | Priority zone name list. | [optional] 
**status** | **str** | Enable/disable SD-WAN service.    enable:Enable SD-WAN service.    disable:Disable SD-WAN service. | [optional] 
**gateway** | **str** | Enable/disable SD-WAN service gateway.    enable:Enable SD-WAN service gateway.    disable:Disable SD-WAN service gateway. | [optional] 
**default** | **str** | Enable/disable use of SD-WAN as default service.    enable:Enable use of SD-WAN as default service.    disable:Disable use of SD-WAN as default service. | [optional] 
**sla_compare_method** | **str** | Method to compare SLA value for SLA mode.    order:Compare SLA value based on the order of health-check.    number:Compare SLA value based on the number of satisfied health-check.  Limits health-checks to only configured member interfaces. | [optional] 
**fib_best_match_force** | **str** | Enable/disable force using fib-best-match oif as outgoing interface.    disable:Do not force using fib-best-match oif as outgoing interface.    enable:Force using fib-best-match oif as outgoing interface. | [optional] 
**tie_break** | **str** | Method of selecting member if more than one meets the SLA.    zone:Use the setting that is configured for the members&#39; zone.    cfg-order:Members that meet the SLA are selected in the order they are configured.    fib-best-match:Members that meet the SLA are selected that match the longest prefix in the routing table.    priority:Select the best members that meet the SLA based on link-cost-factor.    input-device:Members that meet the SLA are selected by matching the input device. | [optional] 
**use_shortcut_sla** | **str** | Enable/disable use of ADVPN shortcut for quality comparison.    enable:Enable use of ADVPN shortcut for quality comparison.    disable:Disable use of ADVPN shortcut for quality comparison. | [optional] 
**passive_measurement** | **str** | Enable/disable passive measurement based on the service criteria.    enable:Enable passive measurement of user traffic.    disable:Disable passive measurement of user traffic. | [optional] 
**agent_exclusive** | **str** | Set/unset the service as agent use exclusively.    enable:Set the service as agent use exclusively.    disable:Unset the service as agent use exclusively. | [optional] 
**shortcut** | **str** | Enable/disable shortcut for this service.    enable:Enable use of ADVPN shortcut for this service.    disable:Disable use of ADVPN shortcut for this service. | [optional] 
**comment** | **str** | Comments. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdwan_get200_response_service_inner import SystemSdwanGet200ResponseServiceInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdwanGet200ResponseServiceInner from a JSON string
system_sdwan_get200_response_service_inner_instance = SystemSdwanGet200ResponseServiceInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdwanGet200ResponseServiceInner.to_json())

# convert the object into a dict
system_sdwan_get200_response_service_inner_dict = system_sdwan_get200_response_service_inner_instance.to_dict()
# create an instance of SystemSdwanGet200ResponseServiceInner from a dict
system_sdwan_get200_response_service_inner_from_dict = SystemSdwanGet200ResponseServiceInner.from_dict(system_sdwan_get200_response_service_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


