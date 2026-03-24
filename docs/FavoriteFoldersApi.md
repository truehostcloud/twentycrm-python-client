# twentycrm_client.FavoriteFoldersApi

All URIs are relative to *https://crm.example.com/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_many_favorite_folders**](FavoriteFoldersApi.md#create_many_favorite_folders) | **POST** /batch/favoriteFolders | Create Many favoriteFolders
[**create_one_favorite_folder**](FavoriteFoldersApi.md#create_one_favorite_folder) | **POST** /favoriteFolders | Create One favoriteFolder
[**delete_many_favorite_folders**](FavoriteFoldersApi.md#delete_many_favorite_folders) | **DELETE** /favoriteFolders | Delete Many favoriteFolders
[**delete_one_favorite_folder**](FavoriteFoldersApi.md#delete_one_favorite_folder) | **DELETE** /favoriteFolders/{id} | Delete One favoriteFolder
[**find_favorite_folder_duplicates**](FavoriteFoldersApi.md#find_favorite_folder_duplicates) | **POST** /favoriteFolders/duplicates | Find favoriteFolder Duplicates
[**find_many_favorite_folders**](FavoriteFoldersApi.md#find_many_favorite_folders) | **GET** /favoriteFolders | Find Many favoriteFolders
[**find_one_favorite_folder**](FavoriteFoldersApi.md#find_one_favorite_folder) | **GET** /favoriteFolders/{id} | Find One favoriteFolder
[**group_by_favorite_folders**](FavoriteFoldersApi.md#group_by_favorite_folders) | **GET** /favoriteFolders/groupBy | Group By favoriteFolders
[**merge_many_favorite_folders**](FavoriteFoldersApi.md#merge_many_favorite_folders) | **PATCH** /favoriteFolders/merge | Merge Many favoriteFolders
[**restore_many_favorite_folders**](FavoriteFoldersApi.md#restore_many_favorite_folders) | **PATCH** /restore/favoriteFolders | Restore Many favoriteFolders
[**restore_one_favorite_folder**](FavoriteFoldersApi.md#restore_one_favorite_folder) | **PATCH** /restore/favoriteFolders/{id} | Restore One favoriteFolder
[**update_many_favorite_folders**](FavoriteFoldersApi.md#update_many_favorite_folders) | **PATCH** /favoriteFolders | Update Many favoriteFolders
[**update_one_favorite_folder**](FavoriteFoldersApi.md#update_one_favorite_folder) | **PATCH** /favoriteFolders/{id} | Update One favoriteFolder


# **create_many_favorite_folders**
> CreateManyFavoriteFolders201Response create_many_favorite_folders(favorite_folder, depth=depth, upsert=upsert)

Create Many favoriteFolders

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.create_many_favorite_folders201_response import CreateManyFavoriteFolders201Response
from twentycrm_client.models.favorite_folder import FavoriteFolder
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    favorite_folder = [twentycrm_client.FavoriteFolder()] # List[FavoriteFolder] | 
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create Many favoriteFolders
        api_response = api_instance.create_many_favorite_folders(favorite_folder, depth=depth, upsert=upsert)
        print("The response of FavoriteFoldersApi->create_many_favorite_folders:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->create_many_favorite_folders: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **favorite_folder** | [**List[FavoriteFolder]**](FavoriteFolder.md)|  | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateManyFavoriteFolders201Response**](CreateManyFavoriteFolders201Response.md)

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

# **create_one_favorite_folder**
> CreateOneFavoriteFolder201Response create_one_favorite_folder(favorite_folder, depth=depth, upsert=upsert)

Create One favoriteFolder

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.create_one_favorite_folder201_response import CreateOneFavoriteFolder201Response
from twentycrm_client.models.favorite_folder import FavoriteFolder
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    favorite_folder = twentycrm_client.FavoriteFolder() # FavoriteFolder | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    upsert = False # bool | If true, creates the object or updates it if it already exists. (optional) (default to False)

    try:
        # Create One favoriteFolder
        api_response = api_instance.create_one_favorite_folder(favorite_folder, depth=depth, upsert=upsert)
        print("The response of FavoriteFoldersApi->create_one_favorite_folder:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->create_one_favorite_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **favorite_folder** | [**FavoriteFolder**](FavoriteFolder.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **upsert** | **bool**| If true, creates the object or updates it if it already exists. | [optional] [default to False]

### Return type

[**CreateOneFavoriteFolder201Response**](CreateOneFavoriteFolder201Response.md)

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

# **delete_many_favorite_folders**
> DeleteManyFavoriteFolders200Response delete_many_favorite_folders(filter=filter, soft_delete=soft_delete)

Delete Many favoriteFolders

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_many_favorite_folders200_response import DeleteManyFavoriteFolders200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete Many favoriteFolders
        api_response = api_instance.delete_many_favorite_folders(filter=filter, soft_delete=soft_delete)
        print("The response of FavoriteFoldersApi->delete_many_favorite_folders:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->delete_many_favorite_folders: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteManyFavoriteFolders200Response**](DeleteManyFavoriteFolders200Response.md)

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

# **delete_one_favorite_folder**
> DeleteOneFavoriteFolder200Response delete_one_favorite_folder(id, soft_delete=soft_delete)

Delete One favoriteFolder

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.delete_one_favorite_folder200_response import DeleteOneFavoriteFolder200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    soft_delete = False # bool | If true, soft deletes the objects. If false, objects are permanently deleted. (optional) (default to False)

    try:
        # Delete One favoriteFolder
        api_response = api_instance.delete_one_favorite_folder(id, soft_delete=soft_delete)
        print("The response of FavoriteFoldersApi->delete_one_favorite_folder:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->delete_one_favorite_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **soft_delete** | **bool**| If true, soft deletes the objects. If false, objects are permanently deleted. | [optional] [default to False]

### Return type

[**DeleteOneFavoriteFolder200Response**](DeleteOneFavoriteFolder200Response.md)

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

# **find_favorite_folder_duplicates**
> FindFavoriteFolderDuplicates200Response find_favorite_folder_duplicates(find_favorite_folder_duplicates_request, depth=depth)

Find favoriteFolder Duplicates

**depth** can be provided to request your **favoriteFolder**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_favorite_folder_duplicates200_response import FindFavoriteFolderDuplicates200Response
from twentycrm_client.models.find_favorite_folder_duplicates_request import FindFavoriteFolderDuplicatesRequest
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    find_favorite_folder_duplicates_request = twentycrm_client.FindFavoriteFolderDuplicatesRequest() # FindFavoriteFolderDuplicatesRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find favoriteFolder Duplicates
        api_response = api_instance.find_favorite_folder_duplicates(find_favorite_folder_duplicates_request, depth=depth)
        print("The response of FavoriteFoldersApi->find_favorite_folder_duplicates:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->find_favorite_folder_duplicates: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **find_favorite_folder_duplicates_request** | [**FindFavoriteFolderDuplicatesRequest**](FindFavoriteFolderDuplicatesRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindFavoriteFolderDuplicates200Response**](FindFavoriteFolderDuplicates200Response.md)

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

# **find_many_favorite_folders**
> FindManyFavoriteFolders200Response find_many_favorite_folders(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)

Find Many favoriteFolders

**order_by**, **filter**, **limit**, **depth**, **starting_after** or **ending_before** can be provided to request your **favoriteFolders**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_many_favorite_folders200_response import FindManyFavoriteFolders200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    starting_after = 'starting_after_example' # str | Returns objects starting after a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)
    ending_before = 'ending_before_example' # str | Returns objects ending before a specific cursor. You can find cursors in **startCursor** and **endCursor** in **pageInfo** in response data (optional)

    try:
        # Find Many favoriteFolders
        api_response = api_instance.find_many_favorite_folders(order_by=order_by, filter=filter, limit=limit, depth=depth, starting_after=starting_after, ending_before=ending_before)
        print("The response of FavoriteFoldersApi->find_many_favorite_folders:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->find_many_favorite_folders: %s\n" % e)
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

[**FindManyFavoriteFolders200Response**](FindManyFavoriteFolders200Response.md)

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

# **find_one_favorite_folder**
> FindOneFavoriteFolder200Response find_one_favorite_folder(id, depth=depth)

Find One favoriteFolder

**depth** can be provided to request your **favoriteFolder**

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.find_one_favorite_folder200_response import FindOneFavoriteFolder200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Find One favoriteFolder
        api_response = api_instance.find_one_favorite_folder(id, depth=depth)
        print("The response of FavoriteFoldersApi->find_one_favorite_folder:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->find_one_favorite_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**FindOneFavoriteFolder200Response**](FindOneFavoriteFolder200Response.md)

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

# **group_by_favorite_folders**
> GroupByFavoriteFolders200Response group_by_favorite_folders(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)

Group By favoriteFolders

Groups **favoriteFolders** by specified fields and optionally computes aggregate values for each group.

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.group_by_favorite_folders200_response import GroupByFavoriteFolders200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    group_by = '[{\"updatedAt\": true}]' # str | Array of fields to group by. Each element can specify a field and optionally a subfield or granularity for date fields.
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    order_by = 'createdAt' # str | Format: **field_name_1,field_name_2[DIRECTION_2]     Refer to the filter section at the top of the page for more details. (optional)
    limit = 60 # int | Limits the number of objects returned. (optional) (default to 60)
    view_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | View ID to apply filters from. (optional)
    aggregate = '[\"countNotEmptyId\"]' # str | Array of aggregate operations to compute for each group. (optional)
    include_records_sample = False # bool | If true, includes a sample of records for each group in the response. (optional) (default to False)
    order_by_for_records = 'createdAt' # str | Order by clause for records within each group. Only applicable when include_records_sample is true. (optional)

    try:
        # Group By favoriteFolders
        api_response = api_instance.group_by_favorite_folders(group_by, filter=filter, order_by=order_by, limit=limit, view_id=view_id, aggregate=aggregate, include_records_sample=include_records_sample, order_by_for_records=order_by_for_records)
        print("The response of FavoriteFoldersApi->group_by_favorite_folders:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->group_by_favorite_folders: %s\n" % e)
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

[**GroupByFavoriteFolders200Response**](GroupByFavoriteFolders200Response.md)

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

# **merge_many_favorite_folders**
> MergeManyFavoriteFolders200Response merge_many_favorite_folders(merge_many_favorite_folders_request, depth=depth)

Merge Many favoriteFolders

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.merge_many_favorite_folders200_response import MergeManyFavoriteFolders200Response
from twentycrm_client.models.merge_many_favorite_folders_request import MergeManyFavoriteFoldersRequest
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    merge_many_favorite_folders_request = twentycrm_client.MergeManyFavoriteFoldersRequest() # MergeManyFavoriteFoldersRequest | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Merge Many favoriteFolders
        api_response = api_instance.merge_many_favorite_folders(merge_many_favorite_folders_request, depth=depth)
        print("The response of FavoriteFoldersApi->merge_many_favorite_folders:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->merge_many_favorite_folders: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merge_many_favorite_folders_request** | [**MergeManyFavoriteFoldersRequest**](MergeManyFavoriteFoldersRequest.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**MergeManyFavoriteFolders200Response**](MergeManyFavoriteFolders200Response.md)

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

# **restore_many_favorite_folders**
> RestoreManyFavoriteFolders200Response restore_many_favorite_folders(filter=filter, depth=depth)

Restore Many favoriteFolders

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_many_favorite_folders200_response import RestoreManyFavoriteFolders200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore Many favoriteFolders
        api_response = api_instance.restore_many_favorite_folders(filter=filter, depth=depth)
        print("The response of FavoriteFoldersApi->restore_many_favorite_folders:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->restore_many_favorite_folders: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreManyFavoriteFolders200Response**](RestoreManyFavoriteFolders200Response.md)

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

# **restore_one_favorite_folder**
> RestoreOneFavoriteFolder200Response restore_one_favorite_folder(id, depth=depth)

Restore One favoriteFolder

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.restore_one_favorite_folder200_response import RestoreOneFavoriteFolder200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Restore One favoriteFolder
        api_response = api_instance.restore_one_favorite_folder(id, depth=depth)
        print("The response of FavoriteFoldersApi->restore_one_favorite_folder:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->restore_one_favorite_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**RestoreOneFavoriteFolder200Response**](RestoreOneFavoriteFolder200Response.md)

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

# **update_many_favorite_folders**
> UpdateManyFavoriteFolders200Response update_many_favorite_folders(favorite_folder_for_update, depth=depth, filter=filter)

Update Many favoriteFolders

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.favorite_folder_for_update import FavoriteFolderForUpdate
from twentycrm_client.models.update_many_favorite_folders200_response import UpdateManyFavoriteFolders200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    favorite_folder_for_update = twentycrm_client.FavoriteFolderForUpdate() # FavoriteFolderForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)
    filter = 'createdAt[gte]:\"2023-01-01\"' # str | Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. (optional)

    try:
        # Update Many favoriteFolders
        api_response = api_instance.update_many_favorite_folders(favorite_folder_for_update, depth=depth, filter=filter)
        print("The response of FavoriteFoldersApi->update_many_favorite_folders:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->update_many_favorite_folders: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **favorite_folder_for_update** | [**FavoriteFolderForUpdate**](FavoriteFolderForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]
 **filter** | **str**| Format: field[COMPARATOR]:value,field2[COMPARATOR]:value2.     For like/ilike, use % as a wildcard (e.g. %value% for substring match).     Refer to the filter section at the top of the page for more details. | [optional] 

### Return type

[**UpdateManyFavoriteFolders200Response**](UpdateManyFavoriteFolders200Response.md)

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

# **update_one_favorite_folder**
> UpdateOneFavoriteFolder200Response update_one_favorite_folder(id, favorite_folder_for_update, depth=depth)

Update One favoriteFolder

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.favorite_folder_for_update import FavoriteFolderForUpdate
from twentycrm_client.models.update_one_favorite_folder200_response import UpdateOneFavoriteFolder200Response
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
    api_instance = twentycrm_client.FavoriteFoldersApi(api_client)
    id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | Object id.
    favorite_folder_for_update = twentycrm_client.FavoriteFolderForUpdate() # FavoriteFolderForUpdate | body
    depth = 1 # int | Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations (optional) (default to 1)

    try:
        # Update One favoriteFolder
        api_response = api_instance.update_one_favorite_folder(id, favorite_folder_for_update, depth=depth)
        print("The response of FavoriteFoldersApi->update_one_favorite_folder:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FavoriteFoldersApi->update_one_favorite_folder: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **UUID**| Object id. | 
 **favorite_folder_for_update** | [**FavoriteFolderForUpdate**](FavoriteFolderForUpdate.md)| body | 
 **depth** | **int**| Determines the level of nested related objects to include in the response.     - 0: Primary object only     - 1: Primary object + direct relations | [optional] [default to 1]

### Return type

[**UpdateOneFavoriteFolder200Response**](UpdateOneFavoriteFolder200Response.md)

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

