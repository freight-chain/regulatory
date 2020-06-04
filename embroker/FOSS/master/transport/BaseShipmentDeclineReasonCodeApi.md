# api_client.api.BaseShipmentDeclineReasonCodeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteShipmentDeclineReasonCode**](BaseShipmentDeclineReasonCodeApi.md#deleteShipmentDeclineReasonCode) | **POST** /deleteShipmentDeclineReasonCode | 
[**getShipmentDeclineReasonCode**](BaseShipmentDeclineReasonCodeApi.md#getShipmentDeclineReasonCode) | **GET** /getShipmentDeclineReasonCode | 
[**getShipmentDeclineReasonCodes**](BaseShipmentDeclineReasonCodeApi.md#getShipmentDeclineReasonCodes) | **POST** /getShipmentDeclineReasonCodes | 
[**saveShipmentDeclineReasonCode**](BaseShipmentDeclineReasonCodeApi.md#saveShipmentDeclineReasonCode) | **POST** /saveShipmentDeclineReasonCode | 


# **deleteShipmentDeclineReasonCode**
> deleteShipmentDeclineReasonCode(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentDeclineReasonCodeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteShipmentDeclineReasonCode(id);
} catch (e) {
    print("Exception when calling BaseShipmentDeclineReasonCodeApi->deleteShipmentDeclineReasonCode: $e\n");
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

# **getShipmentDeclineReasonCode**
> ShipmentDeclineReasonCodeServiceModel getShipmentDeclineReasonCode(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentDeclineReasonCodeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getShipmentDeclineReasonCode(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentDeclineReasonCodeApi->getShipmentDeclineReasonCode: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**ShipmentDeclineReasonCodeServiceModel**](ShipmentDeclineReasonCodeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getShipmentDeclineReasonCodes**
> QueryResultShipmentDeclineReasonCodeServiceModel getShipmentDeclineReasonCodes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentDeclineReasonCodeApi();
var request = new ShipmentDeclineReasonCodeQueryRequest(); // ShipmentDeclineReasonCodeQueryRequest | 

try { 
    var result = api_instance.getShipmentDeclineReasonCodes(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentDeclineReasonCodeApi->getShipmentDeclineReasonCodes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipmentDeclineReasonCodeQueryRequest**](ShipmentDeclineReasonCodeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultShipmentDeclineReasonCodeServiceModel**](QueryResultShipmentDeclineReasonCodeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveShipmentDeclineReasonCode**
> ShipmentDeclineReasonCodeServiceModel saveShipmentDeclineReasonCode(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentDeclineReasonCodeApi();
var model = new ShipmentDeclineReasonCodeServiceModel(); // ShipmentDeclineReasonCodeServiceModel | 

try { 
    var result = api_instance.saveShipmentDeclineReasonCode(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentDeclineReasonCodeApi->saveShipmentDeclineReasonCode: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ShipmentDeclineReasonCodeServiceModel**](ShipmentDeclineReasonCodeServiceModel.md)|  | [optional] 

### Return type

[**ShipmentDeclineReasonCodeServiceModel**](ShipmentDeclineReasonCodeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

