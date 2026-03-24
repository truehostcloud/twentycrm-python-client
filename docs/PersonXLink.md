# PersonXLink

Contact's X/Twitter account

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary_link_label** | **str** |  | [optional] 
**primary_link_url** | **str** |  | [optional] 
**secondary_links** | [**List[CalendarEventConferenceLinkSecondaryLinksInner]**](CalendarEventConferenceLinkSecondaryLinksInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.person_x_link import PersonXLink

# TODO update the JSON string below
json = "{}"
# create an instance of PersonXLink from a JSON string
person_x_link_instance = PersonXLink.from_json(json)
# print the JSON string representation of the object
print(PersonXLink.to_json())

# convert the object into a dict
person_x_link_dict = person_x_link_instance.to_dict()
# create an instance of PersonXLink from a dict
person_x_link_from_dict = PersonXLink.from_dict(person_x_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


