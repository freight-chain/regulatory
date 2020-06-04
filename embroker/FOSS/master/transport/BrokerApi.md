# api_client.api.BrokerApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteBroker**](BrokerApi.md#deleteBroker) | **POST** /api/Broker/deleteBroker | 
[**getBroker**](BrokerApi.md#getBroker) | **GET** /api/Broker/getBroker | 
[**getBrokers**](BrokerApi.md#getBrokers) | **POST** /api/Broker/getBrokers | 
[**saveBroker**](BrokerApi.md#saveBroker) | **POST** /api/Broker/saveBroker | 


# **deleteBroker**
> deleteBroker(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new BrokerApi();
var id = id_example; // String | 

try { 
    api_instance.deleteBroker(id);
} catch (e) {
    print("Exception when calling BrokerApi->deleteBroker: $e\n");
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

# **getBroker**
> BrokerServiceModel getBroker(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new BrokerApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getBroker(id);
    print(result);
} catch (e) {
    print("Exception when calling BrokerApi->getBroker: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**BrokerServiceModel**](BrokerServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getBrokers**
> QueryResultBrokerServiceModel getBrokers(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new BrokerApi();
var request = new BrokerQueryRequest(); // BrokerQueryRequest | 

try { 
    var result = api_instance.getBrokers(request);
    print(result);
} catch (e) {
    print("Exception when calling BrokerApi->getBrokers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**BrokerQueryRequest**](BrokerQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultBrokerServiceModel**](QueryResultBrokerServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveBroker**
> BrokerServiceModel saveBroker(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new BrokerApi();
var model = new BrokerServiceModel(); // BrokerServiceModel | 

try { 
    var result = api_instance.saveBroker(model);
    print(result);
} catch (e) {
    print("Exception when calling BrokerApi->saveBroker: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**BrokerServiceModel**](BrokerServiceModel.md)|  | [optional] 

### Return type

[**BrokerServiceModel**](BrokerServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

