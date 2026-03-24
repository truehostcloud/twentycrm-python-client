# DashboardForResponse

A dashboard

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**title** | **str** | Dashboard title | [optional] 
**position** | **float** | Dashboard record Position | [optional] 
**page_layout_id** | **UUID** | Dashboard page layout | [optional] 
**created_by** | [**AttachmentForResponseCreatedBy**](AttachmentForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**attachments** | [**List[AttachmentForResponse]**](AttachmentForResponse.md) | Attachments linked to the dashboard | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Timeline activities linked to the dashboard | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the dashboard | [optional] 

## Example

```python
from twentycrm_client.models.dashboard_for_response import DashboardForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of DashboardForResponse from a JSON string
dashboard_for_response_instance = DashboardForResponse.from_json(json)
# print the JSON string representation of the object
print(DashboardForResponse.to_json())

# convert the object into a dict
dashboard_for_response_dict = dashboard_for_response_instance.to_dict()
# create an instance of DashboardForResponse from a dict
dashboard_for_response_from_dict = DashboardForResponse.from_dict(dashboard_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


