# MergeManyMessageChannelMessageAssociationsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ids** | **List[UUID]** | The IDs of the records to merge | 
**conflict_priority_index** | **float** | The index of the record to use when conflicts occur | 
**dry_run** | **bool** | If true, the merge will not be performed and a preview of the merge will be returned. | [optional] [default to False]

## Example

```python
from twentycrm_client.models.merge_many_message_channel_message_associations_request import MergeManyMessageChannelMessageAssociationsRequest

# TODO update the JSON string below
json = "{}"
# create an instance of MergeManyMessageChannelMessageAssociationsRequest from a JSON string
merge_many_message_channel_message_associations_request_instance = MergeManyMessageChannelMessageAssociationsRequest.from_json(json)
# print the JSON string representation of the object
print(MergeManyMessageChannelMessageAssociationsRequest.to_json())

# convert the object into a dict
merge_many_message_channel_message_associations_request_dict = merge_many_message_channel_message_associations_request_instance.to_dict()
# create an instance of MergeManyMessageChannelMessageAssociationsRequest from a dict
merge_many_message_channel_message_associations_request_from_dict = MergeManyMessageChannelMessageAssociationsRequest.from_dict(merge_many_message_channel_message_associations_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


