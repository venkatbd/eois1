**Description**

 EI-3.1-US-EvidenceOfInsurabilityApplicationStatusRequest-Response.json




**Parameters**


| Name                   | Type          | Description                                                             |
|:-----------------------|:--------------|:------------------------------------------------------------------------|
| TransmissionGUID       | string        | Global Unique identifier created by the originator for this instance of |
|                        |               |             the electronic transmission.                                |
| CreationDateTime       | dateTime      | UTC date and time the transmission was created.                         |
| EmployerPartyID        | string        | An unique identifier for each instance of an object established within  |
|                        |               |             the context of a given transaction.                         |
| EmployeePartyID        | string        | An unique identifier for each instance of an object established within  |
|                        |               |             the context of a given transaction.                         |
| Coverage               | eois:Coverage | A risk or service based benefit associated with a categorization of     |
|                        |               |             employees / members.                                        |
| Audit                  | eois:Audit    | No documentation available                                              |
| AuditID                | string        | Unique identifier created by the originator for this instance of the    |
|                        |               |             electronic transmission.                                    |
| EmployerRecordQuantity | int           | A count of Employer records included in the electronic transmission.    |
| EmployeeRecordQuantity | int           | A count of Employer records included in the electronic transmission.    |
| CoverageRecordQuantity | int           | A count of Coverage records included in the electronic transmission.    |

```json

{
  "rsp:TransmissionResponse": {
    "@xmlns:rsp": "https://ldex.limra.com/xsd/1.0/LDExRSP",
    "@xmlns:xsi": "http://www.w3.org/2001/XMLSchema-instance",
    "@xsi:schemaLocation": "https://ldex.limra.com/xsd/1.0/LDExRSP_1.3.2022.01.01.xsd",
    "TransmissionGUID": "9cbd7bb6-9132-11ea-bb37-0242ac130002",
    "TransmissionStatusCode": "Failure",
    "CreationDateTime": "2020-05-08T10:05:42",
    "TransactionDetail": {
      "EmployerPartyID": "ER1520",
      "EmployeePartyID": "EE987650",
      "TransactionRemark": {
        "EntityCode": "Coverage",
        "EntityReferenceID": "C123456",
        "RemarkStatusCode": "Error",
        "MessageTypeCode": "UnknownCoverageOrApplicant",
        "MessageText": "Not Started - No Record Found as Carrier has no knowledge of the enrolled\n\t\t\t\tcoverage identified in the request"
      }
    },
    "Audit": {
      "AuditID": "A4567890",
      "EmployerRecordQuantity": "1",
      "EmployeeRecordQuantity": "1",
      "CoverageRecordQuantity": "1"
    }
  }
}
```
