# api_client.api.BaseDocumentApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteDocument**](BaseDocumentApi.md#deleteDocument) | **POST** /deleteDocument | 
[**getDocument**](BaseDocumentApi.md#getDocument) | **GET** /getDocument | 
[**getDocuments**](BaseDocumentApi.md#getDocuments) | **POST** /getDocuments | 
[**saveDocument**](BaseDocumentApi.md#saveDocument) | **POST** /saveDocument | 


# **deleteDocument**
> deleteDocument(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDocumentApi();
var id = id_example; // String | 

try { 
    api_instance.deleteDocument(id);
} catch (e) {
    print("Exception when calling BaseDocumentApi->deleteDocument: $e\n");
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

# **getDocument**
> DocumentServiceModel getDocument(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDocumentApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getDocument(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseDocumentApi->getDocument: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**DocumentServiceModel**](DocumentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getDocuments**
> QueryResultDocumentServiceModel getDocuments(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDocumentApi();
var request = new DocumentQueryRequest(); // DocumentQueryRequest | 

try { 
    var result = api_instance.getDocuments(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseDocumentApi->getDocuments: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**DocumentQueryRequest**](DocumentQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultDocumentServiceModel**](QueryResultDocumentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveDocument**
> DocumentServiceModel saveDocument(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseDocumentApi();
var model = new DocumentServiceModel(); // DocumentServiceModel | 

try { 
    var result = api_instance.saveDocument(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseDocumentApi->saveDocument: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**DocumentServiceModel**](DocumentServiceModel.md)|  | [optional] 

### Return type

[**DocumentServiceModel**](DocumentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

