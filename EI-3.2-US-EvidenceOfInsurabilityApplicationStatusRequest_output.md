**Description**

 EI-3.2-US-EvidenceOfInsurabilityApplicationStatusRequest.json




**Parameters**


| Name                             | Type                           | Description                                                                                          |
|:---------------------------------|:-------------------------------|:-----------------------------------------------------------------------------------------------------|
| TransmissionGUID                 | string                         | Global Unique identifier created by the originator for this instance of                              |
|                                  |                                |             the electronic transmission.                                                             |
| SenderName                       | string                         | Name of the company sending electronic benefit records on behalf of a                                |
|                                  |                                |             group.                                                                                   |
| SenderPlatformName               | string                         | Identifies the Sender's system that is providing the data for this data                              |
|                                  |                                |             set.                                                                                     |
| ReceiverName                     | string                         | Name of the company receiving electronic benefit records on behalf of a                              |
|                                  |                                |             group.                                                                                   |
| CreationDateTime                 | dateTime                       | UTC date and time the transmission was created.                                                      |
| TestProductionCode               | eois:TestProduction            | Indicates the elements contained in this data set are production or                                  |
|                                  |                                |             test data.                                                                               |
| TransmissionTypeCode             | eois:TransmissionType          | The type of data contained within the data set.                                                      |
| SchemaVersionIdentifier          | eois:SchemaVersionNumber       | Identifies the version of the standard that is being adhered to in this                              |
|                                  |                                |             data set.                                                                                |
| Employer                         | eois:Employer                  | An entity that employees people or is organized for a joint purpose.                                 |
| EmployerPartyID                  | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| MasterAgreementNumber            | string                         | Carrier assigned group number. All individual policies or certificates                               |
|                                  |                                |             at the group level would roll up to this master group number. This may be the same as    |
|                                  |                                |             the agreement (aka policy) number for some carriers.                                     |
| EmployerName                     | string                         | This is a representation of the organizational entity's name.                                        |
| Employee                         | eois:Employee                  | An individual who works part-time or full-time under a contract of                                   |
|                                  |                                |             employment, whether oral or written, express or implied, and has recognized rights and   |
|                                  |                                |             duties.                                                                                  |
| EmployeePartyID                  | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| EmployeeSocialSecurityNumber     | string                         | A numerical identifier assigned to U.S.citizens and some residents to                                |
|                                  |                                |             track their income.                                                                      |
| EmployeeIdentifier               | string                         | Employer or Plan Sponsor Issued Identifier.                                                          |
| EmployeeName                     | eois:StructuredPersonName      | This is a representation of the person entity's name. MiddleName -                                   |
|                                  |                                |             Optional - can be just a middle initial.                                                 |
| FirstName                        | string                         | The person's name normally preceding the last name and typically used                                |
|                                  |                                |             to refer to the person in both formal and/or informal circumstances.                     |
| MiddleName                       | string                         | The additional names given to a person, usually at birth, and which                                  |
|                                  |                                |             appear sequentially between the first name and last name.                                |
| LastName                         | string                         | The part of a person's name arising from family identifications.                                     |
| Dependent                        | eois:Dependent                 | Person who relies on another, especially a family member, for financial                              |
|                                  |                                |             support.                                                                                 |
| DependentPartyID                 | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| DependentSocialSecurityNumber    | string                         | A numerical identifier assigned to U.S.citizens and some residents to                                |
|                                  |                                |             track their income.                                                                      |
| DependentName                    | eois:StructuredPersonName      | This is a representation of the person entity's name.                                                |
| FirstName                        | string                         | The person's name normally preceding the last name and typically used                                |
|                                  |                                |             to refer to the person in both formal and/or informal circumstances.                     |
| MiddleName                       | string                         | The additional names given to a person, usually at birth, and which                                  |
|                                  |                                |             appear sequentially between the first name and last name.                                |
| LastName                         | string                         | The part of a person's name arising from family identifications.                                     |
| DependentRelationshipTypeCode    | eois:DependentRelationshipType | Relationship of the dependent to the employee.                                                       |
| Coverage                         | eois:Coverage                  | A risk or service based benefit associated with a categorization of                                  |
|                                  |                                |             employees / members.                                                                     |
| CoverageID                       | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| GroupPolicyNumber                | string                         | Carrier assigned number for the group policy / agreement for which the                               |
|                                  |                                |             coverage may be associated.                                                              |
| IndividualPolicyNumber           | string                         | Carrier specific identifier indicating the benefit/product elected by                                |
|                                  |                                |             the member (this could be associated to one benefit or many)                             |
| ProductTypeCode                  | eois:ProductType               | Universal identifier for a specific logical product group that may be                                |
|                                  |                                |             elected by a member.                                                                     |
| BenefitPlanIdentifier            | string                         | Carrier specific identifier used to denote the plan being elected by                                 |
|                                  |                                |             the member based on the product being purchased.                                         |
| BenefitAmount                    | decimal                        | Value of approved coverage, based on the defined plan rules for the                                  |
|                                  |                                |             enrolling person.                                                                        |
| ElectedCoverage                  | eois:ElectedCoverage           | The risk elected for a person by way of insurance products and                                       |
|                                  |                                |             coverages.                                                                               |
| ElectedBenefitAmount             | decimal                        | Value of the coverage being asked for (aka elected) based on the                                     |
|                                  |                                |             defined plan rules for the enrolling person.                                             |
| ElectedCoverageInsured           | eois:CoverageInsured           | The insured person associated with their respective elected benefit                                  |
|                                  |                                |             plans, for example an Employee or a Dependent.                                           |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| CoverageInsured                  | eois:CoverageInsured           | Associates a given Insured to their respective coverages, for example                                |
|                                  |                                |             an Employee or a Dependent.                                                              |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| UnderwritingStatus               | eois:UnderwritingStatus        | Represents the state of the evidence of insurability application and                                 |
|                                  |                                |             subsequent decision made by the carrier's underwriter.                                   |
| EvidenceChannelCode              | eois:EvidenceChannel           | The medium for initial questions and answers requested by the Carrier.                               |
|                                  |                                |             Requirement: Optional                                                                    |
| ApplicationStatusCode            | eois:ApplicationStatus         | Describes the status of the application with the Carrier.                                            |
| ApplicationStatusDateTime        | dateTime                       | Date and time the EOI Application status was set.                                                    |
| CoverageID                       | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| GroupPolicyNumber                | string                         | Carrier assigned number for the group policy / agreement for which the                               |
|                                  |                                |             coverage may be associated.                                                              |
| IndividualPolicyNumber           | string                         | Carrier specific identifier indicating the benefit/product elected by                                |
|                                  |                                |             the member (this could be associated to one benefit or many)                             |
| ProductTypeCode                  | eois:ProductType               | Universal identifier for a specific logical product group that may be                                |
|                                  |                                |             elected by a member.                                                                     |
| BenefitPlanIdentifier            | string                         | Carrier specific identifier used to denote the plan being elected by                                 |
|                                  |                                |             the member based on the product being purchased.                                         |
| BenefitAmount                    | decimal                        | Value of approved coverage, based on the defined plan rules for the                                  |
|                                  |                                |             enrolling person.                                                                        |
| ElectedCoverage                  | eois:ElectedCoverage           | The risk elected for a person by way of insurance products and                                       |
|                                  |                                |             coverages.                                                                               |
| ElectedBenefitAmount             | decimal                        | Value of the coverage being asked for (aka elected) based on the                                     |
|                                  |                                |             defined plan rules for the enrolling person.                                             |
| ElectedCoverageInsured           | eois:CoverageInsured           | The insured person associated with their respective elected benefit                                  |
|                                  |                                |             plans, for example an Employee or a Dependent.                                           |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| CoverageInsured                  | eois:CoverageInsured           | Associates a given Insured to their respective coverages, for example                                |
|                                  |                                |             an Employee or a Dependent.                                                              |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| UnderwritingStatus               | eois:UnderwritingStatus        | Represents the state of the evidence of insurability application and                                 |
|                                  |                                |             subsequent decision made by the carrier's underwriter.                                   |
| EvidenceChannelCode              | eois:EvidenceChannel           | The medium for initial questions and answers requested by the Carrier.                               |
|                                  |                                |             Requirement: Optional                                                                    |
| ApplicationStatusCode            | eois:ApplicationStatus         | Describes the status of the application with the Carrier.                                            |
| ApplicationStatusDateTime        | dateTime                       | Date and time the EOI Application status was set.                                                    |
| CoverageID                       | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| GroupPolicyNumber                | string                         | Carrier assigned number for the group policy / agreement for which the                               |
|                                  |                                |             coverage may be associated.                                                              |
| IndividualPolicyNumber           | string                         | Carrier specific identifier indicating the benefit/product elected by                                |
|                                  |                                |             the member (this could be associated to one benefit or many)                             |
| ProductTypeCode                  | eois:ProductType               | Universal identifier for a specific logical product group that may be                                |
|                                  |                                |             elected by a member.                                                                     |
| BenefitPlanIdentifier            | string                         | Carrier specific identifier used to denote the plan being elected by                                 |
|                                  |                                |             the member based on the product being purchased.                                         |
| BenefitFactor                    | decimal                        | The benefit multiple or percentage factor for the defined type (e.g.,                                |
|                                  |                                |             approved), when the benefit is not a flat dollar amount.                                 |
| ElectedCoverage                  | eois:ElectedCoverage           | The risk elected for a person by way of insurance products and                                       |
|                                  |                                |             coverages.                                                                               |
| ElectedBenefitFactor             | decimal                        | The benefit multiple or percentage factor for the defined type (e.g.,                                |
|                                  |                                |             elected), when the benefit is not a flat dollar amount.                                  |
| ElectedCoverageInsured           | eois:CoverageInsured           | The insured person associated with their respective elected benefit                                  |
|                                  |                                |             plans, for example an Employee or a Dependent.                                           |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| CoverageInsured                  | eois:CoverageInsured           | Associates a given Insured to their respective coverages, for example                                |
|                                  |                                |             an Employee or a Dependent.                                                              |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| UnderwritingStatus               | eois:UnderwritingStatus        | Represents the state of the evidence of insurability application and                                 |
|                                  |                                |             subsequent decision made by the carrier's underwriter.                                   |
| EvidenceChannelCode              | eois:EvidenceChannel           | The medium for initial questions and answers requested by the Carrier.                               |
|                                  |                                |             Requirement: Optional                                                                    |
| ApplicationStatusCode            | eois:ApplicationStatus         | Describes the status of the application with the Carrier.                                            |
| ApplicationStatusDateTime        | dateTime                       | Date and time the EOI Application status was set.                                                    |
| CoverageID                       | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| GroupPolicyNumber                | string                         | Carrier assigned number for the group policy / agreement for which the                               |
|                                  |                                |             coverage may be associated.                                                              |
| IndividualPolicyNumber           | string                         | Carrier specific identifier indicating the benefit/product elected by                                |
|                                  |                                |             the member (this could be associated to one benefit or many)                             |
| ProductTypeCode                  | eois:ProductType               | Universal identifier for a specific logical product group that may be                                |
|                                  |                                |             elected by a member.                                                                     |
| BenefitPlanIdentifier            | string                         | Carrier specific identifier used to denote the plan being elected by                                 |
|                                  |                                |             the member based on the product being purchased.                                         |
| BenefitFactor                    | decimal                        | The benefit multiple or percentage factor for the defined type (e.g.,                                |
|                                  |                                |             approved), when the benefit is not a flat dollar amount.                                 |
| ElectedCoverage                  | eois:ElectedCoverage           | The risk elected for a person by way of insurance products and                                       |
|                                  |                                |             coverages.                                                                               |
| ElectedBenefitFactor             | decimal                        | The benefit multiple or percentage factor for the defined type (e.g.,                                |
|                                  |                                |             elected), when the benefit is not a flat dollar amount.                                  |
| ElectedCoverageInsured           | eois:CoverageInsured           | The insured person associated with their respective elected benefit                                  |
|                                  |                                |             plans, for example an Employee or a Dependent.                                           |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| CoverageInsured                  | eois:CoverageInsured           | Associates a given Insured to their respective coverages, for example                                |
|                                  |                                |             an Employee or a Dependent.                                                              |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| UnderwritingStatus               | eois:UnderwritingStatus        | Represents the state of the evidence of insurability application and                                 |
|                                  |                                |             subsequent decision made by the carrier's underwriter.                                   |
| EvidenceChannelCode              | eois:EvidenceChannel           | The medium for initial questions and answers requested by the Carrier.                               |
|                                  |                                |             Requirement: Optional                                                                    |
| ApplicationStatusCode            | eois:ApplicationStatus         | Describes the status of the application with the Carrier.                                            |
| ApplicationStatusDateTime        | dateTime                       | Date and time the EOI Application status was set.                                                    |
| CoverageID                       | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| GroupPolicyNumber                | string                         | Carrier assigned number for the group policy / agreement for which the                               |
|                                  |                                |             coverage may be associated.                                                              |
| IndividualPolicyNumber           | string                         | Carrier specific identifier indicating the benefit/product elected by                                |
|                                  |                                |             the member (this could be associated to one benefit or many)                             |
| ProductTypeCode                  | eois:ProductType               | Universal identifier for a specific logical product group that may be                                |
|                                  |                                |             elected by a member.                                                                     |
| BenefitPlanIdentifier            | string                         | Carrier specific identifier used to denote the plan being elected by                                 |
|                                  |                                |             the member based on the product being purchased.                                         |
| CoverageTierCode                 | eois:CoverageTier              | Universal level of coverage being elected by the employee (including                                 |
|                                  |                                |             dependents) or provided by the group based on the selected benefit plan type.            |
| BenefitAmount                    | decimal                        | Value of approved coverage, based on the defined plan rules for the                                  |
|                                  |                                |             enrolling person.                                                                        |
| ElectedCoverage                  | eois:ElectedCoverage           | The risk elected for a person by way of insurance products and                                       |
|                                  |                                |             coverages.                                                                               |
| ElectedCoverageTierCode          | eois:CoverageTier              | Universal level of coverage being elected by the employee (including                                 |
|                                  |                                |             dependents) or provided by the group based on the selected benefit plan type.            |
|                                  |                                |             Situational, required for Tier-based coverages else not required. When CoverageTierCode  |
|                                  |                                |             is used, CoverageInsured(s) are optional. However, when CoverageInsured(s) are included, |
|                                  |                                |             the following rules apply: CoverageInsured for the Employee is not valid for             |
|                                  |                                |             CoverageTierCode values of SpouseOnly, ChildOnly, SpouseDependent, SpouseChildren.       |
|                                  |                                |             Employee must be included for all other tiers. CoverageInsured for a Spouse or Partner   |
|                                  |                                |             is not valid for CoverageTierCode values of Employee, EmployeeChildren and ChildOnly.    |
|                                  |                                |             CoverageInsured for Spouse/Partner is required for EmployeeSpouse, SpouseOnly,           |
|                                  |                                |             SpouseDependent and SpouseChildren tiers. CoverageInsured for Spouse/Partner is optional |
|                                  |                                |             for the remaining tier values. CoverageInsured for non-spouse/non-partner dependents is  |
|                                  |                                |             not valid for Employee, EmployeeSpouse and SpouseOnly tiers, and is optional for all     |
|                                  |                                |             other tiers. Note that the valid, eligible relationship values for any given tier in a   |
|                                  |                                |             benefit will be defined by the Carrier.                                                  |
| ElectedBenefitAmount             | decimal                        | Value of the coverage being asked for (aka elected) based on the                                     |
|                                  |                                |             defined plan rules for the enrolling person.                                             |
| ElectedCoverageInsured           | eois:CoverageInsured           | The insured person associated with their respective elected benefit                                  |
|                                  |                                |             plans, for example an Employee or a Dependent.                                           |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| CoverageInsured                  | eois:CoverageInsured           | Associates a given Insured to their respective coverages, for example                                |
|                                  |                                |             an Employee or a Dependent.                                                              |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| InsuredPartyID                   | string                         | An unique identifier for each instance of an object established within                               |
|                                  |                                |             the context of a given transaction.                                                      |
| PrimaryInsuredIndicator          | boolean                        | A flag that indicates whether the Insured associated with the Benefit                                |
|                                  |                                |             Plan is the primary insured.                                                             |
| TobaccoUseIndicator              | boolean                        | Denotes if the Employee and/or Spouse is a tobacco user.                                             |
| InsuredCoverageEffectiveDate     | date                           | Earliest date of continuous coverage for this insured in the associated                              |
|                                  |                                |             benefit plan. Separate benefit effective dates must be sent for each dependent covered   |
|                                  |                                |             under the benefit plan.                                                                  |
| UnderwritingStatus               | eois:UnderwritingStatus        | Represents the state of the evidence of insurability application and                                 |
|                                  |                                |             subsequent decision made by the carrier's underwriter.                                   |
| EvidenceChannelCode              | eois:EvidenceChannel           | The medium for initial questions and answers requested by the Carrier.                               |
|                                  |                                |             Requirement: Optional                                                                    |
| ApplicationStatusCode            | eois:ApplicationStatus         | Describes the status of the application with the Carrier.                                            |
| ApplicationStatusDateTime        | dateTime                       | Date and time the EOI Application status was set.                                                    |
| Audit                            | eois:Audit                     | No documentation available                                                                           |
| AuditID                          | string                         | Unique identifier created by the originator for this instance of the                                 |
|                                  |                                |             electronic transmission.                                                                 |
| EmployerRecordQuantity           | int                            | A count of Employer records included in the electronic transmission.                                 |
| EmployeeRecordQuantity           | int                            | A count of Employer records included in the electronic transmission.                                 |
| DependentRecordQuantity          | int                            | A count of Dependent records included in the electronic transmission.                                |
| CoverageRecordQuantity           | int                            | A count of Coverage records included in the electronic transmission.                                 |
| UnderwritingStatusRecordQuantity | int                            | A count of UnderwritingDecision records included in the electronic                                   |
|                                  |                                |             transmission.                                                                            |

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
        "Dependent": {
          "DependentPartyID": "80001",
          "DependentSocialSecurityNumber": "123-45-6788",
          "DependentIdentifier": null,
          "DependentName": {
            "FirstName": "Sue",
            "MiddleName": null,
            "LastName": "Ross"
          },
          "DependentRelationshipTypeCode": "Spouse"
        },
        "Coverage": [
          {
            "CoverageID": "1",
            "GroupPolicyNumber": "GROUP_POLICY_NUMBER_1",
            "IndividualPolicyNumber": null,
            "ProductTypeCode": "Life",
            "BenefitPlanIdentifier": "VGTL",
            "BenefitAmount": "50000",
            "ElectedCoverage": {
              "ElectedBenefitAmount": "150000",
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
              "ApplicationStatusCode": "NotStarted",
              "ApplicationStatusDateTime": "2020-03-29T09:49:45"
            }
          },
          {
            "CoverageID": "2",
            "GroupPolicyNumber": "GROUP_POLICY_NUMBER_1",
            "IndividualPolicyNumber": null,
            "ProductTypeCode": "Life",
            "BenefitPlanIdentifier": "VGTLSP",
            "BenefitAmount": "20000",
            "ElectedCoverage": {
              "ElectedBenefitAmount": "100000",
              "ElectedCoverageInsured": {
                "InsuredPartyID": "80001",
                "PrimaryInsuredIndicator": "false",
                "TobaccoUseIndicator": "false",
                "InsuredCoverageEffectiveDate": "2020-05-01"
              }
            },
            "CoverageInsured": {
              "InsuredPartyID": "80001",
              "PrimaryInsuredIndicator": "false",
              "TobaccoUseIndicator": "false",
              "InsuredCoverageEffectiveDate": "2020-05-01"
            },
            "UnderwritingStatus": {
              "EvidenceChannelCode": "Web",
              "ApplicationStatusCode": "NotStarted",
              "ApplicationStatusDateTime": "2020-03-29T09:49:45"
            }
          },
          {
            "CoverageID": "3",
            "GroupPolicyNumber": "GROUP_POLICY_NUMBER_1",
            "IndividualPolicyNumber": null,
            "ProductTypeCode": "STD",
            "BenefitPlanIdentifier": "VSTD",
            "BenefitFactor": "0.40",
            "ElectedCoverage": {
              "ElectedBenefitFactor": "0.65",
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
              "ApplicationStatusCode": "NotStarted",
              "ApplicationStatusDateTime": "2020-03-29T09:49:45"
            }
          },
          {
            "CoverageID": "4",
            "GroupPolicyNumber": "GROUP_POLICY_NUMBER_1",
            "IndividualPolicyNumber": null,
            "ProductTypeCode": "LTD",
            "BenefitPlanIdentifier": "VLTD",
            "BenefitFactor": "0.40",
            "ElectedCoverage": {
              "ElectedBenefitFactor": "0.60",
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
              "ApplicationStatusCode": "NotStarted",
              "ApplicationStatusDateTime": "2020-03-29T09:49:45"
            }
          },
          {
            "CoverageID": "5",
            "GroupPolicyNumber": "GROUP_POLICY_NUMBER_7",
            "IndividualPolicyNumber": null,
            "ProductTypeCode": "CriticalIllness",
            "BenefitPlanIdentifier": "CI",
            "CoverageTierCode": "EmployeeSpouse",
            "BenefitAmount": "10000",
            "ElectedCoverage": {
              "ElectedCoverageTierCode": "EmployeeSpouse",
              "ElectedBenefitAmount": "20000",
              "ElectedCoverageInsured": [
                {
                  "InsuredPartyID": "90001",
                  "PrimaryInsuredIndicator": "true",
                  "TobaccoUseIndicator": "false",
                  "InsuredCoverageEffectiveDate": "2020-05-01"
                },
                {
                  "InsuredPartyID": "80001",
                  "PrimaryInsuredIndicator": "false",
                  "TobaccoUseIndicator": "false",
                  "InsuredCoverageEffectiveDate": "2020-05-01"
                }
              ]
            },
            "CoverageInsured": [
              {
                "InsuredPartyID": "90001",
                "PrimaryInsuredIndicator": "true",
                "TobaccoUseIndicator": "false",
                "InsuredCoverageEffectiveDate": "2020-05-01"
              },
              {
                "InsuredPartyID": "80001",
                "PrimaryInsuredIndicator": "true",
                "TobaccoUseIndicator": "false",
                "InsuredCoverageEffectiveDate": "2020-05-01"
              }
            ],
            "UnderwritingStatus": {
              "EvidenceChannelCode": "Web",
              "ApplicationStatusCode": "NotStarted",
              "ApplicationStatusDateTime": "2020-03-29T09:49:45"
            }
          }
        ]
      }
    },
    "Audit": {
      "AuditID": null,
      "EmployerRecordQuantity": "1",
      "EmployeeRecordQuantity": "1",
      "DependentRecordQuantity": "1",
      "CoverageRecordQuantity": "5",
      "UnderwritingStatusRecordQuantity": "5"
    }
  }
}
```
