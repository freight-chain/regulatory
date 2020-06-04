# api_client.api.BaseShipmentDriverDispatchApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getShipmentDriverDispatches**](BaseShipmentDriverDispatchApi.md#getShipmentDriverDispatches) | **POST** /getShipmentDriverDispatches | 


# **getShipmentDriverDispatches**
> QueryResultShipmentDriverDispatchServiceModel getShipmentDriverDispatches(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentDriverDispatchApi();
var request = new ShipmentDriverDispatchQueryRequest(); // ShipmentDriverDispatchQueryRequest | 

try { 
    var result = api_instance.getShipmentDriverDispatches(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentDriverDispatchApi->getShipmentDriverDispatches: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipmentDriverDispatchQueryRequest**](ShipmentDriverDispatchQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultShipmentDriverDispatchServiceModel**](QueryResultShipmentDriverDispatchServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

