# CreateOneNote201ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**create_note** | [**NoteForResponse**](NoteForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.create_one_note201_response_data import CreateOneNote201ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of CreateOneNote201ResponseData from a JSON string
create_one_note201_response_data_instance = CreateOneNote201ResponseData.from_json(json)
# print the JSON string representation of the object
print(CreateOneNote201ResponseData.to_json())

# convert the object into a dict
create_one_note201_response_data_dict = create_one_note201_response_data_instance.to_dict()
# create an instance of CreateOneNote201ResponseData from a dict
create_one_note201_response_data_from_dict = CreateOneNote201ResponseData.from_dict(create_one_note201_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


