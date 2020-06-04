# api_client.api.BaseLoadSizeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteLoadSize**](BaseLoadSizeApi.md#deleteLoadSize) | **POST** /deleteLoadSize | 
[**getLoadSize**](BaseLoadSizeApi.md#getLoadSize) | **GET** /getLoadSize | 
[**getLoadSizes**](BaseLoadSizeApi.md#getLoadSizes) | **POST** /getLoadSizes | 
[**saveLoadSize**](BaseLoadSizeApi.md#saveLoadSize) | **POST** /saveLoadSize | 


# **deleteLoadSize**
> deleteLoadSize(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLoadSizeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteLoadSize(id);
} catch (e) {
    print("Exception when calling BaseLoadSizeApi->deleteLoadSize: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getLoadSize**
> LoadSizeServiceModel getLoadSize(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLoadSizeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getLoadSize(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseLoadSizeApi->getLoadSize: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**LoadSizeServiceModel**](LoadSizeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getLoadSizes**
> QueryResultLoadSizeServiceModel getLoadSizes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLoadSizeApi();
var request = new LoadSizeQueryRequest(); // LoadSizeQueryRequest | 

try { 
    var result = api_instance.getLoadSizes(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseLoadSizeApi->getLoadSizes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**LoadSizeQueryRequest**](LoadSizeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultLoadSizeServiceModel**](QueryResultLoadSizeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveLoadSize**
> LoadSizeServiceModel saveLoadSize(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLoadSizeApi();
var model = new LoadSizeServiceModel(); // LoadSizeServiceModel | 

try { 
    var result = api_instance.saveLoadSize(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseLoadSizeApi->saveLoadSize: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**LoadSizeServiceModel**](LoadSizeServiceModel.md)|  | [optional] 

### Return type

[**LoadSizeServiceModel**](LoadSizeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

