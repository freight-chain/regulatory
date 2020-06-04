# api_client.api.BaseDriverSafetyApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getDriverSafety**](BaseDriverSafetyApi.md#getDriverSafety) | **GET** /getDriverSafety | 


# **getDriverSafety**
> DriverSafetyServiceModel getDriverSafety(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDriverSafetyApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getDriverSafety(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseDriverSafetyApi->getDriverSafety: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**DriverSafetyServiceModel**](DriverSafetyServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

