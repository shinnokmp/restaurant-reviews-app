# Front End Nanodegree - Restaurant Review App

This is the 6th project for the [Front End NanoDegree with Udacity](https://eu.udacity.com/course/front-end-web-developer-nanodegree--nd001).

The goal is to practise responsive design, accessibility using ARIA and service worker to cache the contents to develop a proper Offline first application.

## Get Started

### For Users

This is a website where you can search for your favourite restaurant. You can filter your search by location or cuisine type.
Use the dropdown lists to filter your result (on the main page).
See the updated map when you change your selection.
You can see the details of the restaurants by clicking in the "View details of..." link.
The restaurant's details include some reviews, the address and the opening hours.

### For Developers

- Clone the repository
- Go to the folder: `cd fend-restaurant-review-app`
- Run the server using the following command:

#### Run the Local Server

In a terminal, check the version of Python you have: `python -V`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

**Python 2**

`python -m SimpleHTTPServer 8000`

**Python 3**

`python -m http.server 8000`

- Go to _localhost:8000_ to open the website.
- The main HTML page is _/index.html_
- The restaurant's details HTML page is _/restaurant.html_
- The CSS file is _/css/styles.css_
- The JS file for the main page is _/js/main.js_
- The JS file for the restaurant page is _/js/restaurant_info.js_
- The JS file to fetch the data from the server is _/js/dbhelper.js_
- The service worker is located in _/service-worker.js_ and registered in the _/js/main.js_ file.
- The images are located in _/img_ and their resized and optimized version is generated by the gulpfile.

#### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write. 

### Dependencies

- [gulp-jimp-resize](https://www.npmjs.com/package/gulp-jimp-resize)
- [gulp-image](https://www.npmjs.com/package/gulp-image)