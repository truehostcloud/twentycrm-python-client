# CreateManyDashboards201ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**create_dashboards** | [**List[DashboardForResponse]**](DashboardForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.create_many_dashboards201_response_data import CreateManyDashboards201ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of CreateManyDashboards201ResponseData from a JSON string
create_many_dashboards201_response_data_instance = CreateManyDashboards201ResponseData.from_json(json)
# print the JSON string representation of the object
print(CreateManyDashboards201ResponseData.to_json())

# convert the object into a dict
create_many_dashboards201_response_data_dict = create_many_dashboards201_response_data_instance.to_dict()
# create an instance of CreateManyDashboards201ResponseData from a dict
create_many_dashboards201_response_data_from_dict = CreateManyDashboards201ResponseData.from_dict(create_many_dashboards201_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


