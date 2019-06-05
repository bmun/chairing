
# Radio

A web app to chair Model United Nations Committees

## Setup


1. Fork, clone, and navigate to this repository
2. You will need to create `src/constants/dbconfig.js`. The file should be of the form:
    ```
        export const apiKey= "stuffHere";
        export const authDomain= "stuffHere";
        export const databaseURL= "stuffHere";
        export const projectId= "stuffHere";
        export const storageBucket= "stuffHere";
        export const messagingSenderId= "stuffHere";
        export const appId= "stuffHere";
    ```
3. This project is designed to use a Firebase Database. Either create your own project in Firebase or contact me for the keys.
4. Run `npm install` for dependencies.
5. Run `npm start`. The project will be hosted at `localhost:5000/`.