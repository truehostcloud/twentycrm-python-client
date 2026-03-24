# CompanyUpdatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**CompanyCreatedPostRequestObjectMetadata**](CompanyCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**CompanyForResponse**](CompanyForResponse.md) |  | [optional] 
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.company_updated_post_request import CompanyUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CompanyUpdatedPostRequest from a JSON string
company_updated_post_request_instance = CompanyUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(CompanyUpdatedPostRequest.to_json())

# convert the object into a dict
company_updated_post_request_dict = company_updated_post_request_instance.to_dict()
# create an instance of CompanyUpdatedPostRequest from a dict
company_updated_post_request_from_dict = CompanyUpdatedPostRequest.from_dict(company_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


