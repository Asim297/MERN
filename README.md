1- create MERN directory
2-npx create-react-app frontend
3-install tailwind cc
4-install routerdom
5-create routes folder in src 
6- create index.js file
In index.js type
import { createBrowserRouter } from "react-router-dom";
import App from "../App";

const router = createBrowserRouter([
import { createBrowserRouter } from "react-router-dom";
import App from "../App";
import Home from "../pages/Home";

const router = createBrowserRouter([
  {
    path: "/",
    element: <App />,
    children: [
      {
        path: "/",
        element: <Home />,
      },
    ],
  },
]);

export default router;
7- make components and pages folder in src.
8- In pages make Home.js file and do rafce
9- add path in routes/index.js file like above in the childer
10- add outlet component in app.js to see the home page in the browser.
