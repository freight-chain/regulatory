# api_client.api.BaseEdiTenderApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteEdiTender**](BaseEdiTenderApi.md#deleteEdiTender) | **POST** /deleteEdiTender | 
[**getEdiTender**](BaseEdiTenderApi.md#getEdiTender) | **GET** /getEdiTender | 
[**getEdiTenders**](BaseEdiTenderApi.md#getEdiTenders) | **POST** /getEdiTenders | 
[**saveEdiTender**](BaseEdiTenderApi.md#saveEdiTender) | **POST** /saveEdiTender | 


# **deleteEdiTender**
> deleteEdiTender(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiTenderApi();
var id = id_example; // String | 

try { 
    api_instance.deleteEdiTender(id);
} catch (e) {
    print("Exception when calling BaseEdiTenderApi->deleteEdiTender: $e\n");
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

# **getEdiTender**
> EdiTenderServiceModel getEdiTender(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiTenderApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getEdiTender(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiTenderApi->getEdiTender: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**EdiTenderServiceModel**](EdiTenderServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getEdiTenders**
> QueryResultEdiTenderServiceModel getEdiTenders(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiTenderApi();
var request = new EdiTenderQueryRequest(); // EdiTenderQueryRequest | 

try { 
    var result = api_instance.getEdiTenders(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiTenderApi->getEdiTenders: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**EdiTenderQueryRequest**](EdiTenderQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultEdiTenderServiceModel**](QueryResultEdiTenderServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveEdiTender**
> EdiTenderServiceModel saveEdiTender(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiTenderApi();
var model = new EdiTenderServiceModel(); // EdiTenderServiceModel | 

try { 
    var result = api_instance.saveEdiTender(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiTenderApi->saveEdiTender: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**EdiTenderServiceModel**](EdiTenderServiceModel.md)|  | [optional] 

### Return type

[**EdiTenderServiceModel**](EdiTenderServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

