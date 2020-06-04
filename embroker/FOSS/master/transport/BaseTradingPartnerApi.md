# api_client.api.BaseTradingPartnerApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteTradingPartner**](BaseTradingPartnerApi.md#deleteTradingPartner) | **POST** /deleteTradingPartner | 
[**getTradingPartner**](BaseTradingPartnerApi.md#getTradingPartner) | **GET** /getTradingPartner | 
[**getTradingPartners**](BaseTradingPartnerApi.md#getTradingPartners) | **POST** /getTradingPartners | 
[**saveTradingPartner**](BaseTradingPartnerApi.md#saveTradingPartner) | **POST** /saveTradingPartner | 
[**sendTestMessage**](BaseTradingPartnerApi.md#sendTestMessage) | **POST** /sendTestMessage | 


# **deleteTradingPartner**
> deleteTradingPartner(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerApi();
var id = id_example; // String | 

try { 
    api_instance.deleteTradingPartner(id);
} catch (e) {
    print("Exception when calling BaseTradingPartnerApi->deleteTradingPartner: $e\n");
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

# **getTradingPartner**
> TradingPartnerServiceModel getTradingPartner(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getTradingPartner(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingPartnerApi->getTradingPartner: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**TradingPartnerServiceModel**](TradingPartnerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTradingPartners**
> QueryResultTradingPartnerServiceModel getTradingPartners(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerApi();
var request = new TradingPartnerQueryRequest(); // TradingPartnerQueryRequest | 

try { 
    var result = api_instance.getTradingPartners(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingPartnerApi->getTradingPartners: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**TradingPartnerQueryRequest**](TradingPartnerQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultTradingPartnerServiceModel**](QueryResultTradingPartnerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveTradingPartner**
> TradingPartnerServiceModel saveTradingPartner(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerApi();
var model = new TradingPartnerServiceModel(); // TradingPartnerServiceModel | 

try { 
    var result = api_instance.saveTradingPartner(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingPartnerApi->saveTradingPartner: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**TradingPartnerServiceModel**](TradingPartnerServiceModel.md)|  | [optional] 

### Return type

[**TradingPartnerServiceModel**](TradingPartnerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sendTestMessage**
> TradingPartnerServiceModel sendTestMessage(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTradingPartnerApi();
var request = new SendTestMessageRequest(); // SendTestMessageRequest | 

try { 
    var result = api_instance.sendTestMessage(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseTradingPartnerApi->sendTestMessage: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**SendTestMessageRequest**](SendTestMessageRequest.md)|  | [optional] 

### Return type

[**TradingPartnerServiceModel**](TradingPartnerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

