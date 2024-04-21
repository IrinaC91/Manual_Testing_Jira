# Testing Project for Farmacia Tei
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. <br> <br>
Application under test: Farmacia Tei <br> <br>
Tools used: Jira, Zephyr Squad. <br> <br>

## Functional specifications:
The below stories were created in Jira and describe the functional specifications of the "Contul meu" module, for which the final project is performed upon.<br>

![story1](https://github.com/IrinaC91/Manual_Testing_Jira/assets/167686962/82df1a88-d395-4f81-a42d-7d464412901c)
![story2](https://github.com/IrinaC91/Manual_Testing_Jira/assets/167686962/c9874167-0160-4359-a763-666f2072e375)
![story3](https://github.com/IrinaC91/Manual_Testing_Jira/assets/167686962/e52a6325-2512-4c01-9082-c238203c7b12)
<br> <br>
Here you can find the release that was created for this project:
![epic](https://github.com/IrinaC91/Manual_Testing_Jira/assets/167686962/dfbb77b5-1c3b-445c-a032-3002228126de)

<br> <br>
## Testing process <br>
The test process was performed based on the standard test process as described below.

### 1.1 Test planning
The Test Plan is designed to describe all details of testing for the "Contul meu" module from the Farmacia Tei application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare) <br> **- trebuie sa fac test plan-ul, dar nu prea stiu exact cum sa-l adaptez. Daca imi poti da o directie, te rog.**

#### 1.1.1. Roles asigned to the project and persons allocated

 - Project manager - Barath Robert
 - Product owner - Ghera Laura
 - Software developer - Tanase Alina
 - QA Engineer - Cioabla Irina

#### 1.1.2 Entry criteria defined
 - The roles are alocated to the team members
 - The requirements are defined and approved
 - The test strategy is developed
 - The project risks are identified and mitigated
 - The test plan is created and approved
 - The test data is prepared
 - Test environment has been set-up and all other necessary resources such as tools and devices are available
 - The test cases are developed and approved

#### 1.1.3 Exit criteria defined
 - All the test cases have been alocated
 - All the test cases have been executed
 - Desired and sufficient coverage of the requirements and functionalities under the test
 - 90% of the faults have been corrected and closed
 - Regression testing is completed
 - No high priority or severity or critical bug has been left out
 - The project risks are identified and mitigated
 - The closing report has been generated and sent to the stakeholders

#### 1.1.4 Test scope
Tests in scope:
 - Positive / Negative testing
 - Functional testing
 - Usability testing
 - Equivalence partitioning
 - Boundary value analysis

Tests not in scope:
 - Security testing
 - Compatibility (with different browsers or devices)

#### 1.1.5 Risks detected - 
Project risks:
 - personnel issues
 - lack of good comunication between the testers 
 - unclear business requirements 
 - continuously changing requirements


Product risks:
 - delivery of a product that contains defects that lead to failure
 - inability of the product to meet the requirements
 - inability of the product to meet the customer's expectations
 - poor functionality of the application

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control

The role of test monitoring and control is critical in the overall software testing process. It involves overseeing, managing and maintaining control over various testing activities to ensure that testing objectives are met efficiently and effectively.

- Tracking progress
- Reporting status
- Resource management
- Risk management
- Defect management
- Desicion making
- Continuous improvement

![teste](https://github.com/IrinaC91/Manual_Testing_Jira/assets/167686962/e756337a-0313-434f-abae-5b217c184ba0)


### 1.3 Test Analysis,
The testing process will be executed based on the application requirements. <br>
The following test conditions were found:<br>

 - CIMT-12 - Verify that the "Favorite" section is properly displayed.
 - CIMT-14 - Verify that I can add a product to "Favorite" section
 - CIMT-15 - Verify that I can remove a product from "Favorite" section
 - CIMT-16 - Verify that the placed order is displayed in "Comenzile mele" section
 - CIMT-17 - Verify that I can view the order details
 - CIMT-18 - Verify that the vouchers are displayed in "Voucherele mele"
 - CIMT-20 - Verify that I can successfully add a credit card
 - CIMT-21 - Verify that I can't successfully add a credit card if I don't write the CVV
 - CIMT-22 - Verify that I can't add the same credit card twice
 - CIMT-24 - Verify that I can't successfully add a credit card if I don't select the year of expiration
 - CIMT-23 - Verify that I can successfully add a delivery address
 - CIMT-26 - Verify that I can't add a delivery address without filling the "Telefon" field
 - CIMT-28 - Verify that I can successfully delete a delivery address
<br>

### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here: 
[ZFJ-issue-export-04-21-2024.xlsx](https://github.com/IrinaC91/Manual_Testing_Jira/files/15052180/ZFJ-issue-export-04-21-2024.xlsx)
<br>
### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

 - Test case execution
 - Test data preparation
 - Environment setup
 - Tool configuration
 - Exection of test scripts
 - Defect reporting
 - Adherence to test procedures
 - Verification and validation
 - Documentation and reporting

### 1.6. Test Execution
Test cases are executed on the created test Cycle summary: FarmaciaTei v1. <br>

Bugs have been created based on the failed tests. The complete bug reports can be found here: 
[Bugs.xlsx](https://github.com/IrinaC91/Manual_Testing_Jira/files/15052268/Bugs.xlsx) . <br>

The following is a summary of the bugs that have been found:
 - CIMT-27 - ["Activitatea mea - Adresele mele"] - the address was successfully saved without the mandatory field "Telefon" <br>
severity: low impact <br>
priority: low <br>
 - CIMT-25 -  ["Activitatea mea - Cardurile mele"] - a new credit card is saved without the expiration year of the card <br>
severity: low impact <br>
priority: low <br>
- CIMT-19 - ["Activitatea mea" - "Voucherele mele"] - my voucher is not displayed in "Voucherele mele" <br>
severity: low impact <br>
priority: low <br>

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 
![image](https://github.com/IrinaC91/Manual_Testing_Jira/assets/167686962/d0c6b132-448c-462e-a1a9-51a03433bea3)

Test execution chart was generated and can be found below.
![image](https://github.com/IrinaC91/Manual_Testing_Jira/assets/167686962/a9d383d4-07c2-49cc-b597-579bdef3d2d8)


The final report shows that a number of 3 tests have failed of a total of 13. <br>

A number of 3 total bugs were found.<br>

A total of 13 tests have been created and executed. <br>
The bugs have a low impact, the final user is not significantly affected, but our recomandation is that the bugs should be fixed before launching.

