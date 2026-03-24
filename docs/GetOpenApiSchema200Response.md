# GetOpenApiSchema200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**openapi** | **str** |  | [optional] 
**info** | [**GetOpenApiSchema200ResponseInfo**](GetOpenApiSchema200ResponseInfo.md) |  | [optional] 
**servers** | [**List[GetOpenApiSchema200ResponseServersInner]**](GetOpenApiSchema200ResponseServersInner.md) |  | [optional] 
**components** | [**GetOpenApiSchema200ResponseComponents**](GetOpenApiSchema200ResponseComponents.md) |  | [optional] 
**paths** | **object** |  | [optional] 
**tags** | **object** |  | [optional] 

## Example

```python
from twentycrm_client.models.get_open_api_schema200_response import GetOpenApiSchema200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetOpenApiSchema200Response from a JSON string
get_open_api_schema200_response_instance = GetOpenApiSchema200Response.from_json(json)
# print the JSON string representation of the object
print(GetOpenApiSchema200Response.to_json())

# convert the object into a dict
get_open_api_schema200_response_dict = get_open_api_schema200_response_instance.to_dict()
# create an instance of GetOpenApiSchema200Response from a dict
get_open_api_schema200_response_from_dict = GetOpenApiSchema200Response.from_dict(get_open_api_schema200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


