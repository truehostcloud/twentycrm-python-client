# RestoreManyMessages200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**RestoreManyMessages200ResponseData**](RestoreManyMessages200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.restore_many_messages200_response import RestoreManyMessages200Response

# TODO update the JSON string below
json = "{}"
# create an instance of RestoreManyMessages200Response from a JSON string
restore_many_messages200_response_instance = RestoreManyMessages200Response.from_json(json)
# print the JSON string representation of the object
print(RestoreManyMessages200Response.to_json())

# convert the object into a dict
restore_many_messages200_response_dict = restore_many_messages200_response_instance.to_dict()
# create an instance of RestoreManyMessages200Response from a dict
restore_many_messages200_response_from_dict = RestoreManyMessages200Response.from_dict(restore_many_messages200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


