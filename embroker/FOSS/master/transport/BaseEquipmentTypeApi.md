# api_client.api.BaseEquipmentTypeApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteEquipmentType**](BaseEquipmentTypeApi.md#deleteEquipmentType) | **POST** /deleteEquipmentType | 
[**getEquipmentType**](BaseEquipmentTypeApi.md#getEquipmentType) | **GET** /getEquipmentType | 
[**getEquipmentTypes**](BaseEquipmentTypeApi.md#getEquipmentTypes) | **POST** /getEquipmentTypes | 
[**saveEquipmentType**](BaseEquipmentTypeApi.md#saveEquipmentType) | **POST** /saveEquipmentType | 


# **deleteEquipmentType**
> deleteEquipmentType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEquipmentTypeApi();
var id = id_example; // String | 

try { 
    api_instance.deleteEquipmentType(id);
} catch (e) {
    print("Exception when calling BaseEquipmentTypeApi->deleteEquipmentType: $e\n");
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

# **getEquipmentType**
> EquipmentTypeServiceModel getEquipmentType(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEquipmentTypeApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getEquipmentType(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseEquipmentTypeApi->getEquipmentType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**EquipmentTypeServiceModel**](EquipmentTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getEquipmentTypes**
> QueryResultEquipmentTypeServiceModel getEquipmentTypes(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEquipmentTypeApi();
var request = new EquipmentTypeQueryRequest(); // EquipmentTypeQueryRequest | 

try { 
    var result = api_instance.getEquipmentTypes(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseEquipmentTypeApi->getEquipmentTypes: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**EquipmentTypeQueryRequest**](EquipmentTypeQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultEquipmentTypeServiceModel**](QueryResultEquipmentTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveEquipmentType**
> EquipmentTypeServiceModel saveEquipmentType(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseEquipmentTypeApi();
var model = new EquipmentTypeServiceModel(); // EquipmentTypeServiceModel | 

try { 
    var result = api_instance.saveEquipmentType(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseEquipmentTypeApi->saveEquipmentType: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**EquipmentTypeServiceModel**](EquipmentTypeServiceModel.md)|  | [optional] 

### Return type

[**EquipmentTypeServiceModel**](EquipmentTypeServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

