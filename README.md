# Documentation
https://www.npmjs.com/package/google-distance

## API Keys

Using an API key is not required, but recommended since you can track your usage and make sure you don't exceed [Google's quota](https://developers.google.com/maps/documentation/distancematrix/#Limits). You can request a key by [following these steps](https://developers.google.com/maps/documentation/distancematrix/#api_key).

Specify an API key for use like this:

```js
import distance from 'google-distance';
distance.apiKey = 'AIzaSyByBzUrHGrjp2VT53SWWszsg9fsuCmhfFU';
```

Business users can omit the API key and instead specify their business client and signature keys:

```js
import distance from 'google-distance';
distance.businessClientKey = 'CLIENT_KEY';
distance.businessSignatureKey = 'SIGNATURE_KEY';
```

## Running Application

1) Install the development dependencies:

    npm install

2) Run the application:

    npm start
