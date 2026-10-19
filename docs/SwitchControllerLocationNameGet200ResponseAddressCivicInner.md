# SwitchControllerLocationNameGet200ResponseAddressCivicInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**additional** | **str** | Location additional details. | [optional] 
**additional_code** | **str** | Location additional code details. | [optional] 
**block** | **str** | Location block details. | [optional] 
**branch_road** | **str** | Location branch road details. | [optional] 
**building** | **str** | Location building details. | [optional] 
**city** | **str** | Location city details. | [optional] 
**city_division** | **str** | Location city division details. | [optional] 
**country** | **str** | The two-letter ISO 3166 country code in capital ASCII letters eg. US, CA, DK, DE. | [optional] 
**country_subdivision** | **str** | National subdivisions (state, canton, region, province, or prefecture). | [optional] 
**county** | **str** | County, parish, gun (JP), or district (IN). | [optional] 
**direction** | **str** | Leading street direction. | [optional] 
**floor** | **str** | Floor. | [optional] 
**landmark** | **str** | Landmark or vanity address. | [optional] 
**language** | **str** | Language. | [optional] 
**name** | **str** | Name (residence and office occupant). | [optional] 
**number** | **str** | House number. | [optional] 
**number_suffix** | **str** | House number suffix. | [optional] 
**place_type** | **str** | Place type. | [optional] 
**post_office_box** | **str** | Post office box. | [optional] 
**postal_community** | **str** | Postal community name. | [optional] 
**primary_road** | **str** | Primary road name. | [optional] 
**road_section** | **str** | Road section. | [optional] 
**room** | **str** | Room number. | [optional] 
**script** | **str** | Script used to present the address information. | [optional] 
**seat** | **str** | Seat number. | [optional] 
**street** | **str** | Street. | [optional] 
**street_name_post_mod** | **str** | Street name post modifier. | [optional] 
**street_name_pre_mod** | **str** | Street name pre modifier. | [optional] 
**street_suffix** | **str** | Street suffix. | [optional] 
**sub_branch_road** | **str** | Sub branch road name. | [optional] 
**trailing_str_suffix** | **str** | Trailing street suffix. | [optional] 
**unit** | **str** | Unit (apartment, suite). | [optional] 
**zip** | **str** | Postal/zip code. | [optional] 
**parent_key** | **str** | Parent key name. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_location_name_get200_response_address_civic_inner import SwitchControllerLocationNameGet200ResponseAddressCivicInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerLocationNameGet200ResponseAddressCivicInner from a JSON string
switch_controller_location_name_get200_response_address_civic_inner_instance = SwitchControllerLocationNameGet200ResponseAddressCivicInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerLocationNameGet200ResponseAddressCivicInner.to_json())

# convert the object into a dict
switch_controller_location_name_get200_response_address_civic_inner_dict = switch_controller_location_name_get200_response_address_civic_inner_instance.to_dict()
# create an instance of SwitchControllerLocationNameGet200ResponseAddressCivicInner from a dict
switch_controller_location_name_get200_response_address_civic_inner_from_dict = SwitchControllerLocationNameGet200ResponseAddressCivicInner.from_dict(switch_controller_location_name_get200_response_address_civic_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


