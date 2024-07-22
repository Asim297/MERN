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
    {
        path: "/",
        element: <App />,
    },
]);

export default router
