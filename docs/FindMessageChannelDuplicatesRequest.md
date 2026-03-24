# FindMessageChannelDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[MessageChannel]**](MessageChannel.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_message_channel_duplicates_request import FindMessageChannelDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindMessageChannelDuplicatesRequest from a JSON string
find_message_channel_duplicates_request_instance = FindMessageChannelDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindMessageChannelDuplicatesRequest.to_json())

# convert the object into a dict
find_message_channel_duplicates_request_dict = find_message_channel_duplicates_request_instance.to_dict()
# create an instance of FindMessageChannelDuplicatesRequest from a dict
find_message_channel_duplicates_request_from_dict = FindMessageChannelDuplicatesRequest.from_dict(find_message_channel_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


