Service screens
================

View different sets of screenshots for each service, zoom in and out of them or step through them in order.

Folked from MOJ [http://ministryofjustice.github.io/service-screens/](http://ministryofjustice.github.io/service-screens/)



## Running this app locally

The app is very simple and doesn't require anything to be installed or run in a terminal. Just open the index.html file in the root folder. It works especially well in Chrome's presentation mode. Your mileage may vary in other browsers.


## How to contribute

If you work on one of the services and want to add or update screenshots of it please go ahead, you'd be doing us all a big favour. Pull requests are the best way. You'll need to know how to use Git and how to edit very simple data files.

### Capturing screenshots

On OSX, [Paparazzi](https://derailer.org/paparazzi/) is the best way to capture screenshots. You can set the maximum and minimum widths for the screens, and can capture images in batches.

[Nixon](https://github.com/joelanman/nixon) is a tool that allows you to automate screenshot capture using CasperJS or PhantomJS.

On Windows you can use the [Awesome Screenshot](https://chrome.google.com/webstore/detail/awesome-screenshot-captur/alelhddbbhepgpmgidjdcjakblofbmce?hl=en) plugin for Chrome.

You can also use services like [BrowserStack](http://www.browserstack.com/) or [Sauce Labs](https://saucelabs.com/) for automated serverside screenshot capture.

### 1. Add your images

Each service has it's own folder in `/service`. Drop all your images into the `images` subfolder (1024px wide is best).

### 2. Update the data file

Edit the `data.js` file in your numbered service folder. There is an example file in `/service/.example/` so you can see how the data should be structured.

### 3. Update the index file

Once you're done, don't forget to add a link to your service from the `index.html` file in the root of this repository (not the one in your numbered service folder).

