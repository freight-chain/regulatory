# api_client.model.AccountingInvoiceServiceModel

## Load the model package
```dart
import 'package:api_client/api.dart';
```

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**canSendInvoice** | **bool** |  | [optional] 
**id** | **String** |  | [optional] 
**fromId** | **String** |  | [optional] 
**from** | [**InvoiceParticipantServiceModel**](InvoiceParticipantServiceModel.md) |  | [optional] 
**toId** | **String** |  | [optional] 
**to** | [**InvoiceParticipantServiceModel**](InvoiceParticipantServiceModel.md) |  | [optional] 
**invoiceNumber** | **String** |  | [optional] 
**referenceType** | **String** |  | [optional] 
**referenceId** | **String** |  | [optional] 
**total** | **double** |  | [optional] 
**totalDelta** | **double** |  | [optional] 
**items** | [**List&lt;InvoiceItemServiceModel&gt;**](InvoiceItemServiceModel.md) |  | [optional] [default to []]
**reconciled** | **bool** |  | [optional] 
**type** | **int** |  | [optional] 
**status** | **int** |  | [optional] 
**documentId** | **String** |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


