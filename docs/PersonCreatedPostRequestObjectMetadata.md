# PersonCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.person_created_post_request_object_metadata import PersonCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of PersonCreatedPostRequestObjectMetadata from a JSON string
person_created_post_request_object_metadata_instance = PersonCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(PersonCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
person_created_post_request_object_metadata_dict = person_created_post_request_object_metadata_instance.to_dict()
# create an instance of PersonCreatedPostRequestObjectMetadata from a dict
person_created_post_request_object_metadata_from_dict = PersonCreatedPostRequestObjectMetadata.from_dict(person_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


