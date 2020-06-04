# api_client.api.BaseSamsaraConfigApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getSamsaraConfig**](BaseSamsaraConfigApi.md#getSamsaraConfig) | **GET** /getSamsaraConfig | 
[**saveSamsaraConfig**](BaseSamsaraConfigApi.md#saveSamsaraConfig) | **POST** /saveSamsaraConfig | 


# **getSamsaraConfig**
> SamsaraConfigServiceModel getSamsaraConfig(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseSamsaraConfigApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getSamsaraConfig(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseSamsaraConfigApi->getSamsaraConfig: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**SamsaraConfigServiceModel**](SamsaraConfigServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveSamsaraConfig**
> SamsaraConfigServiceModel saveSamsaraConfig(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseSamsaraConfigApi();
var model = new SamsaraConfigServiceModel(); // SamsaraConfigServiceModel | 

try { 
    var result = api_instance.saveSamsaraConfig(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseSamsaraConfigApi->saveSamsaraConfig: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**SamsaraConfigServiceModel**](SamsaraConfigServiceModel.md)|  | [optional] 

### Return type

[**SamsaraConfigServiceModel**](SamsaraConfigServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

