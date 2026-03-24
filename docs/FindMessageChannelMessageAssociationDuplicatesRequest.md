# FindMessageChannelMessageAssociationDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[MessageChannelMessageAssociation]**](MessageChannelMessageAssociation.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_message_channel_message_association_duplicates_request import FindMessageChannelMessageAssociationDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindMessageChannelMessageAssociationDuplicatesRequest from a JSON string
find_message_channel_message_association_duplicates_request_instance = FindMessageChannelMessageAssociationDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindMessageChannelMessageAssociationDuplicatesRequest.to_json())

# convert the object into a dict
find_message_channel_message_association_duplicates_request_dict = find_message_channel_message_association_duplicates_request_instance.to_dict()
# create an instance of FindMessageChannelMessageAssociationDuplicatesRequest from a dict
find_message_channel_message_association_duplicates_request_from_dict = FindMessageChannelMessageAssociationDuplicatesRequest.from_dict(find_message_channel_message_association_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


