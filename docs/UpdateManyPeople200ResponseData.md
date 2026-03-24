# UpdateManyPeople200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**update_people** | [**List[PersonForResponse]**](PersonForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.update_many_people200_response_data import UpdateManyPeople200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateManyPeople200ResponseData from a JSON string
update_many_people200_response_data_instance = UpdateManyPeople200ResponseData.from_json(json)
# print the JSON string representation of the object
print(UpdateManyPeople200ResponseData.to_json())

# convert the object into a dict
update_many_people200_response_data_dict = update_many_people200_response_data_instance.to_dict()
# create an instance of UpdateManyPeople200ResponseData from a dict
update_many_people200_response_data_from_dict = UpdateManyPeople200ResponseData.from_dict(update_many_people200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


