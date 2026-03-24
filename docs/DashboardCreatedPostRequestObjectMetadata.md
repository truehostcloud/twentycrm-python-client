# DashboardCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.dashboard_created_post_request_object_metadata import DashboardCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of DashboardCreatedPostRequestObjectMetadata from a JSON string
dashboard_created_post_request_object_metadata_instance = DashboardCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(DashboardCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
dashboard_created_post_request_object_metadata_dict = dashboard_created_post_request_object_metadata_instance.to_dict()
# create an instance of DashboardCreatedPostRequestObjectMetadata from a dict
dashboard_created_post_request_object_metadata_from_dict = DashboardCreatedPostRequestObjectMetadata.from_dict(dashboard_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


