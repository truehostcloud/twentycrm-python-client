# twentycrm_client.GeneralApi

All URIs are relative to *https://crm.example.com/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_open_api_schema**](GeneralApi.md#get_open_api_schema) | **GET** /open-api/core | Get Open Api Schema


# **get_open_api_schema**
> GetOpenApiSchema200Response get_open_api_schema()

Get Open Api Schema

### Example

* Bearer (JWT) Authentication (bearerAuth):

```python
import twentycrm_client
from twentycrm_client.models.get_open_api_schema200_response import GetOpenApiSchema200Response
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
    api_instance = twentycrm_client.GeneralApi(api_client)

    try:
        # Get Open Api Schema
        api_response = api_instance.get_open_api_schema()
        print("The response of GeneralApi->get_open_api_schema:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GeneralApi->get_open_api_schema: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**GetOpenApiSchema200Response**](GetOpenApiSchema200Response.md)

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

