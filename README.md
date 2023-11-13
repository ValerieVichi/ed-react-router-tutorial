# React Router tutorial which is taken from their official web page https://reactrouter.com/en/main/start/tutorial

Building a small, but feature-rich app that lets you keep track of your contacts.
Exploring usage of the most common React Router hooks and features:

- creating a router, root element, and using the router provider
- establishing and rendering error page through error element
- rendering components inside the Root component by passing them as children and rendering (importing and using) an "Outlet" (way to tell React Router where the children should go) inside of our output code
- setting up the client side routing by changing the "a href" to "Link to"
- loading data by using loader and useLoaderData, so that React Router would automatically keep that data in sync with the UI.
- creating new items using client-side routing - an action in our root route, wiring it up to the route config, and changing HTML "form" to a React Router "Form".
- using "params" that are passed to the loader as keys that match the dynamic (:key) segment
- setting up CRUD using React Router
- setting up the default children route by using { index:true } instead of { path: "" }.
- establishing the cancel button using the "Navigation" hook
- enabling submissions using client-side routing (search form)
- implementing the "useSubmit" hook for submitting the search form filter on any change in the search tab
- managing the history stack using "replace" in useSubmit hook
- applying the "useFetcher" hook to communicate with loaders and actions without causing a navigation
- using the Optimistic UI technique that helps the user see the change before it is registered


<img width="886" alt="image" src="https://github.com/ValerieVichi/ed-react-router-tutorial/assets/127167123/e9a1ce48-4e2e-4563-ab37-430cd111229b">
