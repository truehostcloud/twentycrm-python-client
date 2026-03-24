# CreateOnePerson201Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**CreateOnePerson201ResponseData**](CreateOnePerson201ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.create_one_person201_response import CreateOnePerson201Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateOnePerson201Response from a JSON string
create_one_person201_response_instance = CreateOnePerson201Response.from_json(json)
# print the JSON string representation of the object
print(CreateOnePerson201Response.to_json())

# convert the object into a dict
create_one_person201_response_dict = create_one_person201_response_instance.to_dict()
# create an instance of CreateOnePerson201Response from a dict
create_one_person201_response_from_dict = CreateOnePerson201Response.from_dict(create_one_person201_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


