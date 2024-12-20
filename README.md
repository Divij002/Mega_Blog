video 15
Redux Toolkit usage
Definitions (npm install redux and redux toolkit first)
store - Store in Redux Toolkit (RTK) is a central hub that manages the state of your React application
reducers - Managing the state by applying reducers to incoming actions. Reducers are pure functions that take the current state and an action as inputs and return a new state.
useSelector - ess se store mei se states ka access mil jata hai
useDispatch - reducer ko use karte hue store ko change karta hai

steps :

1. Create Store - create store in store.js using configureStore() , introduce reducer
2. Create Slice(functions) method(createSlice)
   Slice has name, initialState, reducers :{key: function}
   Access of two things (State, action)
   state = state value in the store
   action = action.payload
   export individual functionality
   export main source export
3. Give values to State i.e Dispatch Courier = use method useDispatch()
4. Take Values - useSelector((state) =>state.todos) state ka access chaiye
   variable me values lelo ek baar aagaie uske baad pure JS concept hai

PROJECT NOTES HERE :-
Video 19
Environment variables are system variables jo sensitive data manage karne m help karte hai. Environment variables project ki root m hona chahie
video 19 --> 11min --> env file ko git ignore m dalte h (i dont have this file)
.env vala data conf.js se leke export karaya hai
.env ka data appwrite se liya hai

Video 20
Built an authentication service file auth.js
In the context of backend development, an authentication service is a system or component responsible for verifying the identity of users and ensuring their access to protected resources. it controls login, logout, sinup, create account and other session mananagement of the user client.

Video 21
Database Service, file upload
config.js banana
Database service is for storage of posts and content on the appwrite platform

Video 22
Redux toolkit insertion and app.jsx redux structuring
store.js and authSlice banai
app.jsx -> loading and useEffect
Note -> postSlice as an assignment khud banani hai. also loading timer

Video 23
React Components
AuthLayout - mechaism/container to protect pages and routes

Video 24
Real time editor, Input Form and Slug
Note - Compare to react-form! Formik and Yup will more easy library to handling and validate the form

changes --> app.jsx, auth,jsx, config.jsx, home.jsx
