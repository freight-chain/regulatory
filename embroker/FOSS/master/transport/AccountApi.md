# api_client.api.AccountApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**activateAccountWithPassword**](AccountApi.md#activateAccountWithPassword) | **POST** /api/Account/activateAccountWithPassword | 
[**confirmEmail**](AccountApi.md#confirmEmail) | **POST** /api/Account/confirmEmail | 
[**createCompanySubdomain**](AccountApi.md#createCompanySubdomain) | **POST** /api/Account/company/subdomain/{id} | 
[**createPermission**](AccountApi.md#createPermission) | **POST** /api/Account/permissions | 
[**createRole**](AccountApi.md#createRole) | **POST** /api/Account/roles | 
[**deleteCompany**](AccountApi.md#deleteCompany) | **DELETE** /api/Account/companies/{id} | 
[**deletePermission**](AccountApi.md#deletePermission) | **DELETE** /api/Account/permissions/{id} | 
[**deleteRole**](AccountApi.md#deleteRole) | **DELETE** /api/Account/roles/{id} | 
[**deleteUser**](AccountApi.md#deleteUser) | **DELETE** /api/Account/users/{id} | 
[**forgotPassword**](AccountApi.md#forgotPassword) | **POST** /api/Account/forgotPassword | 
[**getAllPermissions**](AccountApi.md#getAllPermissions) | **GET** /api/Account/permissions | 
[**getCompanies**](AccountApi.md#getCompanies) | **POST** /api/Account/companies | 
[**getCompany**](AccountApi.md#getCompany) | **GET** /api/Account/company | 
[**getCompanyById**](AccountApi.md#getCompanyById) | **GET** /api/Account/company/{id} | 
[**getCurrentUser**](AccountApi.md#getCurrentUser) | **GET** /api/Account/users/me | 
[**getRoleById**](AccountApi.md#getRoleById) | **GET** /api/Account/roles/{id} | 
[**getRoleByName**](AccountApi.md#getRoleByName) | **GET** /api/Account/roles/name/{name} | 
[**getRoles**](AccountApi.md#getRoles) | **GET** /api/Account/roles | 
[**getRolesEditable**](AccountApi.md#getRolesEditable) | **GET** /api/Account/roles/editable | 
[**getRolesEditablePaging**](AccountApi.md#getRolesEditablePaging) | **GET** /api/Account/roles/editable/{page}/{pageSize} | 
[**getRoles_0**](AccountApi.md#getRoles_0) | **GET** /api/Account/roles/{page}/{pageSize} | 
[**getUserById**](AccountApi.md#getUserById) | **GET** /api/Account/users/{id} | 
[**getUserByUserName**](AccountApi.md#getUserByUserName) | **GET** /api/Account/users/username/{userName} | 
[**getUsers**](AccountApi.md#getUsers) | **GET** /api/Account/users | 
[**getUsersByCurrentCompany**](AccountApi.md#getUsersByCurrentCompany) | **GET** /api/Account/users/company | 
[**getUsersByCurrentCompany_0**](AccountApi.md#getUsersByCurrentCompany_0) | **GET** /api/Account/users/company/{page}/{pageSize} | 
[**getUsers_0**](AccountApi.md#getUsers_0) | **GET** /api/Account/users/{page}/{pageSize}/{companyId} | 
[**register**](AccountApi.md#register) | **POST** /api/Account/users | 
[**registerCompany**](AccountApi.md#registerCompany) | **POST** /api/Account/registerCompany | 
[**registerUserForCurrentCompany**](AccountApi.md#registerUserForCurrentCompany) | **POST** /api/Account/users/company | 
[**resendAccountActivationEmail**](AccountApi.md#resendAccountActivationEmail) | **POST** /api/Account/resendAccountActivationEmail | 
[**resetPassword**](AccountApi.md#resetPassword) | **POST** /api/Account/resetPassword | 
[**unblockUser**](AccountApi.md#unblockUser) | **PUT** /api/Account/users/unblock/{id} | 
[**updateCompany**](AccountApi.md#updateCompany) | **POST** /api/Account/company | 
[**updateCurrentUser**](AccountApi.md#updateCurrentUser) | **PUT** /api/Account/users/me | 
[**updateCurrentUser_0**](AccountApi.md#updateCurrentUser_0) | **PATCH** /api/Account/users/me | 
[**updatePermission**](AccountApi.md#updatePermission) | **PUT** /api/Account/permissions/{id} | 
[**updateRole**](AccountApi.md#updateRole) | **PUT** /api/Account/roles/{id} | 
[**updateUser**](AccountApi.md#updateUser) | **PUT** /api/Account/users/{id} | 
[**updateUser_0**](AccountApi.md#updateUser_0) | **PATCH** /api/Account/users/{id} | 
[**userPreferences**](AccountApi.md#userPreferences) | **GET** /api/Account/users/me/preferences | 
[**userPreferences_0**](AccountApi.md#userPreferences_0) | **PUT** /api/Account/users/me/preferences | 


# **activateAccountWithPassword**
> activateAccountWithPassword(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var model = new ResetPasswordViewModel(); // ResetPasswordViewModel | 

try { 
    api_instance.activateAccountWithPassword(model);
} catch (e) {
    print("Exception when calling AccountApi->activateAccountWithPassword: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ResetPasswordViewModel**](ResetPasswordViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **confirmEmail**
> confirmEmail(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var model = new ConfirmEmailViewModel(); // ConfirmEmailViewModel | 

try { 
    api_instance.confirmEmail(model);
} catch (e) {
    print("Exception when calling AccountApi->confirmEmail: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ConfirmEmailViewModel**](ConfirmEmailViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createCompanySubdomain**
> CompanyServiceModel createCompanySubdomain(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    var result = api_instance.createCompanySubdomain(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->createCompanySubdomain: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**CompanyServiceModel**](CompanyServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createPermission**
> PermissionViewModel createPermission(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var model = new PermissionViewModel(); // PermissionViewModel | 

try { 
    var result = api_instance.createPermission(model);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->createPermission: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**PermissionViewModel**](PermissionViewModel.md)|  | [optional] 

### Return type

[**PermissionViewModel**](PermissionViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createRole**
> createRole(role)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var role = new RoleViewModel(); // RoleViewModel | 

try { 
    api_instance.createRole(role);
} catch (e) {
    print("Exception when calling AccountApi->createRole: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **role** | [**RoleViewModel**](RoleViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteCompany**
> CompanyServiceModel deleteCompany(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    var result = api_instance.deleteCompany(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->deleteCompany: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**CompanyServiceModel**](CompanyServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deletePermission**
> PermissionViewModel deletePermission(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    var result = api_instance.deletePermission(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->deletePermission: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**PermissionViewModel**](PermissionViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteRole**
> RoleViewModel deleteRole(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    var result = api_instance.deleteRole(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->deleteRole: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**RoleViewModel**](RoleViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteUser**
> UserViewModel deleteUser(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    var result = api_instance.deleteUser(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->deleteUser: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**UserViewModel**](UserViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **forgotPassword**
> forgotPassword(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var model = new ForgotPasswordViewModel(); // ForgotPasswordViewModel | 

try { 
    api_instance.forgotPassword(model);
} catch (e) {
    print("Exception when calling AccountApi->forgotPassword: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ForgotPasswordViewModel**](ForgotPasswordViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAllPermissions**
> List<PermissionViewModel> getAllPermissions()



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();

try { 
    var result = api_instance.getAllPermissions();
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getAllPermissions: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List<PermissionViewModel>**](PermissionViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCompanies**
> QueryResultCompanyServiceModel getCompanies(query)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var query = new Query(); // Query | 

try { 
    var result = api_instance.getCompanies(query);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getCompanies: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | [**Query**](Query.md)|  | [optional] 

### Return type

[**QueryResultCompanyServiceModel**](QueryResultCompanyServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCompany**
> CompanyServiceModel getCompany()



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();

try { 
    var result = api_instance.getCompany();
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getCompany: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**CompanyServiceModel**](CompanyServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCompanyById**
> CompanyViewModel getCompanyById(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getCompanyById(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getCompanyById: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**CompanyViewModel**](CompanyViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCurrentUser**
> UserViewModel getCurrentUser()



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();

try { 
    var result = api_instance.getCurrentUser();
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getCurrentUser: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**UserViewModel**](UserViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRoleById**
> RoleViewModel getRoleById(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getRoleById(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getRoleById: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**RoleViewModel**](RoleViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRoleByName**
> RoleViewModel getRoleByName(name)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var name = name_example; // String | 

try { 
    var result = api_instance.getRoleByName(name);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getRoleByName: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **String**|  | 

### Return type

[**RoleViewModel**](RoleViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRoles**
> List<RoleViewModel> getRoles()



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();

try { 
    var result = api_instance.getRoles();
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getRoles: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List<RoleViewModel>**](RoleViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRolesEditable**
> List<RoleViewModel> getRolesEditable()



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();

try { 
    var result = api_instance.getRolesEditable();
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getRolesEditable: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List<RoleViewModel>**](RoleViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRolesEditablePaging**
> List<RoleViewModel> getRolesEditablePaging(page, pageSize)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var page = 56; // int | 
var pageSize = 56; // int | 

try { 
    var result = api_instance.getRolesEditablePaging(page, pageSize);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getRolesEditablePaging: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**|  | 
 **pageSize** | **int**|  | 

### Return type

[**List<RoleViewModel>**](RoleViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRoles_0**
> List<RoleViewModel> getRoles_0(page, pageSize, onlyEditableRoles)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var page = 56; // int | 
var pageSize = 56; // int | 
var onlyEditableRoles = true; // bool | 

try { 
    var result = api_instance.getRoles_0(page, pageSize, onlyEditableRoles);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getRoles_0: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**|  | 
 **pageSize** | **int**|  | 
 **onlyEditableRoles** | **bool**|  | [optional] [default to false]

### Return type

[**List<RoleViewModel>**](RoleViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUserById**
> UserViewModel getUserById(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getUserById(id);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getUserById: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**UserViewModel**](UserViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUserByUserName**
> UserViewModel getUserByUserName(userName)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var userName = userName_example; // String | 

try { 
    var result = api_instance.getUserByUserName(userName);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getUserByUserName: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userName** | **String**|  | 

### Return type

[**UserViewModel**](UserViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUsers**
> List<UserViewModel> getUsers()



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();

try { 
    var result = api_instance.getUsers();
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getUsers: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List<UserViewModel>**](UserViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUsersByCurrentCompany**
> List<UserViewModel> getUsersByCurrentCompany()



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();

try { 
    var result = api_instance.getUsersByCurrentCompany();
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getUsersByCurrentCompany: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List<UserViewModel>**](UserViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUsersByCurrentCompany_0**
> List<UserViewModel> getUsersByCurrentCompany_0(page, pageSize)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var page = 56; // int | 
var pageSize = 56; // int | 

try { 
    var result = api_instance.getUsersByCurrentCompany_0(page, pageSize);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getUsersByCurrentCompany_0: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**|  | 
 **pageSize** | **int**|  | 

### Return type

[**List<UserViewModel>**](UserViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUsers_0**
> List<UserViewModel> getUsers_0(page, pageSize, companyId)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var page = 56; // int | 
var pageSize = 56; // int | 
var companyId = companyId_example; // String | 

try { 
    var result = api_instance.getUsers_0(page, pageSize, companyId);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->getUsers_0: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int**|  | 
 **pageSize** | **int**|  | 
 **companyId** | **String**|  | [optional] 

### Return type

[**List<UserViewModel>**](UserViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **register**
> register(user)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var user = new UserEditViewModel(); // UserEditViewModel | 

try { 
    api_instance.register(user);
} catch (e) {
    print("Exception when calling AccountApi->register: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user** | [**UserEditViewModel**](UserEditViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **registerCompany**
> registerCompany(registration)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var registration = new RegisterCompanyViewModel(); // RegisterCompanyViewModel | 

try { 
    api_instance.registerCompany(registration);
} catch (e) {
    print("Exception when calling AccountApi->registerCompany: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **registration** | [**RegisterCompanyViewModel**](RegisterCompanyViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **registerUserForCurrentCompany**
> registerUserForCurrentCompany(user)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var user = new UserEditViewModel(); // UserEditViewModel | 

try { 
    api_instance.registerUserForCurrentCompany(user);
} catch (e) {
    print("Exception when calling AccountApi->registerUserForCurrentCompany: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user** | [**UserEditViewModel**](UserEditViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **resendAccountActivationEmail**
> resendAccountActivationEmail(email)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var email = email_example; // String | 

try { 
    api_instance.resendAccountActivationEmail(email);
} catch (e) {
    print("Exception when calling AccountApi->resendAccountActivationEmail: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **email** | **String**|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **resetPassword**
> resetPassword(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var model = new ResetPasswordViewModel(); // ResetPasswordViewModel | 

try { 
    api_instance.resetPassword(model);
} catch (e) {
    print("Exception when calling AccountApi->resetPassword: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ResetPasswordViewModel**](ResetPasswordViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **unblockUser**
> unblockUser(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 

try { 
    api_instance.unblockUser(id);
} catch (e) {
    print("Exception when calling AccountApi->unblockUser: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateCompany**
> CompanyServiceModel updateCompany(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var model = new CompanyServiceModel(); // CompanyServiceModel | 

try { 
    var result = api_instance.updateCompany(model);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->updateCompany: $e\n");
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

# **updateCurrentUser**
> updateCurrentUser(user)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var user = new UserEditViewModel(); // UserEditViewModel | 

try { 
    api_instance.updateCurrentUser(user);
} catch (e) {
    print("Exception when calling AccountApi->updateCurrentUser: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user** | [**UserEditViewModel**](UserEditViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateCurrentUser_0**
> updateCurrentUser_0(patch)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var patch = [new List&lt;Operation&gt;()]; // List<Operation> | 

try { 
    api_instance.updateCurrentUser_0(patch);
} catch (e) {
    print("Exception when calling AccountApi->updateCurrentUser_0: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **patch** | [**List&lt;Operation&gt;**](Operation.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updatePermission**
> PermissionViewModel updatePermission(id, model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 
var model = new PermissionViewModel(); // PermissionViewModel | 

try { 
    var result = api_instance.updatePermission(id, model);
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->updatePermission: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 
 **model** | [**PermissionViewModel**](PermissionViewModel.md)|  | [optional] 

### Return type

[**PermissionViewModel**](PermissionViewModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateRole**
> updateRole(id, role)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 
var role = new RoleViewModel(); // RoleViewModel | 

try { 
    api_instance.updateRole(id, role);
} catch (e) {
    print("Exception when calling AccountApi->updateRole: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 
 **role** | [**RoleViewModel**](RoleViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateUser**
> updateUser(id, user)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 
var user = new UserEditViewModel(); // UserEditViewModel | 

try { 
    api_instance.updateUser(id, user);
} catch (e) {
    print("Exception when calling AccountApi->updateUser: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 
 **user** | [**UserEditViewModel**](UserEditViewModel.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateUser_0**
> updateUser_0(id, patch)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var id = id_example; // String | 
var patch = [new List&lt;Operation&gt;()]; // List<Operation> | 

try { 
    api_instance.updateUser_0(id, patch);
} catch (e) {
    print("Exception when calling AccountApi->updateUser_0: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 
 **patch** | [**List&lt;Operation&gt;**](Operation.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **userPreferences**
> String userPreferences()



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();

try { 
    var result = api_instance.userPreferences();
    print(result);
} catch (e) {
    print("Exception when calling AccountApi->userPreferences: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

**String**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **userPreferences_0**
> userPreferences_0(data)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new AccountApi();
var data = new String(); // String | 

try { 
    api_instance.userPreferences_0(data);
} catch (e) {
    print("Exception when calling AccountApi->userPreferences_0: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **data** | **String**|  | [optional] 

### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

