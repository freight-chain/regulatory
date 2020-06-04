# api_client.api.CarrierQuoteRequestApi

## Load the API package
```dart
import 'package:api_client/api.dart';
```

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteCarrierQuoteRequest**](CarrierQuoteRequestApi.md#deleteCarrierQuoteRequest) | **POST** /api/CarrierQuoteRequest/deleteCarrierQuoteRequest | 
[**getCarrierQuoteRequest**](CarrierQuoteRequestApi.md#getCarrierQuoteRequest) | **GET** /api/CarrierQuoteRequest/getCarrierQuoteRequest | 
[**getCarrierquoterequests**](CarrierQuoteRequestApi.md#getCarrierquoterequests) | **POST** /api/CarrierQuoteRequest/getCarrierquoterequests | 
[**getPickupAppointment**](CarrierQuoteRequestApi.md#getPickupAppointment) | **GET** /api/CarrierQuoteRequest/getPickupAppointment | 
[**saveAdditionalInformation**](CarrierQuoteRequestApi.md#saveAdditionalInformation) | **POST** /api/CarrierQuoteRequest/saveAdditionalInformation | 
[**saveCarrierQuoteRequest**](CarrierQuoteRequestApi.md#saveCarrierQuoteRequest) | **POST** /api/CarrierQuoteRequest/saveCarrierQuoteRequest | 
[**savePickupAppointment**](CarrierQuoteRequestApi.md#savePickupAppointment) | **POST** /api/CarrierQuoteRequest/savePickupAppointment | 
[**sendCounterOffer**](CarrierQuoteRequestApi.md#sendCounterOffer) | **POST** /api/CarrierQuoteRequest/sendCounterOffer | 
[**sendQuote**](CarrierQuoteRequestApi.md#sendQuote) | **POST** /api/CarrierQuoteRequest/sendQuote | 


# **deleteCarrierQuoteRequest**
> CarrierQuoteRequestServiceModel deleteCarrierQuoteRequest(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var id = id_example; // String | 

try { 
    var result = api_instance.deleteCarrierQuoteRequest(id);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->deleteCarrierQuoteRequest: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**CarrierQuoteRequestServiceModel**](CarrierQuoteRequestServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCarrierQuoteRequest**
> CarrierQuoteRequestServiceModel getCarrierQuoteRequest(id)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var id = id_example; // String | 

try { 
    var result = api_instance.getCarrierQuoteRequest(id);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->getCarrierQuoteRequest: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | [optional] 

### Return type

[**CarrierQuoteRequestServiceModel**](CarrierQuoteRequestServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getCarrierquoterequests**
> QueryResultCarrierQuoteRequestServiceModel getCarrierquoterequests(query)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var query = new Query(); // Query | 

try { 
    var result = api_instance.getCarrierquoterequests(query);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->getCarrierquoterequests: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | [**Query**](Query.md)|  | [optional] 

### Return type

[**QueryResultCarrierQuoteRequestServiceModel**](QueryResultCarrierQuoteRequestServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getPickupAppointment**
> PickupAppointmentServiceModel getPickupAppointment(carrierQuoteRequestId)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var carrierQuoteRequestId = carrierQuoteRequestId_example; // String | 

try { 
    var result = api_instance.getPickupAppointment(carrierQuoteRequestId);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->getPickupAppointment: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **carrierQuoteRequestId** | **String**|  | [optional] 

### Return type

[**PickupAppointmentServiceModel**](PickupAppointmentServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveAdditionalInformation**
> CarrierQuoteRequestServiceModel saveAdditionalInformation(carrierQuoteRequestId, model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var carrierQuoteRequestId = carrierQuoteRequestId_example; // String | 
var model = new CarrierAdditionalInfoServiceModel(); // CarrierAdditionalInfoServiceModel | 

try { 
    var result = api_instance.saveAdditionalInformation(carrierQuoteRequestId, model);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->saveAdditionalInformation: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **carrierQuoteRequestId** | **String**|  | [optional] 
 **model** | [**CarrierAdditionalInfoServiceModel**](CarrierAdditionalInfoServiceModel.md)|  | [optional] 

### Return type

[**CarrierQuoteRequestServiceModel**](CarrierQuoteRequestServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **saveCarrierQuoteRequest**
> CarrierQuoteRequestServiceModel saveCarrierQuoteRequest(model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var model = new CarrierQuoteRequestServiceModel(); // CarrierQuoteRequestServiceModel | 

try { 
    var result = api_instance.saveCarrierQuoteRequest(model);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->saveCarrierQuoteRequest: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | [**CarrierQuoteRequestServiceModel**](CarrierQuoteRequestServiceModel.md)|  | [optional] 

### Return type

[**CarrierQuoteRequestServiceModel**](CarrierQuoteRequestServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **savePickupAppointment**
> PickupAppointmentServiceModel savePickupAppointment(carrierQuoteRequestId, model)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var carrierQuoteRequestId = carrierQuoteRequestId_example; // String | 
var model = new PickupAppointmentServiceModel(); // PickupAppointmentServiceModel | 

try { 
    var result = api_instance.savePickupAppointment(carrierQuoteRequestId, model);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->savePickupAppointment: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **carrierQuoteRequestId** | **String**|  | [optional] 
 **model** | [**PickupAppointmentServiceModel**](PickupAppointmentServiceModel.md)|  | [optional] 

### Return type

[**PickupAppointmentServiceModel**](PickupAppointmentServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sendCounterOffer**
> ShipmentServiceModel sendCounterOffer(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var request = new CarrierCounterOfferLoadRequest(); // CarrierCounterOfferLoadRequest | 

try { 
    var result = api_instance.sendCounterOffer(request);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->sendCounterOffer: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CarrierCounterOfferLoadRequest**](CarrierCounterOfferLoadRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sendQuote**
> ShipmentServiceModel sendQuote(request)



### Example 
```dart
import 'package:api_client/api.dart';
// TODO Configure OAuth2 access token for authorization: oauth2
//api_client.api.Configuration.accessToken = 'YOUR_ACCESS_TOKEN';

var api_instance = new CarrierQuoteRequestApi();
var request = new CarrierApproveLoadRequest(); // CarrierApproveLoadRequest | 

try { 
    var result = api_instance.sendQuote(request);
    print(result);
} catch (e) {
    print("Exception when calling CarrierQuoteRequestApi->sendQuote: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**CarrierApproveLoadRequest**](CarrierApproveLoadRequest.md)|  | [optional] 

### Return type

[**ShipmentServiceModel**](ShipmentServiceModel.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json-patch+json, application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

