# chrome-extensions

### I want to make some extensions and see if i can spark some creativity

Followed the tutorial found here : https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world

#### **Examples**:

- Service Worker
  - https://developer.chrome.com/docs/extensions/get-started/tutorial/service-worker-events
  - `change-page-color`

- Content Scripts
  - https://developer.chrome.com/docs/extensions/get-started/tutorial/scripts-on-every-tab
  -

#### **Useful docs**

- components for how a user interacts with an extension : https://developer.chrome.com/docs/extensions/develop/ui

#### **Useful Dev Tips**

- **To compile scss file:**
  - ctrl + shift + p
  - Live Sass: Compile Sass without watch mode

#### **Future Plans**

- update this to use gulp sass and have all the different extension project folders compile their scss separately

"content_scripts": [
{
"js": ["scripts/content.js"],
"matches": []
}
],
