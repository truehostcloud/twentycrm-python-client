# twentycrm_client.CalendarChannelEventAssociationsApi

All URIs are relative to *https://crm.example.com/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_many_calendar_channel_event_associations**](CalendarChannelEventAssociationsApi.md#create_many_calendar_channel_event_associations) | **POST** /batch/calendarChannelEventAssociations | Create Many calendarChannelEventAssociations
[**create_one_calendar_channel_event_association**](CalendarChannelEventAssociationsApi.md#create_one_calendar_channel_event_association) | **POST** /calendarChannelEventAssociations | Create One calendarChannelEventAssociation
[**delete_many_calendar_channel_event_associations**](CalendarChannelEventAssociationsApi.md#delete_many_calendar_channel_event_associations) | **DELETE** /calendarChannelEventAssociations | Delete Many calendarChannelEventAssociations
[**delete_one_calendar_channel_event_association**](CalendarChannelEventAssociationsApi.md#delete_one_calendar_channel_event_association) | **DELETE** /calendarChannelEventAssociations/{id} | Delete One calendarChannelEventAssociation
[**find_calendar_channel_event_association_duplicates**](CalendarChannelEventAssociationsApi.md#find_calendar_channel_event_association_duplicates) | **POST** /calendarChannelEventAssociations/duplicates | Find calendarChannelEventAssociation Duplicates
[**find_many_calendar_channel_event_associations**](CalendarChannelEventAssociationsApi.md#find_many_calendar_channel_event_associations) | **GET** /calendarChannelEventAssociations | Find Many calendarChannelEventAssociations
[**find_one_calendar_channel_event_association**](CalendarChannelEventAssociationsApi.md#find_one_calendar_channel_event_association) | **GET** /calendarChannelEventAssociations/{id} | Find One calendarChannelEventAssociation
[**group_by_calendar_channel_event_associations**](CalendarChannelEventAssociationsApi.md#group_by_calendar_channel_event_associations) | **GET** /calendarChannelEventAssociations/groupBy | Group By calendarChannelEventAssociations
[**merge_many_calendar_channel_event_associations**](CalendarChannelEventAssociationsApi.md#merge_many_calendar_channel_event_associations) | **PATCH** /calendarChannelEventAssociations/merge | Merge Many calendarChannelEventAssociations
[**restore_many_calendar_channel_event_associations**](CalendarChannelEventAssociationsApi.md#restore_many_calendar_channel_event_associations) | **PATCH** /restore/calendarChannelEventAssociations | Restore Many calendarChannelEventAssociations
[**restore_one_calendar_channel_event_association**](CalendarChannelEventAssociationsApi.md#restore_one_calendar_channel_event_association) | **PATCH** /restore/calendarChannelEventAssociations/{id} | Restore One calendarChannelEventAssociation
[**update_many_calendar_channel_event_associations**](CalendarChannelEventAssociationsApi.md#update_many_calendar_channel_event_associations) | **PATCH** /calendarChannelEventAssociations | Update Many calendarChannelEventAssociations
[**update_one_calendar_channel_event_association**](CalendarChannelEventAssociationsApi.md#update_one_calendar_channel_event_association) | **PATCH** /calendarChannelEventAssociations/{id} | Update One calendarChannelEventAssociation


# **create_many_calendar_channel_event_associations**
> CreateManyCalendarChannelEventAssociations201Response create_many_calendar_channel_event_associations(calendar_channel_event_association, depth=depth, upsert=upsert)

Create Many calendarChannelEventAssociations

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.calendar_channel_event_association import CalendarChannelEventAssociation
from twentycrm_client.models.create_many_calendar_channel_event_associations201_response import CreateManyCalendarChannelEventAssociations201Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    calendar_channel_event_association = [twentycrm_client.CalendarChannelEventAssociation()] # List[CalendarChannelEventAssociation] | 
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create Many calendarChannelEventAssociations
        api_response = api_instance.create_many_calendar_channel_event_associations(calendar_channel_event_association, depth=depth, upsert=upsert)
        print("The response of CalendarChannelEventAssociationsApi->create_many_calendar_channel_event_associations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->create_many_calendar_channel_event_associations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_channel_event_association** | [**List[CalendarChannelEventAssociation]**](CalendarChannelEventAssociation.md)|  | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateManyCalendarChannelEventAssociations201Response**](CreateManyCalendarChannelEventAssociations201Response.md)

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

# **create_one_calendar_channel_event_association**
> CreateOneCalendarChannelEventAssociation201Response create_one_calendar_channel_event_association(calendar_channel_event_association, depth=depth, upsert=upsert)

Create One calendarChannelEventAssociation

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.calendar_channel_event_association import CalendarChannelEventAssociation
from twentycrm_client.models.create_one_calendar_channel_event_association201_response import CreateOneCalendarChannelEventAssociation201Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    calendar_channel_event_association = twentycrm_client.CalendarChannelEventAssociation() # CalendarChannelEventAssociation | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create One calendarChannelEventAssociation
        api_response = api_instance.create_one_calendar_channel_event_association(calendar_channel_event_association, depth=depth, upsert=upsert)
        print("The response of CalendarChannelEventAssociationsApi->create_one_calendar_channel_event_association:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->create_one_calendar_channel_event_association: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_channel_event_association** | [**CalendarChannelEventAssociation**](CalendarChannelEventAssociation.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateOneCalendarChannelEventAssociation201Response**](CreateOneCalendarChannelEventAssociation201Response.md)

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

# **delete_many_calendar_channel_event_associations**
> DeleteManyCalendarChannelEventAssociations200Response delete_many_calendar_channel_event_associations(filter=filter, soft_delete=soft_delete)

Delete Many calendarChannelEventAssociations

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_many_calendar_channel_event_associations200_response import DeleteManyCalendarChannelEventAssociations200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete Many calendarChannelEventAssociations
        api_response = api_instance.delete_many_calendar_channel_event_associations(filter=filter, soft_delete=soft_delete)
        print("The response of CalendarChannelEventAssociationsApi->delete_many_calendar_channel_event_associations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->delete_many_calendar_channel_event_associations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteManyCalendarChannelEventAssociations200Response**](DeleteManyCalendarChannelEventAssociations200Response.md)

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

# **delete_one_calendar_channel_event_association**
> DeleteOneCalendarChannelEventAssociation200Response delete_one_calendar_channel_event_association(id, soft_delete=soft_delete)

Delete One calendarChannelEventAssociation

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_one_calendar_channel_event_association200_response import DeleteOneCalendarChannelEventAssociation200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete One calendarChannelEventAssociation
        api_response = api_instance.delete_one_calendar_channel_event_association(id, soft_delete=soft_delete)
        print("The response of CalendarChannelEventAssociationsApi->delete_one_calendar_channel_event_association:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->delete_one_calendar_channel_event_association: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteOneCalendarChannelEventAssociation200Response**](DeleteOneCalendarChannelEventAssociation200Response.md)

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

# **find_calendar_channel_event_association_duplicates**
> FindCalendarChannelEventAssociationDuplicates200Response find_calendar_channel_event_association_duplicates(find_calendar_channel_event_association_duplicates_request, depth=depth)

Find calendarChannelEventAssociation Duplicates

**depth** can be provided to request your **calendarChannelEventAssociation**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_calendar_channel_event_association_duplicates200_response import FindCalendarChannelEventAssociationDuplicates200Response
from twentycrm_client.models.find_calendar_channel_event_association_duplicates_request import FindCalendarChannelEventAssociationDuplicatesRequest
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    find_calendar_channel_event_association_duplicates_request = twentycrm_client.FindCalendarChannelEventAssociationDuplicatesRequest() # FindCalendarChannelEventAssociationDuplicatesRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find calendarChannelEventAssociation Duplicates
        api_response = api_instance.find_calendar_channel_event_association_duplicates(find_calendar_channel_event_association_duplicates_request, depth=depth)
        print("The response of CalendarChannelEventAssociationsApi->find_calendar_channel_event_association_duplicates:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->find_calendar_channel_event_association_duplicates: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **find_calendar_channel_event_association_duplicates_request** | [**FindCalendarChannelEventAssociationDuplicatesRequest**](FindCalendarChannelEventAssociationDuplicatesRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindCalendarChannelEventAssociationDuplicates200Response**](FindCalendarChannelEventAssociationDuplicates200Response.md)

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

# **find_many_calendar_channel_event_associations**
> FindManyCalendarChannelEventAssociations200Response find_many_calendar_channel_event_associations(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)

Find Many calendarChannelEventAssociations

**order_by**, **filter**, **limit**, **depth**, **starting_after** or **ending_before** can be provided to request your **calendarChannelEventAssociations**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_many_calendar_channel_event_associations200_response import FindManyCalendarChannelEventAssociations200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    starting_after = 'starting_after_example' # str | Returns objects starting after a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)
    ending_before = 'ending_before_example' # str | Returns objects ending before a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)

    try:
        # Find Many calendarChannelEventAssociations
        api_response = api_instance.find_many_calendar_channel_event_associations(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)
        print("The response of CalendarChannelEventAssociationsApi->find_many_calendar_channel_event_associations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->find_many_calendar_channel_event_associations: %s\n" % e)
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

[**FindManyCalendarChannelEventAssociations200Response**](FindManyCalendarChannelEventAssociations200Response.md)

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

# **find_one_calendar_channel_event_association**
> FindOneCalendarChannelEventAssociation200Response find_one_calendar_channel_event_association(id, depth=depth)

Find One calendarChannelEventAssociation

**depth** can be provided to request your **calendarChannelEventAssociation**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_one_calendar_channel_event_association200_response import FindOneCalendarChannelEventAssociation200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find One calendarChannelEventAssociation
        api_response = api_instance.find_one_calendar_channel_event_association(id, depth=depth)
        print("The response of CalendarChannelEventAssociationsApi->find_one_calendar_channel_event_association:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->find_one_calendar_channel_event_association: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindOneCalendarChannelEventAssociation200Response**](FindOneCalendarChannelEventAssociation200Response.md)

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

# **group_by_calendar_channel_event_associations**
> GroupByCalendarChannelEventAssociations200Response group_by_calendar_channel_event_associations(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)

Group By calendarChannelEventAssociations

Groups **calendarChannelEventAssociations** by specified fields and optionally computes aggregate values for each group.

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.group_by_calendar_channel_event_associations200_response import GroupByCalendarChannelEventAssociations200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    group_by = '[{\"updatedAt\": true}]' # str | Array of fields to group by. Each element can specify a field and optionally a subfield or granularity for date fields.
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    view_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | View ID to apply filters from. (optional)
    aggregate = '[\"countNotEmptyId\"]' # str | Array of aggregate operations to compute for each group. (optional)
    include_records_sample = False # bool | If true, includes a sample of records for each group in the response. (optional) (default to False)
    order_by_for_records = 'createdAt' # str | Order by clause for records within each group. Only applicable when include_records_sample is true. (optional)

    try:
        # Group By calendarChannelEventAssociations
        api_response = api_instance.group_by_calendar_channel_event_associations(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)
        print("The response of CalendarChannelEventAssociationsApi->group_by_calendar_channel_event_associations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->group_by_calendar_channel_event_associations: %s\n" % e)
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

[**GroupByCalendarChannelEventAssociations200Response**](GroupByCalendarChannelEventAssociations200Response.md)

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

# **merge_many_calendar_channel_event_associations**
> MergeManyCalendarChannelEventAssociations200Response merge_many_calendar_channel_event_associations(merge_many_calendar_channel_event_associations_request, depth=depth)

Merge Many calendarChannelEventAssociations

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.merge_many_calendar_channel_event_associations200_response import MergeManyCalendarChannelEventAssociations200Response
from twentycrm_client.models.merge_many_calendar_channel_event_associations_request import MergeManyCalendarChannelEventAssociationsRequest
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    merge_many_calendar_channel_event_associations_request = twentycrm_client.MergeManyCalendarChannelEventAssociationsRequest() # MergeManyCalendarChannelEventAssociationsRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Merge Many calendarChannelEventAssociations
        api_response = api_instance.merge_many_calendar_channel_event_associations(merge_many_calendar_channel_event_associations_request, depth=depth)
        print("The response of CalendarChannelEventAssociationsApi->merge_many_calendar_channel_event_associations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->merge_many_calendar_channel_event_associations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merge_many_calendar_channel_event_associations_request** | [**MergeManyCalendarChannelEventAssociationsRequest**](MergeManyCalendarChannelEventAssociationsRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**MergeManyCalendarChannelEventAssociations200Response**](MergeManyCalendarChannelEventAssociations200Response.md)

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

# **restore_many_calendar_channel_event_associations**
> RestoreManyCalendarChannelEventAssociations200Response restore_many_calendar_channel_event_associations(filter=filter, depth=depth)

Restore Many calendarChannelEventAssociations

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_many_calendar_channel_event_associations200_response import RestoreManyCalendarChannelEventAssociations200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore Many calendarChannelEventAssociations
        api_response = api_instance.restore_many_calendar_channel_event_associations(filter=filter, depth=depth)
        print("The response of CalendarChannelEventAssociationsApi->restore_many_calendar_channel_event_associations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->restore_many_calendar_channel_event_associations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreManyCalendarChannelEventAssociations200Response**](RestoreManyCalendarChannelEventAssociations200Response.md)

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

# **restore_one_calendar_channel_event_association**
> RestoreOneCalendarChannelEventAssociation200Response restore_one_calendar_channel_event_association(id, depth=depth)

Restore One calendarChannelEventAssociation

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_one_calendar_channel_event_association200_response import RestoreOneCalendarChannelEventAssociation200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore One calendarChannelEventAssociation
        api_response = api_instance.restore_one_calendar_channel_event_association(id, depth=depth)
        print("The response of CalendarChannelEventAssociationsApi->restore_one_calendar_channel_event_association:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->restore_one_calendar_channel_event_association: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreOneCalendarChannelEventAssociation200Response**](RestoreOneCalendarChannelEventAssociation200Response.md)

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

# **update_many_calendar_channel_event_associations**
> UpdateManyCalendarChannelEventAssociations200Response update_many_calendar_channel_event_associations(calendar_channel_event_association_for_update, depth=depth, filter=filter)

Update Many calendarChannelEventAssociations

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.calendar_channel_event_association_for_update import CalendarChannelEventAssociationForUpdate
from twentycrm_client.models.update_many_calendar_channel_event_associations200_response import UpdateManyCalendarChannelEventAssociations200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    calendar_channel_event_association_for_update = twentycrm_client.CalendarChannelEventAssociationForUpdate() # CalendarChannelEventAssociationForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)

    try:
        # Update Many calendarChannelEventAssociations
        api_response = api_instance.update_many_calendar_channel_event_associations(calendar_channel_event_association_for_update, depth=depth, filter=filter)
        print("The response of CalendarChannelEventAssociationsApi->update_many_calendar_channel_event_associations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->update_many_calendar_channel_event_associations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_channel_event_association_for_update** | [**CalendarChannelEventAssociationForUpdate**](CalendarChannelEventAssociationForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 

### Return type

[**UpdateManyCalendarChannelEventAssociations200Response**](UpdateManyCalendarChannelEventAssociations200Response.md)

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

# **update_one_calendar_channel_event_association**
> UpdateOneCalendarChannelEventAssociation200Response update_one_calendar_channel_event_association(id, calendar_channel_event_association_for_update, depth=depth)

Update One calendarChannelEventAssociation

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.calendar_channel_event_association_for_update import CalendarChannelEventAssociationForUpdate
from twentycrm_client.models.update_one_calendar_channel_event_association200_response import UpdateOneCalendarChannelEventAssociation200Response
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
    api_instance = twentycrm_client.CalendarChannelEventAssociationsApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    calendar_channel_event_association_for_update = twentycrm_client.CalendarChannelEventAssociationForUpdate() # CalendarChannelEventAssociationForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Update One calendarChannelEventAssociation
        api_response = api_instance.update_one_calendar_channel_event_association(id, calendar_channel_event_association_for_update, depth=depth)
        print("The response of CalendarChannelEventAssociationsApi->update_one_calendar_channel_event_association:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarChannelEventAssociationsApi->update_one_calendar_channel_event_association: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **calendar_channel_event_association_for_update** | [**CalendarChannelEventAssociationForUpdate**](CalendarChannelEventAssociationForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**UpdateOneCalendarChannelEventAssociation200Response**](UpdateOneCalendarChannelEventAssociation200Response.md)

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

