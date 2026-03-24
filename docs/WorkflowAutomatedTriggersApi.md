# twentycrm_client.WorkflowAutomatedTriggersApi

All URIs are relative to *https://crm.example.com/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_many_workflow_automated_triggers**](WorkflowAutomatedTriggersApi.md#create_many_workflow_automated_triggers) | **POST** /batch/workflowAutomatedTriggers | Create Many workflowAutomatedTriggers
[**create_one_workflow_automated_trigger**](WorkflowAutomatedTriggersApi.md#create_one_workflow_automated_trigger) | **POST** /workflowAutomatedTriggers | Create One workflowAutomatedTrigger
[**delete_many_workflow_automated_triggers**](WorkflowAutomatedTriggersApi.md#delete_many_workflow_automated_triggers) | **DELETE** /workflowAutomatedTriggers | Delete Many workflowAutomatedTriggers
[**delete_one_workflow_automated_trigger**](WorkflowAutomatedTriggersApi.md#delete_one_workflow_automated_trigger) | **DELETE** /workflowAutomatedTriggers/{id} | Delete One workflowAutomatedTrigger
[**find_many_workflow_automated_triggers**](WorkflowAutomatedTriggersApi.md#find_many_workflow_automated_triggers) | **GET** /workflowAutomatedTriggers | Find Many workflowAutomatedTriggers
[**find_one_workflow_automated_trigger**](WorkflowAutomatedTriggersApi.md#find_one_workflow_automated_trigger) | **GET** /workflowAutomatedTriggers/{id} | Find One workflowAutomatedTrigger
[**find_workflow_automated_trigger_duplicates**](WorkflowAutomatedTriggersApi.md#find_workflow_automated_trigger_duplicates) | **POST** /workflowAutomatedTriggers/duplicates | Find workflowAutomatedTrigger Duplicates
[**group_by_workflow_automated_triggers**](WorkflowAutomatedTriggersApi.md#group_by_workflow_automated_triggers) | **GET** /workflowAutomatedTriggers/groupBy | Group By workflowAutomatedTriggers
[**merge_many_workflow_automated_triggers**](WorkflowAutomatedTriggersApi.md#merge_many_workflow_automated_triggers) | **PATCH** /workflowAutomatedTriggers/merge | Merge Many workflowAutomatedTriggers
[**restore_many_workflow_automated_triggers**](WorkflowAutomatedTriggersApi.md#restore_many_workflow_automated_triggers) | **PATCH** /restore/workflowAutomatedTriggers | Restore Many workflowAutomatedTriggers
[**restore_one_workflow_automated_trigger**](WorkflowAutomatedTriggersApi.md#restore_one_workflow_automated_trigger) | **PATCH** /restore/workflowAutomatedTriggers/{id} | Restore One workflowAutomatedTrigger
[**update_many_workflow_automated_triggers**](WorkflowAutomatedTriggersApi.md#update_many_workflow_automated_triggers) | **PATCH** /workflowAutomatedTriggers | Update Many workflowAutomatedTriggers
[**update_one_workflow_automated_trigger**](WorkflowAutomatedTriggersApi.md#update_one_workflow_automated_trigger) | **PATCH** /workflowAutomatedTriggers/{id} | Update One workflowAutomatedTrigger


# **create_many_workflow_automated_triggers**
> CreateManyWorkflowAutomatedTriggers201Response create_many_workflow_automated_triggers(workflow_automated_trigger, depth=depth, upsert=upsert)

Create Many workflowAutomatedTriggers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.create_many_workflow_automated_triggers201_response import CreateManyWorkflowAutomatedTriggers201Response
from twentycrm_client.models.workflow_automated_trigger import WorkflowAutomatedTrigger
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    workflow_automated_trigger = [twentycrm_client.WorkflowAutomatedTrigger()] # List[WorkflowAutomatedTrigger] | 
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create Many workflowAutomatedTriggers
        api_response = api_instance.create_many_workflow_automated_triggers(workflow_automated_trigger, depth=depth, upsert=upsert)
        print("The response of WorkflowAutomatedTriggersApi->create_many_workflow_automated_triggers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->create_many_workflow_automated_triggers: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workflow_automated_trigger** | [**List[WorkflowAutomatedTrigger]**](WorkflowAutomatedTrigger.md)|  | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateManyWorkflowAutomatedTriggers201Response**](CreateManyWorkflowAutomatedTriggers201Response.md)

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

# **create_one_workflow_automated_trigger**
> CreateOneWorkflowAutomatedTrigger201Response create_one_workflow_automated_trigger(workflow_automated_trigger, depth=depth, upsert=upsert)

Create One workflowAutomatedTrigger

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.create_one_workflow_automated_trigger201_response import CreateOneWorkflowAutomatedTrigger201Response
from twentycrm_client.models.workflow_automated_trigger import WorkflowAutomatedTrigger
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    workflow_automated_trigger = twentycrm_client.WorkflowAutomatedTrigger() # WorkflowAutomatedTrigger | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create One workflowAutomatedTrigger
        api_response = api_instance.create_one_workflow_automated_trigger(workflow_automated_trigger, depth=depth, upsert=upsert)
        print("The response of WorkflowAutomatedTriggersApi->create_one_workflow_automated_trigger:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->create_one_workflow_automated_trigger: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workflow_automated_trigger** | [**WorkflowAutomatedTrigger**](WorkflowAutomatedTrigger.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateOneWorkflowAutomatedTrigger201Response**](CreateOneWorkflowAutomatedTrigger201Response.md)

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

# **delete_many_workflow_automated_triggers**
> DeleteManyWorkflowAutomatedTriggers200Response delete_many_workflow_automated_triggers(filter=filter, soft_delete=soft_delete)

Delete Many workflowAutomatedTriggers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_many_workflow_automated_triggers200_response import DeleteManyWorkflowAutomatedTriggers200Response
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete Many workflowAutomatedTriggers
        api_response = api_instance.delete_many_workflow_automated_triggers(filter=filter, soft_delete=soft_delete)
        print("The response of WorkflowAutomatedTriggersApi->delete_many_workflow_automated_triggers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->delete_many_workflow_automated_triggers: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteManyWorkflowAutomatedTriggers200Response**](DeleteManyWorkflowAutomatedTriggers200Response.md)

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

# **delete_one_workflow_automated_trigger**
> DeleteOneWorkflowAutomatedTrigger200Response delete_one_workflow_automated_trigger(id, soft_delete=soft_delete)

Delete One workflowAutomatedTrigger

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_one_workflow_automated_trigger200_response import DeleteOneWorkflowAutomatedTrigger200Response
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete One workflowAutomatedTrigger
        api_response = api_instance.delete_one_workflow_automated_trigger(id, soft_delete=soft_delete)
        print("The response of WorkflowAutomatedTriggersApi->delete_one_workflow_automated_trigger:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->delete_one_workflow_automated_trigger: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteOneWorkflowAutomatedTrigger200Response**](DeleteOneWorkflowAutomatedTrigger200Response.md)

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

# **find_many_workflow_automated_triggers**
> FindManyWorkflowAutomatedTriggers200Response find_many_workflow_automated_triggers(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)

Find Many workflowAutomatedTriggers

**order_by**, **filter**, **limit**, **depth**, **starting_after** or **ending_before** can be provided to request your **workflowAutomatedTriggers**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_many_workflow_automated_triggers200_response import FindManyWorkflowAutomatedTriggers200Response
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    starting_after = 'starting_after_example' # str | Returns objects starting after a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)
    ending_before = 'ending_before_example' # str | Returns objects ending before a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)

    try:
        # Find Many workflowAutomatedTriggers
        api_response = api_instance.find_many_workflow_automated_triggers(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)
        print("The response of WorkflowAutomatedTriggersApi->find_many_workflow_automated_triggers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->find_many_workflow_automated_triggers: %s\n" % e)
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

[**FindManyWorkflowAutomatedTriggers200Response**](FindManyWorkflowAutomatedTriggers200Response.md)

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

# **find_one_workflow_automated_trigger**
> FindOneWorkflowAutomatedTrigger200Response find_one_workflow_automated_trigger(id, depth=depth)

Find One workflowAutomatedTrigger

**depth** can be provided to request your **workflowAutomatedTrigger**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_one_workflow_automated_trigger200_response import FindOneWorkflowAutomatedTrigger200Response
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find One workflowAutomatedTrigger
        api_response = api_instance.find_one_workflow_automated_trigger(id, depth=depth)
        print("The response of WorkflowAutomatedTriggersApi->find_one_workflow_automated_trigger:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->find_one_workflow_automated_trigger: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindOneWorkflowAutomatedTrigger200Response**](FindOneWorkflowAutomatedTrigger200Response.md)

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

# **find_workflow_automated_trigger_duplicates**
> FindWorkflowAutomatedTriggerDuplicates200Response find_workflow_automated_trigger_duplicates(find_workflow_automated_trigger_duplicates_request, depth=depth)

Find workflowAutomatedTrigger Duplicates

**depth** can be provided to request your **workflowAutomatedTrigger**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_workflow_automated_trigger_duplicates200_response import FindWorkflowAutomatedTriggerDuplicates200Response
from twentycrm_client.models.find_workflow_automated_trigger_duplicates_request import FindWorkflowAutomatedTriggerDuplicatesRequest
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    find_workflow_automated_trigger_duplicates_request = twentycrm_client.FindWorkflowAutomatedTriggerDuplicatesRequest() # FindWorkflowAutomatedTriggerDuplicatesRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find workflowAutomatedTrigger Duplicates
        api_response = api_instance.find_workflow_automated_trigger_duplicates(find_workflow_automated_trigger_duplicates_request, depth=depth)
        print("The response of WorkflowAutomatedTriggersApi->find_workflow_automated_trigger_duplicates:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->find_workflow_automated_trigger_duplicates: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **find_workflow_automated_trigger_duplicates_request** | [**FindWorkflowAutomatedTriggerDuplicatesRequest**](FindWorkflowAutomatedTriggerDuplicatesRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindWorkflowAutomatedTriggerDuplicates200Response**](FindWorkflowAutomatedTriggerDuplicates200Response.md)

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

# **group_by_workflow_automated_triggers**
> GroupByWorkflowAutomatedTriggers200Response group_by_workflow_automated_triggers(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)

Group By workflowAutomatedTriggers

Groups **workflowAutomatedTriggers** by specified fields and optionally computes aggregate values for each group.

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.group_by_workflow_automated_triggers200_response import GroupByWorkflowAutomatedTriggers200Response
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    group_by = '[{\"updatedAt\": true}]' # str | Array of fields to group by. Each element can specify a field and optionally a subfield or granularity for date fields.
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    view_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | View ID to apply filters from. (optional)
    aggregate = '[\"countNotEmptyId\"]' # str | Array of aggregate operations to compute for each group. (optional)
    include_records_sample = False # bool | If true, includes a sample of records for each group in the response. (optional) (default to False)
    order_by_for_records = 'createdAt' # str | Order by clause for records within each group. Only applicable when include_records_sample is true. (optional)

    try:
        # Group By workflowAutomatedTriggers
        api_response = api_instance.group_by_workflow_automated_triggers(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)
        print("The response of WorkflowAutomatedTriggersApi->group_by_workflow_automated_triggers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->group_by_workflow_automated_triggers: %s\n" % e)
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

[**GroupByWorkflowAutomatedTriggers200Response**](GroupByWorkflowAutomatedTriggers200Response.md)

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

# **merge_many_workflow_automated_triggers**
> MergeManyWorkflowAutomatedTriggers200Response merge_many_workflow_automated_triggers(merge_many_workflow_automated_triggers_request, depth=depth)

Merge Many workflowAutomatedTriggers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.merge_many_workflow_automated_triggers200_response import MergeManyWorkflowAutomatedTriggers200Response
from twentycrm_client.models.merge_many_workflow_automated_triggers_request import MergeManyWorkflowAutomatedTriggersRequest
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    merge_many_workflow_automated_triggers_request = twentycrm_client.MergeManyWorkflowAutomatedTriggersRequest() # MergeManyWorkflowAutomatedTriggersRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Merge Many workflowAutomatedTriggers
        api_response = api_instance.merge_many_workflow_automated_triggers(merge_many_workflow_automated_triggers_request, depth=depth)
        print("The response of WorkflowAutomatedTriggersApi->merge_many_workflow_automated_triggers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->merge_many_workflow_automated_triggers: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merge_many_workflow_automated_triggers_request** | [**MergeManyWorkflowAutomatedTriggersRequest**](MergeManyWorkflowAutomatedTriggersRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**MergeManyWorkflowAutomatedTriggers200Response**](MergeManyWorkflowAutomatedTriggers200Response.md)

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

# **restore_many_workflow_automated_triggers**
> RestoreManyWorkflowAutomatedTriggers200Response restore_many_workflow_automated_triggers(filter=filter, depth=depth)

Restore Many workflowAutomatedTriggers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_many_workflow_automated_triggers200_response import RestoreManyWorkflowAutomatedTriggers200Response
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore Many workflowAutomatedTriggers
        api_response = api_instance.restore_many_workflow_automated_triggers(filter=filter, depth=depth)
        print("The response of WorkflowAutomatedTriggersApi->restore_many_workflow_automated_triggers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->restore_many_workflow_automated_triggers: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreManyWorkflowAutomatedTriggers200Response**](RestoreManyWorkflowAutomatedTriggers200Response.md)

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

# **restore_one_workflow_automated_trigger**
> RestoreOneWorkflowAutomatedTrigger200Response restore_one_workflow_automated_trigger(id, depth=depth)

Restore One workflowAutomatedTrigger

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_one_workflow_automated_trigger200_response import RestoreOneWorkflowAutomatedTrigger200Response
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore One workflowAutomatedTrigger
        api_response = api_instance.restore_one_workflow_automated_trigger(id, depth=depth)
        print("The response of WorkflowAutomatedTriggersApi->restore_one_workflow_automated_trigger:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->restore_one_workflow_automated_trigger: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreOneWorkflowAutomatedTrigger200Response**](RestoreOneWorkflowAutomatedTrigger200Response.md)

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

# **update_many_workflow_automated_triggers**
> UpdateManyWorkflowAutomatedTriggers200Response update_many_workflow_automated_triggers(workflow_automated_trigger_for_update, depth=depth, filter=filter)

Update Many workflowAutomatedTriggers

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.update_many_workflow_automated_triggers200_response import UpdateManyWorkflowAutomatedTriggers200Response
from twentycrm_client.models.workflow_automated_trigger_for_update import WorkflowAutomatedTriggerForUpdate
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    workflow_automated_trigger_for_update = twentycrm_client.WorkflowAutomatedTriggerForUpdate() # WorkflowAutomatedTriggerForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)

    try:
        # Update Many workflowAutomatedTriggers
        api_response = api_instance.update_many_workflow_automated_triggers(workflow_automated_trigger_for_update, depth=depth, filter=filter)
        print("The response of WorkflowAutomatedTriggersApi->update_many_workflow_automated_triggers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->update_many_workflow_automated_triggers: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workflow_automated_trigger_for_update** | [**WorkflowAutomatedTriggerForUpdate**](WorkflowAutomatedTriggerForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 

### Return type

[**UpdateManyWorkflowAutomatedTriggers200Response**](UpdateManyWorkflowAutomatedTriggers200Response.md)

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

# **update_one_workflow_automated_trigger**
> UpdateOneWorkflowAutomatedTrigger200Response update_one_workflow_automated_trigger(id, workflow_automated_trigger_for_update, depth=depth)

Update One workflowAutomatedTrigger

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.update_one_workflow_automated_trigger200_response import UpdateOneWorkflowAutomatedTrigger200Response
from twentycrm_client.models.workflow_automated_trigger_for_update import WorkflowAutomatedTriggerForUpdate
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
    api_instance = twentycrm_client.WorkflowAutomatedTriggersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    workflow_automated_trigger_for_update = twentycrm_client.WorkflowAutomatedTriggerForUpdate() # WorkflowAutomatedTriggerForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Update One workflowAutomatedTrigger
        api_response = api_instance.update_one_workflow_automated_trigger(id, workflow_automated_trigger_for_update, depth=depth)
        print("The response of WorkflowAutomatedTriggersApi->update_one_workflow_automated_trigger:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WorkflowAutomatedTriggersApi->update_one_workflow_automated_trigger: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **workflow_automated_trigger_for_update** | [**WorkflowAutomatedTriggerForUpdate**](WorkflowAutomatedTriggerForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**UpdateOneWorkflowAutomatedTrigger200Response**](UpdateOneWorkflowAutomatedTrigger200Response.md)

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

