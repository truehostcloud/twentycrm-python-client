# PersonEmails

Contact's Emails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary_email** | **str** |  | [optional] 
**additional_emails** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.person_emails import PersonEmails

# TODO update the JSON string below
json = "{}"
# create an instance of PersonEmails from a JSON string
person_emails_instance = PersonEmails.from_json(json)
# print the JSON string representation of the object
print(PersonEmails.to_json())

# convert the object into a dict
person_emails_dict = person_emails_instance.to_dict()
# create an instance of PersonEmails from a dict
person_emails_from_dict = PersonEmails.from_dict(person_emails_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


