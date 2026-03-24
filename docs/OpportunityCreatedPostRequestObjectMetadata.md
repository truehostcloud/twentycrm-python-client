# OpportunityCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.opportunity_created_post_request_object_metadata import OpportunityCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of OpportunityCreatedPostRequestObjectMetadata from a JSON string
opportunity_created_post_request_object_metadata_instance = OpportunityCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(OpportunityCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
opportunity_created_post_request_object_metadata_dict = opportunity_created_post_request_object_metadata_instance.to_dict()
# create an instance of OpportunityCreatedPostRequestObjectMetadata from a dict
opportunity_created_post_request_object_metadata_from_dict = OpportunityCreatedPostRequestObjectMetadata.from_dict(opportunity_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


