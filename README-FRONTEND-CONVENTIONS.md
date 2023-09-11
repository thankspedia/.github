
  Kombucha.js ES6 Module Convention in React.js (Komesmcoir)
===============================================================

We defines the form of ES6 modules and its filename as described below. We call
it Komesmcoir.

 The Purpose of Komesmcoir
----------------------------
The design purpose of Komesmcoir is to implement scalable development of
frontend applications especially with React-Router.

Modularizing components with React-Router is often complicated and tricky. And
the solutions are tent to vary among the developpers; so we decided to define
the unique convention for modules which are used in React.js applications to
resolve style conflicts.

 The Fields to be Defined in Komesmcoir Modules
-------------------------------------------------

```javascript

/*
 * Define components that should be placed outside the router here.
 * These are usually dialogs.
 */
export const dialogs = [
  <ErrorDialog />,
  <FooDialog />,
  <BarDialog />,
],


/*
 * For further information about data contents of `routes`
 * please see React.js' documentation
 * https://reactrouter.com/en/main/routers/create-browser-router
 */
export const routes = [
  {
    path: "/",
    element: <Root />,
    loader: rootLoader,
    children: [
      {
        path: "team",
        element: <Team />,
        loader: teamLoader,
      },
    ],
  },
];

/*
 * Export the path to the main route.
 */
export const path = '/';



/*
 * Export an object which consists all exported variables.
 */
export default {
  dialogs,
  path,
  routes,
}

```

Komesmcoir modules must have three fields:

- routes : an array contains [React-Router's routes][routes]
- path : string contains the abstract path to the main component
- dialogs : an array of react components



[routes]: https://reactrouter.com/en/main/routers/create-browser-router


