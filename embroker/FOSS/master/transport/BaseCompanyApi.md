# api_client.api.BaseCompanyApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteCompany**](BaseCompanyApi.md#deleteCompany) | **POST** /deleteCompany | 
[**getCompanies**](BaseCompanyApi.md#getCompanies) | **POST** /getCompanies | 
[**getCompany**](BaseCompanyApi.md#getCompany) | **GET** /getCompany | 
[**saveCompany**](BaseCompanyApi.md#saveCompany) | **POST** /saveCompany | 


# **deleteCompany**
> deleteCompany(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCompanyApi();
var id = id_example; // String | 

try { 
    api_instance.deleteCompany(id);
} catch (e) {
    print("Exception when calling BaseCompanyApi->deleteCompany: $e\n");
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

# **getCompanies**
> QueryResultCompanyServiceModel getCompanies(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCompanyApi();
var request = new CompanyQueryRequest(); // CompanyQueryRequest | 

try { 
    var result = api_instance.getCompanies(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseCompanyApi->getCompanies: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CompanyQueryRequest**](CompanyQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultCompanyServiceModel**](QueryResultCompanyServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCompany**
> CompanyServiceModel getCompany(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCompanyApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getCompany(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseCompanyApi->getCompany: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**CompanyServiceModel**](CompanyServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveCompany**
> CompanyServiceModel saveCompany(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseCompanyApi();
var model = new CompanyServiceModel(); // CompanyServiceModel | 

try { 
    var result = api_instance.saveCompany(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseCompanyApi->saveCompany: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**CompanyServiceModel**](CompanyServiceModel.md)|  | [optional] 

### Return type

[**CompanyServiceModel**](CompanyServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

