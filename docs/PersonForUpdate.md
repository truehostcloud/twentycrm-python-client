# PersonForUpdate

A person

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | [**PersonName**](PersonName.md) |  | [optional] 
**emails** | [**PersonEmails**](PersonEmails.md) |  | [optional] 
**linkedin_link** | [**PersonLinkedinLink**](PersonLinkedinLink.md) |  | [optional] 
**x_link** | [**PersonXLink**](PersonXLink.md) |  | [optional] 
**job_title** | **str** | Contact&#39;s job title | [optional] 
**phones** | [**PersonPhones**](PersonPhones.md) |  | [optional] 
**city** | **str** | Contact&#39;s city | [optional] 
**avatar_url** | **str** | Contact&#39;s avatar | [optional] 
**avatar_file** | [**List[AttachmentFileInner]**](AttachmentFileInner.md) | Contact&#39;s avatar file | [optional] 
**position** | **float** | Person record Position | [optional] 
**created_by** | [**AttachmentCreatedBy**](AttachmentCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 
**company_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.person_for_update import PersonForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of PersonForUpdate from a JSON string
person_for_update_instance = PersonForUpdate.from_json(json)
# print the JSON string representation of the object
print(PersonForUpdate.to_json())

# convert the object into a dict
person_for_update_dict = person_for_update_instance.to_dict()
# create an instance of PersonForUpdate from a dict
person_for_update_from_dict = PersonForUpdate.from_dict(person_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


