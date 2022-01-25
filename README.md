# Accelerating Poutine Production

Below is a list of all the technologies I used to build this app:

- React.js
- Tailwinds CSS
- GSAP animations library
- Axios HTTP client library
- Jest Testing Framework

I wasn't sure what the projects were asking for at first. I randomly selected a project. I clicked on, and choose Accelerating Poutine Production.

I focused on the design first, as it gave me time to think about the logic. After completing the design, I had a better idea on what the project was asking for. I tried my best to fullfill all that is needed for this web app, and to interpret what's needed for the app to function, and I hope that my work is ok.

I'm new to testing and this is the first time I've built a test suite, but I read through the documentation at jestjs.io and understand what it is now.

I used jsonlint.com JSON linting tool, to make sure the JSON in the API is in valid JSON format, and I hosted the API data on https://www.jsonserve.com

For the components, I made the background all one component, and I made a component for each of the robots. The robot components consists of, the robot, the kitchen item beside the robot, and the button underneath them.

## Bonus/optional

### Differentiate the business critical part against the purely technical ones:

The business critical parts of the application are the API data source. This is because the API data gives others in the future to view the inventory (Robots' tasks) and understand the structure of the business by viewing the types of data that it holds for the business to function. The API calls from the browser can also be considered as a business critical part of the site.

The technical part is the simple animations which interacts with the user and keeps them engaged. The UI/UX design is also technical, giving the user a user-friendly experience, that is accessible, simple to navigate, and easy to understand. Making the site functional and usable.

The the test suite is also a technical part of the application. It allows for a new person to be able to figure out how the application works, add new functionality and maintain the code. That way if the code needs to be refactored, the test suite will ensure the web application works the way it's intended.

### Identify the part that will be costly to maintain in your test suite, and propose solutions:

The part that will be costly to maintain in the test suite would be making sure the API calls are all active and working. I would recommend making sure code (callback functions) be maintained and monitored to ensure calls to the API are consistent with any updates made to the API data. Any changes to the API data should be reported, so the robots can always return the most up-to-date info, and ensure the robots are properly co-ordinated with their tasks.

### Pick GraphQL/gRPC or other non-RESTful API format to streamline part of the process and explain your choices:

I did not include GraphQL/gRPC in this project, as I have yet to get myself familiar with these technologies. I've already taken a look at GraphQL and will be using it in the near future. As it has become an important and popular tool to use in the development process.

### Using The Text Editor?
1. To get the app running in the browser while using a text editor, you will need to use "npm start".
2. To add any missing packages/dependancies, you will need to use "npm install".
3. To run the test suite you will need to use "npm test".
