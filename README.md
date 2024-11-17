# Testing Project for **Automation Exercise** E-commerce Website

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test**: Automation Exercise e-commerce website

**Tools used**: Jira, Zephyr Squad.

Functional specifications:
The below stories were created in Jira and describes the functional specifications of the Registration, login, and password recovery module and Shopping cart items module, for which the final project is performed upon.

![5](https://github.com/user-attachments/assets/1104440b-bb85-4889-9493-326ed525d7f3)

![15](https://github.com/user-attachments/assets/480ddce1-022e-49af-96a8-0010d4b2ea1a)



Here you can find the release that was created for this project:

![31](https://github.com/user-attachments/assets/2c2626f5-1f64-4643-8481-3230ec7c4afd)

## Testing process
The test process was performed based on the standard test process as described below.

### 1.1 Test planning
The Test Plan is designed to describe all details of testing for all the modules from the Automation Exercise e-commerce website.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 

#### 1.1.1. Roles asigned to the project and persons allocated

<table> <tr> <td> Project manager </td> <td> Dragos BRATU </td></tr>
<tr> <td>Product owner </td> <td> Liviu FLORIU </td> </tr>
<tr> <td>Software developer </td> <td> Andrei IANCU </td> </tr>
<tr> <td>QA Engineer </td> <td> Oana Maria PREDA </td> </tr> </table> 

#### 1.1.2 Entry criteria defined

- Requirements: All functional and non-functional requirements must be clearly defined and approved.
- Tools: Jira and Zephyr Squad must be installed, configured, and accessible to the testing team.
- Resources: All required human resources, including testers and developers, must be available.
- Documentation: Test plan, test cases, and any necessary documentation must be completed and reviewed.

#### 1.1.3 Exit criteria defined

- Test Case Execution: All planned test cases must be executed.
- Defect Resolution: All critical and high-priority defects must be resolved and retested.
- Coverage: Achieve at least 95% test coverage for in-scope functionalities.
- Acceptance Criteria: All acceptance criteria for the project must be met.
- Sign-Off: Obtain formal sign-off from stakeholders confirming that all exit criteria have been met.

#### 1.1.4 Test scope
a) Tests in scope:

- Functional Testing: Validate core functionalities such as user registration, login, product browsing, adding items to the cart, and checkout.
- Regression Testing: Ensure that new changes have not adversely affected existing functionality.
- Usability Testing: Assess the user experience of key features.
- Cross-Browser Testing: Verify the site works correctly on different web browsers (Chrome, Firefox, Safari, Edge).
- Responsive Testing: Ensure the website is responsive and functions correctly on different devices (desktop, tablet, mobile).
- Accessibility Testing: Ensure that the platform adheres to accessibility best practices (e.g., proper color contrast, compatibility with screen readers).
- Localization Testing: Test that the platform supports multiple languages

b) Tests not in scope:

- Performance Testing: Load and stress testing will not be conducted.
- Security Testing: Detailed security and penetration testing will be excluded.

#### 1.1.5 Risks detected
a) Project risks:

- Lipsa experientei echipei de testare.
- Timpul scurt de fixare a defectelor.
- Riscul de a dezvolta un produs software slab calitativ si neconform din cauza specificatiilor neactualizate.

b) Product risks:

- Functionalitati noi care pot afecta performanta aplicatiei.
- Complexitatea unor module ale aplicatiei pentru care exista riscul ca utilizatorului sa ii fie dificil sa le parcurga.

#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control

Monitoring and control ensure that testing progresses according to plan and any deviations are addressed promptly. This includes daily status meetings, progress tracking in Jira, and regular test status reports from Zephyr Squad.

**Test Status Report**: A report from Zephyr reflecting test activities and progress is included below, showing metrics such as tests executed, passed, failed, and blocked.

![Daily](https://github.com/user-attachments/assets/793fbe6d-7758-4427-9f60-0f9af0b5e8d5)

### 1.3 Test Analysis
The testing process will be executed based on the application requirements. 

The following test conditions were found:

![32](https://github.com/user-attachments/assets/bec62334-9278-4364-8558-7bf34ab6b092)

### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/AnaoMaria/Repo1/blob/main/ZFJ-Cycles-11-15-2024.csv)

### 1.5 Test Implementation
The following elements need to be ready before the test execution phase begins:

- Test environment setup.
- Test data preparation.
- Test scripts written and reviewed.
- Necessary permissions and access granted.
- Tools configured and validated.

### 1.6. Test Execution
Test cases are executed on the created test Cycle summaries Automation Exercise V1.

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/AnaoMaria/Repo1/blob/main/Jira%20Export%20CSV%20(all%20fields)%2020241118000040.csv).

The following is a summary of the bugs that have been found for Automation Exercise V1.

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

## 1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here: 

![22](https://github.com/user-attachments/assets/d30ce57d-9a48-4abc-a5c2-1b72bb60bb81)

Regular updates to the Traceability matrix help maintain transparency and alignment between testing and project objectives throughout the test life cycle
The matrix indicates the current status of each test case, helping to monitor the testing process and identify any gaps or missing coverage
The matrix can be used for compliance purposes and to demonstrate that all requirements have been adequately tested and verified

Test execution chart was generated and can be found below.

![23](https://github.com/user-attachments/assets/1f2960cc-43e5-4fd9-93cf-ac18a17085ec)

The final report shows that 3 tests have failed of a total of 10.

A number of 4 total bugs were found, from which the priority is: 2 are high and 2 are medium.

The testing revealed significant gaps in both functionality and user experience, particularly in user registration, login, and cart management.

The identified bugs, especially those related to security and usability, greatly impact the final user experience, causing inconvenience and potential security risks.

Immediate attention to high-severity issues is essential to ensure a smooth and secure shopping journey for users on the "Automation Exercise" e-commerce website.
