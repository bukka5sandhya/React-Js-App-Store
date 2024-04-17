In this project, let's build an App Store by applying the concepts we have learned till now.

Refer to the image below:

![image](https://github.com/bukka5sandhya/React-Js-App-Store/assets/133884532/1de129eb-d777-4128-a6fc-ba06328a14c2)

https://assets.ccbp.in/frontend/content/react-js/app-store-output.gif

Design Files
Click to view
Extra Small (Size < 576px) and Small (Size >= 576px)
Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)
Set Up Instructions
Click to view
Download dependencies by running npm install
Start up the app using npm start
Completion Instructions
Functionality to be added

The app must have the following functionalities

Initially, the Social tab should be active and the apps with Social as their category should be displayed
When a value is provided in the search input
The apps in the active category, that include search input value in their name should be displayed
When another tab is clicked, the apps in the corresponding category, that include search input value in their name should be displayed
The search should be case insensitive
When the search input is empty,
All the apps in the active category should be displayed
When another tab is clicked, the apps in the corresponding category should be displayed
The AppStore component is provided with tabsList. It consists of a list of tabItem objects with the following properties in each tabItem object

Key	Data Type
tabId	String
displayText	String
The AppStore component is provided with appsList. It consists of a list of app objects with the following properties in each app object

Key	Data Type
appId	Number
appName	String
imageUrl	String
category	String
Components Structure

![image](https://github.com/bukka5sandhya/React-Js-App-Store/assets/133884532/5ae1f206-2ce8-4330-9b29-cf9ac38efc27)

Implementation Files

Use these files to complete the implementation:

src/components/AppStore/index.js
src/components/AppStore/index.css
src/components/TabItem/index.js
src/components/TabItem/index.css
src/components/AppItem/index.js
src/components/AppItem/index.css
Quick Tips
Click to view

You can use the cursor CSS property to specify the mouse cursor to be displayed when pointing over an element


  cursor: pointer;

![image](https://github.com/bukka5sandhya/React-Js-App-Store/assets/133884532/91a9cdd4-8395-4636-8932-dc6c8471e820)

You can use the below outline CSS property for buttons and input elements to remove the highlighting when the elements are clicked

 outline: none;

Important Note
Click to view

The following instructions are required for the tests to pass

The apps should have the alt attribute equal to appName of each app object
Resources
Image URLs
https://assets.ccbp.in/frontend/react-js/app-store/app-store-search-img.png alt should be search icon
Colors

Hex: #fff1eb
Hex: #ace0f9
Hex: #1e293b
Hex: #7b8794
Hex: #dfe2e5
Hex: #2563eb
Hex: #ffffff
Font-families
Bree Serif
Things to Keep in Mind
All components you implement should go in the src/components directory.
Don't change the component folder names as those are the files being imported into the tests.
Do not remove the pre-filled code
Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
