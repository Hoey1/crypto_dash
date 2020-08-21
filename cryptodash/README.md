# crypto_dash

# Industry Technology Used

`React`
`Styled-Components`
`CSS Grid`
`HighCharts`
`CryptoCompare API`
`Async/await`
`Fuzzy Search`
`Lodash`
`Webkit Inspector`
`localStorage`
`Google Fonts`

---

# Product Tour

### Settings Page with Intro Greeting

- Greeting the user on first visit, asking them to choose their favorits
- Providing a defualt 5 coins as favorites & a complete list of all coins
- Searching for coins with `Fuzzy Search`
- Hovering and Selecting coins
- Adding/Removing coins on the list of favorites
- Disabling out chosen coins
- Confirm Favorite Coin
  - Remembers those values for the user
  - Generates dashboard prices & historical data

### Dashboard

- Data initializes from remember3ed favorites, or forwards to `Settings` page
- Displays 5 major `Cards` for first 5 favorites and compact `Cards` for next 5
- Renders a line chart for the 10 historical points on current favorite symbol
- Select coins changes and re-fetch data, remembers current favorite
- Select to render historical points on Date: `Days` `Weeks` `Months`
- Display name and image of coin next to chart
- Dark / Light Mode

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
