# SpotifyApi

## About
- Skeleton code to help iOS developers with setting up and using Spotify's API
- You can see its implementation on the app https://apps.apple.com/us/app/favorites-for-spotify/id1523134103

## Setup
- Spotify's guide: https://developer.spotify.com/documentation/general/guides/authorization-guide/
- Create a redirect URL: with URL, encode the website using https://www.urlencoder.org/
- Create Encoded ID: Spotify's Basic Auth which is "clientID:clientSecret", base64 encoded using https://www.base64encode.org/
- Set scopes to retrieve certain information: ie, "user-top-read" is required for reading user's top artists/tracks data
- Client ID and Secret ID on Spotify's Developer site: https://developer.spotify.com/documentation/general/guides/app-settings/

## Links
- Spotify Developer Dashboard: https://developer.spotify.com/dashboard/login
- Spotify Authoration Guide: https://developer.spotify.com/documentation/general/guides/authorization-guide/
- Spotify API Reference: https://developer.spotify.com/documentation/web-api/reference/
- Base 64 encoder: https://www.base64encode.org
- URL encoder: https://www.urlencoder.org

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
