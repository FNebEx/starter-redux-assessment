# Starter redux assessment: Doggiegram 

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Assessment for the Redux module for Chegg Skills. 

There is a file that was added to project, `test.http`. It only exists to make sure that the server is actually returning data. 

Here are some of the things that I learned from this module:
1. Slices are really just part of the state. This entire project could've had a state variable with `photos`, `suggestions`, and `search` properties. 
2. It's important what the reducer key in `store.js` is called. If the reducer's key is "something", and an object called "notes", in the slice file, you'd export `state.something.object` where the object is whatever is in the initial state. 

This was a good project. The only downside is that I believe that Redux has a new way doing things. It's somehting that I'll have to look into more. 