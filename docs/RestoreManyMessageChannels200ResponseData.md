# RestoreManyMessageChannels200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**restore_message_channels** | [**List[MessageChannelForResponse]**](MessageChannelForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.restore_many_message_channels200_response_data import RestoreManyMessageChannels200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of RestoreManyMessageChannels200ResponseData from a JSON string
restore_many_message_channels200_response_data_instance = RestoreManyMessageChannels200ResponseData.from_json(json)
# print the JSON string representation of the object
print(RestoreManyMessageChannels200ResponseData.to_json())

# convert the object into a dict
restore_many_message_channels200_response_data_dict = restore_many_message_channels200_response_data_instance.to_dict()
# create an instance of RestoreManyMessageChannels200ResponseData from a dict
restore_many_message_channels200_response_data_from_dict = RestoreManyMessageChannels200ResponseData.from_dict(restore_many_message_channels200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


