# redux-firebase
## UNDER DEVELOPMENT

# Preface
This library integrate firebase into redux using the following library, now only support firebase authentication only
- redux-observable
- recompose

# Setup
1. `npm i -s redux-firebase`
2. register reducer and epic

     import { reducer as fireBaseReducer } from 'redux-firebase';
     import { createStore, combineReducers } from 'redux';
     
     const fireBaseApp = createFireBaseApp;
     
     const reducers = {
       fireBase: fireBaseReducer,
     };
     
     const store = createStore(combineReducers(reducers), )
     
