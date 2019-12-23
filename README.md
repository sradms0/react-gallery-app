# Image Gallery
An image gallery application that fetches data from the Flickr API.

## Built With
* Node 11
* React 16

## Prerequisites
* A modern web browser using an up-to-date JavaScript engine.
* A Flickr API key: https://www.flickr.com/services/api/misc.api_keys.html

## Configuration
* Store your Flickr API key in an environment variable in `/.env`:
    ```bash
    REACT_APP_API_KEY='flickr_api_key'
    ```
* The application generates 'default' topics for images in buttons, based on a JSON file, `/src/etc/data.json`:
    ```javascript
    {"default_queries": ["samurai", "mountains", "goat yoga"]}
    ```
    This data may be changed to whatever you'd like.

## Run
```sh
npm install && npm start
```
