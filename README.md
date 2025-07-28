## What is strict mode in React?
It is a useful component for highlighting potential problems in an application. Just like `<Fragment>`, `<StrictMode>` does not render any extra DOM elements. It activates additional checks and warnings for its descendants. These checks apply for development mode only. It has no impact on the production build. 
## Adjacent JSX Elements Must Be Wrapped In An Enclosing Tag 
Use fragment to wrap the two component. You are returning two elements simultaneously which causes that error 
