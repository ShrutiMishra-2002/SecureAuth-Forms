# SecureAuth Forms
### This is an automation script using Selenium and TestNG to test a register page.

### Testing scope : 
    - In scope: functions related to register process,
      1- Verify if all input fields meet the requirements (first name - last name - email - phone - password)
      2- Verify whether the verification email was sent or not.
    - Out of scope: all non-functional tests, such as load and performance tests and UI tests.


# How to run this project:
1- Install java and eclipse IDE.
2- Install TestNG extension to eclipse (from eclipse marketplace). 
3- Add selenium JARs as external JARs to the project (JARs exist in the folder "selenium").
4- The class newtest: it contains all methods used to perform test cases.
5- After running the project successfully, an auto-generated report will be created containing the testing results. It can be found at:
    folder->test-output/index.html and test-output/emailable-report.html
5- The test can be run only once successfully; to rerun it again, a change would be done, and emails used in all functions would be changed.

# Additional Project Files:
Two Excel files containing:
Test case reports for manual testing.
Bug reports documenting manually detected defects.
Automation test reports are included in two .html files:
"index.html"
"emailable-report.html"


  
