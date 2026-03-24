# UpdateManyMessageChannels200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**update_message_channels** | [**List[MessageChannelForResponse]**](MessageChannelForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.update_many_message_channels200_response_data import UpdateManyMessageChannels200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateManyMessageChannels200ResponseData from a JSON string
update_many_message_channels200_response_data_instance = UpdateManyMessageChannels200ResponseData.from_json(json)
# print the JSON string representation of the object
print(UpdateManyMessageChannels200ResponseData.to_json())

# convert the object into a dict
update_many_message_channels200_response_data_dict = update_many_message_channels200_response_data_instance.to_dict()
# create an instance of UpdateManyMessageChannels200ResponseData from a dict
update_many_message_channels200_response_data_from_dict = UpdateManyMessageChannels200ResponseData.from_dict(update_many_message_channels200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


