Name : MINNAMAREDDY KALPIKA
Company : CODETECH IT SOLUTIONS
ID :  CT4WD2607
DOMAIN: wedevelopment
DURATION : JUNE 20TH,2024 TO JULY 20TH, 2024
MENTOR : neeela santhosh kumar


Project Overview
Objective:
Create a simple web-based weather forecast application that allows users to enter a city name and retrieve the current weather information for that city using the OpenWeatherMap API.

Key Features:
Search Functionality: Users can input a city name and click a button to fetch the weather data.
Weather Display: The app displays the weather information such as temperature, weather description, humidity, and wind speed.
Components:
1. HTML (index.html):
Structure: Defines the basic structure of the app, including input fields, buttons, and a container to display weather information.
Elements:
A text input for entering the city name.
A button to initiate the search.
A div to display the fetched weather information.
2. CSS (style.css):
Styling: Provides styling to the HTML elements to make the app visually appealing.
Responsive Design: Ensures the app looks good on different screen sizes.
Key Styles:
Centered container for the weather app.
Styled input and button for the search functionality.
Layout for displaying weather information.
3. JavaScript (script.js):
Functionality: Handles the logic for fetching and displaying weather data.
Key Functions:
Event Listener: Listens for the search button click and retrieves the city name entered by the user.
API Request: Sends a request to the OpenWeatherMap API with the city name and processes the response.
Display Weather: Updates the DOM to display the fetched weather information.
Step-by-Step Workflow:
User Interaction:

The user enters a city name in the text input field.
The user clicks the search button.
Fetching Weather Data:

An event listener detects the button click.
The entered city name is retrieved from the input field.
A request is sent to the OpenWeatherMap API using the city name and an API key.
The API responds with weather data in JSON format.
Displaying Weather Data:

The response from the API is processed.
Relevant weather information (e.g., temperature, weather description, humidity, wind speed) is extracted.
The extracted information is displayed in the designated area of the webpage.
Technologies Used:
HTML: For structuring the webpage.
CSS: For styling the webpage.
JavaScript: For handling the logic, API requests, and DOM manipulation.
OpenWeatherMap API: For retrieving current weather data.
How to Run the Project:
API Key Setup:

Sign up on OpenWeatherMap to get an API key.
Replace 'YOUR_API_KEY' in script.js with your actual API key.
Open the Project:

Open index.html in a web browser.
Enter a city name in the input field and click the search button to see the weather forecast.
