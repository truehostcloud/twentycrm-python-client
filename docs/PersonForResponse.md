# PersonForResponse

A person

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**name** | [**PersonName**](PersonName.md) |  | [optional] 
**emails** | [**PersonEmails**](PersonEmails.md) |  | [optional] 
**linkedin_link** | [**PersonLinkedinLink**](PersonLinkedinLink.md) |  | [optional] 
**x_link** | [**PersonXLink**](PersonXLink.md) |  | [optional] 
**job_title** | **str** | Contact&#39;s job title | [optional] 
**phones** | [**PersonPhones**](PersonPhones.md) |  | [optional] 
**city** | **str** | Contact&#39;s city | [optional] 
**avatar_url** | **str** | Contact&#39;s avatar | [optional] 
**avatar_file** | [**List[AttachmentForResponseFileInner]**](AttachmentForResponseFileInner.md) | Contact&#39;s avatar file | [optional] 
**position** | **float** | Person record Position | [optional] 
**created_by** | [**AttachmentForResponseCreatedBy**](AttachmentForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**company_id** | **UUID** |  | [optional] 
**attachments** | [**List[AttachmentForResponse]**](AttachmentForResponse.md) | Attachments linked to the contact. | [optional] 
**calendar_event_participants** | [**List[CalendarEventParticipantForResponse]**](CalendarEventParticipantForResponse.md) | Calendar Event Participants | [optional] 
**company** | [**CompanyForResponse**](CompanyForResponse.md) |  | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the contact | [optional] 
**message_participants** | [**List[MessageParticipantForResponse]**](MessageParticipantForResponse.md) | Message Participants | [optional] 
**note_targets** | [**List[NoteTargetForResponse]**](NoteTargetForResponse.md) | Notes tied to the contact | [optional] 
**point_of_contact_for_opportunities** | [**List[OpportunityForResponse]**](OpportunityForResponse.md) | List of opportunities for which that person is the point of contact | [optional] 
**task_targets** | [**List[TaskTargetForResponse]**](TaskTargetForResponse.md) | Tasks tied to the contact | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Events linked to the person | [optional] 

## Example

```python
from twentycrm_client.models.person_for_response import PersonForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of PersonForResponse from a JSON string
person_for_response_instance = PersonForResponse.from_json(json)
# print the JSON string representation of the object
print(PersonForResponse.to_json())

# convert the object into a dict
person_for_response_dict = person_for_response_instance.to_dict()
# create an instance of PersonForResponse from a dict
person_for_response_from_dict = PersonForResponse.from_dict(person_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


