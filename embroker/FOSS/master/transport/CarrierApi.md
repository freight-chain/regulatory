# api_client.api.CarrierApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteCarrier**](CarrierApi.md#deleteCarrier) | **POST** /api/Carrier/deleteCarrier | 
[**getCarrier**](CarrierApi.md#getCarrier) | **GET** /api/Carrier/getCarrier | 
[**getCarriers**](CarrierApi.md#getCarriers) | **POST** /api/Carrier/getCarriers | 
[**saveCarrier**](CarrierApi.md#saveCarrier) | **POST** /api/Carrier/saveCarrier | 


# **deleteCarrier**
> deleteCarrier(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierApi();
var id = id_example; // String | 

try { 
    api_instance.deleteCarrier(id);
} catch (e) {
    print("Exception when calling CarrierApi->deleteCarrier: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCarrier**
> CarrierServiceModel getCarrier(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getCarrier(id);
    print(result);
} catch (e) {
    print("Exception when calling CarrierApi->getCarrier: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**CarrierServiceModel**](CarrierServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCarriers**
> QueryResultCarrierServiceModel getCarriers(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierApi();
var request = new CarrierQueryRequest(); // CarrierQueryRequest | 

try { 
    var result = api_instance.getCarriers(request);
    print(result);
} catch (e) {
    print("Exception when calling CarrierApi->getCarriers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CarrierQueryRequest**](CarrierQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultCarrierServiceModel**](QueryResultCarrierServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveCarrier**
> CarrierServiceModel saveCarrier(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierApi();
var model = new CarrierServiceModel(); // CarrierServiceModel | 

try { 
    var result = api_instance.saveCarrier(model);
    print(result);
} catch (e) {
    print("Exception when calling CarrierApi->saveCarrier: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**CarrierServiceModel**](CarrierServiceModel.md)|  | [optional] 

### Return type

[**CarrierServiceModel**](CarrierServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

