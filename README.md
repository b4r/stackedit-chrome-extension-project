# localhost:8080 StackEdit.io Markdown Extension

This extension is lightly modified from the existing version 1.0.4 in the Chrome Web Store.

In order for this extension to work fully it will rely on https://github.com/benweet/stackedit

StackEdit.io must be running locally (`npm start`) for the extension to work - by default the extension relies on access to the stackedit.io website.

For information how to setup a local copy of stackedit.io server, check https://github.com/benweet/stackedit/issues/1697
(this may change in the future)

![image](chrome-load-ext.png)

## Steps

* Clone this repo

* Open Chrome

* Open the extensions window or visit the address chrome://extensions

* Activate Developer Mode on the top right corner.

* Click the button "Load unpacked" currently near the top left corner.

* Navigate to this repo and select to open the directory `stackedit.io-chrome-ext-standalone` - optionally, move the directory where you need it and point Chrome to the new location.

* Done, the extension should now be loaded in Chrome and ready to use the same as the original.

Features will be missing from this - a lot of this is just a hack but might be useful for you in some way.

