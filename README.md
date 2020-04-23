# Compliance and Regulatory Disclosures and Transparency for Instruments

## Corporate 
For Document Retention Policies, GDPR, CCPA, and other Generalized Compliance please see our [omnibus documentation](https://freight-chain.github.io/obm)


#### Instrumentalisation Process: Bringing about dematerialization at-scale while retaining contractual/property rights


##### Generalized Instrument Wrapping Facility
Parts of this are licensed under the BSD-3 Clause License, Apache 2.0 and MIT. No AGPL Licnesed products are used.

**ERC777 implementation - Advanced token standard for asset transfers**

* Empowerment of operators with the ability to send tokens on behalf of other addresses.
* Setup of send/receive hooks to offer token holders more control over their tokens.
* Use of ER820\(eips.ethereum.org/EIPS/eip-820\) to notify contracts and regular addresses when they receive tokens.
* Backwards compatible with ERC20.

**ERC1400 implementation - Partially fungible token standard**

* Differentiated ownership / transparent restrictions.
* Controller operations \(force transfer\).
* On-chain restriction checking with error signalling, off-chain data injection for transfer restrictions and issuance/redemption semantics.
* Document management.
* Backwards compatible with ERC20 and ERC777.

**Ethereum Registration Authority / Trusted Certificate Authority**

```
Data Field for Signature Injection <Triggering_Event>

function transferWithData(address recipient, uint256 value, bytes data)
```

**ERC1643 implementation**

AddressID specifies which package is used for that operation/interrogative and subordinate clauses

Enables Agreement to be as homogenized or unique as needed, thereby extending the possibility of liquidity for layer 2+ applications.
<br>


##### Definitions and Specifications 

<br>
a **registry** is a deployed contract which manages a collection of packages.

a **package** is a collection of releases

a **package** is identified by a unique string name and unique bytes32 packageId within a given registry

a** release** is identified by a bytes32 releaseId which must be unique for a given package name and release version string pair.

a** releaseId **maps to a set of data that includes a manifestURI string which describes the location of an EIP 1123 package manifest. This manifest contains data about the release including the location of its component code assets.

a **manifestURI** is a URI as defined by RFC3986 which can be used to retrieve the contents of the package manifest. In addition to validation against RFC3986, each manifestURI must also contain a hash of the content as specified in the EIP 1123.

a l**ibrary** is a static set of standard contracts like SafeMath. **libsol **is the authoritative library.

the **Kernel** compromises interlocking contracts that execute operations by invocation or trigger

```
Registry -> Package [libsol, kernel...] -> Release [specific contract updates] -> latest release
```

**Stand Alone:**    Package has no external dependencies \(i.e. no build\_dependencies\), contains all contract data needed without reaching into another package.

**Dependent:   ** Package does not contain all necessary contract data \(i.e. has build\_dependencies\), must reach into a package dependency to retrieve data.

**Inheritable**:    Contract doesn’t provide useful functionality on its own and is meant to serve as a base contract for others to inherit from.

**Reusable: **   Contract is useful on it’s own, meant to be used as-is. This applies only to kernel level contracts.

**Deployed Contract/Library:**

```
 Refers to an instance of a contract/library that has already been deployed to a specific address on a chain.
```

**Package Dependency:**

```
 External dependency directly referenced via the build\_dependencies of the package.
```

**Deep Dependency:**

```
 External dependency referenced via the build\_dependencies of a package dependency 
 (or by reaching down dependency tree as far as necessary\).
``

| &lt;/&gt; | Action |
| :--- | :--- |
| defaultOperator | Freight Trust, _Network Operations _ |
| AuthorizedOperator | 3rd Party \(e.g. Invoice Factoring, Insurance, etc\) |
| RevokedOperator | Default: 0 |
| setManager | Deployed On-Contracts, _Network Operations_ |
| getAttributeTypeID | interger |
| hasAttribute | string |
| symbol | Self Describing Contract Parameters |
| documentationIdentification | <string_prefix]little einden |


| legalAgreement | ... |
| masterAgreement | ... |
| tradeAgreement | . |
| uniqueAgreement | . |
| effectiveDate | . |
| eventDate | . |
| eventQualifier | . |
| eventIdentifier | . |
| lineage | . |
| contractKeyUID | . |
|  |  |

Object	Description
event_time	The exact time (UNIX timestamp) the event occurred.
event_type	The type of event that occurred.
event_hash	The unique hash of the event that occurred.
meta.related_document_hash	The unique document hash this event is associated with.
meta.related_user_id	The user identification this event is associated with. (Sender User ID)
meta.related_business_id	The business ID this event is associated with. (Sender Business ID)
meta.related_app_id	If this event is sent as part of a webhook notification for a specific app, this will contain the associated App ID.
signer.id	The signer ID this event is associated with.
signer.name	The name of the signer this event is associated with.
signer.email	The email address of the signer this event is associated with.
signer.role	The role of the signer this event is associated with. (Templates only)
signer.order	The signer order sequence number of the signer this event is associated with.\

Software Licensed under the BSD-3 Clause License
Text Licensed under the (CC BY-NC-ND 2.5) w/ an exception for Academic Derivative works clause. (c) 2019 Freight Trust & Clearing Corporation.



#### Corporate Contact 

FreightTrust and Clearing Corporation

Office:
246 Brannan Street, San Francisco CA 94107

Corporate Mailing:
1424 4th St Ste 214 PMB 1513 Santa Monica, CA 90401

Limited Parntership Mailing:
20929 Ventura Blvd STE 47-327
Woodland Hills, CA 91364

General Contact
Email: Admin@FreightTrust.com
Tel: 628-222-5915
Fax: 818-457-5660

<<<<<<< HEAD
Bloomberg LEI: Pending <br>
NFA: Pending <br>
DUNS: 117388893 <br>
SCAC: FGHG<br>

## Security
priority messages: admin@freighttrust.com with subject "Priority: <your subject here>"
---
Software Licensed under the BSD-3 Clause License
Text Licensed under the (CC BY-NC-ND 2.5) w/ an exception for Academic Derivative works clause. (c) 2019 Freight Trust & Clearing Corporation.
=======
Bloomberg LEI: Pending
NFA: Pending
DUNS: 117388893
>>>>>>> parent of f22cb56... references and pdfs
