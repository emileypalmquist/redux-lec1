# Redux Pt.I

# Questions

1. How do we create our store using Redux?
  - What argument/s does that function take?

  - What does that argument do?


2. How do we change the state of our application (/store)?
  - What one property should this POJO always have?


3. What piece of Redux assures that we don't directly modify state, and 
instead make a new copy w/ the modifications?
  - 


4. Knowing what we know now, how can we make React and Redux play nicely together so that we can update our application state, without using component-level state?


* Vocab
application state - Redux state, lives in store.
component-level state - regular React state, can live in any component in the app.


* (After going through Store, rootReducer, getState(), dispatch(), and modifiying Redux state)


BONUS: (10 minutes)
```
Build a way to increment the count by 2 and 5 in our app. 

At first do this using multiple buttons, then try to do it by using one (you can also do this using a form).
```