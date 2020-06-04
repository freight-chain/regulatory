# api_client.api.BaseShipmentStatusUpdateTypeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteShipmentStatusUpdateType**](BaseShipmentStatusUpdateTypeApi.md#deleteShipmentStatusUpdateType) | **POST** /deleteShipmentStatusUpdateType | 
[**getShipmentStatusUpdateType**](BaseShipmentStatusUpdateTypeApi.md#getShipmentStatusUpdateType) | **GET** /getShipmentStatusUpdateType | 
[**getShipmentStatusUpdateTypes**](BaseShipmentStatusUpdateTypeApi.md#getShipmentStatusUpdateTypes) | **POST** /getShipmentStatusUpdateTypes | 
[**saveShipmentStatusUpdateType**](BaseShipmentStatusUpdateTypeApi.md#saveShipmentStatusUpdateType) | **POST** /saveShipmentStatusUpdateType | 


# **deleteShipmentStatusUpdateType**
> deleteShipmentStatusUpdateType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentStatusUpdateTypeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteShipmentStatusUpdateType(id);
} catch (e) {
    print("Exception when calling BaseShipmentStatusUpdateTypeApi->deleteShipmentStatusUpdateType: $e\n");
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

# **getShipmentStatusUpdateType**
> ShipmentStatusUpdateTypeServiceModel getShipmentStatusUpdateType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentStatusUpdateTypeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getShipmentStatusUpdateType(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentStatusUpdateTypeApi->getShipmentStatusUpdateType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**ShipmentStatusUpdateTypeServiceModel**](ShipmentStatusUpdateTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getShipmentStatusUpdateTypes**
> QueryResultShipmentStatusUpdateTypeServiceModel getShipmentStatusUpdateTypes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentStatusUpdateTypeApi();
var request = new ShipmentStatusUpdateTypeQueryRequest(); // ShipmentStatusUpdateTypeQueryRequest | 

try { 
    var result = api_instance.getShipmentStatusUpdateTypes(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentStatusUpdateTypeApi->getShipmentStatusUpdateTypes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipmentStatusUpdateTypeQueryRequest**](ShipmentStatusUpdateTypeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultShipmentStatusUpdateTypeServiceModel**](QueryResultShipmentStatusUpdateTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveShipmentStatusUpdateType**
> ShipmentStatusUpdateTypeServiceModel saveShipmentStatusUpdateType(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentStatusUpdateTypeApi();
var model = new ShipmentStatusUpdateTypeServiceModel(); // ShipmentStatusUpdateTypeServiceModel | 

try { 
    var result = api_instance.saveShipmentStatusUpdateType(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentStatusUpdateTypeApi->saveShipmentStatusUpdateType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ShipmentStatusUpdateTypeServiceModel**](ShipmentStatusUpdateTypeServiceModel.md)|  | [optional] 

### Return type

[**ShipmentStatusUpdateTypeServiceModel**](ShipmentStatusUpdateTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

