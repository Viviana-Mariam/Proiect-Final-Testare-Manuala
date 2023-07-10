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
As an approach in the monitoring and control process, we were guided by the **Agile Scrum** methodology

- Product Backlog – prioritization of testing according to requirements 
- Sprint – prioritization of testing according to requirements
- Daily Scrum – a one-on-one session with the mentor for a few minutes in which we discussed the tests performed, if there are any impediments and what is next in the testing
- Sprint Planning Meeting – a short planning session of the following tasks 
- Sprint Retrospective – at the end of the sprint week, different status reports were generated

### 1.3 Test Analysis
After all the business requirements were clarified in a **Review** process, I created the following test conditions:

(To view the original list as created in **Jira** [click here](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/tree/main/Jira_test_condition) )

Test condition, list 1:

![test condition list 1](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/test_condition/test_condition_list1.jpg)

Test condition, list 2:

![test condition list 2](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/test_condition/test_condition_list2.jpg)


### 1.4 Test Design
The application was tested through the static testing technique (Review) and through the black box dynamic testing techniques (boundary value analysis,equivalence partitioning) .
Functional test cases were created in Zephyr Squad.

![test_cases 1](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/test.jpg%20(2)/Screenshot%20test.jpg)


  For the full list with test cases [click here](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/tests.pdf/Book1.pdf)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

- Verifying the integrity of the test environment - ensuring that the test environment is fully functional and there are no technical issues that could affect testing.

- Ensuring the availability of test data - providing and validating the test data necessary to execute the planned test cases, such as authentication data, basic test data or other specific data (username: Admin; password: admin123).

- Test tool setup - setup and preparation of test tools required for test execution,the cycle summary is created and the test cases to be executed are added to the cycle summary.
### 1.6 Test Execution

![bug_list](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/jira_bug.jpg%20(2)/ScreenshotBugJira.jpg)
For the bug with steps [click here](https://github.com/Viviana-Mariam/Proiect-Final-Testare-Manuala/blob/main/bug_jira.pdf/PDF%20(Jira).pdf)


### 1.7 Test Completion
- Exit criteria was evaluated and passed
- The deadline has been reached, but there are still critical errors in the application
- All 50 tests planned for execution were executed
- A total of 11 errors were found
- Exit criteria were evaluated and passed

### 2 SQL section
