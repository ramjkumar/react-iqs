## What is strict mode in React?
It is a useful component for highlighting potential problems in an application. Just like `<Fragment>`, `<StrictMode>` does not render any extra DOM elements. It activates additional checks and warnings for its descendants. These checks apply for development mode only. It has no impact on the production build. 
## Adjacent JSX Elements Must Be Wrapped In An Enclosing Tag 
Use fragment to wrap the two component. You are returning two elements simultaneously which causes that error 
## Component composition
Component composition is a fundamental concept in React that allows us to build complex UIs by combining smaller, independent components. 
It provides the following advantages:
- **Reusability**: components can be reused
- **Maintainability**: easier to update and manage the code
- **Improved Readability**: Smaller, focused components are easier to understand and debug 
```js
const Header = () => <h1>Welcome !< /h1>; 
const Content = () => <p>This is the main content .< /p>; 
const Footer = () => <small>@ 2025</small>; 
const Page = () => ( 
  <div> 
    <Header /> 
    <Content /> 
    <Footer /> 
  </div> )
  ```
