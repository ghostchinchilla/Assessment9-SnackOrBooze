### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
  React Router is a powerful library that simplifies client-side routing in React applications, making it easier to create dynamic, interactive, and navigable SPAs.

- What is a single page application?
   It's a type of web application that loads a single HTML page and dynamically updates that page as the user interacts with the application.

- What are some differences between client side and server side routing?
  Client-side routing is commonly used in SPAs to provide a smoother and more responsive user experience. It allows for faster navigation between different sections of the application without requiring full page reloads.
  Server-side routing is commonly used in traditional MPAs, where each page is a separate HTML document served by the server. Each navigation request results in a new page being generated and sent from the server to the client.


- What are two ways of handling redirects with React Router? When would you use each?
  <Redirect> component and redirect via history object. The <Redirect> component is typically used when you want to conditionally redirect users based on certain criteria within your components, while the history object approach is more suitable for programmatic redirects triggered by user actions or application logic.

- What are two different ways to handle page-not-found user experiences using React Router? 
  You can define a catch-all route with no specific path at the end of your route configuration. This route will match any URL that doesn't match any of the previously defined routes. You can render a custom component for the 404 page within this route. You can also use the <Switch> component to wrap your routes. The <Switch> component renders the first child <Route> or <Redirect> that matches the current location. By placing your routes inside a <Switch> component, you can define a special 404 page at the end that will only render if none of the other routes match.

- How do you grab URL parameters from within a component using React Router?
  import { useParams } from 'react-router-dom';

- What is context in React? When would you use it?
  Context is a feature that allows you to pass data through the component tree without having to pass props manually at every level. It's useful for providing global data such as themes, localization, or authentication state to components at different levels of the application hierarchy.


- Describe some differences between class-based components and function
  components in React.
  Class-based components have been more traditional, but functin components are gaining popularity due to their simplicity, reusability, and the introduction of hooks. 

- What are some of the problems that hooks were designed to solve?
  They promote functional programming concepts and make it easier to write modular, reusable code.