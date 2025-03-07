------------------------------------------------
|-## How to create a slice in redux toolkit ##-|
------------------------------------------------

--> step:1👍 import createSlice method from redux toolkit
    import { createSlice } from "@reduxjs/toolkit";

--> step:2👍 create a variable and store createSlice() method 
    const signInSlice = createSlice()

--> step:3👍 createSlice() method will take a object as parameter which has the following properties
{
      name:createSlice,
      initialState: {},
      reducers:{
        // some fucntions 
        }
  }

--> step:4👍 now export action methods from signInSlice.actions
    const {addUser, deleteUser} = signInSlice.actions

--> step:5👍 default export signSlice.actions
    export default signInSlice.reducer
____________________________________________________________________________________________________________________________________


