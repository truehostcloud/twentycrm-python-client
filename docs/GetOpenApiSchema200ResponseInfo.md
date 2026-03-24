# GetOpenApiSchema200ResponseInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**terms_of_service** | **str** |  | [optional] 
**contact** | [**GetOpenApiSchema200ResponseInfoContact**](GetOpenApiSchema200ResponseInfoContact.md) |  | [optional] 
**license** | [**GetOpenApiSchema200ResponseInfoLicense**](GetOpenApiSchema200ResponseInfoLicense.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.get_open_api_schema200_response_info import GetOpenApiSchema200ResponseInfo

# TODO update the JSON string below
json = "{}"
# create an instance of GetOpenApiSchema200ResponseInfo from a JSON string
get_open_api_schema200_response_info_instance = GetOpenApiSchema200ResponseInfo.from_json(json)
# print the JSON string representation of the object
print(GetOpenApiSchema200ResponseInfo.to_json())

# convert the object into a dict
get_open_api_schema200_response_info_dict = get_open_api_schema200_response_info_instance.to_dict()
# create an instance of GetOpenApiSchema200ResponseInfo from a dict
get_open_api_schema200_response_info_from_dict = GetOpenApiSchema200ResponseInfo.from_dict(get_open_api_schema200_response_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


