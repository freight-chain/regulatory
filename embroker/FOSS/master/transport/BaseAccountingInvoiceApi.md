# api_client.api.BaseAccountingInvoiceApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteAccountingInvoice**](BaseAccountingInvoiceApi.md#deleteAccountingInvoice) | **POST** /deleteAccountingInvoice | 
[**getAccountingInvoice**](BaseAccountingInvoiceApi.md#getAccountingInvoice) | **GET** /getAccountingInvoice | 
[**getAccountingInvoices**](BaseAccountingInvoiceApi.md#getAccountingInvoices) | **POST** /getAccountingInvoices | 
[**saveAccountingInvoice**](BaseAccountingInvoiceApi.md#saveAccountingInvoice) | **POST** /saveAccountingInvoice | 
[**sendInvoice**](BaseAccountingInvoiceApi.md#sendInvoice) | **POST** /sendInvoice | 


# **deleteAccountingInvoice**
> deleteAccountingInvoice(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAccountingInvoiceApi();
var id = id_example; // String | 

try { 
    api_instance.deleteAccountingInvoice(id);
} catch (e) {
    print("Exception when calling BaseAccountingInvoiceApi->deleteAccountingInvoice: $e\n");
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

# **getAccountingInvoice**
> AccountingInvoiceServiceModel getAccountingInvoice(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAccountingInvoiceApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getAccountingInvoice(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseAccountingInvoiceApi->getAccountingInvoice: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**AccountingInvoiceServiceModel**](AccountingInvoiceServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAccountingInvoices**
> QueryResultAccountingInvoiceServiceModel getAccountingInvoices(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAccountingInvoiceApi();
var request = new AccountingInvoiceQueryRequest(); // AccountingInvoiceQueryRequest | 

try { 
    var result = api_instance.getAccountingInvoices(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseAccountingInvoiceApi->getAccountingInvoices: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**AccountingInvoiceQueryRequest**](AccountingInvoiceQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultAccountingInvoiceServiceModel**](QueryResultAccountingInvoiceServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveAccountingInvoice**
> AccountingInvoiceServiceModel saveAccountingInvoice(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAccountingInvoiceApi();
var model = new AccountingInvoiceServiceModel(); // AccountingInvoiceServiceModel | 

try { 
    var result = api_instance.saveAccountingInvoice(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseAccountingInvoiceApi->saveAccountingInvoice: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**AccountingInvoiceServiceModel**](AccountingInvoiceServiceModel.md)|  | [optional] 

### Return type

[**AccountingInvoiceServiceModel**](AccountingInvoiceServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sendInvoice**
> AccountingInvoiceServiceModel sendInvoice(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseAccountingInvoiceApi();
var request = new SendInvoiceRequest(); // SendInvoiceRequest | 

try { 
    var result = api_instance.sendInvoice(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseAccountingInvoiceApi->sendInvoice: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**SendInvoiceRequest**](SendInvoiceRequest.md)|  | [optional] 

### Return type

[**AccountingInvoiceServiceModel**](AccountingInvoiceServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

