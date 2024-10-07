## <a name="api">API</a>

You can view the source code for the API here:

[https://github.com/billy93/expo-web-api-uber](https://github.com/billy93/expo-web-api-uber)

To change the API link, go to `app.json` -> `plugin` -> `expo-router` -> `origin`, and replace it with your API deployment URL.
Additionally, there is a small update in `lib/fetch.ts` to add a base URL when performing the fetch request (link from app.json above).
