# DeleteManyCompanies200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delete_companies** | [**List[DeleteManyAttachments200ResponseDataDeleteAttachmentsInner]**](DeleteManyAttachments200ResponseDataDeleteAttachmentsInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_companies200_response_data import DeleteManyCompanies200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyCompanies200ResponseData from a JSON string
delete_many_companies200_response_data_instance = DeleteManyCompanies200ResponseData.from_json(json)
# print the JSON string representation of the object
print(DeleteManyCompanies200ResponseData.to_json())

# convert the object into a dict
delete_many_companies200_response_data_dict = delete_many_companies200_response_data_instance.to_dict()
# create an instance of DeleteManyCompanies200ResponseData from a dict
delete_many_companies200_response_data_from_dict = DeleteManyCompanies200ResponseData.from_dict(delete_many_companies200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


