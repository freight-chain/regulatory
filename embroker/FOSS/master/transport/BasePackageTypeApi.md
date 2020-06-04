# api_client.api.BasePackageTypeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deletePackageType**](BasePackageTypeApi.md#deletePackageType) | **POST** /deletePackageType | 
[**getPackageType**](BasePackageTypeApi.md#getPackageType) | **GET** /getPackageType | 
[**getPackageTypes**](BasePackageTypeApi.md#getPackageTypes) | **POST** /getPackageTypes | 
[**savePackageType**](BasePackageTypeApi.md#savePackageType) | **POST** /savePackageType | 


# **deletePackageType**
> deletePackageType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BasePackageTypeApi();
var id = id_example; // String | 

try { 
    api_instance.deletePackageType(id);
} catch (e) {
    print("Exception when calling BasePackageTypeApi->deletePackageType: $e\n");
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

# **getPackageType**
> PackageTypeServiceModel getPackageType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BasePackageTypeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getPackageType(id);
    print(result);
} catch (e) {
    print("Exception when calling BasePackageTypeApi->getPackageType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**PackageTypeServiceModel**](PackageTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getPackageTypes**
> QueryResultPackageTypeServiceModel getPackageTypes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BasePackageTypeApi();
var request = new PackageTypeQueryRequest(); // PackageTypeQueryRequest | 

try { 
    var result = api_instance.getPackageTypes(request);
    print(result);
} catch (e) {
    print("Exception when calling BasePackageTypeApi->getPackageTypes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**PackageTypeQueryRequest**](PackageTypeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultPackageTypeServiceModel**](QueryResultPackageTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **savePackageType**
> PackageTypeServiceModel savePackageType(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BasePackageTypeApi();
var model = new PackageTypeServiceModel(); // PackageTypeServiceModel | 

try { 
    var result = api_instance.savePackageType(model);
    print(result);
} catch (e) {
    print("Exception when calling BasePackageTypeApi->savePackageType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**PackageTypeServiceModel**](PackageTypeServiceModel.md)|  | [optional] 

### Return type

[**PackageTypeServiceModel**](PackageTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

