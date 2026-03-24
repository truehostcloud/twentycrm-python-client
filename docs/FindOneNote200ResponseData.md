# FindOneNote200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**note** | [**NoteForResponse**](NoteForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_one_note200_response_data import FindOneNote200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of FindOneNote200ResponseData from a JSON string
find_one_note200_response_data_instance = FindOneNote200ResponseData.from_json(json)
# print the JSON string representation of the object
print(FindOneNote200ResponseData.to_json())

# convert the object into a dict
find_one_note200_response_data_dict = find_one_note200_response_data_instance.to_dict()
# create an instance of FindOneNote200ResponseData from a dict
find_one_note200_response_data_from_dict = FindOneNote200ResponseData.from_dict(find_one_note200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


