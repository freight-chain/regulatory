# api_client.api.BaseNmfcNumberApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteNmfcNumber**](BaseNmfcNumberApi.md#deleteNmfcNumber) | **POST** /deleteNmfcNumber | 
[**getNmfcNumber**](BaseNmfcNumberApi.md#getNmfcNumber) | **GET** /getNmfcNumber | 
[**getNmfcNumbers**](BaseNmfcNumberApi.md#getNmfcNumbers) | **POST** /getNmfcNumbers | 
[**saveNmfcNumber**](BaseNmfcNumberApi.md#saveNmfcNumber) | **POST** /saveNmfcNumber | 


# **deleteNmfcNumber**
> deleteNmfcNumber(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseNmfcNumberApi();
var id = id_example; // String | 

try { 
    api_instance.deleteNmfcNumber(id);
} catch (e) {
    print("Exception when calling BaseNmfcNumberApi->deleteNmfcNumber: $e\n");
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

# **getNmfcNumber**
> NmfcNumberServiceModel getNmfcNumber(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseNmfcNumberApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getNmfcNumber(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseNmfcNumberApi->getNmfcNumber: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**NmfcNumberServiceModel**](NmfcNumberServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getNmfcNumbers**
> QueryResultNmfcNumberServiceModel getNmfcNumbers(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseNmfcNumberApi();
var request = new NmfcNumberQueryRequest(); // NmfcNumberQueryRequest | 

try { 
    var result = api_instance.getNmfcNumbers(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseNmfcNumberApi->getNmfcNumbers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**NmfcNumberQueryRequest**](NmfcNumberQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultNmfcNumberServiceModel**](QueryResultNmfcNumberServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveNmfcNumber**
> NmfcNumberServiceModel saveNmfcNumber(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseNmfcNumberApi();
var model = new NmfcNumberServiceModel(); // NmfcNumberServiceModel | 

try { 
    var result = api_instance.saveNmfcNumber(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseNmfcNumberApi->saveNmfcNumber: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**NmfcNumberServiceModel**](NmfcNumberServiceModel.md)|  | [optional] 

### Return type

[**NmfcNumberServiceModel**](NmfcNumberServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

