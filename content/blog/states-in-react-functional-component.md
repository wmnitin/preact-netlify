---
title: STATES in React Functional Component
date: 2021-09-06T12:02:30.174Z
subtitle: You know how to use variables inside React but you can change varibale
  in reactjs as it will not rerender the component, so here comes the states to
  do this.
tags: reactjs
---
States are also variables, you have to define it differently.

To define a variable you use syntax:
**const name = "Hello World";**

To define a state, you will use this syntax:
**const \[name, setName] = useState("Hello World");**

If you do **console.log(name)** , it will give **Hello World** output in both above cases.

> *Now lets understand what is setName and useState here.*
>
> **setName** is a function, that you will use to change the value of **name.**
>
> **useState** is a react function, which takes the initial value of state.

Now let's understand how you will create state and change the value and see how it will re-render the component to display the updated value.

Play with the example below, try creating another state with different name.

<iframe src="https://codesandbox.io/embed/great-hooks-g1xhc?fontsize=14&hidenavigation=1&theme=dark&view=editor&view=preview"
     style="width:100%; height:500px; border:0; border-radius: 4px; overflow:hidden;"
     title="great-hooks-g1xhc"
     allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
     sandbox="allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
   ></iframe>