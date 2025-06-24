Architecture

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

The project structure using Angular involved rendering the views on the client side, while the previous Express structure rendered views on the server side and then sent them to the client. This is a difference of frontend vs. backend rendering. There are additional components, models, and services with the Angular structure compared to the views, controllers, and routes of Express. Both use API calls to send and receive data. Angular is a single HTML page dynamically updating on the client. Express is a template engine using Handlebars, dynamically generating HTML on the server before sending it to the client.

The pros of SPA functionality are reduced server load, increased site interactivity and functionality, as well as overall speed and user experience. The disadvantages are a longer initial load and more difficulty optimizing for search engines.

When testing the SPA API calls, Postman was of great benefit. GET calls were tested by loading the trip list view and it was apparent whether it was functioning based on whether the data was displayed. Testing PUT API calls required editing/updating a trip and then saving it. Both the backend and frontend needed to be running for this to function.

Why did the backend use a NoSQL MongoDB database?

MongoDB is great for fast queries and scaling. It also works well with JSON formatting.

Functionality

How is JSON different from JavaScript and how does JSON tie together the frontend and backend development pieces?

JSON is a data formatting specification. By using data stored in JSON and RESTful APIs, the frontend and backend are linked.

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

Code was refactored from static HTML pages to templates using Handlebars, for example.

Testing

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

The GET, POST, PUT, and DELETE methods were all used to communicate between client and server.

Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course has been by far the most comprehensive development experience so far. It was really rewarding to work through the challenges week by week, and I gained a lot of knowledge and confidence along the way. I feel much more comfortable using TypeScript and JavaScript, as well as CSS, HTML, and Handlebars.
My understanding of the full stack has also greatly improved, and being able to work through backend to frontend completely is great. Having experience using Postman and PowerShell is also valuable.
