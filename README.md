# JSX-React Conditional Rendering
Created with CodeSandbox

## userIsRegistered = TRUE
```javascript

var userIsRegistered = true;

function App() {
  return (
    <div className="container">
      <Form registered={userIsRegistered} />
    </div>
  );
}
```
![alt-text](https://github.com/ericDevSantana/JSX-react-conditional-rendering/blob/master/login.png)


## userIsRegistered = FALSE
```javascript

var userIsRegistered = false;

function App() {
  return (
    <div className="container">
      <Form registered={userIsRegistered} />
    </div>
  );
}
```
![alt-text](https://github.com/ericDevSantana/JSX-react-conditional-rendering/blob/master/register.png)
