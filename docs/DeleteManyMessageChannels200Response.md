# DeleteManyMessageChannels200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**DeleteManyMessageChannels200ResponseData**](DeleteManyMessageChannels200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_message_channels200_response import DeleteManyMessageChannels200Response

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyMessageChannels200Response from a JSON string
delete_many_message_channels200_response_instance = DeleteManyMessageChannels200Response.from_json(json)
# print the JSON string representation of the object
print(DeleteManyMessageChannels200Response.to_json())

# convert the object into a dict
delete_many_message_channels200_response_dict = delete_many_message_channels200_response_instance.to_dict()
# create an instance of DeleteManyMessageChannels200Response from a dict
delete_many_message_channels200_response_from_dict = DeleteManyMessageChannels200Response.from_dict(delete_many_message_channels200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


