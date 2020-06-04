# api_client.model.CarrierQuoteRequestServiceModel

## Load the model package
```dart
import 'package:api_client/api.dart';
```

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **String** |  | [optional] 
**shipmentId** | **String** |  | [optional] 
**quotePrice** | **double** |  | [optional] 
**status** | **int** |  | [optional] 
**requestedTimestamp** | [**DateTime**](DateTime.md) |  | [optional] 
**responseTimestamp** | [**DateTime**](DateTime.md) |  | [optional] 
**companyId** | **String** |  | [optional] 
**shipperCompany** | [**CompanyServiceModel**](CompanyServiceModel.md) |  | [optional] 
**auditTrail** | [**List&lt;AuditTrailServiceModel&gt;**](AuditTrailServiceModel.md) |  | [optional] [default to []]
**terms** | **int** |  | [optional] 
**createdBy** | [**UserServiceModel**](UserServiceModel.md) |  | [optional] 
**lastModifiedBy** | [**UserServiceModel**](UserServiceModel.md) |  | [optional] 
**additionalInformation** | [**CarrierAdditionalInfoServiceModel**](CarrierAdditionalInfoServiceModel.md) |  | [optional] 
**brokerCompany** | [**CompanyServiceModel**](CompanyServiceModel.md) |  | [optional] 
**isSubscribed** | **bool** |  | [optional] 
**lineItems** | [**List&lt;ShipmentFeeServiceModel&gt;**](ShipmentFeeServiceModel.md) |  | [optional] [default to []]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


