# api_client.api.BaseEdiConfigApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteEdiConfig**](BaseEdiConfigApi.md#deleteEdiConfig) | **POST** /deleteEdiConfig | 
[**getEdiConfig**](BaseEdiConfigApi.md#getEdiConfig) | **GET** /getEdiConfig | 
[**getEdiConfigs**](BaseEdiConfigApi.md#getEdiConfigs) | **POST** /getEdiConfigs | 
[**saveEdiConfig**](BaseEdiConfigApi.md#saveEdiConfig) | **POST** /saveEdiConfig | 


# **deleteEdiConfig**
> deleteEdiConfig(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiConfigApi();
var id = id_example; // String | 

try { 
    api_instance.deleteEdiConfig(id);
} catch (e) {
    print("Exception when calling BaseEdiConfigApi->deleteEdiConfig: $e\n");
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

# **getEdiConfig**
> EdiConfigServiceModel getEdiConfig(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiConfigApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getEdiConfig(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiConfigApi->getEdiConfig: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**EdiConfigServiceModel**](EdiConfigServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getEdiConfigs**
> QueryResultEdiConfigServiceModel getEdiConfigs(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiConfigApi();
var request = new EdiConfigQueryRequest(); // EdiConfigQueryRequest | 

try { 
    var result = api_instance.getEdiConfigs(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiConfigApi->getEdiConfigs: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**EdiConfigQueryRequest**](EdiConfigQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultEdiConfigServiceModel**](QueryResultEdiConfigServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveEdiConfig**
> EdiConfigServiceModel saveEdiConfig(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEdiConfigApi();
var model = new EdiConfigServiceModel(); // EdiConfigServiceModel | 

try { 
    var result = api_instance.saveEdiConfig(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseEdiConfigApi->saveEdiConfig: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**EdiConfigServiceModel**](EdiConfigServiceModel.md)|  | [optional] 

### Return type

[**EdiConfigServiceModel**](EdiConfigServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

