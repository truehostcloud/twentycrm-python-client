# RestoreOneNote200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**RestoreOneNote200ResponseData**](RestoreOneNote200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.restore_one_note200_response import RestoreOneNote200Response

# TODO update the JSON string below
json = "{}"
# create an instance of RestoreOneNote200Response from a JSON string
restore_one_note200_response_instance = RestoreOneNote200Response.from_json(json)
# print the JSON string representation of the object
print(RestoreOneNote200Response.to_json())

# convert the object into a dict
restore_one_note200_response_dict = restore_one_note200_response_instance.to_dict()
# create an instance of RestoreOneNote200Response from a dict
restore_one_note200_response_from_dict = RestoreOneNote200Response.from_dict(restore_one_note200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


