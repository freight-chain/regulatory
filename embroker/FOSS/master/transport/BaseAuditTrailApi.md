# api_client.api.BaseAuditTrailApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteAuditTrail**](BaseAuditTrailApi.md#deleteAuditTrail) | **POST** /deleteAuditTrail | 
[**getAuditTrail**](BaseAuditTrailApi.md#getAuditTrail) | **GET** /getAuditTrail | 
[**getAuditTrails**](BaseAuditTrailApi.md#getAuditTrails) | **POST** /getAuditTrails | 
[**saveAuditTrail**](BaseAuditTrailApi.md#saveAuditTrail) | **POST** /saveAuditTrail | 


# **deleteAuditTrail**
> deleteAuditTrail(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAuditTrailApi();
var id = id_example; // String | 

try { 
    api_instance.deleteAuditTrail(id);
} catch (e) {
    print("Exception when calling BaseAuditTrailApi->deleteAuditTrail: $e\n");
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

# **getAuditTrail**
> AuditTrailServiceModel getAuditTrail(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAuditTrailApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getAuditTrail(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseAuditTrailApi->getAuditTrail: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**AuditTrailServiceModel**](AuditTrailServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAuditTrails**
> QueryResultAuditTrailServiceModel getAuditTrails(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAuditTrailApi();
var request = new AuditTrailQueryRequest(); // AuditTrailQueryRequest | 

try { 
    var result = api_instance.getAuditTrails(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseAuditTrailApi->getAuditTrails: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**AuditTrailQueryRequest**](AuditTrailQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultAuditTrailServiceModel**](QueryResultAuditTrailServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveAuditTrail**
> AuditTrailServiceModel saveAuditTrail(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAuditTrailApi();
var model = new AuditTrailServiceModel(); // AuditTrailServiceModel | 

try { 
    var result = api_instance.saveAuditTrail(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseAuditTrailApi->saveAuditTrail: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**AuditTrailServiceModel**](AuditTrailServiceModel.md)|  | [optional] 

### Return type

[**AuditTrailServiceModel**](AuditTrailServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

