# OpportunityCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**OpportunityCreatedPostRequestObjectMetadata**](OpportunityCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**OpportunityForResponse**](OpportunityForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.opportunity_created_post_request import OpportunityCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of OpportunityCreatedPostRequest from a JSON string
opportunity_created_post_request_instance = OpportunityCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(OpportunityCreatedPostRequest.to_json())

# convert the object into a dict
opportunity_created_post_request_dict = opportunity_created_post_request_instance.to_dict()
# create an instance of OpportunityCreatedPostRequest from a dict
opportunity_created_post_request_from_dict = OpportunityCreatedPostRequest.from_dict(opportunity_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


