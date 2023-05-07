Hi,
Here's the command that you can use to run the file from command prompt:

mvn test -Dbrowser=Chrome 

Also, the structure is defined as follows:

Assignment.AbstractComponents - contains all the reusable codes used throughout the framework
Assignment.pageobjects - contains all the test scenarios that has been considered according to the assignment.
Assignment.resources - contains information on setting browsers as per tester's choice.
Assignment.StepDefinitions - contains all the functions that has been written in the feature file
Assignment.testcomponent - contains POM format of Test Execution.
Assignment.tests - contains initial setup of the the flow of the page which has been drastically changed during the creation of framework.
cucumber - consists of TestRunner file and feature files.
