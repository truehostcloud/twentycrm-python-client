# FindPersonDuplicates200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[FindPersonDuplicates200ResponseDataInner]**](FindPersonDuplicates200ResponseDataInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_person_duplicates200_response import FindPersonDuplicates200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FindPersonDuplicates200Response from a JSON string
find_person_duplicates200_response_instance = FindPersonDuplicates200Response.from_json(json)
# print the JSON string representation of the object
print(FindPersonDuplicates200Response.to_json())

# convert the object into a dict
find_person_duplicates200_response_dict = find_person_duplicates200_response_instance.to_dict()
# create an instance of FindPersonDuplicates200Response from a dict
find_person_duplicates200_response_from_dict = FindPersonDuplicates200Response.from_dict(find_person_duplicates200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


