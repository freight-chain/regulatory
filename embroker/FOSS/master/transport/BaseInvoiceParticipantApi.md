# api_client.api.BaseInvoiceParticipantApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteInvoiceParticipant**](BaseInvoiceParticipantApi.md#deleteInvoiceParticipant) | **POST** /deleteInvoiceParticipant | 
[**getInvoiceParticipant**](BaseInvoiceParticipantApi.md#getInvoiceParticipant) | **GET** /getInvoiceParticipant | 
[**getInvoiceParticipants**](BaseInvoiceParticipantApi.md#getInvoiceParticipants) | **POST** /getInvoiceParticipants | 
[**saveInvoiceParticipant**](BaseInvoiceParticipantApi.md#saveInvoiceParticipant) | **POST** /saveInvoiceParticipant | 


# **deleteInvoiceParticipant**
> deleteInvoiceParticipant(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceParticipantApi();
var id = id_example; // String | 

try { 
    api_instance.deleteInvoiceParticipant(id);
} catch (e) {
    print("Exception when calling BaseInvoiceParticipantApi->deleteInvoiceParticipant: $e\n");
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

# **getInvoiceParticipant**
> InvoiceParticipantServiceModel getInvoiceParticipant(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceParticipantApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getInvoiceParticipant(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceParticipantApi->getInvoiceParticipant: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**InvoiceParticipantServiceModel**](InvoiceParticipantServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getInvoiceParticipants**
> QueryResultInvoiceParticipantServiceModel getInvoiceParticipants(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceParticipantApi();
var request = new InvoiceParticipantQueryRequest(); // InvoiceParticipantQueryRequest | 

try { 
    var result = api_instance.getInvoiceParticipants(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceParticipantApi->getInvoiceParticipants: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**InvoiceParticipantQueryRequest**](InvoiceParticipantQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultInvoiceParticipantServiceModel**](QueryResultInvoiceParticipantServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveInvoiceParticipant**
> InvoiceParticipantServiceModel saveInvoiceParticipant(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseInvoiceParticipantApi();
var model = new InvoiceParticipantServiceModel(); // InvoiceParticipantServiceModel | 

try { 
    var result = api_instance.saveInvoiceParticipant(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvoiceParticipantApi->saveInvoiceParticipant: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**InvoiceParticipantServiceModel**](InvoiceParticipantServiceModel.md)|  | [optional] 

### Return type

[**InvoiceParticipantServiceModel**](InvoiceParticipantServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

