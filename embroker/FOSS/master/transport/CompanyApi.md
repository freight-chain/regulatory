# api_client.api.CompanyApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteCompany**](CompanyApi.md#deleteCompany) | **POST** /api/Company/deleteCompany | 
[**getCompanies**](CompanyApi.md#getCompanies) | **POST** /api/Company/getCompanies | 
[**getCompany**](CompanyApi.md#getCompany) | **GET** /api/Company/getCompany | 
[**saveCompany**](CompanyApi.md#saveCompany) | **POST** /api/Company/saveCompany | 


# **deleteCompany**
> deleteCompany(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CompanyApi();
var id = id_example; // String | 

try { 
    api_instance.deleteCompany(id);
} catch (e) {
    print("Exception when calling CompanyApi->deleteCompany: $e\n");
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

# **getCompanies**
> QueryResultCompanyServiceModel getCompanies(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CompanyApi();
var request = new CompanyQueryRequest(); // CompanyQueryRequest | 

try { 
    var result = api_instance.getCompanies(request);
    print(result);
} catch (e) {
    print("Exception when calling CompanyApi->getCompanies: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CompanyQueryRequest**](CompanyQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultCompanyServiceModel**](QueryResultCompanyServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCompany**
> CompanyServiceModel getCompany(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CompanyApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getCompany(id);
    print(result);
} catch (e) {
    print("Exception when calling CompanyApi->getCompany: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**CompanyServiceModel**](CompanyServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveCompany**
> CompanyServiceModel saveCompany(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CompanyApi();
var model = new CompanyServiceModel(); // CompanyServiceModel | 

try { 
    var result = api_instance.saveCompany(model);
    print(result);
} catch (e) {
    print("Exception when calling CompanyApi->saveCompany: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**CompanyServiceModel**](CompanyServiceModel.md)|  | [optional] 

### Return type

[**CompanyServiceModel**](CompanyServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

