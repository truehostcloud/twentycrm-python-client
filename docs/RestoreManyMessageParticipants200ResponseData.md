# RestoreManyMessageParticipants200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**restore_message_participants** | [**List[MessageParticipantForResponse]**](MessageParticipantForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.restore_many_message_participants200_response_data import RestoreManyMessageParticipants200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of RestoreManyMessageParticipants200ResponseData from a JSON string
restore_many_message_participants200_response_data_instance = RestoreManyMessageParticipants200ResponseData.from_json(json)
# print the JSON string representation of the object
print(RestoreManyMessageParticipants200ResponseData.to_json())

# convert the object into a dict
restore_many_message_participants200_response_data_dict = restore_many_message_participants200_response_data_instance.to_dict()
# create an instance of RestoreManyMessageParticipants200ResponseData from a dict
restore_many_message_participants200_response_data_from_dict = RestoreManyMessageParticipants200ResponseData.from_dict(restore_many_message_participants200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


