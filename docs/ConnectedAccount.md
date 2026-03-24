# ConnectedAccount

A connected account

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**handle** | **str** | The account handle (email, username, phone number, etc.) | [optional] 
**provider** | **str** | The account provider | [optional] 
**access_token** | **str** | Messaging provider access token | [optional] 
**refresh_token** | **str** | Messaging provider refresh token | [optional] 
**last_sync_history_id** | **str** | Last sync history ID | [optional] 
**auth_failed_at** | **datetime** | Auth failed at | [optional] 
**last_credentials_refreshed_at** | **datetime** | Last credentials refreshed at | [optional] 
**handle_aliases** | **str** | Handle Aliases | [optional] 
**scopes** | **List[str]** | Scopes | [optional] 
**connection_parameters** | **object** | JSON object containing custom connection parameters | [optional] 
**account_owner_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.connected_account import ConnectedAccount

# TODO update the JSON string below
json = "{}"
# create an instance of ConnectedAccount from a JSON string
connected_account_instance = ConnectedAccount.from_json(json)
# print the JSON string representation of the object
print(ConnectedAccount.to_json())

# convert the object into a dict
connected_account_dict = connected_account_instance.to_dict()
# create an instance of ConnectedAccount from a dict
connected_account_from_dict = ConnectedAccount.from_dict(connected_account_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


