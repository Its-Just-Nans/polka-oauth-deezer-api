# polka-deezer-api

A tiny web server using [polka](https://github.com/lukeed/polka) to access the [Deezer API](https://api.deezer.com/) using the [OAuth Procedure](https://developers.deezer.com/api/oauth).

In this example the server is retreving informations about tracks of the loved playlist.

## Usage

- Create a Deezer App at [https://developers.deezer.com/myapps](https://developers.deezer.com/myapps).
- Edit the config.json file
- Run commands

```sh
npm i
node index.js
# go to the web page /
# you will be redirected to Deezer login then the Deezer authorization page
```
