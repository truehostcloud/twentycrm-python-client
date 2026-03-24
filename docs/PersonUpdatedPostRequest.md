# PersonUpdatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**PersonCreatedPostRequestObjectMetadata**](PersonCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**PersonForResponse**](PersonForResponse.md) |  | [optional] 
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.person_updated_post_request import PersonUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PersonUpdatedPostRequest from a JSON string
person_updated_post_request_instance = PersonUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(PersonUpdatedPostRequest.to_json())

# convert the object into a dict
person_updated_post_request_dict = person_updated_post_request_instance.to_dict()
# create an instance of PersonUpdatedPostRequest from a dict
person_updated_post_request_from_dict = PersonUpdatedPostRequest.from_dict(person_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


