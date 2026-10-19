# SystemModemGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable Modem support (equivalent to bringing an interface up or down).    enable:Enable setting.    disable:Disable setting. | [optional] 
**pin_init** | **str** | AT command to set the PIN (AT+PIN&#x3D;&lt;pin&gt;). | [optional] 
**network_init** | **str** | AT command to set the Network name/type (AT+COPS&#x3D;&lt;mode&gt;,[&lt;format&gt;,&lt;oper&gt;[,&lt;AcT&gt;]]). | [optional] 
**lockdown_lac** | **str** | Allow connection only to the specified Location Area Code (LAC). | [optional] 
**mode** | **str** | Set MODEM operation mode to redundant or standalone.    standalone:Standalone.    redundant:Redundant for an interface. | [optional] 
**auto_dial** | **str** | Enable/disable auto-dial after a reboot or disconnection.    enable:Enable setting.    disable:Disable setting. | [optional] 
**dial_on_demand** | **str** | Enable/disable to dial the modem when packets are routed to the modem interface.    enable:Enable setting.    disable:Disable setting. | [optional] 
**idle_timer** | **int** | MODEM connection idle time (1 - 9999 min, default &#x3D; 5). | [optional] 
**redial** | **str** | Redial limit (1 - 10 attempts, none &#x3D; redial forever).    none:Forever.    1:One attempt.    2:Two attempts.    3:Three attempts.    4:Four attempts.    5:Five attempts.    6:Six attempts.    7:Seven attempts.    8:Eight attempts.    9:Nine attempts.    10:Ten attempts. | [optional] 
**reset** | **int** | Number of dial attempts before resetting modem (0 &#x3D; never reset). | [optional] 
**holddown_timer** | **int** | Hold down timer in seconds (1 - 60 sec). | [optional] 
**connect_timeout** | **int** | Connection completion timeout (30 - 255 sec, default &#x3D; 90). | [optional] 
**interface** | **str** | Name of redundant interface. | [optional] 
**wireless_port** | **int** | Enter wireless port number: 0 for default, 1 for first port, and so on (0 - 4294967295). | [optional] 
**dont_send_cr1** | **str** | Do not send CR when connected (ISP1).    enable:Enable setting.    disable:Disable setting. | [optional] 
**phone1** | **str** | Phone number to connect to the dialup account (must not contain spaces, and should include standard special characters). | [optional] 
**dial_cmd1** | **str** | Dial command (this is often an ATD or ATDT command). | [optional] 
**username1** | **str** | User name to access the specified dialup account. | [optional] 
**passwd1** | **str** | Password to access the specified dialup account. | [optional] 
**extra_init1** | **str** | Extra initialization string to ISP 1. | [optional] 
**peer_modem1** | **str** | Specify peer MODEM type for phone1.    generic:All other modem type.    actiontec:ActionTec modem.    ascend_TNT:Ascend TNT modem. | [optional] 
**ppp_echo_request1** | **str** | Enable/disable PPP echo-request to ISP 1.    enable:Enable setting.    disable:Disable setting. | [optional] 
**authtype1** | **str** | Allowed authentication types for ISP 1.    pap:PAP    chap:CHAP    mschap:MSCHAP    mschapv2:MSCHAPv2 | [optional] 
**dont_send_cr2** | **str** | Do not send CR when connected (ISP2).    enable:Enable setting.    disable:Disable setting. | [optional] 
**phone2** | **str** | Phone number to connect to the dialup account (must not contain spaces, and should include standard special characters). | [optional] 
**dial_cmd2** | **str** | Dial command (this is often an ATD or ATDT command). | [optional] 
**username2** | **str** | User name to access the specified dialup account. | [optional] 
**passwd2** | **str** | Password to access the specified dialup account. | [optional] 
**extra_init2** | **str** | Extra initialization string to ISP 2. | [optional] 
**peer_modem2** | **str** | Specify peer MODEM type for phone2.    generic:All other modem type.    actiontec:ActionTec modem.    ascend_TNT:Ascend TNT modem. | [optional] 
**ppp_echo_request2** | **str** | Enable/disable PPP echo-request to ISP 2.    enable:Enable setting.    disable:Disable setting. | [optional] 
**authtype2** | **str** | Allowed authentication types for ISP 2.    pap:PAP    chap:CHAP    mschap:MSCHAP    mschapv2:MSCHAPv2 | [optional] 
**dont_send_cr3** | **str** | Do not send CR when connected (ISP3).    enable:Enable setting.    disable:Disable setting. | [optional] 
**phone3** | **str** | Phone number to connect to the dialup account (must not contain spaces, and should include standard special characters). | [optional] 
**dial_cmd3** | **str** | Dial command (this is often an ATD or ATDT command). | [optional] 
**username3** | **str** | User name to access the specified dialup account. | [optional] 
**passwd3** | **str** | Password to access the specified dialup account. | [optional] 
**extra_init3** | **str** | Extra initialization string to ISP 3. | [optional] 
**peer_modem3** | **str** | Specify peer MODEM type for phone3.    generic:All other modem type.    actiontec:ActionTec modem.    ascend_TNT:Ascend TNT modem. | [optional] 
**ppp_echo_request3** | **str** | Enable/disable PPP echo-request to ISP 3.    enable:Enable setting.    disable:Disable setting. | [optional] 
**altmode** | **str** | Enable/disable altmode for installations using PPP in China.    enable:Enable setting.    disable:Disable setting. | [optional] 
**authtype3** | **str** | Allowed authentication types for ISP 3.    pap:PAP    chap:CHAP    mschap:MSCHAP    mschapv2:MSCHAPv2 | [optional] 
**traffic_check** | **str** | Enable/disable traffic-check.    enable:Enable setting.    disable:Disable setting. | [optional] 
**action** | **str** | Dial up/stop MODEM.    dial:Dial up number.    stop:Stop dialup.    none:No action. | [optional] 
**distance** | **int** | Distance of learned routes (1 - 255, default &#x3D; 1). | [optional] 
**priority** | **int** | Priority of learned routes (1 - 65535, default &#x3D; 1). | [optional] 

## Example

```python
from microlab_fortinet.models.system_modem_get200_response import SystemModemGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemModemGet200Response from a JSON string
system_modem_get200_response_instance = SystemModemGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemModemGet200Response.to_json())

# convert the object into a dict
system_modem_get200_response_dict = system_modem_get200_response_instance.to_dict()
# create an instance of SystemModemGet200Response from a dict
system_modem_get200_response_from_dict = SystemModemGet200Response.from_dict(system_modem_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


