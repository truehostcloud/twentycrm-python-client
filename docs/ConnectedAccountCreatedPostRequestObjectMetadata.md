# ConnectedAccountCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.connected_account_created_post_request_object_metadata import ConnectedAccountCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of ConnectedAccountCreatedPostRequestObjectMetadata from a JSON string
connected_account_created_post_request_object_metadata_instance = ConnectedAccountCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(ConnectedAccountCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
connected_account_created_post_request_object_metadata_dict = connected_account_created_post_request_object_metadata_instance.to_dict()
# create an instance of ConnectedAccountCreatedPostRequestObjectMetadata from a dict
connected_account_created_post_request_object_metadata_from_dict = ConnectedAccountCreatedPostRequestObjectMetadata.from_dict(connected_account_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


