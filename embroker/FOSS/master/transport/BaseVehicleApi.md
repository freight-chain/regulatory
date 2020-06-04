# api_client.api.BaseVehicleApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteVehicle**](BaseVehicleApi.md#deleteVehicle) | **POST** /deleteVehicle | 
[**getVehicle**](BaseVehicleApi.md#getVehicle) | **GET** /getVehicle | 
[**getVehicles**](BaseVehicleApi.md#getVehicles) | **POST** /getVehicles | 
[**saveVehicle**](BaseVehicleApi.md#saveVehicle) | **POST** /saveVehicle | 


# **deleteVehicle**
> deleteVehicle(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseVehicleApi();
var id = id_example; // String | 

try { 
    api_instance.deleteVehicle(id);
} catch (e) {
    print("Exception when calling BaseVehicleApi->deleteVehicle: $e\n");
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

# **getVehicle**
> VehicleServiceModel getVehicle(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseVehicleApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getVehicle(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseVehicleApi->getVehicle: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**VehicleServiceModel**](VehicleServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getVehicles**
> QueryResultVehicleServiceModel getVehicles(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseVehicleApi();
var request = new VehicleQueryRequest(); // VehicleQueryRequest | 

try { 
    var result = api_instance.getVehicles(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseVehicleApi->getVehicles: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**VehicleQueryRequest**](VehicleQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultVehicleServiceModel**](QueryResultVehicleServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveVehicle**
> VehicleServiceModel saveVehicle(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseVehicleApi();
var model = new VehicleServiceModel(); // VehicleServiceModel | 

try { 
    var result = api_instance.saveVehicle(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseVehicleApi->saveVehicle: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**VehicleServiceModel**](VehicleServiceModel.md)|  | [optional] 

### Return type

[**VehicleServiceModel**](VehicleServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

