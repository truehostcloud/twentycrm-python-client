# GroupByMessageParticipants200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**GroupByMessageParticipants200ResponseData**](GroupByMessageParticipants200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_message_participants200_response import GroupByMessageParticipants200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByMessageParticipants200Response from a JSON string
group_by_message_participants200_response_instance = GroupByMessageParticipants200Response.from_json(json)
# print the JSON string representation of the object
print(GroupByMessageParticipants200Response.to_json())

# convert the object into a dict
group_by_message_participants200_response_dict = group_by_message_participants200_response_instance.to_dict()
# create an instance of GroupByMessageParticipants200Response from a dict
group_by_message_participants200_response_from_dict = GroupByMessageParticipants200Response.from_dict(group_by_message_participants200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


