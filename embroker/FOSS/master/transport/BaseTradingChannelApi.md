# api_client.api.BaseTradingChannelApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteTradingChannel**](BaseTradingChannelApi.md#deleteTradingChannel) | **POST** /deleteTradingChannel | 
[**generateKeys**](BaseTradingChannelApi.md#generateKeys) | **POST** /generateKeys | 
[**getTradingChannel**](BaseTradingChannelApi.md#getTradingChannel) | **GET** /getTradingChannel | 
[**getTradingChannels**](BaseTradingChannelApi.md#getTradingChannels) | **POST** /getTradingChannels | 
[**saveTradingChannel**](BaseTradingChannelApi.md#saveTradingChannel) | **POST** /saveTradingChannel | 


# **deleteTradingChannel**
> deleteTradingChannel(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingChannelApi();
var id = id_example; // String | 

try { 
    api_instance.deleteTradingChannel(id);
} catch (e) {
    print("Exception when calling BaseTradingChannelApi->deleteTradingChannel: $e\n");
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

# **generateKeys**
> TradingChannelServiceModel generateKeys(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingChannelApi();
var request = new GenerateKeysRequest(); // GenerateKeysRequest | 

try { 
    var result = api_instance.generateKeys(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingChannelApi->generateKeys: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**GenerateKeysRequest**](GenerateKeysRequest.md)|  | [optional] 

### Return type

[**TradingChannelServiceModel**](TradingChannelServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTradingChannel**
> TradingChannelServiceModel getTradingChannel(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingChannelApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getTradingChannel(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingChannelApi->getTradingChannel: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**TradingChannelServiceModel**](TradingChannelServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTradingChannels**
> QueryResultTradingChannelServiceModel getTradingChannels(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingChannelApi();
var request = new TradingChannelQueryRequest(); // TradingChannelQueryRequest | 

try { 
    var result = api_instance.getTradingChannels(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingChannelApi->getTradingChannels: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**TradingChannelQueryRequest**](TradingChannelQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultTradingChannelServiceModel**](QueryResultTradingChannelServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveTradingChannel**
> TradingChannelServiceModel saveTradingChannel(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingChannelApi();
var model = new TradingChannelServiceModel(); // TradingChannelServiceModel | 

try { 
    var result = api_instance.saveTradingChannel(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingChannelApi->saveTradingChannel: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**TradingChannelServiceModel**](TradingChannelServiceModel.md)|  | [optional] 

### Return type

[**TradingChannelServiceModel**](TradingChannelServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

