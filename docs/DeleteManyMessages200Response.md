# DeleteManyMessages200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**DeleteManyMessages200ResponseData**](DeleteManyMessages200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_messages200_response import DeleteManyMessages200Response

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyMessages200Response from a JSON string
delete_many_messages200_response_instance = DeleteManyMessages200Response.from_json(json)
# print the JSON string representation of the object
print(DeleteManyMessages200Response.to_json())

# convert the object into a dict
delete_many_messages200_response_dict = delete_many_messages200_response_instance.to_dict()
# create an instance of DeleteManyMessages200Response from a dict
delete_many_messages200_response_from_dict = DeleteManyMessages200Response.from_dict(delete_many_messages200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


