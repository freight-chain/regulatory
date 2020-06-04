# api_client.api.BaseStopApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteStop**](BaseStopApi.md#deleteStop) | **POST** /deleteStop | 
[**getStop**](BaseStopApi.md#getStop) | **GET** /getStop | 
[**getStops**](BaseStopApi.md#getStops) | **POST** /getStops | 
[**saveStop**](BaseStopApi.md#saveStop) | **POST** /saveStop | 
[**stopStatusUpdate**](BaseStopApi.md#stopStatusUpdate) | **POST** /stopStatusUpdate | 


# **deleteStop**
> deleteStop(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopApi();
var id = id_example; // String | 

try { 
    api_instance.deleteStop(id);
} catch (e) {
    print("Exception when calling BaseStopApi->deleteStop: $e\n");
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

# **getStop**
> StopServiceModel getStop(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getStop(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseStopApi->getStop: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**StopServiceModel**](StopServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getStops**
> QueryResultStopServiceModel getStops(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopApi();
var request = new StopQueryRequest(); // StopQueryRequest | 

try { 
    var result = api_instance.getStops(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseStopApi->getStops: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**StopQueryRequest**](StopQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultStopServiceModel**](QueryResultStopServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveStop**
> StopServiceModel saveStop(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopApi();
var model = new StopServiceModel(); // StopServiceModel | 

try { 
    var result = api_instance.saveStop(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseStopApi->saveStop: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**StopServiceModel**](StopServiceModel.md)|  | [optional] 

### Return type

[**StopServiceModel**](StopServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **stopStatusUpdate**
> StopServiceModel stopStatusUpdate(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseStopApi();
var request = new StopStatusUpdateRequest(); // StopStatusUpdateRequest | 

try { 
    var result = api_instance.stopStatusUpdate(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseStopApi->stopStatusUpdate: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**StopStatusUpdateRequest**](StopStatusUpdateRequest.md)|  | [optional] 

### Return type

[**StopServiceModel**](StopServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

