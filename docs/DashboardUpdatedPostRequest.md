# DashboardUpdatedPostRequest


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
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.dashboard_updated_post_request import DashboardUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of DashboardUpdatedPostRequest from a JSON string
dashboard_updated_post_request_instance = DashboardUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(DashboardUpdatedPostRequest.to_json())

# convert the object into a dict
dashboard_updated_post_request_dict = dashboard_updated_post_request_instance.to_dict()
# create an instance of DashboardUpdatedPostRequest from a dict
dashboard_updated_post_request_from_dict = DashboardUpdatedPostRequest.from_dict(dashboard_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


