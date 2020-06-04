# api_client.api.BaseTrailerApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteTrailer**](BaseTrailerApi.md#deleteTrailer) | **POST** /deleteTrailer | 
[**getTrailer**](BaseTrailerApi.md#getTrailer) | **GET** /getTrailer | 
[**getTrailers**](BaseTrailerApi.md#getTrailers) | **POST** /getTrailers | 
[**saveTrailer**](BaseTrailerApi.md#saveTrailer) | **POST** /saveTrailer | 


# **deleteTrailer**
> deleteTrailer(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTrailerApi();
var id = id_example; // String | 

try { 
    api_instance.deleteTrailer(id);
} catch (e) {
    print("Exception when calling BaseTrailerApi->deleteTrailer: $e\n");
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

# **getTrailer**
> TrailerServiceModel getTrailer(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTrailerApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getTrailer(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseTrailerApi->getTrailer: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**TrailerServiceModel**](TrailerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTrailers**
> QueryResultTrailerServiceModel getTrailers(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTrailerApi();
var request = new TrailerQueryRequest(); // TrailerQueryRequest | 

try { 
    var result = api_instance.getTrailers(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseTrailerApi->getTrailers: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**TrailerQueryRequest**](TrailerQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultTrailerServiceModel**](QueryResultTrailerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveTrailer**
> TrailerServiceModel saveTrailer(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseTrailerApi();
var model = new TrailerServiceModel(); // TrailerServiceModel | 

try { 
    var result = api_instance.saveTrailer(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseTrailerApi->saveTrailer: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**TrailerServiceModel**](TrailerServiceModel.md)|  | [optional] 

### Return type

[**TrailerServiceModel**](TrailerServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

