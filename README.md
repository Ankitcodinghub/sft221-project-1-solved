# sft221-project-1-solved
**TO GET THIS SOLUTION VISIT:** [SFT221 Project 1 Solved](https://www.ankitcodinghub.com/product/sft221-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119139&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SFT221 Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Learning Outcomes

• Design and build the solution to a small problem,

• Design the testing for the problem.

Project Description

You have been hired by a local delivery company that has three different trucks that deliver on three different routes in your part of the city. The map of your city is represented as a 25 by 25 square grid as shown in the diagram below.

Our offices are located at the square 1A. From that location our three different delivery vans start out initially on a common path and then branch out to cover different parts of the neighborhood. The paths taken by our delivery trucks are shown in blue, yellow, and green. Initially, all trucks start out and follow the blue path and then the green and yellow trucks branch off from the path taken by the blue trucks. The black rectangles represent buildings to which packages can be delivered. The white areas are empty space and the blue, yellow, and green areas represent the paths taken by our three delivery trucks. All addresses are specified in terms of the row number and column letter to which a package should be delivered.

All our trucks are the same size and can hold up to 1000 kilograms of cargo. The trucks are also capable of carrying 36 cubic meters of boxes. The boxes that we use for shipping come in 1/4 cubic meter, 1/2 cubic meter, and 1 cubic meter sizes. All our boxes are square, meaning that they have the same dimensions on all sides.

When a customer comes in with a shipment, they specify:

• The weight of the shipment in kilograms,

• The size of the box required in cubic meters,

• The destination of the box in terms of a building specified by a row number and column letter that is within the black rectangle represented by the building.

A truck is full when it hits either its maximum weight or maximum volume – whichever is reached first. For example, if a truck already has 900 kilograms in it but only has 10 cubic meters of boxes then the limiting factor must be taken as the weight. If another truck has 30 cubic meters of boxes but only 200 kilograms of cargo, then you must assume that it is limited on space rather than weight. When you compare two trucks to see which one has the most space remaining, you should look at the limiting factor for each truck as a percentage and compare the percentages.

Measuring Distance

While it is relatively easy to determine the truck that has the most room or weight available for a package, it is less obvious how to determine which truck comes closest to the destination for a particular package. In some cases, it doesn’t really matter since they will be equidistant.

Consider the case where a package needs to be delivered to 7F. This location is actually on the route of two of our trucks. Since the green and blue routes overlap at this point it does not really matter whether we assign it to a blue or a green truck and that must be determined by the truck which has the most available space. On the other hand, it is very close to the route of the yellow truck. To determine whether we should put it in a yellow truck or one of the blue or green trucks we must measure the distance from the nearest point on the yellow trucks route to destination and the distance from the blue and green trucks to the destination. Looking at the problem visually, we can see that the blue and green trucks come within two squares of the destination, but the yellow truck comes within three squares of the destination. Therefore, since the blue and green trucks come equally close to the destination, the truck in which the object will be placed is based upon available weight and volume.

The Shortest Path Algorithm

One of the problems we need to solve is how to find the shortest path between two points given that you cannot go through a building. One solution to this problem is what is called the A* algorithm. The A* algorithm users the Euclidean distance from where you are on the path to the destination as a heuristic as to which way to go at any point.

Consider being at 8T and wanting to go to 8P. This is the shortest Euclidian distance to the destination, but might not be the shortest when you consider not being able to go through buildings. When you are at 8T, you can go to 7T, 7U, 8U, 9T or 9U since these all touch on 8T and are not part of a building. What we do next is to measure the Euclidian destination from each of these squares to the destination, as shown in the table below.

Start Square Distance to 8P

7T 4.12

7U 5.1

8U 5

9T 4.12

9U 5.1

From this table you can see that both 7T and 9T are equidistant to destination and our shortest distances. The algorithm says you always pick the shortest distance and go to that square. Since the two squares are the same distance, it does not matter which one we pick. Therefore, we will randomly select 7T as our destination.

Once we get to 7T, we need to go through the same process again. We select all the squares it is possible to move to and then calculate the distance to the destination square and move to the square which is closest to the destination. We repeat this process until we reach the destination. If we count the number of squares we move along the way, we will find the total distance that it takes to get to the destination.

One of the big problems with the shortest path algorithm is that it can get stuck. It can get stuck either at the edge of the map or in a corner of a building. You know you are stuck when you have tried every direction in which you can move forward, and you cannot reach the destination. Remember, you cannot go back along the path you came, as this can result in going in circles. At this point, you will simply say that the destination cannot be reached and mark that as not an eligible point to divert from the route to make a delivery.

The Overall Algorithm

The overall algorithm will

• Follow the route for each of the trucks.

• At every square on the route for each truck it will calculate the Euclidean distance to the destination.

• It will select the minimum Euclidean distance for each of the trucks and then calculate the shortest path from each of those positions to the destination.

• In the event one of the trucks cannot find a path to the destination, that truck will not be used for the delivery and one of the other trucks will be used.

• Finally, it will select the truck which has the shortest path from the nearest point on its route to the destination and attempt to add the package to that truck.

• If that truck cannot hold the package, it will try to put it in the truck that is next closest to the destination.

• If no truck can take the package, it will be placed in storage at the depot until the trucks return empty and it will be shipped out the next day. It will print the message “Ships tomorrow”.

Our algorithm will run for one day. This means we accept items until all trucks are full or items stop arriving. Once this happens, the trucks will be dispatched but that is not the responsibility of the program. All the program needs to do is:

• Decide which truck the package will be placed in.

• Print out where the truck will deliver the package.

• If the truck needs to divert to deliver the package, you will print the path to divert.

Sample Output

=================

=================

Enter shipment weight, box size and destination (0 0 x to stop): 20 .5 28x Invalid destination

Enter shipment weight, box size and destination (0 0 x to stop): 20 2 12L Invalid size

Enter shipment weight, box size and destination (0 0 x to stop): 1005 .5 12L

Invalid weight (must be 1-1000 Kg.)

Enter shipment weight, box size and destination (0 0 x to stop): 20 .5 12L

Ship on BLUE LINE, no diversion

Enter shipment weight, box size and destination (0 0 x to stop): 200 1.0 8Y Ship on GREEN LINE, divert: 7T, 7U, 7V, 7W, 7X, 7Y, 8Y

Enter shipment weight, box size and destination (0 0 x to stop): 500 1.0 8Y Ship on GREEN LINE, divert: 7T, 7U, 7V, 7W, 7X, 7Y, 8Y

Enter shipment weight, box size and destination (0 0 x to stop): 500 1.0 8Y

Ship on BLUE LINE, divert 18V, 17V, 16V, 15V, 14V, 13V, 12V, 11V, 10V, 9V, 8V, 7V, 7W, 7X, 7Y, 8Y

Deliverables

This project has multiple milestones and will follow a development process approximately the same as indicated above. Since the process is agile, it will deviate from the above process whenever it makes sense to do so.

During the project, teams are expected to:

• use the Git repository to store all work produced by the team.

• Document code with a comment at the top of each data structure and function which not only states the purpose of the data structure or function but also the author(s). Changes to code should include a comment saying who made the change and why.

• Add comments when items are committed to Git indicating what is being added or changed and why.

• Create an issue in Jira every time new work needs to be done o Move the issue across the Kanban board as its status changes.

• Add comments to the issue as work progresses.

• Meet one or more times per week to discuss the project.

• Team members should select work items they want from the Kanban board and assign it to themselves. It is the responsibility of each team member to ensure that they do their fair share of the work.

Marking

Create GitHub Account

2. Go to https://github.senecacollege.ca

3. Login using the SAML button

5.

6. Install tortoiseGit on your windows computer which can be downloaded from https://tortoisegit.org.

7. The group leader should clone the group repository onto a local computer and set up the following directory structure with one readme.md file in each directory.

The group leader should then commit and push the changes to the remote repository.

8. Finally, GitHub is moving away from usernames and passwords and requiring the use of access tokens. These are strings you can use in place of a password. There are instructions on how to create them here:

Tokens and Keys (sharepoint.com)

Follow these steps if the above link is not working:

a. Download and install Git from https://git-scm.com/downloads

b. Follow the steps here https://docs.github.com/en/authentication/connecting-to-githubwith-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=windows to generate a new SSH key and adding it to the ssh-agent.

c. Follow the instructions here https://help.github.com/articles/set-up-git to set up the Username and Email for Git

d. Set up your private and public SSH identification following these instructions https://help.github.com/articles/generating-ssh-keys

9. Then, you need to set up TortoiseGit to access your account. Right click on a file browser to show the TortoiseGit menu and select settings.

To link a local directory to your GitHub repository:

a. Create a repo directory on your machine.

b. Right click on the repo directory and select Git Clone…

c. Past in the URL for the GitHub repository in the URL field

d. Make sure the Directory field point to the &lt;local_repo_directory&gt;&lt;name_of_github_repo&gt; e. Click OK

This is my example for GitHub.com. You will build a new Global credential for github.senecacollege.ca and fill in your username. Use the Add /New/Save button to create the new credential and click OK at the bottom. Once you try to access the remote repository, it will prompt you for the token you were given, which you will use in lieu of a password. It will store this so that you only need to provide it again if it expires.

NOTE:

• All source code and testing code should be placed in the SourceCode directory. This should be one Visual Studio solution similar to the one set up in an earlier workshop.

• Weekly scrum reports should be stored in the ScrumReports directory at the end of every class. You should change the name of each scrum report to have the milestone number in the name to make it easy to identify.

• The group contract should be completed and stored in the GroupContract directory.

• Function specifications refer to the new functions you will be writing to complete the project. These function specifications are textual documents that use the provided template and should be stored in the FunctionSpecs directory.

• All documents about testing should be stored in the Testing directory. The main Test Plan and the traceability matrix should go in the TestPlan directory.

• Documents which describe the individual tests to be performed will be placed in

TestDocuments. Although you only need to write specifications for the new functions you will create, you will need to write test descriptions for both the existing functions provided for you as well as the new functions you create. You should either create subdirectories for black box tests, white box tests, integration tests and acceptance tests or name the test documents so that the type of test they describe is indicated in the file name.

Set Up a Jira Account

1. All group members should go to https://www.atlassian.com

2. Select Sign In and then Sign Up for an Account

3. Go to Products | Jira Software and get a free account

4. The group leader should set up a new project

a. Create a new project and select Kanban

b. Set the project type to be team managed

c. Finally, set the project name to be the same as the Git repository you created.

We will use Jira to record all issues in the project. When you need to write a document, a function, test code, or fix a bug you will create the issue and add it to the to do column of the kanban board. One of the team members should assign the work item to themselves in the SCRUM meeting and then move it through the kanban board until it is completed. Each issue should have a tag on it indicating the milestone to which it pertains.

When you write a Jira issue, you should provide:

• A short description used as a title,

• A description of what is to be done in the issue. If code or documents are to be written, it should list all of the files to be produced.

• Whether this issue is related to other issues such as being blocked by other issues or blocking other issues.

Milestone 1 Tasks

• Completed scrum report including reflection questions answered.

• Completed team contract.

• Fully initialized Git repository.

• Fully setup Jira project.

Rubric:

Individual Group Participation 75%

Teamwork 25%

Group Contract 15%

Git Repository 25%

Jira Project 25%

Scrum Report &amp; Reflects 35%

Milestone 2 Tasks

Some of the software for the project has already been written for you and is available on Blackboard.

You must use this in your project and every team should add it to the source code for their repository. Anything in the main function is simply for demonstration purposes and can be replaced. The software you are being given has not been tested and you will need to test it.

You need to study the problem and the code provided for you and then:

• Add any new data structures you will require This will require a thorough analysis of the problem and the existing software. This should be done by creating a new header file in the directory where the rest of the source code has been placed. You do not want to go back and modify it later if you can avoid it as it will slow the project.

• Create a test plan for the project by replacing the text in the supplied test plan template with your test plan.

• Completed scrum report including reflection questions answered.

• An analysis of the problem (no written artifacts produced).

• A series of data structures created as header files and stored in the repository.

• A test plan stored in the repository.

Rubric:

Individual Group Participation 75%

Teamwork 25%

Group Data structures (complete, correct and well-designed, project updated) 20%

Test Plan (complete, well-written) 20%

Git Usage (used properly with good structure) 10%

Jira Usage (creates issues, tracks progress) 10%

Scrum Report &amp; Reflections 25%

Meets Deadlines 15&amp;

Milestone 3

Function Specification

Before building functions, we need to specify them. These specifications are in textual form and provide all of the information to start writing black box tests for the function as well as to provide the information the developers need to create the functions. A function specification should contain:

• The name of the function

• A description of what the function does

• A description of any unusual conditions

• The return type and parameters

Here is an example of what one should look like:

NAME: findTruckForShipment

Description: Finds the best truck for a shipment. It considers both the load on the truck, the size and weight of the shipment, and the route of the truck to try to place it on a truck which goes closest to the destination. If there is no truck that can deliver the shipment, it returns -1.

Parameters:

• Map – the map of the delivery area with buildings on it.

• Trucks[] – an array of trucks including the route for each of the trucks

• numTrucks – the number of trucks in the array of trucks

• shipment – a data struct contain the size and weight of the shipment

Returns: An integer representing the index of the truck in the trucks array on which the shipment should be placed. If no truck can take the shipment, then -1 is returned.

• Completed scrum report including reflection questions answered.

• A set of function specifications stored in the repository.

• A set of blackbox tests as test documents with test data for the functions.

• Start writing blackbox test code and store in repository (at least 1 required).

• Start implementing functions and store in repository. (optional).

• A function-test matrix added to the repository.

• Updated Jira project to show activities and progress.

Rubric:

Individual Group Participation 75%

Teamwork 25%

Group Function Specs (documented, correct, complete, well-written, added to the project) 20%

Test documents (well-written, complete, good test data) 20%

Test Code (well-designed, written and documented) 10%

Git Usage (used properly with good structure) 5%

Jira Usage (creates issues, tracks progress) 10%

Scrum Report &amp; Reflections 25%

Meets Deadlines 10&amp;

Milestone 4

This milestone will complete the implementation of the functions, the blackbox tests, execute the blackbox tests, and create new issues for any failed tests. Tests which passed can have comments added to the issue and it can be moved ahead on the Kanban board. Whitebox tests will be written and stored in the repository and then implemented and executed. The goal is by the end of the milestone all unit tests will have been run and the code debugged.

Test Automation

Now that we have tests to run, we need to automate the testing process. The goal of this automation is to ensure the code has passed the suite of tests before pushing the code to the repository. This will keep bugs out of the repository and eliminate the headaches which result from having a bug introduced into the repository.

To automate the testing, we need to install a script into the directory .git/hooks in your repository. Directories under .git are not checked into the remote repository so every team member on the project has to install his own hook. The hook must be stored in a file called pre-push in the hooks directory. The contents of the file will be like this:

#!/bin/sh

echo “Starting test runner…”

test_runner=”C:Program FilesMicrosoft Visual

testout=`”$test_runner” “$tests_dll”`

if [[ $testout == *”$failure_string”* ]]; then echo &gt;&amp;2 “Unit test are not passing! Push aborted!” exit 1

fi echo &gt;&amp;2 “All tests run successfully.” exit 0

This is the script set up for my machine and every team member will need to edit it to work on their own computer. You need to edit:

• test_runner – this is the location of the vstest.console.exe program installed by Visual Studio. Check the location and modify it if it is different on your computer.

• tests_dll – this is the location of the dll built for your test project. It is relative to the root of the project. Modify this to refer to the dll you want to test.

Once this is installed, every time you try to push to the remote repository, it will run the tests. If the tests fail, the push will be aborted. You will need to fix the code and then commit the changes and push again until the tests pass. This step is an important part of the setup of the testing process and cannot be skipped.

• Completed scrum report including reflection questions answered.

• Implemented Functions.

• Implemented blackbox tests (store in repo), executed (results in Jira and on corresponding test documents) and debugged.

• Whitebox tests written and stored in repository.

• Whitebox tests implemented (store in repo), executed (results in Jira and on corresponding test documents) and debugged.

• Updated function-test matrix stored in the repository.

• Completed hook for test automation.

Rubric:

Individual Group Participation 75%

Teamwork 25%

Group Implemented Functions (well-designed, written and documented) 20%

Whitebox tests (well-designed, written and documented) 20%

Test Execution (performed, results recorded, issues created) 20%

Debugging (Bugs fixed, documented, Jira updated) 5%

Git Usage (used properly with good structure) 5%

Jira Usage (creates issues, tracks progress) 5%

Scrum Report &amp; Reflections 20%

Meets Deadlines 5&amp;

Milestone 5

In this milestone, you should write, implement, and execute integration tests. Integration tests test how multiple functions work together to complete a task.

Integration tests execute multiple functions that work together to make sure that no bugs appear from the interaction of the functions as they work together. Typically, you would prepare some test data, pass it to one function and then pass the results of that function onto another function. At the end, you should compare the results from the last function with the expected results to make sure things are working as expected.

In some situations, you might have written new functions that invoke several simpler functions. You can test these functions to ensure they have integrated the functions they call by creating unit tests for the functions as you would create unit tests for any other function.

Acceptance tests are the final tests written to demonstrate to the customer that all the requirements have been met. There will typically be one set of tests for each major requirement of the project. This will start with the type of data usually provided by the customer and will check to see that the final result is what the customer expects.

• Completed scrum report including reflection questions answered.

• Integration tests written and stored in repository.

• Integration tests written (store in repo), executed (results in Jira and in test documents) and debugged.

• Acceptance tests written and stored in repository.

• Updated function-integration-requirements-test matrix stored to the repository.

Rubric:

Individual Group Participation 75%

Teamwork 25%

Group Integration tests (well-designed, written and documented) 20%

Acceptance tests (well-designed, written and documented) 20%

Test Execution (performed, results recorded, issues created) 15%

Debugging (Bugs fixed, documented, Jira updated) 5%

Function-test matrix updated 5%

Git Usage (used properly with good structure) 5%

Jira Usage (creates issues, tracks progress) 5%

Scrum Report &amp; Reflections 20%

Meets Deadlines 5&amp;

Milestone 6

This is the final milestone where you will run the acceptance tests and fix any remaining bugs found. In addition, you will produce a testing report which lists all the tests conducted, the results and whether the bugs were fixed, and the final test passed. You will also review the test matrix to ensure every test has been performed and passed. You can change the colour of the test in the matrix to show it was run and passed. At the end, all tests in the matrix should have been passed.

The final test report can be tabular like this:

Function/acceptance/requirement Test Run Bugs Fixed Passed

Distance TF001 Did not handle negative coordinates 

• Completed scrum report including reflection questions answered.

• Execute acceptance tests (results in Jira), and debug.

• Updated function-test matrix stored in the repository.

• Final testing report listing tests conducted, bugs fixed, and the final test passed.

Rubric:

Individual Group Participation 75%

Teamwork 25%

Group Updated test matrix 20%

Final test report 20%

Test Execution (performed, results recorded, issues created) 10%

Debugging (Bugs fixed, documented, Jira updated) 5%

Git Usage (used properly with good structure) 5%

Jira Usage (creates issues, tracks progress) 5%

Scrum Report &amp; Reflections 30%

Meets Deadlines 5&amp;
