# WorkflowVersionCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_version_created_post_request_object_metadata import WorkflowVersionCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowVersionCreatedPostRequestObjectMetadata from a JSON string
workflow_version_created_post_request_object_metadata_instance = WorkflowVersionCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(WorkflowVersionCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
workflow_version_created_post_request_object_metadata_dict = workflow_version_created_post_request_object_metadata_instance.to_dict()
# create an instance of WorkflowVersionCreatedPostRequestObjectMetadata from a dict
workflow_version_created_post_request_object_metadata_from_dict = WorkflowVersionCreatedPostRequestObjectMetadata.from_dict(workflow_version_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


