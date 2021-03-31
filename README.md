# Amplience-Front-End-Automation
Automation Code for the Front End Gui Amplience Tech Application

Task 1: API Back End Coding
For this task I took the time to extensively utilise every resource available to me in an attempt to create a solution that met the requirements of the task. This involved me exploring multiple coding languages, tools, forums and guides in addition to utilising the knowledge and expertise of former colleagues to better my own understanding and work through ideas with them. In spite of this, I did not have the knowledge to apply the technical application effeciently and while I was able to create some code to open a browser that directed to the API webpage this was not, in my opinion, sufficient enough but I have included it below;

Imports System.Text
Imports System.Text.Json.Serialization
Imports OpenQA.Selenium
Imports OpenQA.Selenium.Chrome
Imports OpenQA.Selenium.Support.UI

Module BackEnd
    Public Sub Main(args As String())
        'Open Chrome to Specified URL
        Process.Start("C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe", "https://api.github.com/users/6wl")

    End Sub

End Module

However, I have included my theoretical understanding of the task to showcase that while I did not know how to execeute the task I understand what is required and what would need to be created.

Through my research I understand that to complete the task I would need to create a series of code that would achieve the following;
1) A function would need to be created that would pull the JSON from the API (webpage)
2) Once a response has been received back there would need to be a function to covert this into JSON objects.
3) Following which, there would be the use of a 'Get.element' type function to pull the required text from the JSON Object and compare this to a pre-set variable.
4) This would be repeated for each value that would need to be compared.

Things to Note/Bugs;
- In the requirements of the assessment the Company field was not present on the UI and therefore a test could not be included. 
- As well as this, the ID provided did not match that of the specified user and so the one presented on the system was utilised for the purpose of the test.
- In addition to this the numbers provided as part of the spec for the follower/repo count were incorrect so the test utilises the current numbers listed on the profile, however it is arguable that because this is a fluctuating number it would be more beneficial to simply check the fields are present instead of ensuring the data matches and expected result as this would require more upkeep in the long term.

                                                           ----------------
Task 2: Test Automation;
The tests were created with the use of Selenium IDE - a chrome integrated programe that allows for identification of objects, creation of tests (and test suites) and the use of a record and play back feature. The programme allows for values to be adjusted prior to running the tests, although these are also clear in the code, and while this code may not have been written from scratch I took the time to read through what was produced by the system to increase my own understanding in addition to doing a large variety of research to locate a suitable tool, coding lanaguage and adjusting the actions to ensure the correct results were achieved.

Run Instructions:
I have included the Java export of the file for ease of review, however from my experience I was only able to get the .side export file from Selenium IDE to function everytime. Therefore the below instructions are for importing and running via Selenium IDE. Note that the tests should be run utilsing a Chrome browser as this will produce the best results.

1) Open Chrome and navigate to https://www.selenium.dev/selenium-ide/.
2) Download and install the Selenium IDE Chrome extension, ensuring to pin it to the extension toolbar for ease of access.
3) Download and save the AmplienceFrontEndTestSuite.side file for the front end tests for use later.
4) Open Selenium IDE via chrome by clicking on the icon in the extension toolbar.
5) When prompted, click to Open an existing project and navigate to the saved AmplienceFrontEndTestSuite.side file.
6) Once opened, the tests will be imported into Selenium IDE for execution and will also open the possibility of changing values utilsing the appropriate fields. 
7) Ensure the URL located at the top of the programe is set to https://github.com/6wl
8) To run all the tests in the suite, click on the Run All Tests button (Ctrl + Shift + R)
9) Tests will be run, marking green for each successful step and red for failed.

Things to Note/bugs:
- In the requirements of the assessment the Public Gists field and the company field was not present on the UI and therefore a test could not be included. 
- In addition to this the numbers provided as part of the spec for the follower/repo count were incorrect so the test utilises the current numbers listed on the profile, however it is arguable that because this is a fluctuating number it would be more beneficial to simply check the fields are present instead of ensuring the data matches and expected result as this would require more upkeep in the long term.
