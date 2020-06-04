# api_client.api.BaseShipmentStatusCodeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteShipmentStatusCode**](BaseShipmentStatusCodeApi.md#deleteShipmentStatusCode) | **POST** /deleteShipmentStatusCode | 
[**getShipmentStatusCode**](BaseShipmentStatusCodeApi.md#getShipmentStatusCode) | **GET** /getShipmentStatusCode | 
[**getShipmentStatusCodes**](BaseShipmentStatusCodeApi.md#getShipmentStatusCodes) | **POST** /getShipmentStatusCodes | 
[**saveShipmentStatusCode**](BaseShipmentStatusCodeApi.md#saveShipmentStatusCode) | **POST** /saveShipmentStatusCode | 


# **deleteShipmentStatusCode**
> deleteShipmentStatusCode(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentStatusCodeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteShipmentStatusCode(id);
} catch (e) {
    print("Exception when calling BaseShipmentStatusCodeApi->deleteShipmentStatusCode: $e\n");
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

# **getShipmentStatusCode**
> ShipmentStatusCodeServiceModel getShipmentStatusCode(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentStatusCodeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getShipmentStatusCode(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentStatusCodeApi->getShipmentStatusCode: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**ShipmentStatusCodeServiceModel**](ShipmentStatusCodeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getShipmentStatusCodes**
> QueryResultShipmentStatusCodeServiceModel getShipmentStatusCodes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentStatusCodeApi();
var request = new ShipmentStatusCodeQueryRequest(); // ShipmentStatusCodeQueryRequest | 

try { 
    var result = api_instance.getShipmentStatusCodes(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentStatusCodeApi->getShipmentStatusCodes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipmentStatusCodeQueryRequest**](ShipmentStatusCodeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultShipmentStatusCodeServiceModel**](QueryResultShipmentStatusCodeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveShipmentStatusCode**
> ShipmentStatusCodeServiceModel saveShipmentStatusCode(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentStatusCodeApi();
var model = new ShipmentStatusCodeServiceModel(); // ShipmentStatusCodeServiceModel | 

try { 
    var result = api_instance.saveShipmentStatusCode(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentStatusCodeApi->saveShipmentStatusCode: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ShipmentStatusCodeServiceModel**](ShipmentStatusCodeServiceModel.md)|  | [optional] 

### Return type

[**ShipmentStatusCodeServiceModel**](ShipmentStatusCodeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

