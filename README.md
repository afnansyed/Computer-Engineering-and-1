# LifeStylePlus

                                                              SECTION 1  

## How solution addressed challenged statement

In the current times, there is not enough awareness on mental health.  Although perception has improved, people still have a difficult time coming to terms with it. In addition, a vast number of the symptoms can be physical, many people might not make the first connection to it being related to their mental wellbeing. Taking the first step to reach out to a professional can be difficult. We took this issue as one of the bases that our product could aid with. The second issue that was accounted for was that in daily life, especially as a student finding a healthy balance between work, school, and relationships as it can be exceptionally hard to find a schedule that fits their needs and stick to it. Sometimes this can be very overwhelming to the point where they might put less priority on their health and hence, causing further hurdles and imbalance in their life.


## Project Description, Features and Functionality
Our software product is centered around the importance of making good physical and mental health habits more attainable in that daily life. The software makes physical and mental goals more structured and goal oriented to achieve a healthy balance. The website mainly consists of two sections: mental and then physical health. The mental health portion consists of surveys that a user can take, that will help them with understanding what mental health condition they might likely have based on their symptoms, daily activities, and thoughts. In addition, the mental health page on our website will also have videos that help a user with understanding basic concepts about a few mental health conditions such as depression and anxiety. After this section, there will be various resources for treatment and their contact information.. The second section will focus more on the tracking of your fitness goals and the user will be able to track their progress throughout their health journey. Having an all in one health tool that tackles both physical and mental health all in one place especially for the student population, will initiate a positive change when trying to find healthy balances in work and health.
The product that we are planning on developing is a website that tracks a user’s data related to their health and exercise goals. Our product not only includes physical health but it also incorporates features pertaining to one’s mental health. We are marketing our product towards UF students to give them a tool that can help keep their busy college lives balanced and organized in addition to encouraging them to pursue options in keeping their body and mind healthy.


## System Models
### Architectural pattern
For our project, we used a layered architectural pattern. This model is a way of organizing a system by structuring models and components of a program that can be decomposed into several groups of subtasks. Each layer gives access to a different service. 

![arc](https://user-images.githubusercontent.com/44105687/236565275-152c4177-9860-40d4-a4ab-5663005dc105.PNG)


### System context model

![django](https://user-images.githubusercontent.com/44105687/236565319-f88ad0a0-022e-4226-b7b9-21b5e64a5bd4.PNG)


### Use Case Model

![usecase](https://user-images.githubusercontent.com/44105687/236565362-357f90cd-74bf-49b6-8684-e3455e019e64.PNG)


                                                           SECTION 2
## Code Management

The source code for the project is stored in a repository on Github. That repository contains all versions of the source code and each team member has their own fork of the original repository.

## Test Plan

1. Testing the graph that indicates running progress:

  - Precondition: There needs to be data already inputted by a user.

  - Test Steps: Firstly, input data as a user. Then run the data tracker. Validate the graph results with the data inputted.

  - Test Data: Test data will be dummy data for the purpose of measuring the abilities of the data tracker. We will be using a range of small to large amounts of data.

  - Expected Results: The expected results  would be the data tracker showing the correct input on graph form.

  - Post-condition: The condition that needs to be achieved will be a graph for the user to measure their progress through a certain time period.

  - Actual Result: Actual result will depict a graph with the inputted data.

  - Status: Pass

  - Comments: Graph should adjust according to period of time.

2. Login validity:

  - Precondition: Set up an email and password

  - Test Steps: Typing in the email and password in their respective boxes. Then clicking login to an account. 

  - Test Data: Email and passwords of accounts created by our team during sign up

  - Expected Result: Login to the account

  - Post-condition: Profile page of the user

  - Actual Result: Redirected to user profile

  - Status: Pass

  - Comments: The profile page should be that of the particular user. If login is unsuccessful, an error message should be shown on the login page

3. Verify registration Process:

  - Precondition: Data for several dummy accounts including invalid data.

  - Test Step: Enter each set of data to the necessary fields and attempt to register

  - Test Data: Users with combinations of valid and invalid data(email, empty fields, duplicates, etc.)

  - Expected Result: Valid attempts will be entered into the system and invalid attempts will be rejected.

  - Post-condition: Successful attempts will proceed to a new screen.

  - Actual result: Valid inputs create a new user and invalid inputs reject/do not save the user.

  - Status: PASS 

4. Verify mental health links are working:

  - Precondition: Having the survey data already inputted

  - Test Steps: Enter your data through the mental health survey. Have the predicted value of what website links should be there. Test where the links actually take 
  you compared with the predicted value.

  - Test Data: Survey data

  - Expected Result: Webpages that pertain to the survey data and answers

  - Post-condition: Website links are shown and can be clicked

  - Actual Result: Website links do redirect correctly to the correct resource

  - Status: Pass

  - Comments: Make sure the predicted test results verify that they are different for every school

5. Testing if our mental health survey works.

  - Precondition: Precondition that needs to be met is that the user must click on the link that leads to the mental health survey and must answer the survey.

  - Test Steps: Firstly, click on the mental survey link. Then input data as a user while answering all the relevant questions. Do this for all the questions until every question is answered. 

  - Test Data: Test data will use dummy data just to make sure all of the questions are able to transition properly and will lead to the appropriate results.

  - Expected Result: The expected result would be that the user can move through the survey answering questions easily.

  - Post-condition: The postcondition that will come about from answering the survey will lead to a screen that shows UF mental health resources.

  - Actual Result: After the completion of the survey, the website will direct the user to the mental health resources provided by UF as well as a quick help guide.

  - Status: PASS

  - Comments: Make sure we get the list of information and solutions accurately.



## Static Code Analysis and Report
### First Code Report:

![repor](https://user-images.githubusercontent.com/44105687/236565545-fe7fb9cb-5c33-4051-9104-570d8e4fe770.PNG)


### Explanation Of Bugs for First Report:
7 Changing i tag to the em tag: This was resolved by going to my loginpage.html and register.html files and changing a simple syntax bug.

2 Adding lang=”en” on the <html> tag: This was resolved by going to my loginpage.html and register.html and adding a simple two words of code.

3 Miscellaneous Duplications in CSS Style File: This was resolved by simply deleting the duplications of style in the styles.css file.

Second Code Report:

![bug](https://user-images.githubusercontent.com/44105687/236565596-4100911e-4dd7-435d-95ad-9b50fbf195a6.PNG)

### Explanation Of Bugs for Second Report:

There are no bugs in the second report so no explanation is needed.


                                                                       SECTION 3

## Technical Details
We used Bootstrap 5 as a means of stylizing the website such as the background. Our main IDE of choice was to use Pycharm mainly because we used a Python-based HTML framework to create our website. Django was extremely helpful during the making of our website because it allowed us to more efficiently implement HTML concepts using Python. Some of the packages that we found extremely helpful for our website was matplotlib and base64. Matplotlib is basically a python library that allows for easy display of graphs, while base64 is a library that encodes binary data into printable ASCII characters as well as decoding of ASCII characters to binary data. In terms of the coding languages that we used for this project we mainly used HTML (50% of project), Python (26% of project), and CSS (23% of project). For the system requirements what is needed is an os that is able to download the Django, Bootstrap, Pycharm, and the following packages along with a modern browser so that the website can be opened up through a local hosting. 

## Languages/Frameworks
- Django (4.1.3) (comes with SQLite)
- Python (3.10.8)
- HTML 5
- CSS 3
- Bootstrap 5

## Installation Instructions
1. Download BootStrap, Python, Pycharm, and Django
2. Open up project in Pycharm
3. Open up terminal
4. Type into terminal: “python manage.py runserver”
5. Run on a local host by clicking on the link generated from the terminal

## Login and Access Credentials
    - Admin Account:
        - User: james.fesik
        - Password: Fezman100

## Login Instructions:

To access the administration area of our website you would first need to sign in to the website using the admin account. Once signed in, typing admin into the url bar right after the corresponding local host server numbers will lead you to the admin section. Otherwise, any interaction as a non-admin will be carried forth after creating an account and using the website.

## API Keys

Not applicable.

                                                                 # SECTION 4

## Risk Management Plan

- Huge redesign needed because of limitations of tool:
    - Solutions: Make sure before the project starts that our team can code the correct things that we want with the tools that we have. A contingency plan is having a back up web development tool to ensure that we have multiple options if Django was not the right fit.

- The size of the software was underestimated:
    - Solutions: Our team can ensure that the software architecture model is not too ambitious and once we learn more about our development tool we will be able to pivot to a more realistic model if our plan turns out to be over ambitious in practice.

- Certain sub-teams need help integrating their parts:
    - Solutions: If certain sub-teams of our project need extra assistance it should not be that much of a delay to put more workforce into one part of the project for a few sessions. This delay could also be adjusted to a later stage of the project if it can be skipped for that moment.

- Software tools cannot be integrated in timely manner:
    - Solutions: This is a trivial solution where we can just take a few more hours to make sure that Django can be implemented correctly to allow collaboration for our project.

- Contacting CWC takes longer than expected
    - Solutions: For the first time, CWC should be contacted at least one or two weeks before the relevant feature is implemented. A faster contact method should be established for future meetings.

- Software tools take longer than expected to learn
    - Solutions: Team members can request help from others or take time to seek online resources. The estimated time to complete will likely be extended or offset to meet these changes.

- Team members busy with other classes
   - Solutions: The team can meet to discuss deadlines for other classes, especially before exam periods. Deadlines and estimations can be adjusted so that members can complete their parts earlier or catch up afterwards.

## Software Quality Attributes and explanations

- Product operation
    - Correctness: Our website operates as we have originally designed it to be. It works well on all web platforms and devices with no errors. 
Efficiency: The code that we have written is well organized and is easy to read and understand. All the code follows a similar syntax and is simple to debug and maintain. 
    - Integrity: The static analysis report returned no security vulnerabilities. There should be none or very few features that threaten the integrity.
    - Reliability: Our website works as it is intended to for all users. A user is able to create an account, login using their credentials, and have access to what our product offers. In addition, the website is fast and simple to navigate through.
    - Usability: Many test cases were used to test the functionality of our product. We also showed the website to people outside of our group to use our product and make sure there are no unwanted hindrances.

- Product revision
    - Maintainability: Our design of our website is very organized so navigating and fixing errors during maintenance is not complex and rather straightforward.
    - Flexibility: As our product has an uncomplicated design, the operational software program can be improved without difficulties.
    - Testability: We used Pycharm as our IDE with the main frontend being developed using HTML and CSS so, testing to see the website can be done without much issue.

- Product transition
    - Portability: Our website uses HTML, CSS, and Javascript for the front-end. These work on any of the popular web browsers. The backend languages are Python and SQL. Any system with the latest version of Python installed can host the server.
    - Reusability: CSS styles come from Bootstrap, a stylesheet file, or in the case where it applies to only one file, the header section. Code from those locations can be called in HTML with classes and IDs.
    - Interoperability: The website was created and tested to make sure it has the same functionality on all web browsers and also different laptops and computers.
