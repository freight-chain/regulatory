# api_client.api.BaseEquipmentLengthApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteEquipmentLength**](BaseEquipmentLengthApi.md#deleteEquipmentLength) | **POST** /deleteEquipmentLength | 
[**getEquipmentLength**](BaseEquipmentLengthApi.md#getEquipmentLength) | **GET** /getEquipmentLength | 
[**getEquipmentLengths**](BaseEquipmentLengthApi.md#getEquipmentLengths) | **POST** /getEquipmentLengths | 
[**saveEquipmentLength**](BaseEquipmentLengthApi.md#saveEquipmentLength) | **POST** /saveEquipmentLength | 


# **deleteEquipmentLength**
> deleteEquipmentLength(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEquipmentLengthApi();
var id = id_example; // String | 

try { 
    api_instance.deleteEquipmentLength(id);
} catch (e) {
    print("Exception when calling BaseEquipmentLengthApi->deleteEquipmentLength: $e\n");
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

# **getEquipmentLength**
> EquipmentLengthServiceModel getEquipmentLength(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEquipmentLengthApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getEquipmentLength(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseEquipmentLengthApi->getEquipmentLength: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**EquipmentLengthServiceModel**](EquipmentLengthServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getEquipmentLengths**
> QueryResultEquipmentLengthServiceModel getEquipmentLengths(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEquipmentLengthApi();
var request = new EquipmentLengthQueryRequest(); // EquipmentLengthQueryRequest | 

try { 
    var result = api_instance.getEquipmentLengths(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseEquipmentLengthApi->getEquipmentLengths: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**EquipmentLengthQueryRequest**](EquipmentLengthQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultEquipmentLengthServiceModel**](QueryResultEquipmentLengthServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveEquipmentLength**
> EquipmentLengthServiceModel saveEquipmentLength(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEquipmentLengthApi();
var model = new EquipmentLengthServiceModel(); // EquipmentLengthServiceModel | 

try { 
    var result = api_instance.saveEquipmentLength(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseEquipmentLengthApi->saveEquipmentLength: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**EquipmentLengthServiceModel**](EquipmentLengthServiceModel.md)|  | [optional] 

### Return type

[**EquipmentLengthServiceModel**](EquipmentLengthServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

