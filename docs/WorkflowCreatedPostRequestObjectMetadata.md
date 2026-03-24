# WorkflowCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_created_post_request_object_metadata import WorkflowCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowCreatedPostRequestObjectMetadata from a JSON string
workflow_created_post_request_object_metadata_instance = WorkflowCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(WorkflowCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
workflow_created_post_request_object_metadata_dict = workflow_created_post_request_object_metadata_instance.to_dict()
# create an instance of WorkflowCreatedPostRequestObjectMetadata from a dict
workflow_created_post_request_object_metadata_from_dict = WorkflowCreatedPostRequestObjectMetadata.from_dict(workflow_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


