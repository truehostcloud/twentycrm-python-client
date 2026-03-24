# FindManyBlocklists200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**FindManyBlocklists200ResponseData**](FindManyBlocklists200ResponseData.md) |  | [optional] 
**page_info** | [**FindManyAttachments200ResponsePageInfo**](FindManyAttachments200ResponsePageInfo.md) |  | [optional] 
**total_count** | **int** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_blocklists200_response import FindManyBlocklists200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyBlocklists200Response from a JSON string
find_many_blocklists200_response_instance = FindManyBlocklists200Response.from_json(json)
# print the JSON string representation of the object
print(FindManyBlocklists200Response.to_json())

# convert the object into a dict
find_many_blocklists200_response_dict = find_many_blocklists200_response_instance.to_dict()
# create an instance of FindManyBlocklists200Response from a dict
find_many_blocklists200_response_from_dict = FindManyBlocklists200Response.from_dict(find_many_blocklists200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


