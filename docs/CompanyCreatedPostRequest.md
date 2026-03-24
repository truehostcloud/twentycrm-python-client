# CompanyCreatedPostRequest


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

## Example

```python
from twentycrm_client.models.company_created_post_request import CompanyCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CompanyCreatedPostRequest from a JSON string
company_created_post_request_instance = CompanyCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(CompanyCreatedPostRequest.to_json())

# convert the object into a dict
company_created_post_request_dict = company_created_post_request_instance.to_dict()
# create an instance of CompanyCreatedPostRequest from a dict
company_created_post_request_from_dict = CompanyCreatedPostRequest.from_dict(company_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


