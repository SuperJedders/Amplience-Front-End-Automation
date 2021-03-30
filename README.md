# Amplience-Front-End-Automation
Automation Code for the Front End Gui Amplience Tech Application

Task 1: API Back End Coding

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
3) Download and save the .side file for the front end tests for use later.
4) Open Selenium IDE via chrome by clicking on the icon in the extension toolbar.
5) When prompted click to Open an existing project and navigate to the location of the .side file.
6) Once opened, the tests will be imported into Selenium IDE for execution and will also open the possibility of changing values utilsing the appropriate fields. 
7) Ensure the URL located at the top of the programe is set to https://github.com/6wl
8) To run all the tests in the suite, click on the Run All Tests button (Ctrl + Shift + R)
9) Tests will be run, marking green for each successful step and red for failed.

Things to Note/bugs:
- In the requirements of the assessment the Public Gists field and the company field was not present on the UI and therefore a test could not be included. 
- In addition to this the numbers provided as part of the spec for the follower/repo count were incorrect so the test utilises the current numbers listed on the profile, however it is arguable that because this is a fluctuating number it would be more beneficial to simply check the fields are present instead of ensuring the data matches and expected result as this would require more upkeep in the long term.
