# api_client.api.BaseSaferCarrierApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteSaferCarrier**](BaseSaferCarrierApi.md#deleteSaferCarrier) | **POST** /deleteSaferCarrier | 
[**getSaferCarrier**](BaseSaferCarrierApi.md#getSaferCarrier) | **GET** /getSaferCarrier | 
[**getSaferCarriers**](BaseSaferCarrierApi.md#getSaferCarriers) | **POST** /getSaferCarriers | 
[**saveSaferCarrier**](BaseSaferCarrierApi.md#saveSaferCarrier) | **POST** /saveSaferCarrier | 


# **deleteSaferCarrier**
> deleteSaferCarrier(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseSaferCarrierApi();
var id = id_example; // String | 

try { 
    api_instance.deleteSaferCarrier(id);
} catch (e) {
    print("Exception when calling BaseSaferCarrierApi->deleteSaferCarrier: $e\n");
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

# **getSaferCarrier**
> SaferCarrierServiceModel getSaferCarrier(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseSaferCarrierApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getSaferCarrier(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseSaferCarrierApi->getSaferCarrier: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**SaferCarrierServiceModel**](SaferCarrierServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSaferCarriers**
> QueryResultSaferCarrierServiceModel getSaferCarriers(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseSaferCarrierApi();
var request = new SaferCarrierQueryRequest(); // SaferCarrierQueryRequest | 

try { 
    var result = api_instance.getSaferCarriers(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseSaferCarrierApi->getSaferCarriers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**SaferCarrierQueryRequest**](SaferCarrierQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultSaferCarrierServiceModel**](QueryResultSaferCarrierServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveSaferCarrier**
> SaferCarrierServiceModel saveSaferCarrier(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseSaferCarrierApi();
var model = new SaferCarrierServiceModel(); // SaferCarrierServiceModel | 

try { 
    var result = api_instance.saveSaferCarrier(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseSaferCarrierApi->saveSaferCarrier: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**SaferCarrierServiceModel**](SaferCarrierServiceModel.md)|  | [optional] 

### Return type

[**SaferCarrierServiceModel**](SaferCarrierServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

