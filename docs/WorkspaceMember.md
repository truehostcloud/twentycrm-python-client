# WorkspaceMember

A workspace member

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**position** | **float** | Workspace member position | [optional] 
**name** | [**WorkspaceMemberName**](WorkspaceMemberName.md) |  | 
**color_scheme** | **str** | Preferred color scheme | [optional] 
**locale** | **str** | Preferred language | [optional] 
**avatar_url** | **str** | Workspace member avatar | [optional] 
**user_email** | **str** | Related user email address | [optional] 
**calendar_start_day** | **int** | User&#39;s preferred start day of the week | [optional] 
**user_id** | **UUID** | Associated User Id | 
**time_zone** | **str** | User time zone | [optional] 
**date_format** | **str** | User&#39;s preferred date format | [optional] 
**time_format** | **str** | User&#39;s preferred time format | [optional] 
**number_format** | **str** | User&#39;s preferred number format | [optional] 

## Example

```python
from twentycrm_client.models.workspace_member import WorkspaceMember

# TODO update the JSON string below
json = "{}"
# create an instance of WorkspaceMember from a JSON string
workspace_member_instance = WorkspaceMember.from_json(json)
# print the JSON string representation of the object
print(WorkspaceMember.to_json())

# convert the object into a dict
workspace_member_dict = workspace_member_instance.to_dict()
# create an instance of WorkspaceMember from a dict
workspace_member_from_dict = WorkspaceMember.from_dict(workspace_member_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


