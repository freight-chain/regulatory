# api_client.api.BaseUserApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteUser**](BaseUserApi.md#deleteUser) | **POST** /deleteUser | 
[**getUser**](BaseUserApi.md#getUser) | **GET** /getUser | 
[**getUsers**](BaseUserApi.md#getUsers) | **POST** /getUsers | 
[**saveUser**](BaseUserApi.md#saveUser) | **POST** /saveUser | 


# **deleteUser**
> deleteUser(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseUserApi();
var id = id_example; // String | 

try { 
    api_instance.deleteUser(id);
} catch (e) {
    print("Exception when calling BaseUserApi->deleteUser: $e\n");
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

# **getUser**
> UserServiceModel getUser(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseUserApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getUser(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseUserApi->getUser: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**UserServiceModel**](UserServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUsers**
> QueryResultUserServiceModel getUsers(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseUserApi();
var request = new UserQueryRequest(); // UserQueryRequest | 

try { 
    var result = api_instance.getUsers(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseUserApi->getUsers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**UserQueryRequest**](UserQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultUserServiceModel**](QueryResultUserServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveUser**
> UserServiceModel saveUser(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseUserApi();
var model = new UserServiceModel(); // UserServiceModel | 

try { 
    var result = api_instance.saveUser(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseUserApi->saveUser: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**UserServiceModel**](UserServiceModel.md)|  | [optional] 

### Return type

[**UserServiceModel**](UserServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

