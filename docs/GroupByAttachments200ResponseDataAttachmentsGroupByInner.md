# GroupByAttachments200ResponseDataAttachmentsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[AttachmentForResponse]**](AttachmentForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_attachments200_response_data_attachments_group_by_inner import GroupByAttachments200ResponseDataAttachmentsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByAttachments200ResponseDataAttachmentsGroupByInner from a JSON string
group_by_attachments200_response_data_attachments_group_by_inner_instance = GroupByAttachments200ResponseDataAttachmentsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByAttachments200ResponseDataAttachmentsGroupByInner.to_json())

# convert the object into a dict
group_by_attachments200_response_data_attachments_group_by_inner_dict = group_by_attachments200_response_data_attachments_group_by_inner_instance.to_dict()
# create an instance of GroupByAttachments200ResponseDataAttachmentsGroupByInner from a dict
group_by_attachments200_response_data_attachments_group_by_inner_from_dict = GroupByAttachments200ResponseDataAttachmentsGroupByInner.from_dict(group_by_attachments200_response_data_attachments_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


