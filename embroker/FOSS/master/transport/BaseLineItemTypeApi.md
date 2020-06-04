# api_client.api.BaseLineItemTypeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteLineItemType**](BaseLineItemTypeApi.md#deleteLineItemType) | **POST** /deleteLineItemType | 
[**getLineItemType**](BaseLineItemTypeApi.md#getLineItemType) | **GET** /getLineItemType | 
[**getLineItemTypes**](BaseLineItemTypeApi.md#getLineItemTypes) | **POST** /getLineItemTypes | 
[**saveLineItemType**](BaseLineItemTypeApi.md#saveLineItemType) | **POST** /saveLineItemType | 


# **deleteLineItemType**
> deleteLineItemType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLineItemTypeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteLineItemType(id);
} catch (e) {
    print("Exception when calling BaseLineItemTypeApi->deleteLineItemType: $e\n");
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

# **getLineItemType**
> LineItemTypeServiceModel getLineItemType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLineItemTypeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getLineItemType(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseLineItemTypeApi->getLineItemType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**LineItemTypeServiceModel**](LineItemTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getLineItemTypes**
> QueryResultLineItemTypeServiceModel getLineItemTypes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLineItemTypeApi();
var request = new LineItemTypeQueryRequest(); // LineItemTypeQueryRequest | 

try { 
    var result = api_instance.getLineItemTypes(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseLineItemTypeApi->getLineItemTypes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**LineItemTypeQueryRequest**](LineItemTypeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultLineItemTypeServiceModel**](QueryResultLineItemTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveLineItemType**
> LineItemTypeServiceModel saveLineItemType(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseLineItemTypeApi();
var model = new LineItemTypeServiceModel(); // LineItemTypeServiceModel | 

try { 
    var result = api_instance.saveLineItemType(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseLineItemTypeApi->saveLineItemType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**LineItemTypeServiceModel**](LineItemTypeServiceModel.md)|  | [optional] 

### Return type

[**LineItemTypeServiceModel**](LineItemTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

