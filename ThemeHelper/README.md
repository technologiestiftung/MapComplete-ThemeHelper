# New theme development folder

**What it does:**

The helper page will pull an external theme JSON -> encode it as base64 -> show the official MapComplete website inside an iframe using this base64 version of your theme.

**How to use it:**

You can then change our json and reload the page to see the changes.

Keep in mind that the json file might be cached, depedning on where you pull it from. Github Gist have a cache, for example.

**How to start it:**

1. Open the root folder locally
1. Run `npx serve ./` from within the folder
1. Open the web page and provide the URL to your theme as `/ThemeHelper/?theme=<URL>` param.
