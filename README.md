# react-test

Task

Create a 3 page application with Zustand as the state management system for auth data

1) Login Page - 2 input fields and 1 "Login" button
2) Dashboard Page - Button that navigates to account page
3) Account Page - Button that navigates to Dashboard page and Logout Button

Login page should be shown by default if the user is not authenticated
Dashboard page should be shown by default if the user is authenticated
The user should not be able to navigate to the account or dashboard page if they are NOT authenticated
The user should not be able to navigate to the login page if they ARE authenticated
There should be a button on the dashboard page to route to the Account page
There should be a button to log the user out in the account page

Implement a basic auth flow with a username and password - There should be some basic validation on input fields
Implement Zustand for state management and create a store for the returned user object and JWT - https://github.com/pmndrs/zustand
Authenticate against an API using the provided credentials
Save the JWT and user object in created store
Route the user to the 'Authenticated' side of the app if their login was successful
If a user is authenticated, create a method of adding the JWT to the Authorization header of every subsequent API call
If the user logs out it should clear all saved state

API: https://app-api.feature.surehub.io/api
Login POST: https://app-api.feature.surehub.io/api/auth/login
Sample Payload: {"email_address":"t@t.com","password":"aA1!1111","device_id":"1430b45a0b"}


Please clone/fork this repository (it was created using Expo instructions here: https://docs.expo.dev/get-started/create-a-new-app/)
Commit work to your own repository then share a link back to your own repo when finished
You can run the app on device or in the web browser with 'expo start' 
