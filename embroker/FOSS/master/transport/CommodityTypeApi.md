# api_client.api.CommodityTypeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteCommodityType**](CommodityTypeApi.md#deleteCommodityType) | **POST** /api/CommodityType/deleteCommodityType | 
[**getCommodityType**](CommodityTypeApi.md#getCommodityType) | **GET** /api/CommodityType/getCommodityType | 
[**getCommodityTypes**](CommodityTypeApi.md#getCommodityTypes) | **POST** /api/CommodityType/getCommodityTypes | 
[**saveCommodityType**](CommodityTypeApi.md#saveCommodityType) | **POST** /api/CommodityType/saveCommodityType | 


# **deleteCommodityType**
> deleteCommodityType(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CommodityTypeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteCommodityType(id);
} catch (e) {
    print("Exception when calling CommodityTypeApi->deleteCommodityType: $e\n");
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

# **getCommodityType**
> CommodityTypeServiceModel getCommodityType(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CommodityTypeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getCommodityType(id);
    print(result);
} catch (e) {
    print("Exception when calling CommodityTypeApi->getCommodityType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**CommodityTypeServiceModel**](CommodityTypeServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCommodityTypes**
> QueryResultCommodityTypeServiceModel getCommodityTypes(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CommodityTypeApi();
var request = new CommodityTypeQueryRequest(); // CommodityTypeQueryRequest | 

try { 
    var result = api_instance.getCommodityTypes(request);
    print(result);
} catch (e) {
    print("Exception when calling CommodityTypeApi->getCommodityTypes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CommodityTypeQueryRequest**](CommodityTypeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultCommodityTypeServiceModel**](QueryResultCommodityTypeServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveCommodityType**
> CommodityTypeServiceModel saveCommodityType(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CommodityTypeApi();
var model = new CommodityTypeServiceModel(); // CommodityTypeServiceModel | 

try { 
    var result = api_instance.saveCommodityType(model);
    print(result);
} catch (e) {
    print("Exception when calling CommodityTypeApi->saveCommodityType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**CommodityTypeServiceModel**](CommodityTypeServiceModel.md)|  | [optional] 

### Return type

[**CommodityTypeServiceModel**](CommodityTypeServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

