# twentycrm_client.TaskApi

All URIs are relative to *https://crm.example.com/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**task_created_post**](TaskApi.md#task_created_post) | **POST** /Task Created | 
[**task_deleted_post**](TaskApi.md#task_deleted_post) | **POST** /Task Deleted | 
[**task_updated_post**](TaskApi.md#task_updated_post) | **POST** /Task Updated | 


# **task_created_post**
> task_created_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, task_created_post_request=task_created_post_request)

### Example


```python
import twentycrm_client
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)


# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.TaskApi(api_client)
    x_twenty_webhook_signature = 'x_twenty_webhook_signature_example' # str | HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate `X-Twenty-Webhook-Timestamp`, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): ```javascript const crypto = require(\"crypto\"); const timestamp = \"1735066639761\"; const payload = JSON.stringify({...}); const secret = \"your-secret\"; const stringToSign = `${timestamp}:${JSON.stringify(payload)}`; const signature = crypto.createHmac(\"sha256\", secret)   .update(stringToSign)   .digest(\"hex\"); ``` (optional)
    x_twenty_webhook_timestamp = 'x_twenty_webhook_timestamp_example' # str | Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. (optional)
    x_twenty_webhook_nonce = 'x_twenty_webhook_nonce_example' # str | Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. (optional)
    task_created_post_request = twentycrm_client.TaskCreatedPostRequest() # TaskCreatedPostRequest |  (optional)

    try:
        api_instance.task_created_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, task_created_post_request=task_created_post_request)
    except Exception as e:
        print("Exception when calling TaskApi->task_created_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x_twenty_webhook_signature** | **str**| HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate &#x60;X-Twenty-Webhook-Timestamp&#x60;, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): &#x60;&#x60;&#x60;javascript const crypto &#x3D; require(\&quot;crypto\&quot;); const timestamp &#x3D; \&quot;1735066639761\&quot;; const payload &#x3D; JSON.stringify({...}); const secret &#x3D; \&quot;your-secret\&quot;; const stringToSign &#x3D; &#x60;${timestamp}:${JSON.stringify(payload)}&#x60;; const signature &#x3D; crypto.createHmac(\&quot;sha256\&quot;, secret)   .update(stringToSign)   .digest(\&quot;hex\&quot;); &#x60;&#x60;&#x60; | [optional] 
 **x_twenty_webhook_timestamp** | **str**| Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. | [optional] 
 **x_twenty_webhook_nonce** | **str**| Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. | [optional] 
 **task_created_post_request** | [**TaskCreatedPostRequest**](TaskCreatedPostRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Return a 200 status to indicate that the data was received successfully |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **task_deleted_post**
> task_deleted_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, task_deleted_post_request=task_deleted_post_request)

### Example


```python
import twentycrm_client
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)


# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.TaskApi(api_client)
    x_twenty_webhook_signature = 'x_twenty_webhook_signature_example' # str | HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate `X-Twenty-Webhook-Timestamp`, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): ```javascript const crypto = require(\"crypto\"); const timestamp = \"1735066639761\"; const payload = JSON.stringify({...}); const secret = \"your-secret\"; const stringToSign = `${timestamp}:${JSON.stringify(payload)}`; const signature = crypto.createHmac(\"sha256\", secret)   .update(stringToSign)   .digest(\"hex\"); ``` (optional)
    x_twenty_webhook_timestamp = 'x_twenty_webhook_timestamp_example' # str | Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. (optional)
    x_twenty_webhook_nonce = 'x_twenty_webhook_nonce_example' # str | Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. (optional)
    task_deleted_post_request = twentycrm_client.TaskDeletedPostRequest() # TaskDeletedPostRequest |  (optional)

    try:
        api_instance.task_deleted_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, task_deleted_post_request=task_deleted_post_request)
    except Exception as e:
        print("Exception when calling TaskApi->task_deleted_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x_twenty_webhook_signature** | **str**| HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate &#x60;X-Twenty-Webhook-Timestamp&#x60;, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): &#x60;&#x60;&#x60;javascript const crypto &#x3D; require(\&quot;crypto\&quot;); const timestamp &#x3D; \&quot;1735066639761\&quot;; const payload &#x3D; JSON.stringify({...}); const secret &#x3D; \&quot;your-secret\&quot;; const stringToSign &#x3D; &#x60;${timestamp}:${JSON.stringify(payload)}&#x60;; const signature &#x3D; crypto.createHmac(\&quot;sha256\&quot;, secret)   .update(stringToSign)   .digest(\&quot;hex\&quot;); &#x60;&#x60;&#x60; | [optional] 
 **x_twenty_webhook_timestamp** | **str**| Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. | [optional] 
 **x_twenty_webhook_nonce** | **str**| Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. | [optional] 
 **task_deleted_post_request** | [**TaskDeletedPostRequest**](TaskDeletedPostRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Return a 200 status to indicate that the data was received successfully |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **task_updated_post**
> task_updated_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, task_updated_post_request=task_updated_post_request)

### Example


```python
import twentycrm_client
from twentycrm_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://crm.example.com/rest
# See configuration.py for a list of all supported configuration parameters.
configuration = twentycrm_client.Configuration(
    host = "https://crm.example.com/rest"
)


# Enter a context with an instance of the API client
with twentycrm_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = twentycrm_client.TaskApi(api_client)
    x_twenty_webhook_signature = 'x_twenty_webhook_signature_example' # str | HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate `X-Twenty-Webhook-Timestamp`, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): ```javascript const crypto = require(\"crypto\"); const timestamp = \"1735066639761\"; const payload = JSON.stringify({...}); const secret = \"your-secret\"; const stringToSign = `${timestamp}:${JSON.stringify(payload)}`; const signature = crypto.createHmac(\"sha256\", secret)   .update(stringToSign)   .digest(\"hex\"); ``` (optional)
    x_twenty_webhook_timestamp = 'x_twenty_webhook_timestamp_example' # str | Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. (optional)
    x_twenty_webhook_nonce = 'x_twenty_webhook_nonce_example' # str | Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. (optional)
    task_updated_post_request = twentycrm_client.TaskUpdatedPostRequest() # TaskUpdatedPostRequest |  (optional)

    try:
        api_instance.task_updated_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, task_updated_post_request=task_updated_post_request)
    except Exception as e:
        print("Exception when calling TaskApi->task_updated_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x_twenty_webhook_signature** | **str**| HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate &#x60;X-Twenty-Webhook-Timestamp&#x60;, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): &#x60;&#x60;&#x60;javascript const crypto &#x3D; require(\&quot;crypto\&quot;); const timestamp &#x3D; \&quot;1735066639761\&quot;; const payload &#x3D; JSON.stringify({...}); const secret &#x3D; \&quot;your-secret\&quot;; const stringToSign &#x3D; &#x60;${timestamp}:${JSON.stringify(payload)}&#x60;; const signature &#x3D; crypto.createHmac(\&quot;sha256\&quot;, secret)   .update(stringToSign)   .digest(\&quot;hex\&quot;); &#x60;&#x60;&#x60; | [optional] 
 **x_twenty_webhook_timestamp** | **str**| Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. | [optional] 
 **x_twenty_webhook_nonce** | **str**| Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. | [optional] 
 **task_updated_post_request** | [**TaskUpdatedPostRequest**](TaskUpdatedPostRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Return a 200 status to indicate that the data was received successfully |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

