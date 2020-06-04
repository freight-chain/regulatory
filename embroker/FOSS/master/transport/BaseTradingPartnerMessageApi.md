# api_client.api.BaseTradingPartnerMessageApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteTradingPartnerMessage**](BaseTradingPartnerMessageApi.md#deleteTradingPartnerMessage) | **POST** /deleteTradingPartnerMessage | 
[**getTradingPartnerMessage**](BaseTradingPartnerMessageApi.md#getTradingPartnerMessage) | **GET** /getTradingPartnerMessage | 
[**getTradingPartnerMessages**](BaseTradingPartnerMessageApi.md#getTradingPartnerMessages) | **POST** /getTradingPartnerMessages | 
[**saveTradingPartnerMessage**](BaseTradingPartnerMessageApi.md#saveTradingPartnerMessage) | **POST** /saveTradingPartnerMessage | 


# **deleteTradingPartnerMessage**
> deleteTradingPartnerMessage(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerMessageApi();
var id = id_example; // String | 

try { 
    api_instance.deleteTradingPartnerMessage(id);
} catch (e) {
    print("Exception when calling BaseTradingPartnerMessageApi->deleteTradingPartnerMessage: $e\n");
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

# **getTradingPartnerMessage**
> TradingPartnerMessageServiceModel getTradingPartnerMessage(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerMessageApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getTradingPartnerMessage(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingPartnerMessageApi->getTradingPartnerMessage: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**TradingPartnerMessageServiceModel**](TradingPartnerMessageServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTradingPartnerMessages**
> QueryResultTradingPartnerMessageServiceModel getTradingPartnerMessages(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerMessageApi();
var request = new TradingPartnerMessageQueryRequest(); // TradingPartnerMessageQueryRequest | 

try { 
    var result = api_instance.getTradingPartnerMessages(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingPartnerMessageApi->getTradingPartnerMessages: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**TradingPartnerMessageQueryRequest**](TradingPartnerMessageQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultTradingPartnerMessageServiceModel**](QueryResultTradingPartnerMessageServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveTradingPartnerMessage**
> TradingPartnerMessageServiceModel saveTradingPartnerMessage(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerMessageApi();
var model = new TradingPartnerMessageServiceModel(); // TradingPartnerMessageServiceModel | 

try { 
    var result = api_instance.saveTradingPartnerMessage(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingPartnerMessageApi->saveTradingPartnerMessage: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**TradingPartnerMessageServiceModel**](TradingPartnerMessageServiceModel.md)|  | [optional] 

### Return type

[**TradingPartnerMessageServiceModel**](TradingPartnerMessageServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

