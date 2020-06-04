# api_client.api.BaseBrokerApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteBroker**](BaseBrokerApi.md#deleteBroker) | **POST** /deleteBroker | 
[**getBroker**](BaseBrokerApi.md#getBroker) | **GET** /getBroker | 
[**getBrokers**](BaseBrokerApi.md#getBrokers) | **POST** /getBrokers | 
[**saveBroker**](BaseBrokerApi.md#saveBroker) | **POST** /saveBroker | 


# **deleteBroker**
> deleteBroker(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseBrokerApi();
var id = id_example; // String | 

try { 
    api_instance.deleteBroker(id);
} catch (e) {
    print("Exception when calling BaseBrokerApi->deleteBroker: $e\n");
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

# **getBroker**
> BrokerServiceModel getBroker(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseBrokerApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getBroker(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseBrokerApi->getBroker: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**BrokerServiceModel**](BrokerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getBrokers**
> QueryResultBrokerServiceModel getBrokers(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseBrokerApi();
var request = new BrokerQueryRequest(); // BrokerQueryRequest | 

try { 
    var result = api_instance.getBrokers(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseBrokerApi->getBrokers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**BrokerQueryRequest**](BrokerQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultBrokerServiceModel**](QueryResultBrokerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveBroker**
> BrokerServiceModel saveBroker(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseBrokerApi();
var model = new BrokerServiceModel(); // BrokerServiceModel | 

try { 
    var result = api_instance.saveBroker(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseBrokerApi->saveBroker: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**BrokerServiceModel**](BrokerServiceModel.md)|  | [optional] 

### Return type

[**BrokerServiceModel**](BrokerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

