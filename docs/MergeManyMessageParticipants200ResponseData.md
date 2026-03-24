# MergeManyMessageParticipants200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merge_message_participants** | [**MessageParticipantForResponse**](MessageParticipantForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.merge_many_message_participants200_response_data import MergeManyMessageParticipants200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of MergeManyMessageParticipants200ResponseData from a JSON string
merge_many_message_participants200_response_data_instance = MergeManyMessageParticipants200ResponseData.from_json(json)
# print the JSON string representation of the object
print(MergeManyMessageParticipants200ResponseData.to_json())

# convert the object into a dict
merge_many_message_participants200_response_data_dict = merge_many_message_participants200_response_data_instance.to_dict()
# create an instance of MergeManyMessageParticipants200ResponseData from a dict
merge_many_message_participants200_response_data_from_dict = MergeManyMessageParticipants200ResponseData.from_dict(merge_many_message_participants200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


