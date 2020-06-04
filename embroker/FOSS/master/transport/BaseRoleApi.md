# api_client.api.BaseRoleApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addPermission**](BaseRoleApi.md#addPermission) | **POST** /addPermission | 
[**addUser**](BaseRoleApi.md#addUser) | **POST** /addUser | 
[**deleteRole**](BaseRoleApi.md#deleteRole) | **POST** /deleteRole | 
[**getRole**](BaseRoleApi.md#getRole) | **GET** /getRole | 
[**getRoles**](BaseRoleApi.md#getRoles) | **POST** /getRoles | 
[**saveRole**](BaseRoleApi.md#saveRole) | **POST** /saveRole | 


# **addPermission**
> RoleServiceModel addPermission(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleApi();
var request = new AddPermissionRequest(); // AddPermissionRequest | 

try { 
    var result = api_instance.addPermission(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseRoleApi->addPermission: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**AddPermissionRequest**](AddPermissionRequest.md)|  | [optional] 

### Return type

[**RoleServiceModel**](RoleServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **addUser**
> RoleServiceModel addUser(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleApi();
var request = new AddUserRequest(); // AddUserRequest | 

try { 
    var result = api_instance.addUser(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseRoleApi->addUser: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**AddUserRequest**](AddUserRequest.md)|  | [optional] 

### Return type

[**RoleServiceModel**](RoleServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteRole**
> deleteRole(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleApi();
var id = id_example; // String | 

try { 
    api_instance.deleteRole(id);
} catch (e) {
    print("Exception when calling BaseRoleApi->deleteRole: $e\n");
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

# **getRole**
> RoleServiceModel getRole(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getRole(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseRoleApi->getRole: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**RoleServiceModel**](RoleServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRoles**
> QueryResultRoleServiceModel getRoles(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleApi();
var request = new RoleQueryRequest(); // RoleQueryRequest | 

try { 
    var result = api_instance.getRoles(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseRoleApi->getRoles: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**RoleQueryRequest**](RoleQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultRoleServiceModel**](QueryResultRoleServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveRole**
> RoleServiceModel saveRole(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleApi();
var model = new RoleServiceModel(); // RoleServiceModel | 

try { 
    var result = api_instance.saveRole(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseRoleApi->saveRole: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**RoleServiceModel**](RoleServiceModel.md)|  | [optional] 

### Return type

[**RoleServiceModel**](RoleServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

