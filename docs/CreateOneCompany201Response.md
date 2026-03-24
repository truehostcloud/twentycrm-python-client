# CreateOneCompany201Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**CreateOneCompany201ResponseData**](CreateOneCompany201ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.create_one_company201_response import CreateOneCompany201Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateOneCompany201Response from a JSON string
create_one_company201_response_instance = CreateOneCompany201Response.from_json(json)
# print the JSON string representation of the object
print(CreateOneCompany201Response.to_json())

# convert the object into a dict
create_one_company201_response_dict = create_one_company201_response_instance.to_dict()
# create an instance of CreateOneCompany201Response from a dict
create_one_company201_response_from_dict = CreateOneCompany201Response.from_dict(create_one_company201_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


