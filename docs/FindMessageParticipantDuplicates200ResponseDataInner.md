# FindMessageParticipantDuplicates200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_count** | **float** |  | [optional] 
**page_info** | [**FindManyAttachments200ResponsePageInfo**](FindManyAttachments200ResponsePageInfo.md) |  | [optional] 
**message_participant_duplicates** | [**List[MessageParticipantForResponse]**](MessageParticipantForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_message_participant_duplicates200_response_data_inner import FindMessageParticipantDuplicates200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of FindMessageParticipantDuplicates200ResponseDataInner from a JSON string
find_message_participant_duplicates200_response_data_inner_instance = FindMessageParticipantDuplicates200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(FindMessageParticipantDuplicates200ResponseDataInner.to_json())

# convert the object into a dict
find_message_participant_duplicates200_response_data_inner_dict = find_message_participant_duplicates200_response_data_inner_instance.to_dict()
# create an instance of FindMessageParticipantDuplicates200ResponseDataInner from a dict
find_message_participant_duplicates200_response_data_inner_from_dict = FindMessageParticipantDuplicates200ResponseDataInner.from_dict(find_message_participant_duplicates200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


