# react-directory-tree
> Directory for react.

## installation
```shell
npm install -S @feizheng/react-directory-tree
```
## properties
| property        | type | description |
| --------------- | ---- | ----------- |
| className       | -    | -           |
| value           | -    | -           |
| onChange        | -    | -           |

## usage
1. import css
  ```scss
  @import "~@feizheng/react-directory-tree/dist/style.scss";

  // customize your styles:
  $react-directory-tree-options: ()
  ```
2. import js
  ```js
  import React from 'react';
  import ReactDOM from 'react-dom';
  import ReactDirectoryTree from '@feizheng/react-directory-tree';
  
  // your app:
  class App extends React.Component{
    render(){
      return (
        <ReactDirectoryTree />
      )
    }
  }

  // render to dom:
  ReactDOM.render(<App/>, document.getElementById('app'));
  ```

## documentation
- https://afeiship.github.io/react-directory-tree/

## resources
- https://medium.com/the-guild/recursive-react-tree-component-implementation-made-easy-466dfce1a008
