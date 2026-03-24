# DashboardCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**DashboardCreatedPostRequestObjectMetadata**](DashboardCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**DashboardForResponse**](DashboardForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.dashboard_created_post_request import DashboardCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of DashboardCreatedPostRequest from a JSON string
dashboard_created_post_request_instance = DashboardCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(DashboardCreatedPostRequest.to_json())

# convert the object into a dict
dashboard_created_post_request_dict = dashboard_created_post_request_instance.to_dict()
# create an instance of DashboardCreatedPostRequest from a dict
dashboard_created_post_request_from_dict = DashboardCreatedPostRequest.from_dict(dashboard_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


