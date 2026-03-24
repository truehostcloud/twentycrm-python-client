# CompanyCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.company_created_post_request_object_metadata import CompanyCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of CompanyCreatedPostRequestObjectMetadata from a JSON string
company_created_post_request_object_metadata_instance = CompanyCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(CompanyCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
company_created_post_request_object_metadata_dict = company_created_post_request_object_metadata_instance.to_dict()
# create an instance of CompanyCreatedPostRequestObjectMetadata from a dict
company_created_post_request_object_metadata_from_dict = CompanyCreatedPostRequestObjectMetadata.from_dict(company_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


