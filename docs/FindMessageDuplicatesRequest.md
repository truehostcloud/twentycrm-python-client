# FindMessageDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Message]**](Message.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_message_duplicates_request import FindMessageDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindMessageDuplicatesRequest from a JSON string
find_message_duplicates_request_instance = FindMessageDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindMessageDuplicatesRequest.to_json())

# convert the object into a dict
find_message_duplicates_request_dict = find_message_duplicates_request_instance.to_dict()
# create an instance of FindMessageDuplicatesRequest from a dict
find_message_duplicates_request_from_dict = FindMessageDuplicatesRequest.from_dict(find_message_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


