1. Test Plan ID:
SP-TP-001
2. Test Plan Title:
Functional Testing for Student Portal – Activities Module
3. Objective:
To verify that all major functions in the Student Portal (Login/Logout, Add Activity, Filter, Sort, Toggle Status, Delete) work as expected and meet business requirements.
4. Scope:
This test covers the “Activities” feature and authentication module of the Student Portal web application.
5. Test Item:
Student Portal Web Interface
6. Features to be Tested:

        Login: Validate user authentication using correct credentials

        Logout: Verify user session ends correctly

        Add Activity: Ensure user can add an activity so that it can track  engagement.

        Filter Activities: Check that user can filter activities so it can see only those that match a specific status.

        Sort Activities: Verify user can sort activities so that it can view them in an order that helps user understand its progress.

        Toggle Status	& Delete Activity: Ensure user can  update or remove activities so that the records remain accurate

7. Test Approach
   
Manual functional testing using UI test cases.

Later automated regression testing may be added using Cypress.

8. Test Environment

Browser: 	Chrome (latest), Firefox

Server: QA Environment

Test Data: Dummy student accounts and sample activities

Network: Stable internet connection

9. Test Cases
    
   TC01 to TC07
   
10. Entry & Exit Criteria

Entry Criteria:

Build deployed to QA environment

Test data available

Functional requirements approved

Exit Criteria:

All test cases executed

Critical and major defects resolved

Test summary report generated

11. Deliverables
    
Test Plan

Test Cases

Test Execution Report

Defect Report   

12. Risks & Assumptions:
Risks:

Unstable QA environment
	      
Incomplete requirements	      
Mitigation:

Coordinate with DevOps for fixes

Clarify with product owner
# Test Cases

TC01: Valid Login:

