# CreateOneBlocklist201ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**create_blocklist** | [**BlocklistForResponse**](BlocklistForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.create_one_blocklist201_response_data import CreateOneBlocklist201ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of CreateOneBlocklist201ResponseData from a JSON string
create_one_blocklist201_response_data_instance = CreateOneBlocklist201ResponseData.from_json(json)
# print the JSON string representation of the object
print(CreateOneBlocklist201ResponseData.to_json())

# convert the object into a dict
create_one_blocklist201_response_data_dict = create_one_blocklist201_response_data_instance.to_dict()
# create an instance of CreateOneBlocklist201ResponseData from a dict
create_one_blocklist201_response_data_from_dict = CreateOneBlocklist201ResponseData.from_dict(create_one_blocklist201_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


