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
----
    requirement analysis
    DESIGN
    CODING
    TESTING           
    deployment
    MaintainaNCE


QE:-QUALITY Engineering @AUTOMATION TESTING AS THEY WRITE CODE
-----------------------
AUTOMATION(CODE) PERSON COME HERE 








==================================================================================================================================================
==================================================================================================================================================