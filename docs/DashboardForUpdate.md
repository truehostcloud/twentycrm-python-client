# DashboardForUpdate

A dashboard

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | Dashboard title | [optional] 
**position** | **float** | Dashboard record Position | [optional] 
**page_layout_id** | **UUID** | Dashboard page layout | [optional] 
**created_by** | [**AttachmentCreatedBy**](AttachmentCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.dashboard_for_update import DashboardForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of DashboardForUpdate from a JSON string
dashboard_for_update_instance = DashboardForUpdate.from_json(json)
# print the JSON string representation of the object
print(DashboardForUpdate.to_json())

# convert the object into a dict
dashboard_for_update_dict = dashboard_for_update_instance.to_dict()
# create an instance of DashboardForUpdate from a dict
dashboard_for_update_from_dict = DashboardForUpdate.from_dict(dashboard_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


