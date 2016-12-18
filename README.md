# <a href='http://redux.js.org'><img src='https://camo.githubusercontent.com/f28b5bc7822f1b7bb28a96d8d09e7d79169248fc/687474703a2f2f692e696d6775722e636f6d2f4a65567164514d2e706e67' height='60'></a>

This fork [contains](https://github.com/joost-de-vries/redux/tree/master/examples/todos) a port of the redux [todos example application](http://redux.js.org/docs/basics/UsageWithReact.html) to Typescript 2.1.4. The following recent Typescript features were required to make the original code compile as Typescript:  
- tagged unions for the reducers
- spread operator for copying objects to preserve immutability
- mapped type `Partial` to [make the attributes of a functions return type optional](https://github.com/joost-de-vries/redux/blob/master/examples/todos/src/containers/FilterLink.ts#L6) to prevent a compilation error that [can be puzzling](http://stackoverflow.com/questions/39908666/property-is-missing-in-type-error).

