# Leapifytalk-bug-report

UI/UX Testing Report
Testing URL: https://musing-saha-2d39c9.netlify.app/
Device & Platform: iOS (iPhone)

Key Issues and Test Cases
1. Back Button Glitch
	•	Description: The back button is not functioning correctly and causing unexpected navigation behavior.
	•	Expected Behavior: The back button should navigate to the previous screen smoothly without glitches.
	•	Actual Behavior: The screen either refreshes unexpectedly or does not navigate back as intended.
	•	Impact: High (Affects user navigation and experience)
	•	Recommendation: Fix the back button functionality to ensure smooth navigation without unexpected behavior.
Test Cases:
Test Case ID
Test Description
Expected Result
Actual Result
Status
TC001
Click the back button on the pricing page
Should navigate to the previous page
Page reloads unexpectedly
Fail
TC002
Click the back button after form submission
Should go back without resetting form data
Unexpected behavior occurs
Fail


2. UI Elements Overlapping & Alignment Issues
	•	Description: Some UI elements are overlapping or misaligned, causing readability and accessibility issues.
	•	Expected Behavior: UI elements should be properly aligned and spaced for a clear user interface.
	•	Actual Behavior: Certain buttons and text fields are either misaligned or overlapping, making it hard to interact with them.
	•	Impact: Medium (Affects usability and aesthetic appeal)
	•	Screenshot: (IMG_9887.PNG)
	•	Recommendation: Adjust CSS styling and ensure elements are correctly positioned across different screen sizes.
Test Cases:
Test Case ID
Test Description
Expected Result
Actual Result
Status
TC003
Check alignment of pricing cards in different screen sizes
Should be properly aligned
Cards are misaligned
Fail
TC004
Verify if text and buttons are readable on mobile
Should be fully visible
Some elements are overlapping
Fail


3. Missing Navigation Arrows
	•	Description: The navigation arrows expected in a section of the UI are missing, leading to confusion in navigation.
	•	Expected Behavior: Users should see clear navigation arrows where required.
	•	Actual Behavior: The arrows are absent, making navigation difficult.
	•	Impact: Medium (Affects usability and user experience)
	•	Recommendation: Implement the missing navigation arrows and test across devices to ensure visibility and functionality.
Test Cases:
Test Case ID
Test Description
Expected Result
Actual Result
Status
TC005
Check if navigation arrows are visible
Arrows should be present
Arrows are missing
Fail
TC006
Click on navigation arrows to scroll through pricing plans
Should move to the next pricing plan smoothly
No response due to missing arrows
Fail


4. Sign-In Button Not Working
	•	Description: The Sign-In button does not respond when clicked, preventing users from logging in.
	•	Expected Behavior: Clicking the Sign-In button should trigger the login process.
	•	Actual Behavior: No response is observed.
	•	Impact: High (Prevents user login and impacts functionality)
	•	Screenshot: (IMG_9889.PNG)
	•	Recommendation: Ensure the button has an active event listener and that the backend login API is correctly connected.
Test Cases:
Test Case ID
Test Description
Expected Result
Actual Result
Status
TC007
Click the Sign-In button with valid credentials
Should log in successfully
No response
Fail
TC008
Click the Sign-In button with invalid credentials
Should show an error message
No response
Fail
TC009
Check if the button is disabled initially
Should be enabled
Button appears inactive
Fail


5. Social Media Links Not Working
	•	Description: The links for social media apps (Instagram, LinkedIn, Facebook, Twitter) are not opening.
	•	Expected Behavior: Clicking on a social media link should open the respective app or website.
	•	Actual Behavior: The links are unresponsive or do not redirect to the correct page.
	•	Impact: High (Users cannot access social media pages, reducing engagement)
	•	Screenshot: (IMG_9888.PNG)
	•	Recommendation:
	•	Check if the URLs are correctly assigned to the buttons.
	•	Ensure that target links open in a new tab (target="_blank").
	•	Verify if JavaScript event handlers are properly attached.
	•	Test in different browsers to see if the issue is browser-specific.
Test Cases:
Test Case ID
Test Description
Expected Result
Actual Result
Status
TC010
Click Instagram link
Should open Instagram app or website
No response
Fail
TC011
Click LinkedIn link
Should open LinkedIn app or website
No response
Fail
TC012
Click Facebook link
Should open Facebook app or website
No response
Fail
TC013
Click Twitter link
Should open Twitter app or website
No response
Fail


Overall Recommendations:
	1.	Perform thorough UI testing on multiple iOS devices to check for inconsistencies in element alignment and navigation.
	2.	Fix the back button issue to prevent unexpected behavior when navigating.
	3.	Ensure UI elements are properly spaced and aligned across different screen sizes.
	4.	Add missing navigation arrows to improve user experience.
	5.	Fix the Sign-In button functionality to ensure a smooth login process.
	6.	Fix broken social media links by verifying URLs and event handlers.
Final Notes: The UI needs refinement to ensure smooth navigation, proper alignment, and a visually appealing interface. Fixing these issues will significantly enhance usability.

