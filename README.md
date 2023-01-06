# Mozilla Firefox - userChrome.css
After switching to Firefox (after years of using of Google Chrome) I found that some of the UI choices were a bit distracting. Luckily Firefox allows you to create a custom userChrome.css file to make as many tweaks as you'd like to personalize the interface. This is my personal userChrome.css file along with instructions on how to install them on another computer.

## Enable Custom Profiles
  1. Navigate to `about:config`
  2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
  3. Set prefence to `true`

## Installation Instructions (Windows)
  1. Click the _Hamburger Menu_ to the right of the address bar
  2. Click `Help`
  3. Click `More Troubleshooting Information`
  4. Find the row labeled _Profile Folder_ and click `Open Folder`
  5. Open the `Chrome` folder (create it if it does not exist)
  6. Extract the contents of this Git
  7. Restart Firefox
  
## Making It Your Own
Edit the CSS in the `userChrome.css` file to add or remove any custom code.

## Helpful Links
  - [FirefoxCSS Subreddit](https://www.reddit.com/r/FirefoxCSS/)
  - [Enabling the Browser Toolbox](https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html)
  - [How-To Geek article about userChrome.css](https://www.howtogeek.com/334716/how-to-customize-firefoxs-user-interface-with-userchrome.css/)
