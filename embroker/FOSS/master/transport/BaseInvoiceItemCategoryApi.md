# api_client.api.BaseInvoiceItemCategoryApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteInvoiceItemCategory**](BaseInvoiceItemCategoryApi.md#deleteInvoiceItemCategory) | **POST** /deleteInvoiceItemCategory | 
[**getInvoiceItemCategories**](BaseInvoiceItemCategoryApi.md#getInvoiceItemCategories) | **POST** /getInvoiceItemCategories | 
[**getInvoiceItemCategory**](BaseInvoiceItemCategoryApi.md#getInvoiceItemCategory) | **GET** /getInvoiceItemCategory | 
[**saveInvoiceItemCategory**](BaseInvoiceItemCategoryApi.md#saveInvoiceItemCategory) | **POST** /saveInvoiceItemCategory | 


# **deleteInvoiceItemCategory**
> deleteInvoiceItemCategory(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceItemCategoryApi();
var id = id_example; // String | 

try { 
    api_instance.deleteInvoiceItemCategory(id);
} catch (e) {
    print("Exception when calling BaseInvoiceItemCategoryApi->deleteInvoiceItemCategory: $e\n");
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

# **getInvoiceItemCategories**
> QueryResultInvoiceItemCategoryServiceModel getInvoiceItemCategories(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceItemCategoryApi();
var request = new InvoiceItemCategoryQueryRequest(); // InvoiceItemCategoryQueryRequest | 

try { 
    var result = api_instance.getInvoiceItemCategories(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceItemCategoryApi->getInvoiceItemCategories: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**InvoiceItemCategoryQueryRequest**](InvoiceItemCategoryQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultInvoiceItemCategoryServiceModel**](QueryResultInvoiceItemCategoryServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getInvoiceItemCategory**
> InvoiceItemCategoryServiceModel getInvoiceItemCategory(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceItemCategoryApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getInvoiceItemCategory(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceItemCategoryApi->getInvoiceItemCategory: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**InvoiceItemCategoryServiceModel**](InvoiceItemCategoryServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveInvoiceItemCategory**
> InvoiceItemCategoryServiceModel saveInvoiceItemCategory(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceItemCategoryApi();
var model = new InvoiceItemCategoryServiceModel(); // InvoiceItemCategoryServiceModel | 

try { 
    var result = api_instance.saveInvoiceItemCategory(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceItemCategoryApi->saveInvoiceItemCategory: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**InvoiceItemCategoryServiceModel**](InvoiceItemCategoryServiceModel.md)|  | [optional] 

### Return type

[**InvoiceItemCategoryServiceModel**](InvoiceItemCategoryServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

