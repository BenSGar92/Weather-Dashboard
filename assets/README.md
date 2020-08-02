# Weather-Dashboard
Weather Forecast Application


HTML:
-Created the layout using Bootstrap.
-Adjusted the columns to get the right sizing.


CSS:
-Created a basic color layout.
-Added a button:hover to make the buttons look/feel more responsive.
-Added text-transform to capitalize the button text.
-Added google fonts.


Javascript:
-Added moment.js to create my h1 tag header and also the future forecast dates.
-Using jQuery I created an on-click function for my search button(.btn) that takes the value of the user-input and runs the searchCity function.
-searchCity() runs an AJAX call that uses the queryURL variable to GET the object.
-Using dot notation to traverse the object I was able to GET temperature, humidity, windspeed, latitude and longitude
-Latitude and longitude were used in my 2nd AJAX call which GETs a 2nd object that includes the 5 day forecast info, as well as the UV index.
-Information stored locally is also within the jQuery click event which pushes the user input into an array and lastly it clears the input field and runs the run() function.
-The run() function first clears the buttons to avoid them piling up and then, using a for loop, displays the information from the local storage as clickable buttons.
-To make these buttons clickable, the 2nd jQuery click event take the text from the button and sends it back into the AJAX call to display the information


Screenshots of App:
