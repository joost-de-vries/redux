# <a href='http://redux.js.org'><img src='https://camo.githubusercontent.com/f28b5bc7822f1b7bb28a96d8d09e7d79169248fc/687474703a2f2f692e696d6775722e636f6d2f4a65567164514d2e706e67' height='60'></a>

This fork [contains](https://github.com/joost-de-vries/redux/tree/master/examples/todos) a port of the redux todos example application to Typescript 2.1.4 using tagged unions and the spread operator.  
It won't compile without either setting defaults for props on every element or making the attributes of the props optional. Neither approach is very elegant. 
This [implements](https://github.com/joost-de-vries/redux/blob/master/examples/todos/src/components/Footer.tsx#L4) the former.
