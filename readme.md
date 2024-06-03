# React Router DOM

- We have configure routes and make sure that different components are loaded for different paths.
- We discuss that we can handle errors and how you can set up layouts that wrap itself around multiple routes.
- Add about nested routes.
- Most importantly, learned about data fetching and submission.
- Moreover, how we can generally set up data fetching and submission with loaders and actions.

#### Advanced use cases

- Where we use the useFetcher() to fetch or load data behind the scenes without navigating.
- And we discuss about deferring data fetching.
- Which can be helpful if you have some slow requests, some slow backend, and you wanna show a page without waiting for the data to be there. Or if you have multiple pieces of data and you wanna show some data before all the data is there as we had it here with the single event and the list of events.

Once you start building real React apps, more complex React apps. You will almost always need routing.

And especially the data fetching and submission capabilities of React router can make that data fetching and submission part a breeze.

#### How to setup this application

This project actually contains two projects:

- A React.js application (i.e., the frontend SPA)
- A dummy backend API to which the React app can "talk" (to send + fetch data)

You must run "npm install" in both project folders.

Thereafter, you can start the dummy backend API server via "npm start" (inside the "backend-api" folder).
The React app dev server is then also started via "npm start" (though inside the "react-frontend" folder).

You MUST have both servers (backend + frontend) up and running for the projects to work.

The dummy backend API does not use any external database - instead the dummy data is saved to an "events.json" file inside the project folder.
