# TaskCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.task_created_post_request_object_metadata import TaskCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of TaskCreatedPostRequestObjectMetadata from a JSON string
task_created_post_request_object_metadata_instance = TaskCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(TaskCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
task_created_post_request_object_metadata_dict = task_created_post_request_object_metadata_instance.to_dict()
# create an instance of TaskCreatedPostRequestObjectMetadata from a dict
task_created_post_request_object_metadata_from_dict = TaskCreatedPostRequestObjectMetadata.from_dict(task_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


