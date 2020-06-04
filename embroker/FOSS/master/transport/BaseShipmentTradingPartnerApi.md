# api_client.api.BaseShipmentTradingPartnerApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteShipmentTradingPartner**](BaseShipmentTradingPartnerApi.md#deleteShipmentTradingPartner) | **POST** /deleteShipmentTradingPartner | 
[**getShipmentTradingPartner**](BaseShipmentTradingPartnerApi.md#getShipmentTradingPartner) | **GET** /getShipmentTradingPartner | 
[**getShipmentTradingPartners**](BaseShipmentTradingPartnerApi.md#getShipmentTradingPartners) | **POST** /getShipmentTradingPartners | 
[**saveShipmentTradingPartner**](BaseShipmentTradingPartnerApi.md#saveShipmentTradingPartner) | **POST** /saveShipmentTradingPartner | 
[**sendTender**](BaseShipmentTradingPartnerApi.md#sendTender) | **POST** /sendTender | 


# **deleteShipmentTradingPartner**
> deleteShipmentTradingPartner(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentTradingPartnerApi();
var id = id_example; // String | 

try { 
    api_instance.deleteShipmentTradingPartner(id);
} catch (e) {
    print("Exception when calling BaseShipmentTradingPartnerApi->deleteShipmentTradingPartner: $e\n");
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

# **getShipmentTradingPartner**
> ShipmentTradingPartnerServiceModel getShipmentTradingPartner(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentTradingPartnerApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getShipmentTradingPartner(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentTradingPartnerApi->getShipmentTradingPartner: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**ShipmentTradingPartnerServiceModel**](ShipmentTradingPartnerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getShipmentTradingPartners**
> QueryResultShipmentTradingPartnerServiceModel getShipmentTradingPartners(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentTradingPartnerApi();
var request = new ShipmentTradingPartnerQueryRequest(); // ShipmentTradingPartnerQueryRequest | 

try { 
    var result = api_instance.getShipmentTradingPartners(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentTradingPartnerApi->getShipmentTradingPartners: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipmentTradingPartnerQueryRequest**](ShipmentTradingPartnerQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultShipmentTradingPartnerServiceModel**](QueryResultShipmentTradingPartnerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveShipmentTradingPartner**
> ShipmentTradingPartnerServiceModel saveShipmentTradingPartner(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentTradingPartnerApi();
var model = new ShipmentTradingPartnerServiceModel(); // ShipmentTradingPartnerServiceModel | 

try { 
    var result = api_instance.saveShipmentTradingPartner(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentTradingPartnerApi->saveShipmentTradingPartner: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ShipmentTradingPartnerServiceModel**](ShipmentTradingPartnerServiceModel.md)|  | [optional] 

### Return type

[**ShipmentTradingPartnerServiceModel**](ShipmentTradingPartnerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sendTender**
> ShipmentTradingPartnerServiceModel sendTender(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentTradingPartnerApi();
var request = new SendTenderRequest(); // SendTenderRequest | 

try { 
    var result = api_instance.sendTender(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentTradingPartnerApi->sendTender: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**SendTenderRequest**](SendTenderRequest.md)|  | [optional] 

### Return type

[**ShipmentTradingPartnerServiceModel**](ShipmentTradingPartnerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

