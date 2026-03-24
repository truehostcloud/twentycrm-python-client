# DeleteManyMessageChannels200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delete_message_channels** | [**List[DeleteManyAttachments200ResponseDataDeleteAttachmentsInner]**](DeleteManyAttachments200ResponseDataDeleteAttachmentsInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_message_channels200_response_data import DeleteManyMessageChannels200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyMessageChannels200ResponseData from a JSON string
delete_many_message_channels200_response_data_instance = DeleteManyMessageChannels200ResponseData.from_json(json)
# print the JSON string representation of the object
print(DeleteManyMessageChannels200ResponseData.to_json())

# convert the object into a dict
delete_many_message_channels200_response_data_dict = delete_many_message_channels200_response_data_instance.to_dict()
# create an instance of DeleteManyMessageChannels200ResponseData from a dict
delete_many_message_channels200_response_data_from_dict = DeleteManyMessageChannels200ResponseData.from_dict(delete_many_message_channels200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


