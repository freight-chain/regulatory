# api_client.api.ConfigApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**explain**](ConfigApi.md#explain) | **GET** /api/Config/explain | 
[**getConfig**](ConfigApi.md#getConfig) | **GET** /api/Config/getConfig | 
[**getConfiguration**](ConfigApi.md#getConfiguration) | **POST** /api/Config/getConfiguration | 
[**saveConfig**](ConfigApi.md#saveConfig) | **GET** /api/Config/saveConfig | 


# **explain**
> String explain(typeName)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new ConfigApi();
var typeName = typeName_example; // String | 

try { 
    var result = api_instance.explain(typeName);
    print(result);
} catch (e) {
    print("Exception when calling ConfigApi->explain: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **typeName** | **String**|  | [optional] 

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getConfig**
> Object getConfig(typeName)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new ConfigApi();
var typeName = typeName_example; // String | 

try { 
    var result = api_instance.getConfig(typeName);
    print(result);
} catch (e) {
    print("Exception when calling ConfigApi->getConfig: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **typeName** | **String**|  | [optional] 

### Return type

[**Object**](Object.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getConfiguration**
> ConfigurationServiceModel getConfiguration()



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new ConfigApi();

try { 
    var result = api_instance.getConfiguration();
    print(result);
} catch (e) {
    print("Exception when calling ConfigApi->getConfiguration: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**ConfigurationServiceModel**](ConfigurationServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveConfig**
> Object saveConfig(typeName, serializedConfig)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new ConfigApi();
var typeName = typeName_example; // String | 
var serializedConfig = new String(); // String | 

try { 
    var result = api_instance.saveConfig(typeName, serializedConfig);
    print(result);
} catch (e) {
    print("Exception when calling ConfigApi->saveConfig: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **typeName** | **String**|  | [optional] 
 **serializedConfig** | **String**|  | [optional] 

### Return type

[**Object**](Object.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

