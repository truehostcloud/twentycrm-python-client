# FindManyAttachments200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**FindManyAttachments200ResponseData**](FindManyAttachments200ResponseData.md) |  | [optional] 
**page_info** | [**FindManyAttachments200ResponsePageInfo**](FindManyAttachments200ResponsePageInfo.md) |  | [optional] 
**total_count** | **int** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_attachments200_response import FindManyAttachments200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyAttachments200Response from a JSON string
find_many_attachments200_response_instance = FindManyAttachments200Response.from_json(json)
# print the JSON string representation of the object
print(FindManyAttachments200Response.to_json())

# convert the object into a dict
find_many_attachments200_response_dict = find_many_attachments200_response_instance.to_dict()
# create an instance of FindManyAttachments200Response from a dict
find_many_attachments200_response_from_dict = FindManyAttachments200Response.from_dict(find_many_attachments200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


