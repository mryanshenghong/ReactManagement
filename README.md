# UI Framework, Ant design
Powerful ui components with encapsulation, also can custmize them for special requirement.
e.g -encapsulate antd form component to a react component and reuse it in project.
    -use Less to manage css variables.
# Install babel-plugin-import plugin to finish antd modules lazy load=>
```
// Process application JS with Babel.
// The preset includes JSX, Flow, TypeScript, and some ESnext features.
{
  ... // code here
    plugins: [
    ... // code here
      [
        require.resolve('babel-plugin-import'),//  import 
        {
          libraryName: 'antd',   //expose antd
          style: 'css'
        }
      ],
    ],
    ... // code here
  },
```
# Ajax request, encapsulate axios plugin with Interceptor unifiy all http request.
# Use React-Router-Dom manage front-end router. 
-Match Parent route and use child route to different pages and modules.
-Use {this.props.children} shows different child components.

# Exract Common Components Header, NavLeft , Footer, Table, Form to reuse in whole project.

# Encapsulate Utils and reuse them when necessary.

