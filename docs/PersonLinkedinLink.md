# PersonLinkedinLink

Contact's Linkedin account

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary_link_label** | **str** |  | [optional] 
**primary_link_url** | **str** |  | [optional] 
**secondary_links** | [**List[CalendarEventConferenceLinkSecondaryLinksInner]**](CalendarEventConferenceLinkSecondaryLinksInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.person_linkedin_link import PersonLinkedinLink

# TODO update the JSON string below
json = "{}"
# create an instance of PersonLinkedinLink from a JSON string
person_linkedin_link_instance = PersonLinkedinLink.from_json(json)
# print the JSON string representation of the object
print(PersonLinkedinLink.to_json())

# convert the object into a dict
person_linkedin_link_dict = person_linkedin_link_instance.to_dict()
# create an instance of PersonLinkedinLink from a dict
person_linkedin_link_from_dict = PersonLinkedinLink.from_dict(person_linkedin_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


