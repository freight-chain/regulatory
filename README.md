# Compliance and Regulatory Disclosures and Transparency for Instruments

## Corporate 
For Document Retention Policies, GDPR, CCPA, and other Generalized Compliance please see our [omnibus documentation](https://freight-chain.github.io/obm)



500.02 Cybersecurity Program 
500.03 Cybersecurity Policy
500.07 Access Privileges 
500.09 Risk Assessment 
500.1 Third Party Service Provider
500.13 Limitations on Data Retention
500.17 Notices to Superintendent
500.18 Confidentiality
500.19 Exemptions 
500.20 Enforcement
500.21 Effective Date 
500.22 Transitional Periods
500.23 Severability 

## MiFR Reports generated 
```markdown
<header>
	body Authority ESMA
body Authority FCA
body Organisation ISDA

corpus Regulation "600/2014" MiFIR
	

corpus Regulation "648/2012" EMIR
	

corpus CommissionDelegatedRegulation "2017/590" RTS_22
	 

corpus CommissionDelegatedRegulation "148/2013" ITS_9
	

corpus ESMA_Q_and_A "09April 2019|ESMA70-1861941480-56" Q_AND_A_MiFIR_DATA_REPORTING
	


corpus ReportingStandard "ISO 20022" ISO_20022
	

segment rationale
segment rationale_author
segment structured_provision

segment article
segment whereas
segment annex
segment table
segment section
segment field
segment paragraph
segment question
	
	<end header>
```

```markdown
report ESMA MiFIR RTS_22 in T+1
	when MifirInvestmentFirm and ReportableTransaction and ReportableProduct
	using standard ISO_20022 with fields
		ReportStatus
		TransactionReferenceNumber
		TradingVenueTransactionIdentificationCode
		ExecutingEntityIdentificationCode
		IsInvestmentFirm
		SubmittingEntityIdentificationCode
		BuyerSeller
		TransmissionOfOrderIndicator
		TradingDateTime
		TradingCapacity
		Quantity
		Price
		Venue
		CountryOfTheBranchMembership
		InstrumentIdentificationCode
		InstrumentFullName
		InstrumentClassification
		NotionalCurrency1
		NotionalCurrency2
		PriceMultiplier
		UnderlyingInstrumentCode
		UnderlyingIndexName
		UnderlyingIndexTermPeriod
		UnderlyingIndexTermMultiplier
		ExpiryDate
    ```
		DeliveryType
		InvestmentDecisionWithinFirm
		PersonResponsibleForInvestmentDecisionCountry
		ExecutionWithinFirm
		PersonResponsibleForExecutionCountry
		CommodityDerivativeIndicator
		SecuritiesFinancingTransactionIndicator
