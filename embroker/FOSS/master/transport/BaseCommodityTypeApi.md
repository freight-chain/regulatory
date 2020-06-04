# api_client.api.BaseCommodityTypeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteCommodityType**](BaseCommodityTypeApi.md#deleteCommodityType) | **POST** /deleteCommodityType | 
[**getCommodityType**](BaseCommodityTypeApi.md#getCommodityType) | **GET** /getCommodityType | 
[**getCommodityTypes**](BaseCommodityTypeApi.md#getCommodityTypes) | **POST** /getCommodityTypes | 
[**saveCommodityType**](BaseCommodityTypeApi.md#saveCommodityType) | **POST** /saveCommodityType | 


# **deleteCommodityType**
> deleteCommodityType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCommodityTypeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteCommodityType(id);
} catch (e) {
    print("Exception when calling BaseCommodityTypeApi->deleteCommodityType: $e\n");
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

# **getCommodityType**
> CommodityTypeServiceModel getCommodityType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCommodityTypeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getCommodityType(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseCommodityTypeApi->getCommodityType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**CommodityTypeServiceModel**](CommodityTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCommodityTypes**
> QueryResultCommodityTypeServiceModel getCommodityTypes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCommodityTypeApi();
var request = new CommodityTypeQueryRequest(); // CommodityTypeQueryRequest | 

try { 
    var result = api_instance.getCommodityTypes(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseCommodityTypeApi->getCommodityTypes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CommodityTypeQueryRequest**](CommodityTypeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultCommodityTypeServiceModel**](QueryResultCommodityTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveCommodityType**
> CommodityTypeServiceModel saveCommodityType(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCommodityTypeApi();
var model = new CommodityTypeServiceModel(); // CommodityTypeServiceModel | 

try { 
    var result = api_instance.saveCommodityType(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseCommodityTypeApi->saveCommodityType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**CommodityTypeServiceModel**](CommodityTypeServiceModel.md)|  | [optional] 

### Return type

[**CommodityTypeServiceModel**](CommodityTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

