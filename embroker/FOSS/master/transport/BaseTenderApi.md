# api_client.api.BaseTenderApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteTender**](BaseTenderApi.md#deleteTender) | **POST** /deleteTender | 
[**getTender**](BaseTenderApi.md#getTender) | **GET** /getTender | 
[**getTenders**](BaseTenderApi.md#getTenders) | **POST** /getTenders | 
[**saveTender**](BaseTenderApi.md#saveTender) | **POST** /saveTender | 


# **deleteTender**
> deleteTender(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTenderApi();
var id = id_example; // String | 

try { 
    api_instance.deleteTender(id);
} catch (e) {
    print("Exception when calling BaseTenderApi->deleteTender: $e\n");
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

# **getTender**
> TenderServiceModel getTender(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTenderApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getTender(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseTenderApi->getTender: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**TenderServiceModel**](TenderServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTenders**
> QueryResultTenderServiceModel getTenders(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTenderApi();
var request = new TenderQueryRequest(); // TenderQueryRequest | 

try { 
    var result = api_instance.getTenders(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseTenderApi->getTenders: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**TenderQueryRequest**](TenderQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultTenderServiceModel**](QueryResultTenderServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveTender**
> TenderServiceModel saveTender(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTenderApi();
var model = new TenderServiceModel(); // TenderServiceModel | 

try { 
    var result = api_instance.saveTender(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseTenderApi->saveTender: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**TenderServiceModel**](TenderServiceModel.md)|  | [optional] 

### Return type

[**TenderServiceModel**](TenderServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

