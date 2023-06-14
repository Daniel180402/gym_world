# Gym_World
#### Video Demo:  https://youtu.be/Vvv3I9Uzb9A
#### Description: In last years people are more likely to stay at home and to study and work for lots of hours a day, it is very important to train a for that reason I developed this app that helps you to stay in shape all while staying in the comfort of your home. In this web app you have the option to select which body part to train, and the app will filter the data it's gets from the API to find the best exercises for the selected body part, you can choose any of the exercises the web app shows you and that will bring you to the detail page of that exercise, showing you the name and the GIF of that exercises to better understand of to perform it.
If you want more info about it, if you scroll down on the exercise detail page, there will be a few videos that will bring you directly to that YouTube video to better understand it.
If you don't like that exercise or want to do another one, on the lower part of the page you can find similar exercises that train a specific body part or exercises that use specific equipment.
  
## Pages

### Home page
  The Home page is made by several components, such as:
  Navbar: A simple navbar with logo, and two links that you can use to navigate the main parts of the Home.
  HeroBanner: Also knows as the jumbotron, it's the part of the page where you can see the catchphrase of the page with a simple but catchy design.
  SearchExercises: In this section you can search for a specific exercise, enter a specific body part or an equipment and the web app will filter the API to show only the desired workouts
  HorizontalScrollbar: In this section you have the option to filter the API by selecting which body part you want to train, and the web app will show only those exercises.
  Exercises: In this part of the home page you will get all the results of the serachExercises and HorizontalScrollbar components, this part divides all the results is several pages using Pagination, only showing 9       results for page. These cards are all clickable and this brings you to the detail page of that exercise.
  Footer: A simple footer for the pages
  
### ExerciseDetail
  The exercise detail page gives you more info about a specific exercise and gives you other exercises to do that have effect on that specific body part or that use the same equipment.
  Detail: The detail component shows you the GIF of the exercise to better understand it, and gives a small description, also it says what body part it has an effect on and which equipment is needed.
  ExerciseVideo: The exercise video component simply gives you a few clickable cards of YouTube videos that can help you understand how to do that specific exercise
  SimilarExercises: This component shows you similar exercises that help you workout that specific body part or use the same equipment type.
  

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
