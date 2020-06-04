# api_client.api.BaseInvitationApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteInvitation**](BaseInvitationApi.md#deleteInvitation) | **POST** /deleteInvitation | 
[**getInvitation**](BaseInvitationApi.md#getInvitation) | **GET** /getInvitation | 
[**getInvitations**](BaseInvitationApi.md#getInvitations) | **POST** /getInvitations | 
[**saveInvitation**](BaseInvitationApi.md#saveInvitation) | **POST** /saveInvitation | 


# **deleteInvitation**
> InvitationServiceModel deleteInvitation(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new BaseInvitationApi();
var id = id_example; // String | 

try { 
    var result = api_instance.deleteInvitation(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvitationApi->deleteInvitation: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**InvitationServiceModel**](InvitationServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getInvitation**
> InvitationServiceModel getInvitation(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new BaseInvitationApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getInvitation(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvitationApi->getInvitation: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**InvitationServiceModel**](InvitationServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getInvitations**
> QueryResultInvitationServiceModel getInvitations(query)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new BaseInvitationApi();
var query = new Query(); // Query | 

try { 
    var result = api_instance.getInvitations(query);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvitationApi->getInvitations: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | [**Query**](Query.md)|  | [optional] 

### Return type

[**QueryResultInvitationServiceModel**](QueryResultInvitationServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveInvitation**
> InvitationServiceModel saveInvitation(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new BaseInvitationApi();
var model = new InvitationServiceModel(); // InvitationServiceModel | 

try { 
    var result = api_instance.saveInvitation(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseInvitationApi->saveInvitation: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**InvitationServiceModel**](InvitationServiceModel.md)|  | [optional] 

### Return type

[**InvitationServiceModel**](InvitationServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

