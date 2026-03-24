# FindDashboardDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Dashboard]**](Dashboard.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_dashboard_duplicates_request import FindDashboardDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindDashboardDuplicatesRequest from a JSON string
find_dashboard_duplicates_request_instance = FindDashboardDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindDashboardDuplicatesRequest.to_json())

# convert the object into a dict
find_dashboard_duplicates_request_dict = find_dashboard_duplicates_request_instance.to_dict()
# create an instance of FindDashboardDuplicatesRequest from a dict
find_dashboard_duplicates_request_from_dict = FindDashboardDuplicatesRequest.from_dict(find_dashboard_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


