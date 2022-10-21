# Create React App - Jamming

This project, I built a React web application called Jammming. It was a larning project using React components, passing state, and requests with the Spotify API to build a website that allows users to search the Spotify library, create a custom playlist, then save it to their Spotify account.
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

---

## Ken's Jamming App Scripts

The applications [surge](https://surge.sh/), a static web publishing to host the site: <https://kenh_tunes.surge.sh/>

## App Features

- Include preview samples for each track
- Only display songs not currently present in the playlist inthe search results
- Add a loading screen while playlist is saving
- Update the access token logic to expire at exactly the right -time, instead of setting expiration from when the user initiatestheir next search
- After user redirect on login, restoring the search term from -before the redirect
- Ensure playlist information doesn’t get cleared if a user hasto refresh their access token

## Acknowledgement

This was a long form project from [Codecademy's Web Development skill path.](https://www.codecademy.com/learn/paths/web-development)