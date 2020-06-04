# api_client.api.AccountingInvoiceApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteAccountingInvoice**](AccountingInvoiceApi.md#deleteAccountingInvoice) | **POST** /api/AccountingInvoice/deleteAccountingInvoice | 
[**exportReconcile**](AccountingInvoiceApi.md#exportReconcile) | **POST** /api/AccountingInvoice/exportReconcile | 
[**getAccountingInvoice**](AccountingInvoiceApi.md#getAccountingInvoice) | **GET** /api/AccountingInvoice/getAccountingInvoice | 
[**getAccountingInvoices**](AccountingInvoiceApi.md#getAccountingInvoices) | **POST** /api/AccountingInvoice/getAccountingInvoices | 
[**saveAccountingInvoice**](AccountingInvoiceApi.md#saveAccountingInvoice) | **POST** /api/AccountingInvoice/saveAccountingInvoice | 
[**sendInvoice**](AccountingInvoiceApi.md#sendInvoice) | **POST** /api/AccountingInvoice/sendInvoice | 


# **deleteAccountingInvoice**
> deleteAccountingInvoice(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountingInvoiceApi();
var id = id_example; // String | 

try { 
    api_instance.deleteAccountingInvoice(id);
} catch (e) {
    print("Exception when calling AccountingInvoiceApi->deleteAccountingInvoice: $e\n");
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

# **exportReconcile**
> MultipartFile exportReconcile(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountingInvoiceApi();
var request = new AccountingInvoiceQueryRequest(); // AccountingInvoiceQueryRequest | 

try { 
    var result = api_instance.exportReconcile(request);
    print(result);
} catch (e) {
    print("Exception when calling AccountingInvoiceApi->exportReconcile: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**AccountingInvoiceQueryRequest**](AccountingInvoiceQueryRequest.md)|  | [optional] 

### Return type

[**MultipartFile**](File.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAccountingInvoice**
> AccountingInvoiceServiceModel getAccountingInvoice(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountingInvoiceApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getAccountingInvoice(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountingInvoiceApi->getAccountingInvoice: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**AccountingInvoiceServiceModel**](AccountingInvoiceServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAccountingInvoices**
> QueryResultAccountingInvoiceServiceModel getAccountingInvoices(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountingInvoiceApi();
var request = new AccountingInvoiceQueryRequest(); // AccountingInvoiceQueryRequest | 

try { 
    var result = api_instance.getAccountingInvoices(request);
    print(result);
} catch (e) {
    print("Exception when calling AccountingInvoiceApi->getAccountingInvoices: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**AccountingInvoiceQueryRequest**](AccountingInvoiceQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultAccountingInvoiceServiceModel**](QueryResultAccountingInvoiceServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveAccountingInvoice**
> AccountingInvoiceServiceModel saveAccountingInvoice(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountingInvoiceApi();
var model = new AccountingInvoiceServiceModel(); // AccountingInvoiceServiceModel | 

try { 
    var result = api_instance.saveAccountingInvoice(model);
    print(result);
} catch (e) {
    print("Exception when calling AccountingInvoiceApi->saveAccountingInvoice: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**AccountingInvoiceServiceModel**](AccountingInvoiceServiceModel.md)|  | [optional] 

### Return type

[**AccountingInvoiceServiceModel**](AccountingInvoiceServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sendInvoice**
> AccountingInvoiceServiceModel sendInvoice(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountingInvoiceApi();
var request = new SendInvoiceRequest(); // SendInvoiceRequest | 

try { 
    var result = api_instance.sendInvoice(request);
    print(result);
} catch (e) {
    print("Exception when calling AccountingInvoiceApi->sendInvoice: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**SendInvoiceRequest**](SendInvoiceRequest.md)|  | [optional] 

### Return type

[**AccountingInvoiceServiceModel**](AccountingInvoiceServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

