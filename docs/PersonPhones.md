# PersonPhones

Contact's phone numbers

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**additional_phones** | **List[str]** |  | [optional] 
**primary_phone_country_code** | **str** |  | [optional] 
**primary_phone_calling_code** | **str** |  | [optional] 
**primary_phone_number** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.person_phones import PersonPhones

# TODO update the JSON string below
json = "{}"
# create an instance of PersonPhones from a JSON string
person_phones_instance = PersonPhones.from_json(json)
# print the JSON string representation of the object
print(PersonPhones.to_json())

# convert the object into a dict
person_phones_dict = person_phones_instance.to_dict()
# create an instance of PersonPhones from a dict
person_phones_from_dict = PersonPhones.from_dict(person_phones_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


