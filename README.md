# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: *[OrangeHRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)*

Documentation: [OrangeHRM documentation](https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf)

Tools used: Jira

# Functional specifications

-> In Jira I have created multiple test cases to determine de funtionality of the "Recruitment" tab, the "Candidates" subtab


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the "Recruitment - Candidates" module from the OrangeHRM application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

#### 1.1.1 Roles assigned to the project and persons allocated

Manual software tester: Chiras Adrian

#### 1.1.2 Entry criteria defined


#### 1.1.3 Exit criteria defined

#### 1.1.4 Test scope

* __Tests in scope:__ The functionaly of the "Edit" button

#### 1.1.5 Risks detected

* Project risks: Tehnical problems - Problems with the testing tools
* Product risks: The product does not meet the business criteria

#### 1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test.

## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Candidates module. The following test conditions were found:
 * As a user I want to be able to edit the informations about a candidate
 * As a user I want to be able to update the status of the hiring process of a candidate

## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases 
are:

**Test cases:**
-> 
As a user I want to be able to mark an interview as passed

As a user I want to be able to mark an interview as failed

As a user I want to be able to reject a candidate

As a user I want to be able to cancel the changes I made to a candidate's profile

As a user I want to be able to select the "Status" of a candidate

As a user I want to be able to delete the CV from a candidate's profile

Verify if the "Full name" fields can be left empty.

As a user I want to be able to replace the current CV from a candidate's profile

As a user I want to be able to schedule an interview with a candidate

As a user I want to be able to modify the full name of a candidate


The test cases with steps can be viewed here: [test_cases.pdf](https://github.com/ChirasAdrian/manual_testing_portofolio/blob/main/Zephyr%20Test%20Steps%20(Jira).pdf)

## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* Test prioretisation
* Grouping the tests based on their objectives
* The business documentation is ready

## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary: [cycle_summary_execution.pdf](https://github.com/ChirasAdrian/manual_testing_portofolio/blob/main/Zephyr%20Test%20Executions%20%2B%20Results%20(Jira)%20(1).pdf)
* Bugs have been created based on the failed tests. 
    *  No cancel button for the changes made in Candidates subtab
    *  Can't select another status for a candidate other than "Rejected"
    *  While rejecting a candidate, the button is called "Save" instead of "Reject"


## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here: [Traceability_matrix.csv](https://github.com/ChirasAdrian/manual_testing_portofolio/blob/main/Traceability%20Report%20(Direct%20Only)%20(Jira).pdf)
* Test execution chart was generated, the final report shows.... -> That 3 tests out of 10 have failed

-> [Test execution report](https://github.com/ChirasAdrian/manual_testing_portofolio/blob/main/Execution%20Report.pdf)
