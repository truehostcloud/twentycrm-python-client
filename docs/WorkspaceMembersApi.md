# twentycrm_client.WorkspaceMembersApi

All URIs are relative to *https://crm.example.com/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_many_workspace_members**](WorkspaceMembersApi.md#create_many_workspace_members) | **POST** /batch/workspaceMembers | Create Many workspaceMembers
[**create_one_workspace_member**](WorkspaceMembersApi.md#create_one_workspace_member) | **POST** /workspaceMembers | Create One workspaceMember
[**delete_many_workspace_members**](WorkspaceMembersApi.md#delete_many_workspace_members) | **DELETE** /workspaceMembers | Delete Many workspaceMembers
[**delete_one_workspace_member**](WorkspaceMembersApi.md#delete_one_workspace_member) | **DELETE** /workspaceMembers/{id} | Delete One workspaceMember
[**find_many_workspace_members**](WorkspaceMembersApi.md#find_many_workspace_members) | **GET** /workspaceMembers | Find Many workspaceMembers
[**find_one_workspace_member**](WorkspaceMembersApi.md#find_one_workspace_member) | **GET** /workspaceMembers/{id} | Find One workspaceMember
[**find_workspace_member_duplicates**](WorkspaceMembersApi.md#find_workspace_member_duplicates) | **POST** /workspaceMembers/duplicates | Find workspaceMember Duplicates
[**group_by_workspace_members**](WorkspaceMembersApi.md#group_by_workspace_members) | **GET** /workspaceMembers/groupBy | Group By workspaceMembers
[**merge_many_workspace_members**](WorkspaceMembersApi.md#merge_many_workspace_members) | **PATCH** /workspaceMembers/merge | Merge Many workspaceMembers
[**restore_many_workspace_members**](WorkspaceMembersApi.md#restore_many_workspace_members) | **PATCH** /restore/workspaceMembers | Restore Many workspaceMembers
[**restore_one_workspace_member**](WorkspaceMembersApi.md#restore_one_workspace_member) | **PATCH** /restore/workspaceMembers/{id} | Restore One workspaceMember
[**update_many_workspace_members**](WorkspaceMembersApi.md#update_many_workspace_members) | **PATCH** /workspaceMembers | Update Many workspaceMembers
[**update_one_workspace_member**](WorkspaceMembersApi.md#update_one_workspace_member) | **PATCH** /workspaceMembers/{id} | Update One workspaceMember


# **create_many_workspace_members**
> CreateManyWorkspaceMembers201Response create_many_workspace_members(workspace_member, depth=depth, upsert=upsert)

Create Many workspaceMembers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.create_many_workspace_members201_response import CreateManyWorkspaceMembers201Response
from twentycrm_client.models.workspace_member import WorkspaceMember
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    workspace_member = [twentycrm_client.WorkspaceMember()] # List[WorkspaceMember] | 
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create Many workspaceMembers
        api_response = api_instance.create_many_workspace_members(workspace_member, depth=depth, upsert=upsert)
        print("The response of WorkspaceMembersApi->create_many_workspace_members:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->create_many_workspace_members: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workspace_member** | [**List[WorkspaceMember]**](WorkspaceMember.md)|  | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateManyWorkspaceMembers201Response**](CreateManyWorkspaceMembers201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_one_workspace_member**
> CreateOneWorkspaceMember201Response create_one_workspace_member(workspace_member, depth=depth, upsert=upsert)

Create One workspaceMember

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.create_one_workspace_member201_response import CreateOneWorkspaceMember201Response
from twentycrm_client.models.workspace_member import WorkspaceMember
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    workspace_member = twentycrm_client.WorkspaceMember() # WorkspaceMember | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create One workspaceMember
        api_response = api_instance.create_one_workspace_member(workspace_member, depth=depth, upsert=upsert)
        print("The response of WorkspaceMembersApi->create_one_workspace_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->create_one_workspace_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workspace_member** | [**WorkspaceMember**](WorkspaceMember.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateOneWorkspaceMember201Response**](CreateOneWorkspaceMember201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_many_workspace_members**
> DeleteManyWorkspaceMembers200Response delete_many_workspace_members(filter=filter, soft_delete=soft_delete)

Delete Many workspaceMembers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_many_workspace_members200_response import DeleteManyWorkspaceMembers200Response
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete Many workspaceMembers
        api_response = api_instance.delete_many_workspace_members(filter=filter, soft_delete=soft_delete)
        print("The response of WorkspaceMembersApi->delete_many_workspace_members:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->delete_many_workspace_members: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteManyWorkspaceMembers200Response**](DeleteManyWorkspaceMembers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_one_workspace_member**
> DeleteOneWorkspaceMember200Response delete_one_workspace_member(id, soft_delete=soft_delete)

Delete One workspaceMember

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_one_workspace_member200_response import DeleteOneWorkspaceMember200Response
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete One workspaceMember
        api_response = api_instance.delete_one_workspace_member(id, soft_delete=soft_delete)
        print("The response of WorkspaceMembersApi->delete_one_workspace_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->delete_one_workspace_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteOneWorkspaceMember200Response**](DeleteOneWorkspaceMember200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_many_workspace_members**
> FindManyWorkspaceMembers200Response find_many_workspace_members(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)

Find Many workspaceMembers

**order_by**, **filter**, **limit**, **depth**, **starting_after** or **ending_before** can be provided to request your **workspaceMembers**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_many_workspace_members200_response import FindManyWorkspaceMembers200Response
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    starting_after = 'starting_after_example' # str | Returns objects starting after a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)
    ending_before = 'ending_before_example' # str | Returns objects ending before a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)

    try:
        # Find Many workspaceMembers
        api_response = api_instance.find_many_workspace_members(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)
        print("The response of WorkspaceMembersApi->find_many_workspace_members:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->find_many_workspace_members: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **order_by** | **str**| Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. | [optional] 
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **limit** | **int**| Limits the number of objects returned. | [optional] [default to 60]
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **starting_after** | **str**| Returns objects starting after a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data | [optional] 
 **ending_before** | **str**| Returns objects ending before a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data | [optional] 

### Return type

[**FindManyWorkspaceMembers200Response**](FindManyWorkspaceMembers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_one_workspace_member**
> FindOneWorkspaceMember200Response find_one_workspace_member(id, depth=depth)

Find One workspaceMember

**depth** can be provided to request your **workspaceMember**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_one_workspace_member200_response import FindOneWorkspaceMember200Response
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find One workspaceMember
        api_response = api_instance.find_one_workspace_member(id, depth=depth)
        print("The response of WorkspaceMembersApi->find_one_workspace_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->find_one_workspace_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindOneWorkspaceMember200Response**](FindOneWorkspaceMember200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **find_workspace_member_duplicates**
> FindWorkspaceMemberDuplicates200Response find_workspace_member_duplicates(find_workspace_member_duplicates_request, depth=depth)

Find workspaceMember Duplicates

**depth** can be provided to request your **workspaceMember**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_workspace_member_duplicates200_response import FindWorkspaceMemberDuplicates200Response
from twentycrm_client.models.find_workspace_member_duplicates_request import FindWorkspaceMemberDuplicatesRequest
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    find_workspace_member_duplicates_request = twentycrm_client.FindWorkspaceMemberDuplicatesRequest() # FindWorkspaceMemberDuplicatesRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find workspaceMember Duplicates
        api_response = api_instance.find_workspace_member_duplicates(find_workspace_member_duplicates_request, depth=depth)
        print("The response of WorkspaceMembersApi->find_workspace_member_duplicates:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->find_workspace_member_duplicates: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **find_workspace_member_duplicates_request** | [**FindWorkspaceMemberDuplicatesRequest**](FindWorkspaceMemberDuplicatesRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindWorkspaceMemberDuplicates200Response**](FindWorkspaceMemberDuplicates200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **group_by_workspace_members**
> GroupByWorkspaceMembers200Response group_by_workspace_members(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)

Group By workspaceMembers

Groups **workspaceMembers** by specified fields and optionally computes aggregate values for each group.

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.group_by_workspace_members200_response import GroupByWorkspaceMembers200Response
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    group_by = '[{\"updatedAt\": true}]' # str | Array of fields to group by. Each element can specify a field and optionally a subfield or granularity for date fields.
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    view_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | View ID to apply filters from. (optional)
    aggregate = '[\"countNotEmptyId\"]' # str | Array of aggregate operations to compute for each group. (optional)
    include_records_sample = False # bool | If true, includes a sample of records for each group in the response. (optional) (default to False)
    order_by_for_records = 'createdAt' # str | Order by clause for records within each group. Only applicable when include_records_sample is true. (optional)

    try:
        # Group By workspaceMembers
        api_response = api_instance.group_by_workspace_members(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)
        print("The response of WorkspaceMembersApi->group_by_workspace_members:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->group_by_workspace_members: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_by** | **str**| Array of fields to group by. Each element can specify a field and optionally a subfield or granularity for date fields. | 
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **order_by** | **str**| Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. | [optional] 
 **limit** | **int**| Limits the number of objects returned. | [optional] [default to 60]
 **view_id** | **UUID**| View ID to apply filters from. | [optional] 
 **aggregate** | **str**| Array of aggregate operations to compute for each group. | [optional] 
 **include_records_sample** | **bool**| If true, includes a sample of records for each group in the response. | [optional] [default to False]
 **order_by_for_records** | **str**| Order by clause for records within each group. Only applicable when include_records_sample is true. | [optional] 

### Return type

[**GroupByWorkspaceMembers200Response**](GroupByWorkspaceMembers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **merge_many_workspace_members**
> MergeManyWorkspaceMembers200Response merge_many_workspace_members(merge_many_workspace_members_request, depth=depth)

Merge Many workspaceMembers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.merge_many_workspace_members200_response import MergeManyWorkspaceMembers200Response
from twentycrm_client.models.merge_many_workspace_members_request import MergeManyWorkspaceMembersRequest
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    merge_many_workspace_members_request = twentycrm_client.MergeManyWorkspaceMembersRequest() # MergeManyWorkspaceMembersRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Merge Many workspaceMembers
        api_response = api_instance.merge_many_workspace_members(merge_many_workspace_members_request, depth=depth)
        print("The response of WorkspaceMembersApi->merge_many_workspace_members:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->merge_many_workspace_members: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merge_many_workspace_members_request** | [**MergeManyWorkspaceMembersRequest**](MergeManyWorkspaceMembersRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**MergeManyWorkspaceMembers200Response**](MergeManyWorkspaceMembers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **restore_many_workspace_members**
> RestoreManyWorkspaceMembers200Response restore_many_workspace_members(filter=filter, depth=depth)

Restore Many workspaceMembers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_many_workspace_members200_response import RestoreManyWorkspaceMembers200Response
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore Many workspaceMembers
        api_response = api_instance.restore_many_workspace_members(filter=filter, depth=depth)
        print("The response of WorkspaceMembersApi->restore_many_workspace_members:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->restore_many_workspace_members: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreManyWorkspaceMembers200Response**](RestoreManyWorkspaceMembers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **restore_one_workspace_member**
> RestoreOneWorkspaceMember200Response restore_one_workspace_member(id, depth=depth)

Restore One workspaceMember

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_one_workspace_member200_response import RestoreOneWorkspaceMember200Response
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore One workspaceMember
        api_response = api_instance.restore_one_workspace_member(id, depth=depth)
        print("The response of WorkspaceMembersApi->restore_one_workspace_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->restore_one_workspace_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreOneWorkspaceMember200Response**](RestoreOneWorkspaceMember200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_many_workspace_members**
> UpdateManyWorkspaceMembers200Response update_many_workspace_members(workspace_member_for_update, depth=depth, filter=filter)

Update Many workspaceMembers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.update_many_workspace_members200_response import UpdateManyWorkspaceMembers200Response
from twentycrm_client.models.workspace_member_for_update import WorkspaceMemberForUpdate
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    workspace_member_for_update = twentycrm_client.WorkspaceMemberForUpdate() # WorkspaceMemberForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)

    try:
        # Update Many workspaceMembers
        api_response = api_instance.update_many_workspace_members(workspace_member_for_update, depth=depth, filter=filter)
        print("The response of WorkspaceMembersApi->update_many_workspace_members:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->update_many_workspace_members: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workspace_member_for_update** | [**WorkspaceMemberForUpdate**](WorkspaceMemberForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 

### Return type

[**UpdateManyWorkspaceMembers200Response**](UpdateManyWorkspaceMembers200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_one_workspace_member**
> UpdateOneWorkspaceMember200Response update_one_workspace_member(id, workspace_member_for_update, depth=depth)

Update One workspaceMember

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.update_one_workspace_member200_response import UpdateOneWorkspaceMember200Response
from twentycrm_client.models.workspace_member_for_update import WorkspaceMemberForUpdate
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearerAuth
configuration = twentycrm_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.WorkspaceMembersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    workspace_member_for_update = twentycrm_client.WorkspaceMemberForUpdate() # WorkspaceMemberForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Update One workspaceMember
        api_response = api_instance.update_one_workspace_member(id, workspace_member_for_update, depth=depth)
        print("The response of WorkspaceMembersApi->update_one_workspace_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkspaceMembersApi->update_one_workspace_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **workspace_member_for_update** | [**WorkspaceMemberForUpdate**](WorkspaceMemberForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**UpdateOneWorkspaceMember200Response**](UpdateOneWorkspaceMember200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful operation |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

