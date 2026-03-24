# FindPersonDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Person]**](Person.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_person_duplicates_request import FindPersonDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindPersonDuplicatesRequest from a JSON string
find_person_duplicates_request_instance = FindPersonDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindPersonDuplicatesRequest.to_json())

# convert the object into a dict
find_person_duplicates_request_dict = find_person_duplicates_request_instance.to_dict()
# create an instance of FindPersonDuplicatesRequest from a dict
find_person_duplicates_request_from_dict = FindPersonDuplicatesRequest.from_dict(find_person_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


