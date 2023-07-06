# Final_Project_Manual_Testing
### Introduction
---
The scope of the final project is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: [OrangeHRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)
(User Management submodule, Job submodule and Organization/General Information submodule) 

Documentation [https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf](https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf)

Tools used: JIRA, Zephyr Squad, MySQL Workbench.

The final project will be split into 2 sections: Testing section and SQL section.

### Functional specifications
---
![ _Story_1:_](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/story.png/PV-36%20(1).png)
![ _Story_2:_](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/story.png/PV-37.png)
![ _Story_3:_](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/story.png/PV-38.png)
![ _Story_4:_](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/story.png/PV-39.png)
![ _Story_5:_](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/story.png/PV-40.png)
![ _Story_6:_](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/story.png/PV-41.png)
![ _Story_7:_](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/story.png/PV-42.png)


### 1.Testing Section
---
#### 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the **"User Management"** and **"Job"** submodule from the **OrangeHRM** application.

The plan encompasses the identification of test items, the features targeted for testing, the various types of testing to be conducted, the designated personnel responsible for testing, the required resources and schedule to accomplish the testing, as well as the risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated
- Project manager - Sorin Marcu;   
- Product owner - Mihaela Ratiu;   
- Software developer - Baniuc Tudor;   
- QA Engenieer - Bura Viviana Mariam.

#### 1.1.2 Entry criteria defined
- Functional specifications are defined;
- Roles needed for the project are allocated;
- Initial project risks were detected and mitigated
- Hardware and software configuration is established.
- Input data is identified and prepared.
- Authentication sessions and permissions are configured according to requirements.
- The initial state of the system is set up and prepared for testing.
- Test scenarios are defined and documented.
- Non-functional requirements are specified and considered in the test plan.
- Expected results are clarified and documented.
- Risks and limitations associated with testing and the software system are identified and addressed.
#### 1.1.3 Exit criteria defined
- The number of critical or unresolved errors is minimal or zero;
- All planned tests have been completed;
- All resolved bugs have been retested and approved by the QA team;
- All functional and non-functional requirements have been tested and met;
- The system is free of critical;
- The necessary test reports have been generated and distributed;
- Users and clients have approved the test results;
- Deadline was reached;
- No detected major risk remained un-mitigated.
  

#### 1.1.4 Test scope
- Tests within scope: All the functionalities of the Admin module, as specified in the software requirement specifications, must undergo testing, including functional testing, exploratory testing, and GUI testing.
- Tests outside scope: Performance testing, security testing, integration of the Admin module with other modules, and compatibility testing with multiple browsers are not included in the testing activities.

#### 1.1.5 Risks detected
#### Project risks:
The QA team's lack of experience; incomplete and inaccurate requirement specifications; a short deadline for the Zephyr trial, the risk that certain serious defects may not be identified during testing and may reach the production environment;insufficient or inaccurate specifications of software functionalities that can lead to incorrect or incomplete testing.
#### Product risks:
Modules or features of the application that involve complex logic and can be more challenging to test and understand;the risk that the application fails to fully or satisfactorily meet the requirements and expectations of users; the application does not operate at the desired performance level, such as slow response times or slowdowns when handling demanding tasks.

#### 1.1.6 Evaluating entry criteria
The entry criterias defined in the Test Planning phase have been achieved and the project manager has reviewed and approved the test planning document and considers that the necessary conditions for starting the testing have been met.
### 1.2 Test Monitoring and Control
It will be done by Agile methodology.
### 1.3 Test Analysis
The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:

Enter test conditions here
### 1.4 Test Design
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are:

Test cases: -> enter here test cases or at least the titles

The test cases with steps can be viewed here: test_cases.pdf

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

enter here what needs to be ready for the test execution to begin
### 1.6 Test Execution
Test cases are executed on the created test Cycle summary: cycle_summary_execution.pdf
Bugs have been created based on the failed tests. The complete bug reports can be found here: created_bugs.pdf
enter here bug titles
### 1.7 Test Completion
Exit criteria was evaluated and passed
The traceability matrix was generated and can be found here: Traceability_matrix.csv
Test execution chart was generated, the final report shows.... -> describe the final report
-> enter here test execution report/chart

### 2 SQL section
