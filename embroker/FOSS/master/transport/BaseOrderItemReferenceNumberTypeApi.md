# api_client.api.BaseOrderItemReferenceNumberTypeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteOrderItemReferenceNumberType**](BaseOrderItemReferenceNumberTypeApi.md#deleteOrderItemReferenceNumberType) | **POST** /deleteOrderItemReferenceNumberType | 
[**getOrderItemReferenceNumberType**](BaseOrderItemReferenceNumberTypeApi.md#getOrderItemReferenceNumberType) | **GET** /getOrderItemReferenceNumberType | 
[**getOrderItemReferenceNumberTypes**](BaseOrderItemReferenceNumberTypeApi.md#getOrderItemReferenceNumberTypes) | **POST** /getOrderItemReferenceNumberTypes | 
[**saveOrderItemReferenceNumberType**](BaseOrderItemReferenceNumberTypeApi.md#saveOrderItemReferenceNumberType) | **POST** /saveOrderItemReferenceNumberType | 


# **deleteOrderItemReferenceNumberType**
> deleteOrderItemReferenceNumberType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseOrderItemReferenceNumberTypeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteOrderItemReferenceNumberType(id);
} catch (e) {
    print("Exception when calling BaseOrderItemReferenceNumberTypeApi->deleteOrderItemReferenceNumberType: $e\n");
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

# **getOrderItemReferenceNumberType**
> OrderItemReferenceNumberTypeServiceModel getOrderItemReferenceNumberType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseOrderItemReferenceNumberTypeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getOrderItemReferenceNumberType(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseOrderItemReferenceNumberTypeApi->getOrderItemReferenceNumberType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**OrderItemReferenceNumberTypeServiceModel**](OrderItemReferenceNumberTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getOrderItemReferenceNumberTypes**
> QueryResultOrderItemReferenceNumberTypeServiceModel getOrderItemReferenceNumberTypes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseOrderItemReferenceNumberTypeApi();
var request = new OrderItemReferenceNumberTypeQueryRequest(); // OrderItemReferenceNumberTypeQueryRequest | 

try { 
    var result = api_instance.getOrderItemReferenceNumberTypes(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseOrderItemReferenceNumberTypeApi->getOrderItemReferenceNumberTypes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**OrderItemReferenceNumberTypeQueryRequest**](OrderItemReferenceNumberTypeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultOrderItemReferenceNumberTypeServiceModel**](QueryResultOrderItemReferenceNumberTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveOrderItemReferenceNumberType**
> OrderItemReferenceNumberTypeServiceModel saveOrderItemReferenceNumberType(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseOrderItemReferenceNumberTypeApi();
var model = new OrderItemReferenceNumberTypeServiceModel(); // OrderItemReferenceNumberTypeServiceModel | 

try { 
    var result = api_instance.saveOrderItemReferenceNumberType(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseOrderItemReferenceNumberTypeApi->saveOrderItemReferenceNumberType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**OrderItemReferenceNumberTypeServiceModel**](OrderItemReferenceNumberTypeServiceModel.md)|  | [optional] 

### Return type

[**OrderItemReferenceNumberTypeServiceModel**](OrderItemReferenceNumberTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

