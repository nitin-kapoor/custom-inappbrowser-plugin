# demo
hidden: set to yes to create the browser and load the page, but not show it. The loadstop event fires when loading is complete. Omit or set to no (default) to have the browser open and load normally.
clearcache: set to yes to have the browser's cookie cache cleared before the new window is opened
clearsessioncache: set to yes to have the session cookie cache cleared before the new window is opened
hardwareback: set to yes to use the hardware back button to navigate backwards through the InAppBrowser's history. If there is no previous page, the InAppBrowser will close. The default value is yes, so you must set it to no if you want the back button to simply close the InAppBrowser.
zoom: set to yes to show Android browser's zoom controls, set to no to hide them. Default value is yes.
mediaPlaybackRequiresUserAction: Set to yes to prevent HTML5 audio or video from autoplaying (defaults to no).
shouldPauseOnSuspend: Set to yes to make InAppBrowser WebView to pause/resume with the app to stop background audio (this may be required to avoid Google Play issues like described in CB-11013).
useWideViewPort: Sets whether the WebView should enable support for the "viewport" HTML meta tag or should use a wide viewport. When th
