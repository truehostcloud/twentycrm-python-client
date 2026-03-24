# FindOneAttachment200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**FindOneAttachment200ResponseData**](FindOneAttachment200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_one_attachment200_response import FindOneAttachment200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FindOneAttachment200Response from a JSON string
find_one_attachment200_response_instance = FindOneAttachment200Response.from_json(json)
# print the JSON string representation of the object
print(FindOneAttachment200Response.to_json())

# convert the object into a dict
find_one_attachment200_response_dict = find_one_attachment200_response_instance.to_dict()
# create an instance of FindOneAttachment200Response from a dict
find_one_attachment200_response_from_dict = FindOneAttachment200Response.from_dict(find_one_attachment200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


