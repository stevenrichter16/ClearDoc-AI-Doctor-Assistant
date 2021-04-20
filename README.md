# ClearDoc, an AI-powered web application to simplify medical terminology

This project was coded mainly by myself (Steven Richter) using React.js and Flask. Styling credit goes to Tim Muster, and GPT-3 prompt engineering credit goes to Alan Majer and Matthew Donaruma.

The motivation for this application came from recognizing the dense and confusing nature of clinical notes and medical terminology. My NextGrid hackathon team brainstormed and developed this application for the purpose of simplifying medical terminology with the use of GPT-3, a deep learning model developed by OpenAI. 

Over the course of 12 hours I created the front-end and back-end from scratch, only having moderate knowledge of React.js, and minimal knowledge of Flask. Through much trial and error, I accomplished setting up a REST API with Flask.

The main issue I encountered in creating the API centered around the POST method. Previously I had used Flask to process and send data from the server to the front-end, but I had never developed an API to send user input from the front-end to the back-end, then back to the front-end. The need for this functionality was due to the fact I needed to grab user input from the front-end, send it to the Python server, process it through the GPT-3 API, then send that data back to the front-end to be displayed. 

In the end this project gave me experience in full-stack web development, and sharpened my communication skills. 

A url for this web application will be available soon. Here is the slide deck for the presentation my team and I gave during the hackathon: https://docs.google.com/presentation/d/1lIQbtUXYoazawjZ-VRQ_8Shp3e8G37gkbUy-jFxrqlI/edit?usp=sharing

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

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
