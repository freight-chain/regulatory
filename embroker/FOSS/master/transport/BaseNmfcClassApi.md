# api_client.api.BaseNmfcClassApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteNmfcClass**](BaseNmfcClassApi.md#deleteNmfcClass) | **POST** /deleteNmfcClass | 
[**getNmfcClass**](BaseNmfcClassApi.md#getNmfcClass) | **GET** /getNmfcClass | 
[**getNmfcClasses**](BaseNmfcClassApi.md#getNmfcClasses) | **POST** /getNmfcClasses | 
[**saveNmfcClass**](BaseNmfcClassApi.md#saveNmfcClass) | **POST** /saveNmfcClass | 


# **deleteNmfcClass**
> deleteNmfcClass(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseNmfcClassApi();
var id = id_example; // String | 

try { 
    api_instance.deleteNmfcClass(id);
} catch (e) {
    print("Exception when calling BaseNmfcClassApi->deleteNmfcClass: $e\n");
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

# **getNmfcClass**
> NmfcClassServiceModel getNmfcClass(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseNmfcClassApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getNmfcClass(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseNmfcClassApi->getNmfcClass: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**NmfcClassServiceModel**](NmfcClassServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getNmfcClasses**
> QueryResultNmfcClassServiceModel getNmfcClasses(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseNmfcClassApi();
var request = new NmfcClassQueryRequest(); // NmfcClassQueryRequest | 

try { 
    var result = api_instance.getNmfcClasses(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseNmfcClassApi->getNmfcClasses: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**NmfcClassQueryRequest**](NmfcClassQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultNmfcClassServiceModel**](QueryResultNmfcClassServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveNmfcClass**
> NmfcClassServiceModel saveNmfcClass(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseNmfcClassApi();
var model = new NmfcClassServiceModel(); // NmfcClassServiceModel | 

try { 
    var result = api_instance.saveNmfcClass(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseNmfcClassApi->saveNmfcClass: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**NmfcClassServiceModel**](NmfcClassServiceModel.md)|  | [optional] 

### Return type

[**NmfcClassServiceModel**](NmfcClassServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

