
# Read: Advanced State with Reducers

Below you will find some reading material, code samples, and some additional resources that support today's topic and the upcoming lecture.

## [](https://github.com/LTUC/asac-advanced-javascript-guide/tree/curriculum-dev/material/class-016#review-and-research)Review and Research

In your reading notes page for this class, provide answers to the following prompts.

1.  How can we ensure that an effect hook runs only once? <br>
*A typical case will be fetching data making an API call, and storing the response in the state variable after the initial render. You do not want to make this API call again.You can pass an empty array as the second argument to the useEffect hook to tackle this use case.*

2.  Can `useState()` update more than one state variable at the same time?<br>
* `useState()` is an asynchronous hook and it doesn't change the state immediately, it has to wait for the component to re-render. useRef is a synchronous hook that updates the state immediately and persists its value through the component's lifecycle, but it doesn't trigger a re-render*
3.  Is `useState()` synchronous?
No, it is not.


### [](https://github.com/LTUC/asac-advanced-javascript-guide/tree/curriculum-dev/material/class-016#document-the-following-vocabulary-terms)Document the following Vocabulary Terms

Term

State Hook

Component Lifecycle

### [](https://github.com/LTUC/asac-advanced-javascript-guide/tree/curriculum-dev/material/class-016#preparation-materials)Preparation Materials

-   [whatIsReducer] ([https://www.robinwieruch.de/javascript-reducer/](https://www.robinwieruch.de/javascript-reducer/))
    
-   [useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)
    
-   [Ultimate Guide to useReducer](https://blog.logrocket.com/guide-to-react-usereducer-hook/)
