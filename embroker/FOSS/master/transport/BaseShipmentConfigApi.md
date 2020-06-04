# api_client.api.BaseShipmentConfigApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getShipmentConfig**](BaseShipmentConfigApi.md#getShipmentConfig) | **GET** /getShipmentConfig | 
[**saveShipmentConfig**](BaseShipmentConfigApi.md#saveShipmentConfig) | **POST** /saveShipmentConfig | 


# **getShipmentConfig**
> ShipmentConfigServiceModel getShipmentConfig(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentConfigApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getShipmentConfig(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentConfigApi->getShipmentConfig: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**ShipmentConfigServiceModel**](ShipmentConfigServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveShipmentConfig**
> ShipmentConfigServiceModel saveShipmentConfig(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentConfigApi();
var model = new ShipmentConfigServiceModel(); // ShipmentConfigServiceModel | 

try { 
    var result = api_instance.saveShipmentConfig(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentConfigApi->saveShipmentConfig: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ShipmentConfigServiceModel**](ShipmentConfigServiceModel.md)|  | [optional] 

### Return type

[**ShipmentConfigServiceModel**](ShipmentConfigServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

