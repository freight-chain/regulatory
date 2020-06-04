# api_client.api.BaseStopUpdateApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteStopUpdate**](BaseStopUpdateApi.md#deleteStopUpdate) | **POST** /deleteStopUpdate | 
[**getStopUpdate**](BaseStopUpdateApi.md#getStopUpdate) | **GET** /getStopUpdate | 
[**getStopUpdates**](BaseStopUpdateApi.md#getStopUpdates) | **POST** /getStopUpdates | 
[**saveStopUpdate**](BaseStopUpdateApi.md#saveStopUpdate) | **POST** /saveStopUpdate | 


# **deleteStopUpdate**
> deleteStopUpdate(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopUpdateApi();
var id = id_example; // String | 

try { 
    api_instance.deleteStopUpdate(id);
} catch (e) {
    print("Exception when calling BaseStopUpdateApi->deleteStopUpdate: $e\n");
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

# **getStopUpdate**
> StopUpdateServiceModel getStopUpdate(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopUpdateApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getStopUpdate(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseStopUpdateApi->getStopUpdate: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**StopUpdateServiceModel**](StopUpdateServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getStopUpdates**
> QueryResultStopUpdateServiceModel getStopUpdates(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopUpdateApi();
var request = new StopUpdateQueryRequest(); // StopUpdateQueryRequest | 

try { 
    var result = api_instance.getStopUpdates(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseStopUpdateApi->getStopUpdates: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**StopUpdateQueryRequest**](StopUpdateQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultStopUpdateServiceModel**](QueryResultStopUpdateServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveStopUpdate**
> StopUpdateServiceModel saveStopUpdate(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopUpdateApi();
var model = new StopUpdateServiceModel(); // StopUpdateServiceModel | 

try { 
    var result = api_instance.saveStopUpdate(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseStopUpdateApi->saveStopUpdate: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**StopUpdateServiceModel**](StopUpdateServiceModel.md)|  | [optional] 

### Return type

[**StopUpdateServiceModel**](StopUpdateServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

