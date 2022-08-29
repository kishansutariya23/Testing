Note:- 1) Try to watch in desktop view.

# Manual Testing

> Module 1: Testing concepts(Theory) WHAT?

> Module 2: Testing Project(Practice) HOW?

> Module 3: Agile process-Jira

-------------------

## Module 1

Topics Covered: Part-1
-------------------------

1. What is Software? Types of Software’s?
2. What is Software Testing?
3. What is Software Quality?
4. Project Vs Product
5. Why do we need Testing?
6. Error, Bug & Failure
7. Why the software has bugs?

* A Software is a collection of computer programs that helps us to perform a task.


 Types of Software:

        1) System Software
            ex: Device drivers, OS, Servers, Utilities, etc
        2) Programming Software
            ex: compilers, debuggers, interpreters, etc,
        3) Application Software
            ex: Web-application, mobile apps, desktop application etc. 

example:-
    
     X Bank(company)------------>IT company--->develop----->test---->deliver---->X Bank
        |                           ^
        |__explain the requirement__|


why testing?--> to give quality product to the customer 

What is Software Testing?
------------------------
    => Software Testing is a part of Software development process.
    => Software Testing is an activity to detect and identify the defect in the software.
    => the objective of testing is to release quality product to the client.



What is Software Quality?
-------------------------
    => customer will decide it .
    => Bug-free.
    => Delivered on time
    => within budget
    => meets requirements and/or expectations.
    => Maintainable by customer after getting deliverd.



    companies
      |--> service
      |--> product

simillarly
we have 

Project vs Product
------------------
    => If software application is developed for specific customer based on the requirement then it is called Project
    => If software application is developed for the multiple customer based on the market requirement then it is called Product.
     

Why do we need Testing?
----------------------
    to give quality product to the customer which is bugsfree,Maintainable,...



Error, Bug/defect & Failure
--------------------
    => Error:-  Human Mistake or incorrect human action
    => Bug:-    Deviation of expecting or actual behaviour or [DEFECT]:- login successful when we give invalid crediantials ;)
    => Failure:-end user action/Deviation identified by end-user while using the software



Why the software has bugs?
--------------------------
    > 3-5 reasons
    > Miscommunication or no communication
    > software complexity
    > Programming errors
    > changing requirement
    > lack of skilled testers


-------------------

Topics Covered: Part-2
-------------------------
1. SDLC 
2. Waterfall Model
3. Spiral Model
4. V-Model
5. Static Testing & Dynamic Testing
6. Verification & Validation
7. White Box & Black Box Testing Methods


SDLC:- Software Development Life Cycle
--------------------------------------
It is a process used by software industry for design, develop and test Software’s

we have 3P's
P-People
P-process
P-Product
@People should follow some @process to deliver the @product

    Software Development Life Cycle
            1) requirement analysis
            2) design
            3) development
            4) testing
            5) maintenance

company will follow there own process model see next

Waterfall model
----------------
in initial day every company started following this model 
old and traditional model 
it look like waterfall 
WE ARE NOT FOLLOWING THIS Model

    requirement-analysis------
        |                    |
        |                    v
        |           System design----------
        |                |                 |
        |                |                 v     
        |                |          Implementation------
        |                |               |              |
        |                |               |              V
        |                |               |            testing------
        |                |               |               |         |         
        |                |               |               |         v
        |                |               |               |    deployment----
        |                |               |               |        |         |  
        |                |               |               |        |         v 
        |________________|_______________|_______________|________|_____maintenance
    

we make documents in 1st step @SRS,
2ND STEP we will make DESIGN documents of HLD & LLD

ADVANTAGES:-

    => Quality of the product will be good as it is long term project and every thing will be documented.
    => Since requirement changes are not allowed, chances of finding bugs will be less
    => initial investment is less since the testers are hired at the later stages.
    => Preferred for small projects where requirement are feezed.

DRAWBACK:-

    => Each phase is dependent on previous phase
    => requirement changes are not allowed
    => If there is defect in requirement that will be continued in later phase
    => Total investment is more because time taking for rework on defect is time consuming which leads to high investement
    => Testing will start only after coding




Spiral Model
------------
@iterative model
to overcome waterfall model disadvantage we came to this model

TAKE PIC FROM INTERNET
    
                                  @RA BOTH P1&P2
                                                   |
                           Planning                |           Risk analysis
                                                   |
                            requirement-analysis   | prototype
    WE GET    |   WE GIVE                      P1  |  P2 
     ---->---------<------------------------------COST-----------------------
           requirement         customer-Evalution  |  Development & Testing
                                             P4    |  P3
                           @testing                |                  @design&development
                                                   |
                           Evalution               |    Engineering & Execution    
                                                   |
                                             spiral model
          
@FOR Product based company it is best sutable 
- we will release new model in every Cycle


* it is iterative model
* *it overcome drawback of waterfall model
* *we follow spiral model whenever there is dependency on the modules.
* in every Cycle new software will be release to customer
* software will be released in multiple Verision. So it is also called version control model
@any how we are  not using this model

ADVANTAGES:
-----
* Testing is done in every Cycle, before going to the next Cycle
* Customer will get to use the software for every modules
* requirement changes are allowed after every Cycle before going to the next Cycle.


disadvantage:
-----
- requirement changes are NOT allowed in between the Cycle.
- Every Cycle of spiral model looks like waterfall model.
- There is no testing in requirement & design phase.

@@ V-model is over-coming above 2 models.

prototype model is between both model
-> blue print of the software
initial requirement from customer---> prototype--->customer--->yes--->design,coding,testing




V-MODEL /VV-MODEL [verification & Validation]
----------------------------------------
see the diagram on internet 

we have 4 phases/level of testing
- in every phase we have testing

@we have white box and black box along with static and dynamic testing 


@verification
Static Testing:- done on document
-------------
testing the project related documents @we do it through below
    Review
    Walkthrough
    inspection



### @Validation

#### dynamic testing:- done on code
testing the actual software

- white box techniques:- 
   
   as we will be knowing what is there inside box @coder knows what is there inside there code :)
   -    unit testing
   - integration testing
    
- black box techniques:-
    
     we dontb know what is there inside box @tester dont know what is there inside the box(code)
    - system testing
    - user acceptance testing
<!-- @1:15:revision -->



Verification/Validation
----------------------
Verification checks whether we are building the right product
Focus on the documentation
verification typically involves
    Review
    Walkthrough
    inspection


Validation checks whether we are building the product right
takes place after verification are completed
Focus on software
Validation typically involves actual software
unit,integration, system UAT testings.

ADVANTAGES

    testing is involved in each and every phase

disadvantage

    documentation is more
    initial investement is more

-------------
Topics Covered: Part-3
------------------------
1. Static Testing & Dynamic Testing
2. Review, Walkthrough & Inspection
3. QA & QC & QE
4. Levels of Software Testing
5. Unit Testing
6. Integration Testing
7. System Testing
8. UAT Testing


STATIC TESTING TECHNIQUE 
    1) Review
    2) Walkthrough
    3) Inspection

DYNAMIC TESTING TECHNIQUE
    1) UNIT TESTING
    2) INTEGRATION TESTING
    3) SYSTEM TESTING
    4) UAT


REVIEW (any buddy can do this at any time)
--------------------------
Conducts on document to ensure correctness and completness
    requirement Review
    design Review
    code Review
    test plan Review
    test case Review,....

Walkthrough(informal review)
--------------------------
Author reads the documents or code and discuss with peers.
it's not pre-planned and can be done whenever required
also Walkthrough does not have minutes of the meet

inspection
--------------
it is more formal review type.
in which at least 3-8 people will sit in meeting 1-reader, 2-writer, 3-moderator plus concerned
it will have a proper schedule which will be intimated via email to the concerned developer/tester



QA VS QC
-----------
   QUALITY ACURANCE AND QUALITY CONTROL 

    ==> QA is process related @define process
        QC is the actual testing of the software
    
    ==> QA Focuses on building in quality
        QC Focuses on testing for quality
    
    ==> QA is preventing defects
        QC is detecting defects
    
    ==> QA is process oriented
        QC is product oriented
    
    ==> QA for entire life Cycle
       QC for testing part in SDLC


    P-People  ----- QC(tester)
    P-process ----- QA
    P-product



SDLC

    requirement analysis
    DESIGN
    CODING
    TESTING           
    deployment
    MaintainaNCE

;


## QE:-QUALITY Engineering 
done by AUTOMATION TESTING AS THEY WRITE CODE
 
 AUTOMATION-tester(CODE) PERSON COME HERE 



    Level of testing
        Unit Testing
        Integration Testing
        System Testing
        User Acceptance Testing (UAT)

- Unit Testing:- single module we will test
- Integration Testing:- we will integrate all single module and test as whole module
- System Testing:- we will test the over all functionality of the application based on the customer requirement
- User Acceptance Testing (UAT):- tester along with the use will make the testing here


## Unit Testing:-  
- A unit is a single component or module of the software
- it is conducted on a single program or small module
- it is white box testing techniques
- it is conducted by developer
- it has 
    - basis path testing :- each and every line should be Execute atleast once
    - control structure testing
        - conditional coverage
        - loops coverage
    - mutation testing :- testing code with multiple sceniario like giving different username with password

## Integration Testing:-
- It performed between 2 or more moduled
- It Focuses on checking data communication between multiple modules
- it is white box testing techniques as well as black box type

at developer level the coder will make integration between the module let us assume mail 
he will write separate module like compose,login, delete and they will integeate it and test it.

and when it come for tester they will do testing at application level and see it as UI/UX part and test the integration is doing well or not
like if we delete any mail it is going to delete box or not?
so it is performed by tester also


Types of Integration testing
---
- *Incremental Integration Testing:- 

   Incrementally adding the modules and testing the data flw between the modules

                |
            2 approaches
                |--> TOP-DOWN
                |       Incrementally adding the modules and testing the data flow between the modules. 
                |       and ensure the module added is the child of previous Module 
                |-->BOTTOM-UP
                |       Incrementally adding the modules and testing the data flow between the modules. 
                |       and ensure the module added is the parent of previous Module 
                |--> sandwich/hybrid approaches:- combination of the above          
  
- Non-Incremental Integration Testing:-
    adding all the modules in a single shot and test the data flow between modules

    DRAWBACK:-
    1) we might miss data flow between some of the Module
    2) If you find any defect we cant understand the root cause of the defect


- System Testing:-
 actual tester will work here
Testing over all functionality of the application with respective client requirement
it is black box testing technique
this testing is conducted by testing team
after completion of the componentand integration level of testing we start system testing
Before conducting system testing we should know the customer requirement@ we will read the document.

    system testing Focuses on below aspects

        -> user interface testing(GUI)
        -> functional testing
        -> non-functional testing: special team with different env. needed
        -> usability testing:- user Manual and help guide when we open new software come here


- UAT After completion of the system testing UAT team conducted this testing in 2 Levels
tester and user, end-user will help here to make a final product which can be deployed in production.
    
    - Alpha testing:- main company will come to develop team and check here and take the software with them after Alpha testing
    
    - Beta testing:- end user will use as pre-release version 


 
# Topics Covered: Part-4

    System Testing
          |--> GUI Testing
          |--> usability testing    
          |--> functional Testing
          |--> non-functional Testing [separate skill set and separate env required]

make as same env as customer have and test the product

testing
  1) front-end testing :- GUI testing
  2) Backend testing
  
GUI TESTING:
---------------
-> Graphical user-interface testing or GUI is a process of testing the user interface of an application

- A GUI includes all the element such as menus, checkbox, button, color, font, size, icons, content, and images

GUI TESTING CHECKLIST(we do this in excel)
@ we will get the design document for help for below checklist 

- Testing the size, position, width, height of the elements.
- Testing of the error messages that are getting displayed.
- Testing the different sections of the screen.
- Testing of the font whether it is readable or not.
- Testing of the screen in different resolutions with the help of zooming in and zooming out.
- Testing the alignment of the texts and other elements like icons, buttons, etc. are in proper place or not.
- Testing the colors of the fonts.
- Testing whether the image has good clarity or not.
-  Testing the alignment of the images.
- Testing of the spelling.
-  The user must not get frustrated while using the system interface.
- Testing whether the interface is attractive or not.
- Testing of the scrollbars according to the size of the page if any.
- Testing of the disabled fields if any.
- Testing of the size of the images.
- Testing of the headings whether it is properly aligned or not.
- Testing of the color of the hyperlink.
- Testing UI Elements like button, textbox, text area, check box, radio buttons, drop downs ,links etc.

usability testing 
-----------------
During this testing validates application provided context sensitive help or not to the user
Checks how easily the end users are able to understand and operate the application is called usability testing



functional Testing
---------------
==> working on customer requirement
functionality is nothing but behaviour of the application according to customer requirement 
it talks about how your feature should work
    
    > object properties testing
    > database testing
    > error handling
    > calculation/manipulation testing
    > links existence & links Execution
    > cookies & sessions

 
object property testing:-check the property of object present on the application

ex:- enable, disable, visible, focus,....

user input should be 8char with all types  then only it is valid , enable or disable , drop down for elements comes here 

database testing[separate skill set is required]
Checking DB operate w.r.t user operations.

- we should know sql
- it is a grey-box testing technique as it has both white&black box testing
- but we know basic of sql knowledge then we can start our work
- backend testing 
- mainly focus on DML is working fine or not, as we will interact with UI and it will interact with database
- we check DB as it is affecting or not when we interact with UI
- we do DB testing also 
- here UI(BLACK BOX)  & DB(WHITE BOX) in this DB-testing

for separate skill set 

    -> Table & column level validation (column type.column length, no.of columns,...)
    -> Relation between the table 
    -> functions
    -> procedures
    -> triggers
    -> index
    -> views
    etc,.....



Error handling Testing:
----
tester verify the error message while performing incorrect action on the application

    -->error message should be readable
    -->user understandable/simple language
    ex:- when user give username and password
            incorrect:-incorrect data 
            correct  :-invalid username 
 


calculation/manipulation testing
-------
tester should 
all calculation related testing like when ever we dedect money from bank it should be updates

--> and when ever we try to click on any operation ex:calculator it should work good in terms of any i/p(+,-)


links existence & links Execution
---------------
NOT APLICABLE FOR DESKTOP 
only web-application

    --> link existence:- where exactly the link are placed
    --> link Execution:- links are navigating to proper page or not
        TYPES
         |-->Internal link:- going to some section of same page
         |-->External links:- going to some other page
         |-->Broken links:- not going any where as developer make it for future reference
    


cookies & sessions
----------------
NOT APLICABLE FOR DESKTOP 
only web-application

- cookies are made by browser like chore not SERVER NOR database
- it store information :-if we leave the page but also the data is not lost 
       ex:- checklist for form-filling 

- sessions are created by server side.

ex:- banking application-->
     time slot start when we stop working in banking application and when we try to do some work it will ask password again/each time


ONCE FUNCTIONALITY IS STABLE THEN ONLY NON-FUNCTIONALITY TESTING WILL START

# Non-functional

    Non-functional testing [we required special skilled person and specific Environment to work]
        |-->Performance testing
        |      |--> load testing
        |      |--> stress testing
        |      |--> volume testing
        |
        |--> security testing
        |--> recovery testing
        |--> compatibility testing
        |--> configuration testing
        |--> installation testing
        |--> Sanitation/Garbage Testing


    ==> Its all on customer expectations NOT on customer requirement
    ==> like my expectations are it should be secure, fast loading when we have heavy traffic, it should be unhackable(for banking domain)
    
    
    perform testing :- speed of application 
       load testing :- increasing load(person visiting ) on the application and check speed of application
       stress testing :-suddenly increasing/decreasing load like 5-->50-->20-->100 (offer time in amazon,..)
       volume testing :-how much data can be handle by application its based on DB 
    we have performance matrix for checking which have preformed well


# security testing

how secure our application mostly for banking related application
--> special person will perform this like dedicated team for this who have security knowledge in terms of https,hacking...

    we mainly go with 
       AUTHENTICATION--> user are valid or not
       Autherization/access control:--> permission of the valid user
           only have a specific feature access ex:- we are not allowed to access the other department files ;)
    



recovery testing:-->in gmail all will be save in draft until we send them or app get crashed  

    compatibility testing
         |--> forward compatibility
         |     
         |--> backward compatibility
         | 
         |-->hardware compatibility:- it is called configuration testing
         |     the application should be work on different hardware like small ram based device and different OS based devices....
    
forward&backward:--
new software should be upgrade with old version
old software can be runned on new devices 


## configuration testing:-

comes under compatibility testing under hardware testing


installation testing:-
-----------------
- check screen are clear to understand 
- simple or not as of for non-technical user :- it should be easily working
- un-installation should be easy as then we try to re-install ,it should not give any error due to some saved file by previous installation 



Sanitation/Garbage Testing:
---------------------------
    --> If any application provides extra feature/functionality then we conside them as bug.
    unwanted stuff like code 
            Bug (non used code of previous version/installation) we should say to programmer to remove it
 
|Non-functional Testing  |  Functional Testing |
|----------------------|---------------|
|Validates functionality of Software.  | Verify the performance, security,reliability of the software.|
|Functionality describes what software does. | Non-Functionality describes howsoftware works.|
|Concentrates on user requirement. | Concentrates on user expectation.|
|Functional testing takes place before Non-functional testing.| Non-Functional testing performed after finishing Functional testing.|


 
# Topics Covered: Part-5
    Regression testing 
    re-testing 
    regression vs re-testing 
    Smoke testing and sanity testing  
    exploratory testing  
    adhoc testing 
    monkey testing 
    Difference b/w exploratory  vs adhoc vs monkey 
    positive and negative testing  
    positive vs negative TCs  
    end to end testing  
    localization and globalization/internalization testing 





Regression testing 
------------------
there should  be NO change in existing testcase/function due to release of new build/new feature(after removing bug)

- Testing conducts on modified build to make sure there will not be impact on existing functionality because of changes like adding/deleting/modifying features.

TYPES 
-----
- Unit regression testing
    - Testing only the changes/modifications done by the developer.
- Regional Regression Testing
    - Testing the modified module along with the impacted modules(dependent modules)
    - *Impact Analysis* meeting conducts to identify impacted modules with QA & Dev.
- Full Regression
    - Testing the main feature & remaining part of the application.
    - Ex: Dev has done changes in many modules, instead of identifying impacted modules, we perform one round of full regression.


re-testing 
------------
- Whenever the developer fixed a bug, tester will test the bug fix is called Re-testing.
- Tester close the bug if it worked otherwise re-open and send to developer.
- To ensure that the defects which were found and posted in the earlier build were fixed or not in the current build.
 
      Example

      -> Build 1.0 was released. Test team found some defects (Defect Id 1.0.1, 1.0.2)
       and posted.

      -> Build 1.1 was released, now testing the defects 1.0.1 and 1.0.2 in this build is retesting.



regression vs re-testing 
------------------------
An Application Under Test has three modules namely

Admin----> Purchase ---->Finance.

    Finance module depends on Purchase module.

    > If a tester found a bug on Purchase module and posted. Once the bug is fixed, the tester needs to do Retesting to verify whether the bug related to the Purchase is fixed or not and also tester needs to do Regression Testing to test the Finance module which depends on the Purchase module.


Smoke testing and sanity testing  
(developer can also do smoke testing)
-------------------------------
Smoke testing:-@build-verification testing
basic level of testing before indepth testing is called smoke testing 
  like all build are there are not, all packages, dependency are there are not and nav is working or not home page is appearing or not and all basic stuff

 ==> #build is stable or not to perform other testings

--> in *initial days* when developer start writing code we will be getting unstable builds so tester will be performing smoke testing on it as it is not a complete build, all small/un-stable builds are tested by smoke

--> when a complete build(stable build) is done and send to tester at that time sanity testing is done on all functions/feature(login, nav, link ,... entire things )but not in deep 


Smoke and Sanity Testing come into the picture after build release.

|Smoke Testing  | Sanity Testing |
|-----------------|--------------|
| Smoke Test is done to make sure the build we receivedfrom the development team is testable/stable or not. | Sanity Test is done during the release phase to check for the main functionalities of the application without going deeper. |
| Smoke Testing is performed by both Developers and Testers| Sanity Testing is performed by Testers alone|
|Smoke Testing, build may be either stable or unstable | Sanity Testing, build is relatively stable| 
|It is done on initial builds.| It is done on stable builds.
|It is a part of basic testing.|It is a part of regression testing.
|Usually it is done every time there is a new build  release.It is planned when there is no enough time to do in-depth testing.

    initial/unstable-build------smoke-testing----->smoke test is passed?----yes-->
    build-1                                           |                          |
    build-2                                           NO                         |
       .                                              |                          |
       .                                              v                          v
       .                                          Build reject            system and/or regression testing
       .                                              ^                          ^
       .                                              |                          |
       .                                              NO                         |
    build N                                           |                          |
    stable build------sanity-testing------->sanity test is passed?----yes---->---



exploratory testing  
-------------------
we know/ have knowledge of application  
   WE dont have documents/requirement/functionalities and application is ready 
- We have to explore the application ,understand completely and test it.
- Understand the application, identify all possible scenarios, document it then use it for testing.
- We do exploratory testing when the Application ready but there is no requirement.
- Test Engineer will do exploratory testing when there is no requirement.
D awbacks:
- You might misunderstand any feature as a bug (or) any bug as a feature since you do nothave requirement.
- Time consuming
- If there is any bug in application, you will never know about it.




adhoc testing 
-------------
we know/ have knowledge of application  
- Testing application randomly without any test cases or any business requirement document.
- Adhoc testing is an informal testing type with an aim to break the system.
- Tester should have knowledge of application even thou he doesn't have requirements/test cases.
- This testing is usually an unplanned activity.
@NO-document, NO-Test_Design, NO-Test_Case


monkey testing 
----------------
ex: in new game we do monkey behaviour 
- Testing application randomly without any test cases or any business requirement document.
- Adhoc testing is an informal testing type with an aim to break the system.
- Tester do not have knowledge of application
- Suitable for gaming applications.


Difference b/w exploratory  vs adhoc vs monkey 
-------------------------------------------------

|Adhoc Testing     |  Monkey Testing    |          Exploratory Testing|
|-----------------|-------------------|----------------------------|
| No Documentation|No Documentation|No Documentation
|No Plan|No Plan|No Plan
|Informal testing| Informal testing|Informal testing
 |Tester should know Application functionality|Testers doesn't know Application functionality|Testers doesn't know Application functionality
|Random Testing|Random Testing|Random Testing
|Intension is to break the application/find out corner defects|Intension is to break the application/find out corner defects|Intension is to learn or explore functionality of application
|Any Applications|Gaming Applications| Any Applications which is new to tester


positive and negative testing 
----------------------------------- 
@positive testing
- Testing the application with *valid inputs* is called as Positive Testing.
- It checks whether an application behaves as expected with positive inputs.
 

    For example -

                           Enter Only Numbers
                                    99999
                            Positive Testing

- There is a text box in an application which can accept only numbers. Entering values up to 99999 will be acceptable by the system and any other values apart from this should not be acceptable.
- To do positive testing, set the valid input values from 0 to 99999 and check whether the system is accepting the values.


@negative testing
- Testing the application with invalid inputs is called as Negative Testing.
- It checks whether an application behaves as expected with the negative inputs.

For example -

                          Enter Only Numbers
                                 abcdef
                           Negative Testing
- Negative testing can be performed by entering characters A to Z or from a to z.
- Either software system should not accept the values or else it should throw an error message for these invalid data inputs.





positive vs negative TestCasess  
---------------------------
Requirement:
 - For Example if a text box is listed as a feature and in FRS it is mentioned as Text box accepts 6-20 characters and only alphabets.

Positive Test Cases:
 - Textbox accepts 6 characters.
 - Textbox accepts upto 20 chars length.
 - Textbox accepts any value in between 6-20 chars length.
 - Textbox accepts all alphabets.

Negative Test Cases:
 - Textbox should not accept less than 6 chars.
 - Textbox should not accept chars more than 20 chars.
 - Textbox should not accept special characters.
   Textbox should not accept numerical.


end to end testing  
--------------------
Testing the overall functionalities of the system including the data integration among all the modules is called end-to-end testing.

END-TO-END TEST

  1) login
  2) add new customer
  3) edit customer
   
  4) delete customer
  5) logout


    1---->2----->3---->---5
          |               ^
          |----->4------>-|


localization and globalization/internalization testing 
-----------------------------------------------------

- Globalization Testing:
    - Performed to ensure the system or software application can run in any cultural or local environment.
    - Different aspects of the software application are tested to ensure that it supports every language and different attributes.
    - It tests the different currency formats, mobile number formats and address formats are supported by the application.
    - For example, Facebook.com supports many of the languages and it can be accessed by people of different countries. Hence it is a globalized product.

- Localization Testing:
    - Performed to check system or software application for a specific geographical and cultural environment.
    - Localized product only supports the specific kind of language and is usable only in specific region.
    - It testes the specific currency format, mobile number format and address format is working properly or not.
    - For example, Baidu.com supports only chinese language and can be accessed only by people of few countries. Hence it is a localized product.

 
# Topics Covered: Part-6
1. Test Case Design Techniques
2. Equivalence Class Partitioning
3. Boundary Value Analysis (BVA)
4. Decision Table
5. State Transition
6. Error Guessing




















