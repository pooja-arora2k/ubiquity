# ubiquity

#ManualTest cases
Acceptance Criteria
• A login screen for the user to log in using username “ubiquity” and password “P@ss123#UbiQuity”.
• All pages should be branded with Ubiquity logo.
• Once logged in, the user should be able to see a landing page with the text “Welcome to the Ubiquity
Tester Test admin page.” on it, an image of our company marketing picture and some placeholder
content (for now)
• An edit user profile page where the logged in user can change the registered information
• A Logout button to remove the session

Test Cases

#TestCase 1: Login with credentials username : ubiquity Password: P@ss123#UbiQuity 
Test Result:PASS
#TestCase 2:  Verify all pages to be branded with Ubiquity logo.
Test Result:FAIL: Landing page after successful login does not show Ubiquity logo

#TestCase 3: Verify landing page text after TestCase 1,
             The text should match: Welcome to the Ubiquity
Tester Test admin page.”
Test Result: FAIL 
 Actual Text:  Welcome to the Ubiquity Tester admin page
 Expected Text:Welcome to the Ubiquity Tester Test admin page
 
 #TestCase 4: Verify that landing page after login shows company marketing picture and placeholder content
 Test Result:PASS
 
#Test Case 5: Verify landing page edits
 Ensure that logged in user can change the registered information
 Verify user can edit 
 Email
 Mobile
 DOB
 Password
 
 #Test Result: FAIL
 
 #Test Case 6: Verify Logout
 Ensure that logged in user can successfully logout from the session
 Test Result: PASS
 
 #Test Summary
 The test requires testing login page Ubiquity
 Total Tests : 6
 Test Executed: 6
 Test Passed: 3
 Test Failed: 3
 #Bug Analysis
 1.Company logo missing on the landing page
 2. Landing page welcome text does not match with the requirement.
 3.User cannot edit the profile on the landing page, the landing page shows content updated successfully but does not update in actual, navigating back to home button and checking the profile again
 
 
 
 
