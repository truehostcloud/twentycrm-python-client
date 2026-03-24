# BlocklistCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**BlocklistCreatedPostRequestObjectMetadata**](BlocklistCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**BlocklistForResponse**](BlocklistForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.blocklist_created_post_request import BlocklistCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of BlocklistCreatedPostRequest from a JSON string
blocklist_created_post_request_instance = BlocklistCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(BlocklistCreatedPostRequest.to_json())

# convert the object into a dict
blocklist_created_post_request_dict = blocklist_created_post_request_instance.to_dict()
# create an instance of BlocklistCreatedPostRequest from a dict
blocklist_created_post_request_from_dict = BlocklistCreatedPostRequest.from_dict(blocklist_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


