# api_client.api.BaseRoleClaimApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteRoleClaim**](BaseRoleClaimApi.md#deleteRoleClaim) | **POST** /deleteRoleClaim | 
[**getRoleClaim**](BaseRoleClaimApi.md#getRoleClaim) | **GET** /getRoleClaim | 
[**getRoleClaims**](BaseRoleClaimApi.md#getRoleClaims) | **POST** /getRoleClaims | 
[**saveRoleClaim**](BaseRoleClaimApi.md#saveRoleClaim) | **POST** /saveRoleClaim | 


# **deleteRoleClaim**
> deleteRoleClaim(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleClaimApi();
var id = id_example; // String | 

try { 
    api_instance.deleteRoleClaim(id);
} catch (e) {
    print("Exception when calling BaseRoleClaimApi->deleteRoleClaim: $e\n");
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

# **getRoleClaim**
> RoleClaimServiceModel getRoleClaim(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleClaimApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getRoleClaim(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseRoleClaimApi->getRoleClaim: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**RoleClaimServiceModel**](RoleClaimServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRoleClaims**
> QueryResultRoleClaimServiceModel getRoleClaims(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleClaimApi();
var request = new RoleClaimQueryRequest(); // RoleClaimQueryRequest | 

try { 
    var result = api_instance.getRoleClaims(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseRoleClaimApi->getRoleClaims: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**RoleClaimQueryRequest**](RoleClaimQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultRoleClaimServiceModel**](QueryResultRoleClaimServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveRoleClaim**
> RoleClaimServiceModel saveRoleClaim(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseRoleClaimApi();
var model = new RoleClaimServiceModel(); // RoleClaimServiceModel | 

try { 
    var result = api_instance.saveRoleClaim(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseRoleClaimApi->saveRoleClaim: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**RoleClaimServiceModel**](RoleClaimServiceModel.md)|  | [optional] 

### Return type

[**RoleClaimServiceModel**](RoleClaimServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

