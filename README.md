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
