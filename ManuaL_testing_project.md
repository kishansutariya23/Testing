# Manual Testing Project

# Part -1
Topics : Documentation part
------------
1. Project Introduction 
2. Explore AUT
3. FRS Document 
4. Test Plan
5. Test Scenarios 



we will be following below steps for manual testing

- Project introduction
- Understanding & Explore the Functionality
    - explore the application by clicking and going into different tabs, links and all
- estimation => done in agile(contain the duration of project)
- Test Plan
- Writing Test Scenarios
- Writing Test Cases & Reviews
- Environment Setup & Build deploymnet
- Test Execution
- Bug Reporting
& Tracking
- Sanity Testing, Re-Testing & Regression Testing
Test Sign off


Project Vs Product
--
- We develope the software for the customer is called as Project
- A software build for multi-customer is called as product

- Any test we are doing it is on product 


## 1. Project Introduction 

We will be doing **Product** based project

eCommerce product/Application

Activity as a customer what they can do

    => Login
    => Search for product/items
    => Add then to cart
    => Do payment
    Product will be delivered
    => Return the product
    etc....

we have 2 parts

1. Frontend --> public access by internet[can do above mention activity] #internetApplication (need internet to access and any one can access)
2. Backend --> can be access by admin of company [adding product,...] #intranetApplication (need internet but only company admin can acess)


So as we are manual tester we will be doing Frontend part activities

**We will be using some online web application for hands-on**
[https://www.opencart.com/]
we can use download for deploying in production and demo as frontend & backend


example:- demo application url:-[https://demo.opencart.com]

## 2. Explore AUT & 3. FRS Document

NOTE:- WE WON'T GET UI AT BEGINING STATE, IN FIRST WE WILL GO THROUGH DOCUMENT some time design DOCUMENTS


We will be having FRA(Functional Requirement Specification) Document(docx) for understanding the requirement

Based on above we will build test case and test sceniro 

- After reading FRS docx we will get idea how our product works interms of functionality
- Mockup screen are used in FRS it means before product get finished a dummy screen are produced in document, based on this we have to imagine the application and in future we can write test cases
- FOCUS ON requirement like what we have to test and don't worry about the entire doc.,,,
- we can highlight the doc       [para,]
- we will be assign more time to read the document 

## 4. Test plan

- we will estimate the time for completing the project based on the requirement, doc,...
- we will refere project plan d(given by manager as it contain the duration of entire project) and FRS doc.

- Test Leads and test engineer will prepare this **test plan documents**[scope of testing,schedule,what not to , what to test,.tool, types of testing, who will, when will be testing conducted.. is mentioned in this doc]

- understand this doc. as it will be help full for writimg the testcase sceniro

## 5. Test Scenarios

it contains
- what to test
- area to test

based on scenarios we will convert into test cases 

it is written in excel
- scenarios description start with **Validate** or **verify**

- excel has 2 table

table 1:-
- Project Nmae
- Client
- Reference Document
- Created By
- Creation Date
- Approval Date

table 2:- 
- Test Scenario ID
- Reference
- Test Scenario Description
- Priority
- Number of Test Cases

<img src="./images/test scenario.jpg">

-------------------------

# Part- 2

Topics :
------------
1. RTM (Requirement Traceability Matrix)
2. Test Cases