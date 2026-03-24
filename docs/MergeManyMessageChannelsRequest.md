# MergeManyMessageChannelsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ids** | **List[UUID]** | The IDs of the records to merge | 
**conflict_priority_index** | **float** | The index of the record to use when conflicts occur | 
**dry_run** | **bool** | If true, the merge will not be performed and a preview of the merge will be returned. | [optional] [default to False]

## Example

```python
from twentycrm_client.models.merge_many_message_channels_request import MergeManyMessageChannelsRequest

# TODO update the JSON string below
json = "{}"
# create an instance of MergeManyMessageChannelsRequest from a JSON string
merge_many_message_channels_request_instance = MergeManyMessageChannelsRequest.from_json(json)
# print the JSON string representation of the object
print(MergeManyMessageChannelsRequest.to_json())

# convert the object into a dict
merge_many_message_channels_request_dict = merge_many_message_channels_request_instance.to_dict()
# create an instance of MergeManyMessageChannelsRequest from a dict
merge_many_message_channels_request_from_dict = MergeManyMessageChannelsRequest.from_dict(merge_many_message_channels_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


