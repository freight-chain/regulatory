# api_client.api.BaseOrderItemApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteOrderItem**](BaseOrderItemApi.md#deleteOrderItem) | **POST** /deleteOrderItem | 
[**getOrderItem**](BaseOrderItemApi.md#getOrderItem) | **GET** /getOrderItem | 
[**getOrderItems**](BaseOrderItemApi.md#getOrderItems) | **POST** /getOrderItems | 
[**saveOrderItem**](BaseOrderItemApi.md#saveOrderItem) | **POST** /saveOrderItem | 


# **deleteOrderItem**
> deleteOrderItem(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseOrderItemApi();
var id = id_example; // String | 

try { 
    api_instance.deleteOrderItem(id);
} catch (e) {
    print("Exception when calling BaseOrderItemApi->deleteOrderItem: $e\n");
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

# **getOrderItem**
> OrderItemServiceModel getOrderItem(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseOrderItemApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getOrderItem(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseOrderItemApi->getOrderItem: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**OrderItemServiceModel**](OrderItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getOrderItems**
> QueryResultOrderItemServiceModel getOrderItems(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseOrderItemApi();
var request = new OrderItemQueryRequest(); // OrderItemQueryRequest | 

try { 
    var result = api_instance.getOrderItems(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseOrderItemApi->getOrderItems: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**OrderItemQueryRequest**](OrderItemQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultOrderItemServiceModel**](QueryResultOrderItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveOrderItem**
> OrderItemServiceModel saveOrderItem(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseOrderItemApi();
var model = new OrderItemServiceModel(); // OrderItemServiceModel | 

try { 
    var result = api_instance.saveOrderItem(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseOrderItemApi->saveOrderItem: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**OrderItemServiceModel**](OrderItemServiceModel.md)|  | [optional] 

### Return type

[**OrderItemServiceModel**](OrderItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

