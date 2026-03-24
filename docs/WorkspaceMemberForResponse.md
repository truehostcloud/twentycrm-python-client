# WorkspaceMemberForResponse

A workspace member

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**position** | **float** | Workspace member position | [optional] 
**name** | [**WorkspaceMemberName**](WorkspaceMemberName.md) |  | [optional] 
**color_scheme** | **str** | Preferred color scheme | [optional] 
**locale** | **str** | Preferred language | [optional] 
**avatar_url** | **str** | Workspace member avatar | [optional] 
**user_email** | **str** | Related user email address | [optional] 
**calendar_start_day** | **int** | User&#39;s preferred start day of the week | [optional] 
**user_id** | **UUID** | Associated User Id | [optional] 
**time_zone** | **str** | User time zone | [optional] 
**date_format** | **str** | User&#39;s preferred date format | [optional] 
**time_format** | **str** | User&#39;s preferred time format | [optional] 
**number_format** | **str** | User&#39;s preferred number format | [optional] 
**blocklist** | [**List[BlocklistForResponse]**](BlocklistForResponse.md) | Blocklisted handles | [optional] 
**calendar_event_participants** | [**List[CalendarEventParticipantForResponse]**](CalendarEventParticipantForResponse.md) | Calendar Event Participants | [optional] 
**account_owner_for_companies** | [**List[CompanyForResponse]**](CompanyForResponse.md) | Account owner for companies | [optional] 
**connected_accounts** | [**List[ConnectedAccountForResponse]**](ConnectedAccountForResponse.md) | Connected accounts | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the workspace member | [optional] 
**message_participants** | [**List[MessageParticipantForResponse]**](MessageParticipantForResponse.md) | Message Participants | [optional] 
**owned_opportunities** | [**List[OpportunityForResponse]**](OpportunityForResponse.md) | Opportunities owned by the workspace member | [optional] 
**assigned_tasks** | [**List[TaskForResponse]**](TaskForResponse.md) | Tasks assigned to the workspace member | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Events linked to the workspace member | [optional] 

## Example

```python
from twentycrm_client.models.workspace_member_for_response import WorkspaceMemberForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of WorkspaceMemberForResponse from a JSON string
workspace_member_for_response_instance = WorkspaceMemberForResponse.from_json(json)
# print the JSON string representation of the object
print(WorkspaceMemberForResponse.to_json())

# convert the object into a dict
workspace_member_for_response_dict = workspace_member_for_response_instance.to_dict()
# create an instance of WorkspaceMemberForResponse from a dict
workspace_member_for_response_from_dict = WorkspaceMemberForResponse.from_dict(workspace_member_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


