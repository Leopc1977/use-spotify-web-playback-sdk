# `use-spotify-web-playback-sdk`

> React hook for interacting with the Spotify Web Playback SDK.

> **Note:** This is using the new [React Hooks API Proposal](https://reactjs.org/docs/hooks-intro.html)
> which is subject to change until React 16.7 final.
>
> You'll need to install `react`, `react-dom`, etc at `^16.7.0-alpha.0`

## Install

```sh
npm install ?
```

## Usage

```js
import useSpotifyWebPlaybackSdk from "?";

function App() {
	const [player, deviceId, isReady] = useSpotifyWebPlaybackSdk({
		name: "NotSpotify Player",
		getOAuthToken: () => token,
	});
}
```

## Help
Check out the best [Spotify Playback SDK](https://developer.spotify.com/documentation/web-playback-sdk/reference/#api-spotify-player) docs for reference or feel free to open an issue.
