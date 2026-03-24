# FindMessageParticipantDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[MessageParticipant]**](MessageParticipant.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_message_participant_duplicates_request import FindMessageParticipantDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindMessageParticipantDuplicatesRequest from a JSON string
find_message_participant_duplicates_request_instance = FindMessageParticipantDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindMessageParticipantDuplicatesRequest.to_json())

# convert the object into a dict
find_message_participant_duplicates_request_dict = find_message_participant_duplicates_request_instance.to_dict()
# create an instance of FindMessageParticipantDuplicatesRequest from a dict
find_message_participant_duplicates_request_from_dict = FindMessageParticipantDuplicatesRequest.from_dict(find_message_participant_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


