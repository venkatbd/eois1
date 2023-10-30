**Description**

 EI-3.4-US-EvidenceOfInsurabilityApplicationStatusRequest.json




**Parameters**


| Name                             | Type                         | Description                                                                                        |
|:---------------------------------|:-----------------------------|:---------------------------------------------------------------------------------------------------|
| TransmissionGUID                 | string                       | Global Unique identifier created by the originator for this instance of                            |
|                                  |                              |             the electronic transmission.                                                           |
| SenderName                       | string                       | Name of the company sending electronic benefit records on behalf of a                              |
|                                  |                              |             group.                                                                                 |
| SenderPlatformName               | string                       | Identifies the Sender's system that is providing the data for this data                            |
|                                  |                              |             set.                                                                                   |
| ReceiverName                     | string                       | Name of the company receiving electronic benefit records on behalf of a                            |
|                                  |                              |             group.                                                                                 |
| CreationDateTime                 | dateTime                     | UTC date and time the transmission was created.                                                    |
| TestProductionCode               | eois:TestProduction          | Indicates the elements contained in this data set are production or                                |
|                                  |                              |             test data.                                                                             |
| TransmissionTypeCode             | eois:TransmissionType        | The type of data contained within the data set.                                                    |
| SchemaVersionIdentifier          | eois:SchemaVersionNumber     | Identifies the version of the standard that is being adhered to in this                            |
|                                  |                              |             data set.                                                                              |
| Employer                         | eois:Employer                | An entity that employees people or is organized for a joint purpose.                               |
| EmployerPartyID                  | string                       | An unique identifier for each instance of an object established within                             |
|                                  |                              |             the context of a given transaction.                                                    |
| MasterAgreementNumber            | string                       | Carrier assigned group number. All individual policies or certificates                             |
|                                  |                              |             at the group level would roll up to this master group number. This may be the same as  |
|                                  |                              |             the agreement (aka policy) number for some carriers.                                   |
| EmployerName                     | string                       | This is a representation of the organizational entity's name.                                      |
| Employee                         | eois:Employee                | An individual who works part-time or full-time under a contract of                                 |
|                                  |                              |             employment, whether oral or written, express or implied, and has recognized rights and |
|                                  |                              |             duties.                                                                                |
| EmployeePartyID                  | string                       | An unique identifier for each instance of an object established within                             |
|                                  |                              |             the context of a given transaction.                                                    |
| EmployeeSocialSecurityNumber     | string                       | A numerical identifier assigned to U.S.citizens and some residents to                              |
|                                  |                              |             track their income.                                                                    |
| EmployeeIdentifier               | string                       | Employer or Plan Sponsor Issued Identifier.                                                        |
| EmployeeName                     | eois:StructuredPersonName    | This is a representation of the person entity's name. MiddleName -                                 |
|                                  |                              |             Optional - can be just a middle initial.                                               |
| FirstName                        | string                       | The person's name normally preceding the last name and typically used                              |
|                                  |                              |             to refer to the person in both formal and/or informal circumstances.                   |
| MiddleName                       | string                       | The additional names given to a person, usually at birth, and which                                |
|                                  |                              |             appear sequentially between the first name and last name.                              |
| LastName                         | string                       | The part of a person's name arising from family identifications.                                   |
| Coverage                         | eois:Coverage                | A risk or service based benefit associated with a categorization of                                |
|                                  |                              |             employees / members.                                                                   |
| CoverageID                       | string                       | An unique identifier for each instance of an object established within                             |
|                                  |                              |             the context of a given transaction.                                                    |
| GroupPolicyNumber                | string                       | Carrier assigned number for the group policy / agreement for which the                             |
|                                  |                              |             coverage may be associated.                                                            |
| IndividualPolicyNumber           | string                       | Carrier specific identifier indicating the benefit/product elected by                              |
|                                  |                              |             the member (this could be associated to one benefit or many)                           |
| ProductTypeCode                  | eois:ProductType             | Universal identifier for a specific logical product group that may be                              |
|                                  |                              |             elected by a member.                                                                   |
| BenefitPlanIdentifier            | string                       | Carrier specific identifier used to denote the plan being elected by                               |
|                                  |                              |             the member based on the product being purchased.                                       |
| BenefitFactor                    | decimal                      | The benefit multiple or percentage factor for the defined type (e.g.,                              |
|                                  |                              |             approved), when the benefit is not a flat dollar amount.                               |
| ElectedCoverage                  | eois:ElectedCoverage         | The risk elected for a person by way of insurance products and                                     |
|                                  |                              |             coverages.                                                                             |
| ElectedBenefitFactor             | decimal                      | The benefit multiple or percentage factor for the defined type (e.g.,                              |
|                                  |                              |             elected), when the benefit is not a flat dollar amount.                                |
| ElectedCoverageInsured           | eois:CoverageInsured         | The insured person associated with their respective elected benefit                                |
|                                  |                              |             plans, for example an Employee or a Dependent.                                         |
| InsuredPartyID                   | string                       | An unique identifier for each instance of an object established within                             |
|                                  |                              |             the context of a given transaction.                                                    |
| PrimaryInsuredIndicator          | boolean                      | A flag that indicates whether the Insured associated with the Benefit                              |
|                                  |                              |             Plan is the primary insured.                                                           |
| TobaccoUseIndicator              | boolean                      | Denotes if the Employee and/or Spouse is a tobacco user.                                           |
| InsuredCoverageEffectiveDate     | date                         | Earliest date of continuous coverage for this insured in the associated                            |
|                                  |                              |             benefit plan. Separate benefit effective dates must be sent for each dependent covered |
|                                  |                              |             under the benefit plan.                                                                |
| CoverageInsured                  | eois:CoverageInsured         | Associates a given Insured to their respective coverages, for example                              |
|                                  |                              |             an Employee or a Dependent.                                                            |
| InsuredPartyID                   | string                       | An unique identifier for each instance of an object established within                             |
|                                  |                              |             the context of a given transaction.                                                    |
| PrimaryInsuredIndicator          | boolean                      | A flag that indicates whether the Insured associated with the Benefit                              |
|                                  |                              |             Plan is the primary insured.                                                           |
| TobaccoUseIndicator              | boolean                      | Denotes if the Employee and/or Spouse is a tobacco user.                                           |
| InsuredCoverageEffectiveDate     | date                         | Earliest date of continuous coverage for this insured in the associated                            |
|                                  |                              |             benefit plan. Separate benefit effective dates must be sent for each dependent covered |
|                                  |                              |             under the benefit plan.                                                                |
| UnderwritingStatus               | eois:UnderwritingStatus      | Represents the state of the evidence of insurability application and                               |
|                                  |                              |             subsequent decision made by the carrier's underwriter.                                 |
| EvidenceChannelCode              | eois:EvidenceChannel         | The medium for initial questions and answers requested by the Carrier.                             |
|                                  |                              |             Requirement: Optional                                                                  |
| ApplicationStatusCode            | eois:ApplicationStatus       | Describes the status of the application with the Carrier.                                          |
| ApplicationStatusReasonCode      | eois:ApplicationStatusReason | Describes the why behind the ApplicationStatusCode, which may be used                              |
|                                  |                              |             by the Technology Partner to further describe to the member a more granular definition |
|                                  |                              |             of where their EOI application is at in the process.                                   |
| ApplicationStatusDateTime        | dateTime                     | Date and time the EOI Application status was set.                                                  |
| Audit                            | eois:Audit                   | No documentation available                                                                         |
| AuditID                          | string                       | Unique identifier created by the originator for this instance of the                               |
|                                  |                              |             electronic transmission.                                                               |
| EmployerRecordQuantity           | int                          | A count of Employer records included in the electronic transmission.                               |
| EmployeeRecordQuantity           | int                          | A count of Employer records included in the electronic transmission.                               |
| DependentRecordQuantity          | int                          | A count of Dependent records included in the electronic transmission.                              |
| CoverageRecordQuantity           | int                          | A count of Coverage records included in the electronic transmission.                               |
| UnderwritingStatusRecordQuantity | int                          | A count of UnderwritingDecision records included in the electronic                                 |
|                                  |                              |             transmission.                                                                          |

```json

{
  "eois:Transmission": {
    "@xmlns:xsi": "http://www.w3.org/2001/XMLSchema-instance",
    "@xmlns:eois": "https://ldex.limra.com/xsd/1.0/LDExEOIS",
    "@xsi:schemaLocation": "https://ldex.limra.com/xsd/1.0/LDExEOIS_1.0.2022.01.01.xsd",
    "TransmissionGUID": "18ff0807-d121-41b9-9494-e0c7da701225",
    "SenderName": "Carrier A",
    "SenderPlatformName": "Carrier Platform C",
    "ReceiverName": "Benefit Administrator B",
    "CreationDateTime": "2020-04-01T21:49:45",
    "TestProductionCode": "Test",
    "TransmissionTypeCode": "ChangesOnly",
    "SchemaVersionIdentifier": "1.0.2022.01.01",
    "Employer": {
      "EmployerPartyID": "10021",
      "MasterAgreementNumber": "GROUP1234",
      "EmployerName": "Group Name 1234",
      "Employee": {
        "EmployeePartyID": "90001",
        "EmployeeSocialSecurityNumber": "123-45-6789",
        "EmployeeIdentifier": null,
        "EmployeeName": {
          "FirstName": "Bob",
          "MiddleName": null,
          "LastName": "Ross"
        },
        "Coverage": {
          "CoverageID": "1",
          "GroupPolicyNumber": "GROUP_POLICY_NUMBER_1",
          "IndividualPolicyNumber": null,
          "ProductTypeCode": "Life",
          "BenefitPlanIdentifier": "VGTL",
          "BenefitFactor": "1",
          "ElectedCoverage": {
            "ElectedBenefitFactor": "3",
            "ElectedCoverageInsured": {
              "InsuredPartyID": "90001",
              "PrimaryInsuredIndicator": "true",
              "TobaccoUseIndicator": "false",
              "InsuredCoverageEffectiveDate": "2020-05-01"
            }
          },
          "CoverageInsured": {
            "InsuredPartyID": "90001",
            "PrimaryInsuredIndicator": "true",
            "TobaccoUseIndicator": "false",
            "InsuredCoverageEffectiveDate": "2020-05-01"
          },
          "UnderwritingStatus": {
            "EvidenceChannelCode": "Web",
            "ApplicationStatusCode": "Pending",
            "ApplicationStatusReasonCode": "CarrierIsReviewing",
            "ApplicationStatusDateTime": "2020-03-29T09:49:45"
          }
        }
      }
    },
    "Audit": {
      "AuditID": null,
      "EmployerRecordQuantity": "1",
      "EmployeeRecordQuantity": "1",
      "DependentRecordQuantity": "0",
      "CoverageRecordQuantity": "1",
      "UnderwritingStatusRecordQuantity": "1"
    }
  }
}
```
