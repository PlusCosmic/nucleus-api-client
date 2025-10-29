# UserEndpointsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**meGet**](UserEndpointsApi.md#meget) | **GET** /me |  |



## meGet

> User meGet()



### Example

```ts
import {
  Configuration,
  UserEndpointsApi,
} from '';
import type { MeGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new UserEndpointsApi();

  try {
    const data = await api.meGet();
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)

