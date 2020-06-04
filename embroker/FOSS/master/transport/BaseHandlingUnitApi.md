# api_client.api.BaseHandlingUnitApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteHandlingUnit**](BaseHandlingUnitApi.md#deleteHandlingUnit) | **POST** /deleteHandlingUnit | 
[**getHandlingUnit**](BaseHandlingUnitApi.md#getHandlingUnit) | **GET** /getHandlingUnit | 
[**getHandlingUnits**](BaseHandlingUnitApi.md#getHandlingUnits) | **POST** /getHandlingUnits | 
[**saveHandlingUnit**](BaseHandlingUnitApi.md#saveHandlingUnit) | **POST** /saveHandlingUnit | 


# **deleteHandlingUnit**
> deleteHandlingUnit(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseHandlingUnitApi();
var id = id_example; // String | 

try { 
    api_instance.deleteHandlingUnit(id);
} catch (e) {
    print("Exception when calling BaseHandlingUnitApi->deleteHandlingUnit: $e\n");
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

# **getHandlingUnit**
> HandlingUnitServiceModel getHandlingUnit(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseHandlingUnitApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getHandlingUnit(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseHandlingUnitApi->getHandlingUnit: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**HandlingUnitServiceModel**](HandlingUnitServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getHandlingUnits**
> QueryResultHandlingUnitServiceModel getHandlingUnits(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseHandlingUnitApi();
var request = new HandlingUnitQueryRequest(); // HandlingUnitQueryRequest | 

try { 
    var result = api_instance.getHandlingUnits(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseHandlingUnitApi->getHandlingUnits: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**HandlingUnitQueryRequest**](HandlingUnitQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultHandlingUnitServiceModel**](QueryResultHandlingUnitServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveHandlingUnit**
> HandlingUnitServiceModel saveHandlingUnit(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseHandlingUnitApi();
var model = new HandlingUnitServiceModel(); // HandlingUnitServiceModel | 

try { 
    var result = api_instance.saveHandlingUnit(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseHandlingUnitApi->saveHandlingUnit: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**HandlingUnitServiceModel**](HandlingUnitServiceModel.md)|  | [optional] 

### Return type

[**HandlingUnitServiceModel**](HandlingUnitServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

