MEET APP


Meet App is a serverless, progressive web application (PWA) with React using a test-driven development (TDD) technique. 
The app uses the Google Calendar API to fetch events happing in a city the user has selected, allowing them to view details about the event.

The app uses serverless functions to handle authorization for accessing public calendar events from the Google Calendar API. 
The app's authorization is facilitated by serverless functions, which are a more efficient alternative to building and maintaining a full server. 
For this project, serverless functions generate and provide access tokens, ensuring secure access to the Google Calendar API. 
To meet these goals, AWS Lambda was the chosen cloud-service provider for implementing these serverless functions, which makes the app's architecture scalable and cost-effective.
