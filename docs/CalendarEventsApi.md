# twentycrm_client.CalendarEventsApi

All URIs are relative to *https://crm.example.com/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_many_calendar_events**](CalendarEventsApi.md#create_many_calendar_events) | **POST** /batch/calendarEvents | Create Many calendarEvents
[**create_one_calendar_event**](CalendarEventsApi.md#create_one_calendar_event) | **POST** /calendarEvents | Create One calendarEvent
[**delete_many_calendar_events**](CalendarEventsApi.md#delete_many_calendar_events) | **DELETE** /calendarEvents | Delete Many calendarEvents
[**delete_one_calendar_event**](CalendarEventsApi.md#delete_one_calendar_event) | **DELETE** /calendarEvents/{id} | Delete One calendarEvent
[**find_calendar_event_duplicates**](CalendarEventsApi.md#find_calendar_event_duplicates) | **POST** /calendarEvents/duplicates | Find calendarEvent Duplicates
[**find_many_calendar_events**](CalendarEventsApi.md#find_many_calendar_events) | **GET** /calendarEvents | Find Many calendarEvents
[**find_one_calendar_event**](CalendarEventsApi.md#find_one_calendar_event) | **GET** /calendarEvents/{id} | Find One calendarEvent
[**group_by_calendar_events**](CalendarEventsApi.md#group_by_calendar_events) | **GET** /calendarEvents/groupBy | Group By calendarEvents
[**merge_many_calendar_events**](CalendarEventsApi.md#merge_many_calendar_events) | **PATCH** /calendarEvents/merge | Merge Many calendarEvents
[**restore_many_calendar_events**](CalendarEventsApi.md#restore_many_calendar_events) | **PATCH** /restore/calendarEvents | Restore Many calendarEvents
[**restore_one_calendar_event**](CalendarEventsApi.md#restore_one_calendar_event) | **PATCH** /restore/calendarEvents/{id} | Restore One calendarEvent
[**update_many_calendar_events**](CalendarEventsApi.md#update_many_calendar_events) | **PATCH** /calendarEvents | Update Many calendarEvents
[**update_one_calendar_event**](CalendarEventsApi.md#update_one_calendar_event) | **PATCH** /calendarEvents/{id} | Update One calendarEvent


# **create_many_calendar_events**
> CreateManyCalendarEvents201Response create_many_calendar_events(calendar_event, depth=depth, upsert=upsert)

Create Many calendarEvents

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.calendar_event import CalendarEvent
from twentycrm_client.models.create_many_calendar_events201_response import CreateManyCalendarEvents201Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    calendar_event = [twentycrm_client.CalendarEvent()] # List[CalendarEvent] | 
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create Many calendarEvents
        api_response = api_instance.create_many_calendar_events(calendar_event, depth=depth, upsert=upsert)
        print("The response of CalendarEventsApi->create_many_calendar_events:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->create_many_calendar_events: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_event** | [**List[CalendarEvent]**](CalendarEvent.md)|  | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateManyCalendarEvents201Response**](CreateManyCalendarEvents201Response.md)

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

# **create_one_calendar_event**
> CreateOneCalendarEvent201Response create_one_calendar_event(calendar_event, depth=depth, upsert=upsert)

Create One calendarEvent

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.calendar_event import CalendarEvent
from twentycrm_client.models.create_one_calendar_event201_response import CreateOneCalendarEvent201Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    calendar_event = twentycrm_client.CalendarEvent() # CalendarEvent | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create One calendarEvent
        api_response = api_instance.create_one_calendar_event(calendar_event, depth=depth, upsert=upsert)
        print("The response of CalendarEventsApi->create_one_calendar_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->create_one_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_event** | [**CalendarEvent**](CalendarEvent.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateOneCalendarEvent201Response**](CreateOneCalendarEvent201Response.md)

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

# **delete_many_calendar_events**
> DeleteManyCalendarEvents200Response delete_many_calendar_events(filter=filter, soft_delete=soft_delete)

Delete Many calendarEvents

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_many_calendar_events200_response import DeleteManyCalendarEvents200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete Many calendarEvents
        api_response = api_instance.delete_many_calendar_events(filter=filter, soft_delete=soft_delete)
        print("The response of CalendarEventsApi->delete_many_calendar_events:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->delete_many_calendar_events: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteManyCalendarEvents200Response**](DeleteManyCalendarEvents200Response.md)

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

# **delete_one_calendar_event**
> DeleteOneCalendarEvent200Response delete_one_calendar_event(id, soft_delete=soft_delete)

Delete One calendarEvent

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_one_calendar_event200_response import DeleteOneCalendarEvent200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete One calendarEvent
        api_response = api_instance.delete_one_calendar_event(id, soft_delete=soft_delete)
        print("The response of CalendarEventsApi->delete_one_calendar_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->delete_one_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteOneCalendarEvent200Response**](DeleteOneCalendarEvent200Response.md)

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

# **find_calendar_event_duplicates**
> FindCalendarEventDuplicates200Response find_calendar_event_duplicates(find_calendar_event_duplicates_request, depth=depth)

Find calendarEvent Duplicates

**depth** can be provided to request your **calendarEvent**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_calendar_event_duplicates200_response import FindCalendarEventDuplicates200Response
from twentycrm_client.models.find_calendar_event_duplicates_request import FindCalendarEventDuplicatesRequest
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    find_calendar_event_duplicates_request = twentycrm_client.FindCalendarEventDuplicatesRequest() # FindCalendarEventDuplicatesRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find calendarEvent Duplicates
        api_response = api_instance.find_calendar_event_duplicates(find_calendar_event_duplicates_request, depth=depth)
        print("The response of CalendarEventsApi->find_calendar_event_duplicates:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->find_calendar_event_duplicates: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **find_calendar_event_duplicates_request** | [**FindCalendarEventDuplicatesRequest**](FindCalendarEventDuplicatesRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindCalendarEventDuplicates200Response**](FindCalendarEventDuplicates200Response.md)

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

# **find_many_calendar_events**
> FindManyCalendarEvents200Response find_many_calendar_events(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)

Find Many calendarEvents

**order_by**, **filter**, **limit**, **depth**, **starting_after** or **ending_before** can be provided to request your **calendarEvents**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_many_calendar_events200_response import FindManyCalendarEvents200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    starting_after = 'starting_after_example' # str | Returns objects starting after a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)
    ending_before = 'ending_before_example' # str | Returns objects ending before a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)

    try:
        # Find Many calendarEvents
        api_response = api_instance.find_many_calendar_events(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)
        print("The response of CalendarEventsApi->find_many_calendar_events:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->find_many_calendar_events: %s\n" % e)
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

[**FindManyCalendarEvents200Response**](FindManyCalendarEvents200Response.md)

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

# **find_one_calendar_event**
> FindOneCalendarEvent200Response find_one_calendar_event(id, depth=depth)

Find One calendarEvent

**depth** can be provided to request your **calendarEvent**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_one_calendar_event200_response import FindOneCalendarEvent200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find One calendarEvent
        api_response = api_instance.find_one_calendar_event(id, depth=depth)
        print("The response of CalendarEventsApi->find_one_calendar_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->find_one_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindOneCalendarEvent200Response**](FindOneCalendarEvent200Response.md)

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

# **group_by_calendar_events**
> GroupByCalendarEvents200Response group_by_calendar_events(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)

Group By calendarEvents

Groups **calendarEvents** by specified fields and optionally computes aggregate values for each group.

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.group_by_calendar_events200_response import GroupByCalendarEvents200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    group_by = '[{\"updatedAt\": true}]' # str | Array of fields to group by. Each element can specify a field and optionally a subfield or granularity for date fields.
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    view_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | View ID to apply filters from. (optional)
    aggregate = '[\"countNotEmptyId\"]' # str | Array of aggregate operations to compute for each group. (optional)
    include_records_sample = False # bool | If true, includes a sample of records for each group in the response. (optional) (default to False)
    order_by_for_records = 'createdAt' # str | Order by clause for records within each group. Only applicable when include_records_sample is true. (optional)

    try:
        # Group By calendarEvents
        api_response = api_instance.group_by_calendar_events(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)
        print("The response of CalendarEventsApi->group_by_calendar_events:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->group_by_calendar_events: %s\n" % e)
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

[**GroupByCalendarEvents200Response**](GroupByCalendarEvents200Response.md)

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

# **merge_many_calendar_events**
> MergeManyCalendarEvents200Response merge_many_calendar_events(merge_many_calendar_events_request, depth=depth)

Merge Many calendarEvents

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.merge_many_calendar_events200_response import MergeManyCalendarEvents200Response
from twentycrm_client.models.merge_many_calendar_events_request import MergeManyCalendarEventsRequest
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    merge_many_calendar_events_request = twentycrm_client.MergeManyCalendarEventsRequest() # MergeManyCalendarEventsRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Merge Many calendarEvents
        api_response = api_instance.merge_many_calendar_events(merge_many_calendar_events_request, depth=depth)
        print("The response of CalendarEventsApi->merge_many_calendar_events:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->merge_many_calendar_events: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merge_many_calendar_events_request** | [**MergeManyCalendarEventsRequest**](MergeManyCalendarEventsRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**MergeManyCalendarEvents200Response**](MergeManyCalendarEvents200Response.md)

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

# **restore_many_calendar_events**
> RestoreManyCalendarEvents200Response restore_many_calendar_events(filter=filter, depth=depth)

Restore Many calendarEvents

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_many_calendar_events200_response import RestoreManyCalendarEvents200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore Many calendarEvents
        api_response = api_instance.restore_many_calendar_events(filter=filter, depth=depth)
        print("The response of CalendarEventsApi->restore_many_calendar_events:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->restore_many_calendar_events: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreManyCalendarEvents200Response**](RestoreManyCalendarEvents200Response.md)

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

# **restore_one_calendar_event**
> RestoreOneCalendarEvent200Response restore_one_calendar_event(id, depth=depth)

Restore One calendarEvent

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_one_calendar_event200_response import RestoreOneCalendarEvent200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore One calendarEvent
        api_response = api_instance.restore_one_calendar_event(id, depth=depth)
        print("The response of CalendarEventsApi->restore_one_calendar_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->restore_one_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreOneCalendarEvent200Response**](RestoreOneCalendarEvent200Response.md)

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

# **update_many_calendar_events**
> UpdateManyCalendarEvents200Response update_many_calendar_events(calendar_event_for_update, depth=depth, filter=filter)

Update Many calendarEvents

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.calendar_event_for_update import CalendarEventForUpdate
from twentycrm_client.models.update_many_calendar_events200_response import UpdateManyCalendarEvents200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    calendar_event_for_update = twentycrm_client.CalendarEventForUpdate() # CalendarEventForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)

    try:
        # Update Many calendarEvents
        api_response = api_instance.update_many_calendar_events(calendar_event_for_update, depth=depth, filter=filter)
        print("The response of CalendarEventsApi->update_many_calendar_events:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->update_many_calendar_events: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_event_for_update** | [**CalendarEventForUpdate**](CalendarEventForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 

### Return type

[**UpdateManyCalendarEvents200Response**](UpdateManyCalendarEvents200Response.md)

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

# **update_one_calendar_event**
> UpdateOneCalendarEvent200Response update_one_calendar_event(id, calendar_event_for_update, depth=depth)

Update One calendarEvent

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.calendar_event_for_update import CalendarEventForUpdate
from twentycrm_client.models.update_one_calendar_event200_response import UpdateOneCalendarEvent200Response
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
    api_instance = twentycrm_client.CalendarEventsApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    calendar_event_for_update = twentycrm_client.CalendarEventForUpdate() # CalendarEventForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Update One calendarEvent
        api_response = api_instance.update_one_calendar_event(id, calendar_event_for_update, depth=depth)
        print("The response of CalendarEventsApi->update_one_calendar_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarEventsApi->update_one_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **calendar_event_for_update** | [**CalendarEventForUpdate**](CalendarEventForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**UpdateOneCalendarEvent200Response**](UpdateOneCalendarEvent200Response.md)

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

