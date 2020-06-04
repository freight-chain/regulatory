# api_client.api.BasePermissionApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deletePermission**](BasePermissionApi.md#deletePermission) | **POST** /deletePermission | 
[**getPermission**](BasePermissionApi.md#getPermission) | **GET** /getPermission | 
[**getPermissions**](BasePermissionApi.md#getPermissions) | **POST** /getPermissions | 
[**savePermission**](BasePermissionApi.md#savePermission) | **POST** /savePermission | 


# **deletePermission**
> deletePermission(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BasePermissionApi();
var id = id_example; // String | 

try { 
    api_instance.deletePermission(id);
} catch (e) {
    print("Exception when calling BasePermissionApi->deletePermission: $e\n");
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

# **getPermission**
> PermissionServiceModel getPermission(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BasePermissionApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getPermission(id);
    print(result);
} catch (e) {
    print("Exception when calling BasePermissionApi->getPermission: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**PermissionServiceModel**](PermissionServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getPermissions**
> QueryResultPermissionServiceModel getPermissions(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BasePermissionApi();
var request = new PermissionQueryRequest(); // PermissionQueryRequest | 

try { 
    var result = api_instance.getPermissions(request);
    print(result);
} catch (e) {
    print("Exception when calling BasePermissionApi->getPermissions: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**PermissionQueryRequest**](PermissionQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultPermissionServiceModel**](QueryResultPermissionServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **savePermission**
> PermissionServiceModel savePermission(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BasePermissionApi();
var model = new PermissionServiceModel(); // PermissionServiceModel | 

try { 
    var result = api_instance.savePermission(model);
    print(result);
} catch (e) {
    print("Exception when calling BasePermissionApi->savePermission: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**PermissionServiceModel**](PermissionServiceModel.md)|  | [optional] 

### Return type

[**PermissionServiceModel**](PermissionServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

