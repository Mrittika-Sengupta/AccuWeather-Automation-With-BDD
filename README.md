# AccuWeather-Automation-With-BDD
This repository showcases automated tests employing Behavior-Driven Development (BDD) principles to validate the AccuWeather web application. Leveraging tools like Cucumber and SpecFlow, tests are written in a clear, human-readable Gherkin syntax, facilitating collaboration among team members.

AccuWeather BDD Automation

Search City Test Case:

Precondition: Open the Main page.

Consent to data usage.
Input "New York" in the search field. 
Verify the search results list.
Click on the first search result.
Confirm city weather page header contains searched city name.

Recent Locations Test Case:

Precondition: Open the Main page.

Consent to data usage.
Input "London" in the search field. 
Click on the first search result.
Go back to the main page.
Choose the first city in Recent locations.
Confirm city weather page header contains searched city name.

Search City Test Case:

Precondition: Open the Main page.
Consent to data usage.
Click search field. Verify search results list. 
Check if "Use your current location" label is displayed.
