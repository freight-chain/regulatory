# api_client.api.BaseDriverApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteDriver**](BaseDriverApi.md#deleteDriver) | **POST** /deleteDriver | 
[**getDriver**](BaseDriverApi.md#getDriver) | **GET** /getDriver | 
[**getDrivers**](BaseDriverApi.md#getDrivers) | **POST** /getDrivers | 
[**saveDriver**](BaseDriverApi.md#saveDriver) | **POST** /saveDriver | 


# **deleteDriver**
> deleteDriver(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDriverApi();
var id = id_example; // String | 

try { 
    api_instance.deleteDriver(id);
} catch (e) {
    print("Exception when calling BaseDriverApi->deleteDriver: $e\n");
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

# **getDriver**
> DriverServiceModel getDriver(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDriverApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getDriver(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseDriverApi->getDriver: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**DriverServiceModel**](DriverServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getDrivers**
> QueryResultDriverServiceModel getDrivers(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDriverApi();
var request = new DriverQueryRequest(); // DriverQueryRequest | 

try { 
    var result = api_instance.getDrivers(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseDriverApi->getDrivers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**DriverQueryRequest**](DriverQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultDriverServiceModel**](QueryResultDriverServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveDriver**
> DriverServiceModel saveDriver(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDriverApi();
var model = new DriverServiceModel(); // DriverServiceModel | 

try { 
    var result = api_instance.saveDriver(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseDriverApi->saveDriver: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**DriverServiceModel**](DriverServiceModel.md)|  | [optional] 

### Return type

[**DriverServiceModel**](DriverServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

