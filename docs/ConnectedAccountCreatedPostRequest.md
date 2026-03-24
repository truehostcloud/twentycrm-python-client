# ConnectedAccountCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**ConnectedAccountCreatedPostRequestObjectMetadata**](ConnectedAccountCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**ConnectedAccountForResponse**](ConnectedAccountForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.connected_account_created_post_request import ConnectedAccountCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of ConnectedAccountCreatedPostRequest from a JSON string
connected_account_created_post_request_instance = ConnectedAccountCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(ConnectedAccountCreatedPostRequest.to_json())

# convert the object into a dict
connected_account_created_post_request_dict = connected_account_created_post_request_instance.to_dict()
# create an instance of ConnectedAccountCreatedPostRequest from a dict
connected_account_created_post_request_from_dict = ConnectedAccountCreatedPostRequest.from_dict(connected_account_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


