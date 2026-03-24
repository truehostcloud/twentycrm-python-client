# GroupByCalendarEvents200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**GroupByCalendarEvents200ResponseData**](GroupByCalendarEvents200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_calendar_events200_response import GroupByCalendarEvents200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByCalendarEvents200Response from a JSON string
group_by_calendar_events200_response_instance = GroupByCalendarEvents200Response.from_json(json)
# print the JSON string representation of the object
print(GroupByCalendarEvents200Response.to_json())

# convert the object into a dict
group_by_calendar_events200_response_dict = group_by_calendar_events200_response_instance.to_dict()
# create an instance of GroupByCalendarEvents200Response from a dict
group_by_calendar_events200_response_from_dict = GroupByCalendarEvents200Response.from_dict(group_by_calendar_events200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


