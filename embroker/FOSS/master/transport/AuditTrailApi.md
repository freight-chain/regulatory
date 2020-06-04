# api_client.api.AuditTrailApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteAuditTrail**](AuditTrailApi.md#deleteAuditTrail) | **POST** /api/AuditTrail/deleteAuditTrail | 
[**getAuditTrail**](AuditTrailApi.md#getAuditTrail) | **GET** /api/AuditTrail/getAuditTrail | 
[**getAuditTrails**](AuditTrailApi.md#getAuditTrails) | **POST** /api/AuditTrail/getAuditTrails | 
[**saveAuditTrail**](AuditTrailApi.md#saveAuditTrail) | **POST** /api/AuditTrail/saveAuditTrail | 


# **deleteAuditTrail**
> deleteAuditTrail(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AuditTrailApi();
var id = id_example; // String | 

try { 
    api_instance.deleteAuditTrail(id);
} catch (e) {
    print("Exception when calling AuditTrailApi->deleteAuditTrail: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAuditTrail**
> AuditTrailServiceModel getAuditTrail(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AuditTrailApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getAuditTrail(id);
    print(result);
} catch (e) {
    print("Exception when calling AuditTrailApi->getAuditTrail: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**AuditTrailServiceModel**](AuditTrailServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAuditTrails**
> QueryResultAuditTrailServiceModel getAuditTrails(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AuditTrailApi();
var request = new AuditTrailQueryRequest(); // AuditTrailQueryRequest | 

try { 
    var result = api_instance.getAuditTrails(request);
    print(result);
} catch (e) {
    print("Exception when calling AuditTrailApi->getAuditTrails: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**AuditTrailQueryRequest**](AuditTrailQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultAuditTrailServiceModel**](QueryResultAuditTrailServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveAuditTrail**
> AuditTrailServiceModel saveAuditTrail(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AuditTrailApi();
var model = new AuditTrailServiceModel(); // AuditTrailServiceModel | 

try { 
    var result = api_instance.saveAuditTrail(model);
    print(result);
} catch (e) {
    print("Exception when calling AuditTrailApi->saveAuditTrail: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**AuditTrailServiceModel**](AuditTrailServiceModel.md)|  | [optional] 

### Return type

[**AuditTrailServiceModel**](AuditTrailServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

