# api_client.api.BaseInvoiceItemApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteInvoiceItem**](BaseInvoiceItemApi.md#deleteInvoiceItem) | **POST** /deleteInvoiceItem | 
[**getInvoiceItem**](BaseInvoiceItemApi.md#getInvoiceItem) | **GET** /getInvoiceItem | 
[**getInvoiceItems**](BaseInvoiceItemApi.md#getInvoiceItems) | **POST** /getInvoiceItems | 
[**saveInvoiceItem**](BaseInvoiceItemApi.md#saveInvoiceItem) | **POST** /saveInvoiceItem | 


# **deleteInvoiceItem**
> deleteInvoiceItem(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceItemApi();
var id = id_example; // String | 

try { 
    api_instance.deleteInvoiceItem(id);
} catch (e) {
    print("Exception when calling BaseInvoiceItemApi->deleteInvoiceItem: $e\n");
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

# **getInvoiceItem**
> InvoiceItemServiceModel getInvoiceItem(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceItemApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getInvoiceItem(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceItemApi->getInvoiceItem: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**InvoiceItemServiceModel**](InvoiceItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getInvoiceItems**
> QueryResultInvoiceItemServiceModel getInvoiceItems(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceItemApi();
var request = new InvoiceItemQueryRequest(); // InvoiceItemQueryRequest | 

try { 
    var result = api_instance.getInvoiceItems(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceItemApi->getInvoiceItems: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**InvoiceItemQueryRequest**](InvoiceItemQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultInvoiceItemServiceModel**](QueryResultInvoiceItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveInvoiceItem**
> InvoiceItemServiceModel saveInvoiceItem(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceItemApi();
var model = new InvoiceItemServiceModel(); // InvoiceItemServiceModel | 

try { 
    var result = api_instance.saveInvoiceItem(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceItemApi->saveInvoiceItem: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**InvoiceItemServiceModel**](InvoiceItemServiceModel.md)|  | [optional] 

### Return type

[**InvoiceItemServiceModel**](InvoiceItemServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

