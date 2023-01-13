**Chapter-04 Talk is Cheap, Show me the code**

\1) Is JSX mandatory for React?

`          `No, JSX is not mandatory for react we can write a react code without using JSX.

\2) Is ES6 mandatory for react?

`          `No, ES6 is not mandatory to learn react.

\3) How can I write comments in JSX?

`          `If we want to use single line comment, then we can use like this /\* comment here \*/. For multiple lines comments we can use {/\* This is the multiple comments/\*}.

\4) What is React.Fragment and <> </>?

`           `The meaning of React.Fragment and <> </> is same. We use this because in JSX we can have only one parents i.e. we can return only one element form a react component. So React Fragment allows you to return multiple elements form react component.

\5) What is a Virtual DOM?

`          `The virtual DOM is a representation or we can say lightweight copy of the actual DOM. Manipulating DOM is slow, Manipulating Virtual DOM is fast as nothing gets drawn on the screen. So each time there is a change in the state of our application, the virtual DOM gets updated first instead of the real DOM.

\6) What is Reconciliation in React?

`        `Basically it is a process where we have a div algorithm which finds the difference between tress. It will only re-render the specific portion which div algorithm finds.

\7) Why we needs keys in react? When we do need keys in react?

`          `If we don’t use keys it will re-render everything and we don’t want that. We need keys when there is a multiple child in a tree.

\8) can we use index as a key in react?

`         `Yes, we can use index as a key but sometimes index have a negative values we don’t want that our key will have a negative values. So its better to use as a key as a unique values.

\9) What is a React fiber?

`         `It came in a React16, basically it is a new reconciliation engine. The goal of react fiber is to increase its suitability for areas like animation, layout and gestures. 

\10) What is props in react? Ways to

`           `Props is basically argument for a functional component. The ways are

`           `1)wrapping under props

`           `2) Destructuring 

`           `3) By spread operator

\10) What is config driven ui?

`           `A config driven UI will control our Frontend. Backend control our website means how our website look like in a different states or a country. 
