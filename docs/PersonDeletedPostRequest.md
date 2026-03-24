# PersonDeletedPostRequest


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

## Example

```python
from twentycrm_client.models.person_deleted_post_request import PersonDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PersonDeletedPostRequest from a JSON string
person_deleted_post_request_instance = PersonDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(PersonDeletedPostRequest.to_json())

# convert the object into a dict
person_deleted_post_request_dict = person_deleted_post_request_instance.to_dict()
# create an instance of PersonDeletedPostRequest from a dict
person_deleted_post_request_from_dict = PersonDeletedPostRequest.from_dict(person_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


