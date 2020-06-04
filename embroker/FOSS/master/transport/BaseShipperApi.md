# api_client.api.BaseShipperApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteShipper**](BaseShipperApi.md#deleteShipper) | **POST** /deleteShipper | 
[**getShipper**](BaseShipperApi.md#getShipper) | **GET** /getShipper | 
[**getShippers**](BaseShipperApi.md#getShippers) | **POST** /getShippers | 
[**saveShipper**](BaseShipperApi.md#saveShipper) | **POST** /saveShipper | 


# **deleteShipper**
> deleteShipper(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipperApi();
var id = id_example; // String | 

try { 
    api_instance.deleteShipper(id);
} catch (e) {
    print("Exception when calling BaseShipperApi->deleteShipper: $e\n");
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

# **getShipper**
> ShipperServiceModel getShipper(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipperApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getShipper(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipperApi->getShipper: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**ShipperServiceModel**](ShipperServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getShippers**
> QueryResultShipperServiceModel getShippers(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipperApi();
var request = new ShipperQueryRequest(); // ShipperQueryRequest | 

try { 
    var result = api_instance.getShippers(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipperApi->getShippers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipperQueryRequest**](ShipperQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultShipperServiceModel**](QueryResultShipperServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveShipper**
> ShipperServiceModel saveShipper(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipperApi();
var model = new ShipperServiceModel(); // ShipperServiceModel | 

try { 
    var result = api_instance.saveShipper(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipperApi->saveShipper: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ShipperServiceModel**](ShipperServiceModel.md)|  | [optional] 

### Return type

[**ShipperServiceModel**](ShipperServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

