# FavoriteUpdatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**FavoriteCreatedPostRequestObjectMetadata**](FavoriteCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**FavoriteForResponse**](FavoriteForResponse.md) |  | [optional] 
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.favorite_updated_post_request import FavoriteUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FavoriteUpdatedPostRequest from a JSON string
favorite_updated_post_request_instance = FavoriteUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(FavoriteUpdatedPostRequest.to_json())

# convert the object into a dict
favorite_updated_post_request_dict = favorite_updated_post_request_instance.to_dict()
# create an instance of FavoriteUpdatedPostRequest from a dict
favorite_updated_post_request_from_dict = FavoriteUpdatedPostRequest.from_dict(favorite_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


