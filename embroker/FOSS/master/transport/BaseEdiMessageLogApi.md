# api_client.api.BaseEdiMessageLogApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteEdiMessageLog**](BaseEdiMessageLogApi.md#deleteEdiMessageLog) | **POST** /deleteEdiMessageLog | 
[**getEdiMessageLog**](BaseEdiMessageLogApi.md#getEdiMessageLog) | **GET** /getEdiMessageLog | 
[**getEdiMessageLogs**](BaseEdiMessageLogApi.md#getEdiMessageLogs) | **POST** /getEdiMessageLogs | 
[**saveEdiMessageLog**](BaseEdiMessageLogApi.md#saveEdiMessageLog) | **POST** /saveEdiMessageLog | 


# **deleteEdiMessageLog**
> deleteEdiMessageLog(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiMessageLogApi();
var id = id_example; // String | 

try { 
    api_instance.deleteEdiMessageLog(id);
} catch (e) {
    print("Exception when calling BaseEdiMessageLogApi->deleteEdiMessageLog: $e\n");
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

# **getEdiMessageLog**
> EdiMessageLogServiceModel getEdiMessageLog(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiMessageLogApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getEdiMessageLog(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiMessageLogApi->getEdiMessageLog: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**EdiMessageLogServiceModel**](EdiMessageLogServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getEdiMessageLogs**
> QueryResultEdiMessageLogServiceModel getEdiMessageLogs(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiMessageLogApi();
var request = new EdiMessageLogQueryRequest(); // EdiMessageLogQueryRequest | 

try { 
    var result = api_instance.getEdiMessageLogs(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiMessageLogApi->getEdiMessageLogs: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**EdiMessageLogQueryRequest**](EdiMessageLogQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultEdiMessageLogServiceModel**](QueryResultEdiMessageLogServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveEdiMessageLog**
> EdiMessageLogServiceModel saveEdiMessageLog(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiMessageLogApi();
var model = new EdiMessageLogServiceModel(); // EdiMessageLogServiceModel | 

try { 
    var result = api_instance.saveEdiMessageLog(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiMessageLogApi->saveEdiMessageLog: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**EdiMessageLogServiceModel**](EdiMessageLogServiceModel.md)|  | [optional] 

### Return type

[**EdiMessageLogServiceModel**](EdiMessageLogServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

