<h1>Manual Testing Project for Otto Broker</h1>



__The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application__


Tools used: __Jira, Zephyr Squad__

Application under test:  https://www.ottobroker.ro/


<h2>Functional specifications:</h2>

The below stories "My insurance" and "Claim"  was created in Jira.
![image](https://github.com/user-attachments/assets/19fd4d99-960e-411c-ac75-21a1e5c46b3f)





<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 



<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


| Job Title                  | Name                |
|----------------------------|---------------------|
| Product Manager            | Ioana Popescu             |
| Business Analyst           | Maria Andrei                  |
| UX/UI Designer             | Tudor Petrisor                |
| Software Developer (Frontend) | Raluca Adam               |
| Software Developer (Backend)  | Roxana Tiberiu             |
| Quality Assurance Tester   | Roxana Martin                 |
| Database Administrator     | Razvan Ionut                   |
| System Architect           | Daniela Ioja                 |
| Project Manager             | Adrian Bretotean                   |
| Technical Support Engineer  | Andreea Vasilache               |




<h4> 1.1.2 Entry criteria defined </h4>

Availability of Project Requirements:

- All functional and non-functional requirements for the "My Insurance" and "Claim" sections have been documented and approved.
- Documentation regarding user flows, use cases, and test cases has been completed.



  

<h4> 1.1.3 Exit criteria defined </h4>


1.Completion of Test Execution:

- All defined test cases for the "My Insurance" and "Claim" sections have been fully executed.
- All critical and most secondary tests have been run without major or critical errors.

2.Resolution of Critical and Major Bugs:

- All identified critical and major bugs have been resolved and verified through retesting.
- Minor bugs and enhancements have been documented and prioritized for future releases, if not blocking the launch.

3.Complete Documentation:

- All test results, including bug reports, test reports, and related documentation, have been completed and archived.
- Feedback and lessons learned from the testing process have been documented to improve future processes.




<h4> 1.1.4 Test scope</h4>

__1. My Insurance Section:__
Tests in Scope:

**Functionality Testing**:


- Verify that users can view, update, and renew their insurance policies.
- Test the ability to download and upload policy documents.
- Ensure accurate display of policy details, such as coverage, expiration dates, and payment history.
  
**User Interface Testing:**

- Check that the "My Insurance" section is displayed correctly across all supported browsers and devices.
- Verify the responsiveness and layout consistency of the interface.
- Ensure that all UI elements (buttons, forms, links) are functional and correctly labeled.

  
**Cross-Browser and Cross-Device Testing:**

 - Test the "My Insurance" section across different browsers (Chrome, Firefox, Safari, Edge) and devices (desktop, tablet, mobile).
 - Ensure consistent behavior and appearance across various platforms.
   
**User Acceptance Testing:**

- Validate that the "My Insurance" section meets user expectations and provides a seamless user experience.
- Conduct user scenario testing to confirm the usability and functionality from an end-user perspective.


Tests not in Scope:



**Performance Testing:**

- Detailed load and stress testing beyond the scope of basic performance verification.
  
**Security Testing:**
  
- Specific security and vulnerability assessments are out of the current test scope.
  
**Unit Testing:**

- Low-level code tests, such as unit tests, will be handled by the development team and are not part of the manual testing scope.




__2. Claim Section:__
Tests in Scope:

**Functionality Testing:**

- Verify that users can report a new claim and track the status of existing claims.
- Test the upload and management of documents related to claims.
- Ensure proper functioning of notifications and updates related to claim status.
  
**User Interface Testing:**

- Check that the "Claim" section is visually consistent and fully operational across different browsers and devices.
- Verify the correct display of claim details, progress tracking, and document attachments.
  
**Integration Testing:**

- Ensure seamless integration with external systems, such as insurance partners and repair shops.
- Validate data flow between the Otto Broker system and third-party services used for claims processing.

  
**User Acceptance Testing:**

- Validate that the "Claim" section aligns with user expectations, particularly in ease of use and accuracy of claim management features.




Tests not in Scope:

**Performance Testing:**

- Advanced performance testing, such as load and stress testing, beyond the basic scope.
  
**Security Testing:**

- Security assessments, including penetration testing, are not included in this testing phase.


**Unit Testing:**

- Unit tests for individual components or modules are excluded from the manual testing process.





<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>
1. Limited Testing Time:Time constraints may limit the depth and breadth of manual testing, forcing the team to prioritize certain features over others.

2. Lack of Test Documentation: Inadequate or inconsistent test documentation can result in missed test cases, difficulty in reproducing bugs, and challenges in knowledge transfer.
   
3. Tester Skill Variability:Variations in tester experience and skill levels can result in inconsistent test execution and issue detection, especially in complex areas like insurance policy management or claims processing.


4. Changing Requirements:Requirements for the website may change during the testing phase, causing confusion and necessitating re-testing of previously validated features.


5. Dependency on Third-Party Systems:The website's integration with external systems (e.g., insurance provider APIs, payment gateways) might face issues outside the control of the testing team.



<h5> Product risks: </h5>
1. Incomplete Functionality Coverage: Certain functionalities of the Otto Broker website, such as niche features within the "Asigurările Mele" and "Dauna" sections, might not be thoroughly tested due to oversight or limited time.

2. Data Integrity Issues: Manual testing might overlook scenarios where data is incorrectly saved, displayed, or updated, especially in complex transactions like adding a new policy or processing a claim.
   
3. Performance Issues Under Load: Manual testing is often limited in its ability to simulate high traffic or peak usage conditions, potentially missing performance bottlenecks.




<h4>1.1.6 Evaluating entry criteria</h4>
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.


<h3>1.2 Test Monitoring and Control<h3>
The Monitoring and Control stage is a critical part of project management and software testing. It is performed to ensure that the project stays on track, meets its goals, and delivers the expected outcomes. 


![image](https://github.com/user-attachments/assets/021ce676-5dee-4324-bcf5-3b163c6faf29)

![image](https://github.com/user-attachments/assets/310de291-cd91-4778-bc0a-761f4cbc862e)

![image](https://github.com/user-attachments/assets/a6f63ae8-0062-4d0c-9ace-680fd06ae73a)

  





![image](https://github.com/user-attachments/assets/d14a6665-cd9b-471e-8613-ebd01550d525)


<h3> 1.3 Test Analysis </h3> 

The testing process will be executed based on the application requirements. 
test conditions: 
![image](https://github.com/user-attachments/assets/b54108e1-9851-42d6-a23c-b952efdadec3)















<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here 

![image](https://github.com/user-attachments/assets/ed232c4d-96a9-4111-9a10-422e0e16b904)
![image](https://github.com/user-attachments/assets/b012da5b-a6a7-4694-af57-a05bd52ee838)






<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:






<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **My insurance and Claim**



The following is a summary of the bugs that have been found:

![image](https://github.com/user-attachments/assets/1d4bfa45-d435-412e-9642-2939c023310f)
![image](https://github.com/user-attachments/assets/b27d4d97-9812-4e83-87ae-84d8a11240e7)







Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

























<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

![image](https://github.com/user-attachments/assets/521d036c-1638-41d3-a510-52145f54a8be)






Test execution chart was generated and can be found below. 





![image](https://github.com/user-attachments/assets/43e3ad12-a6f9-4691-b60f-74910c628e6b)






 Conclusions:
12 tests were created and executed to validate the new functionalities.
All planned functionalities were successfully tested.
A number of 3 total bugs were found, from which the priority for all of them-  medium.



__Recommendations for a Testing Team to Ensure High-Quality Work__

The testing team should invest time in understanding the Otto Broker website's functionalities, especially the critical sections like "Asigurările Mele" and "Dauna." This includes familiarizing themselves with user stories, requirements documents, and any relevant business rules.A deep understanding of the product helps testers anticipate potential issues, create more comprehensive test cases, and ensure all critical features are thoroughly tested.

Identify and prioritize high-risk areas of the website (e.g., payment processing, user data handling) for more intensive testing. Allocate more time and resources to these areas.


Regularly review test results, analyze trends, and adjust the testing strategy as needed. Use metrics like defect density, test coverage, and pass/fail rates to measure progress and identify areas for improvement.

