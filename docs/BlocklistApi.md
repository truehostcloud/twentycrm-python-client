# twentycrm_client.BlocklistApi

All URIs are relative to *https://crm.example.com/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**blocklist_created_post**](BlocklistApi.md#blocklist_created_post) | **POST** /Blocklist Created | 
[**blocklist_deleted_post**](BlocklistApi.md#blocklist_deleted_post) | **POST** /Blocklist Deleted | 
[**blocklist_updated_post**](BlocklistApi.md#blocklist_updated_post) | **POST** /Blocklist Updated | 


# **blocklist_created_post**
> blocklist_created_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, blocklist_created_post_request=blocklist_created_post_request)

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
    api_instance = twentycrm_client.BlocklistApi(api_client)
    x_twenty_webhook_signature = 'x_twenty_webhook_signature_example' # str | HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate `X-Twenty-Webhook-Timestamp`, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): ```javascript const crypto = require(\"crypto\"); const timestamp = \"1735066639761\"; const payload = JSON.stringify({...}); const secret = \"your-secret\"; const stringToSign = `${timestamp}:${JSON.stringify(payload)}`; const signature = crypto.createHmac(\"sha256\", secret)   .update(stringToSign)   .digest(\"hex\"); ``` (optional)
    x_twenty_webhook_timestamp = 'x_twenty_webhook_timestamp_example' # str | Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. (optional)
    x_twenty_webhook_nonce = 'x_twenty_webhook_nonce_example' # str | Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. (optional)
    blocklist_created_post_request = twentycrm_client.BlocklistCreatedPostRequest() # BlocklistCreatedPostRequest |  (optional)

    try:
        api_instance.blocklist_created_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, blocklist_created_post_request=blocklist_created_post_request)
    except Exception as e:
        print("Exception when calling BlocklistApi->blocklist_created_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x_twenty_webhook_signature** | **str**| HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate &#x60;X-Twenty-Webhook-Timestamp&#x60;, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): &#x60;&#x60;&#x60;javascript const crypto &#x3D; require(\&quot;crypto\&quot;); const timestamp &#x3D; \&quot;1735066639761\&quot;; const payload &#x3D; JSON.stringify({...}); const secret &#x3D; \&quot;your-secret\&quot;; const stringToSign &#x3D; &#x60;${timestamp}:${JSON.stringify(payload)}&#x60;; const signature &#x3D; crypto.createHmac(\&quot;sha256\&quot;, secret)   .update(stringToSign)   .digest(\&quot;hex\&quot;); &#x60;&#x60;&#x60; | [optional] 
 **x_twenty_webhook_timestamp** | **str**| Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. | [optional] 
 **x_twenty_webhook_nonce** | **str**| Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. | [optional] 
 **blocklist_created_post_request** | [**BlocklistCreatedPostRequest**](BlocklistCreatedPostRequest.md)|  | [optional] 

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

# **blocklist_deleted_post**
> blocklist_deleted_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, blocklist_deleted_post_request=blocklist_deleted_post_request)

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
    api_instance = twentycrm_client.BlocklistApi(api_client)
    x_twenty_webhook_signature = 'x_twenty_webhook_signature_example' # str | HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate `X-Twenty-Webhook-Timestamp`, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): ```javascript const crypto = require(\"crypto\"); const timestamp = \"1735066639761\"; const payload = JSON.stringify({...}); const secret = \"your-secret\"; const stringToSign = `${timestamp}:${JSON.stringify(payload)}`; const signature = crypto.createHmac(\"sha256\", secret)   .update(stringToSign)   .digest(\"hex\"); ``` (optional)
    x_twenty_webhook_timestamp = 'x_twenty_webhook_timestamp_example' # str | Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. (optional)
    x_twenty_webhook_nonce = 'x_twenty_webhook_nonce_example' # str | Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. (optional)
    blocklist_deleted_post_request = twentycrm_client.BlocklistDeletedPostRequest() # BlocklistDeletedPostRequest |  (optional)

    try:
        api_instance.blocklist_deleted_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, blocklist_deleted_post_request=blocklist_deleted_post_request)
    except Exception as e:
        print("Exception when calling BlocklistApi->blocklist_deleted_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x_twenty_webhook_signature** | **str**| HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate &#x60;X-Twenty-Webhook-Timestamp&#x60;, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): &#x60;&#x60;&#x60;javascript const crypto &#x3D; require(\&quot;crypto\&quot;); const timestamp &#x3D; \&quot;1735066639761\&quot;; const payload &#x3D; JSON.stringify({...}); const secret &#x3D; \&quot;your-secret\&quot;; const stringToSign &#x3D; &#x60;${timestamp}:${JSON.stringify(payload)}&#x60;; const signature &#x3D; crypto.createHmac(\&quot;sha256\&quot;, secret)   .update(stringToSign)   .digest(\&quot;hex\&quot;); &#x60;&#x60;&#x60; | [optional] 
 **x_twenty_webhook_timestamp** | **str**| Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. | [optional] 
 **x_twenty_webhook_nonce** | **str**| Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. | [optional] 
 **blocklist_deleted_post_request** | [**BlocklistDeletedPostRequest**](BlocklistDeletedPostRequest.md)|  | [optional] 

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

# **blocklist_updated_post**
> blocklist_updated_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, blocklist_updated_post_request=blocklist_updated_post_request)

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
    api_instance = twentycrm_client.BlocklistApi(api_client)
    x_twenty_webhook_signature = 'x_twenty_webhook_signature_example' # str | HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate `X-Twenty-Webhook-Timestamp`, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): ```javascript const crypto = require(\"crypto\"); const timestamp = \"1735066639761\"; const payload = JSON.stringify({...}); const secret = \"your-secret\"; const stringToSign = `${timestamp}:${JSON.stringify(payload)}`; const signature = crypto.createHmac(\"sha256\", secret)   .update(stringToSign)   .digest(\"hex\"); ``` (optional)
    x_twenty_webhook_timestamp = 'x_twenty_webhook_timestamp_example' # str | Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. (optional)
    x_twenty_webhook_nonce = 'x_twenty_webhook_nonce_example' # str | Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. (optional)
    blocklist_updated_post_request = twentycrm_client.BlocklistUpdatedPostRequest() # BlocklistUpdatedPostRequest |  (optional)

    try:
        api_instance.blocklist_updated_post(x_twenty_webhook_signature=x_twenty_webhook_signature, x_twenty_webhook_timestamp=x_twenty_webhook_timestamp, x_twenty_webhook_nonce=x_twenty_webhook_nonce, blocklist_updated_post_request=blocklist_updated_post_request)
    except Exception as e:
        print("Exception when calling BlocklistApi->blocklist_updated_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x_twenty_webhook_signature** | **str**| HMAC SHA256 signature of the request payload using the webhook secret. To compute the signature: 1. Concatenate &#x60;X-Twenty-Webhook-Timestamp&#x60;, a colon (:), and the JSON string of the request payload. 2. Compute the HMAC SHA256 hash using the shared secret as the key. 3. Send the resulting hex digest as this header value. Example (Node.js): &#x60;&#x60;&#x60;javascript const crypto &#x3D; require(\&quot;crypto\&quot;); const timestamp &#x3D; \&quot;1735066639761\&quot;; const payload &#x3D; JSON.stringify({...}); const secret &#x3D; \&quot;your-secret\&quot;; const stringToSign &#x3D; &#x60;${timestamp}:${JSON.stringify(payload)}&#x60;; const signature &#x3D; crypto.createHmac(\&quot;sha256\&quot;, secret)   .update(stringToSign)   .digest(\&quot;hex\&quot;); &#x60;&#x60;&#x60; | [optional] 
 **x_twenty_webhook_timestamp** | **str**| Unix timestamp of when the webhook was sent. This timestamp is included in the HMAC signature generation to prevent replay attacks. | [optional] 
 **x_twenty_webhook_nonce** | **str**| Unique identifier for this webhook request to prevent replay attacks. Consumers should ensure this nonce is not reused. | [optional] 
 **blocklist_updated_post_request** | [**BlocklistUpdatedPostRequest**](BlocklistUpdatedPostRequest.md)|  | [optional] 

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

