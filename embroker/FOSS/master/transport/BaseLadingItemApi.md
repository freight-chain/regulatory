# api_client.api.BaseLadingItemApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteLadingItem**](BaseLadingItemApi.md#deleteLadingItem) | **POST** /deleteLadingItem | 
[**getLadingItem**](BaseLadingItemApi.md#getLadingItem) | **GET** /getLadingItem | 
[**getLadingItems**](BaseLadingItemApi.md#getLadingItems) | **POST** /getLadingItems | 
[**saveLadingItem**](BaseLadingItemApi.md#saveLadingItem) | **POST** /saveLadingItem | 


# **deleteLadingItem**
> deleteLadingItem(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLadingItemApi();
var id = id_example; // String | 

try { 
    api_instance.deleteLadingItem(id);
} catch (e) {
    print("Exception when calling BaseLadingItemApi->deleteLadingItem: $e\n");
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

# **getLadingItem**
> LadingItemServiceModel getLadingItem(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLadingItemApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getLadingItem(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseLadingItemApi->getLadingItem: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**LadingItemServiceModel**](LadingItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getLadingItems**
> QueryResultLadingItemServiceModel getLadingItems(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLadingItemApi();
var request = new LadingItemQueryRequest(); // LadingItemQueryRequest | 

try { 
    var result = api_instance.getLadingItems(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseLadingItemApi->getLadingItems: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**LadingItemQueryRequest**](LadingItemQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultLadingItemServiceModel**](QueryResultLadingItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveLadingItem**
> LadingItemServiceModel saveLadingItem(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLadingItemApi();
var model = new LadingItemServiceModel(); // LadingItemServiceModel | 

try { 
    var result = api_instance.saveLadingItem(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseLadingItemApi->saveLadingItem: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**LadingItemServiceModel**](LadingItemServiceModel.md)|  | [optional] 

### Return type

[**LadingItemServiceModel**](LadingItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

