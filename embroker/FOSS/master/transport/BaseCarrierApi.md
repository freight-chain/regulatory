# api_client.api.BaseCarrierApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteCarrier**](BaseCarrierApi.md#deleteCarrier) | **POST** /deleteCarrier | 
[**getCarrier**](BaseCarrierApi.md#getCarrier) | **GET** /getCarrier | 
[**getCarriers**](BaseCarrierApi.md#getCarriers) | **POST** /getCarriers | 
[**saveCarrier**](BaseCarrierApi.md#saveCarrier) | **POST** /saveCarrier | 


# **deleteCarrier**
> deleteCarrier(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCarrierApi();
var id = id_example; // String | 

try { 
    api_instance.deleteCarrier(id);
} catch (e) {
    print("Exception when calling BaseCarrierApi->deleteCarrier: $e\n");
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

# **getCarrier**
> CarrierServiceModel getCarrier(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCarrierApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getCarrier(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseCarrierApi->getCarrier: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**CarrierServiceModel**](CarrierServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCarriers**
> QueryResultCarrierServiceModel getCarriers(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCarrierApi();
var request = new CarrierQueryRequest(); // CarrierQueryRequest | 

try { 
    var result = api_instance.getCarriers(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseCarrierApi->getCarriers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CarrierQueryRequest**](CarrierQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultCarrierServiceModel**](QueryResultCarrierServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveCarrier**
> CarrierServiceModel saveCarrier(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCarrierApi();
var model = new CarrierServiceModel(); // CarrierServiceModel | 

try { 
    var result = api_instance.saveCarrier(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseCarrierApi->saveCarrier: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**CarrierServiceModel**](CarrierServiceModel.md)|  | [optional] 

### Return type

[**CarrierServiceModel**](CarrierServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

