# api_client.api.BaseShipmentApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**acceptShipment**](BaseShipmentApi.md#acceptShipment) | **POST** /acceptShipment | 
[**begin**](BaseShipmentApi.md#begin) | **POST** /begin | 
[**complete**](BaseShipmentApi.md#complete) | **POST** /complete | 
[**deleteShipment**](BaseShipmentApi.md#deleteShipment) | **POST** /deleteShipment | 
[**getShipment**](BaseShipmentApi.md#getShipment) | **GET** /getShipment | 
[**getShipments**](BaseShipmentApi.md#getShipments) | **POST** /getShipments | 
[**refreshPartners**](BaseShipmentApi.md#refreshPartners) | **POST** /refreshPartners | 
[**saveShipment**](BaseShipmentApi.md#saveShipment) | **POST** /saveShipment | 
[**shipmentCancel**](BaseShipmentApi.md#shipmentCancel) | **POST** /shipmentCancel | 
[**shipmentDecline**](BaseShipmentApi.md#shipmentDecline) | **POST** /shipmentDecline | 
[**trackingSettings**](BaseShipmentApi.md#trackingSettings) | **POST** /trackingSettings | 


# **acceptShipment**
> ShipmentServiceModel acceptShipment(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var request = new AcceptShipmentRequest(); // AcceptShipmentRequest | 

try { 
    var result = api_instance.acceptShipment(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->acceptShipment: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**AcceptShipmentRequest**](AcceptShipmentRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **begin**
> ShipmentServiceModel begin(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var request = new BeginRequest(); // BeginRequest | 

try { 
    var result = api_instance.begin(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->begin: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**BeginRequest**](BeginRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **complete**
> ShipmentServiceModel complete(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var request = new CompleteRequest(); // CompleteRequest | 

try { 
    var result = api_instance.complete(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->complete: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CompleteRequest**](CompleteRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteShipment**
> deleteShipment(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var id = id_example; // String | 

try { 
    api_instance.deleteShipment(id);
} catch (e) {
    print("Exception when calling BaseShipmentApi->deleteShipment: $e\n");
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

# **getShipment**
> ShipmentServiceModel getShipment(id)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getShipment(id);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->getShipment: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getShipments**
> QueryResultShipmentServiceModel getShipments(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var request = new ShipmentQueryRequest(); // ShipmentQueryRequest | 

try { 
    var result = api_instance.getShipments(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->getShipments: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipmentQueryRequest**](ShipmentQueryRequest.md)|  | [optional] 

### Return type

[**QueryResultShipmentServiceModel**](QueryResultShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **refreshPartners**
> ShipmentServiceModel refreshPartners(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var request = new RefreshPartnersRequest(); // RefreshPartnersRequest | 

try { 
    var result = api_instance.refreshPartners(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->refreshPartners: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**RefreshPartnersRequest**](RefreshPartnersRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveShipment**
> ShipmentServiceModel saveShipment(model)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var model = new ShipmentServiceModel(); // ShipmentServiceModel | 

try { 
    var result = api_instance.saveShipment(model);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->saveShipment: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**ShipmentServiceModel**](ShipmentServiceModel.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **shipmentCancel**
> ShipmentServiceModel shipmentCancel(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var request = new ShipmentCancelRequest(); // ShipmentCancelRequest | 

try { 
    var result = api_instance.shipmentCancel(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->shipmentCancel: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipmentCancelRequest**](ShipmentCancelRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **shipmentDecline**
> ShipmentServiceModel shipmentDecline(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var request = new ShipmentDeclineRequest(); // ShipmentDeclineRequest | 

try { 
    var result = api_instance.shipmentDecline(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->shipmentDecline: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ShipmentDeclineRequest**](ShipmentDeclineRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **trackingSettings**
> ShipmentServiceModel trackingSettings(request)



### Example 
```dart
import 'package:api_client/api.dart';

var api_instance = new BaseShipmentApi();
var request = new TrackingSettingsRequest(); // TrackingSettingsRequest | 

try { 
    var result = api_instance.trackingSettings(request);
    print(result);
} catch (e) {
    print("Exception when calling BaseShipmentApi->trackingSettings: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**TrackingSettingsRequest**](TrackingSettingsRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

