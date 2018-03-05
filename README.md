# Next Web Info React-native sample app

Basic useful feature list:

 * This is the app for [The Next Web](https://thenextweb.com/#.tnw_zeXCSz3h) to display published technology blogs.
 * We are using Public api [News API](https://newsapi.org/) to get the JSON response from the REST APIs hosted by The Next Web.
 * We are using react-native listview to render the list of blogs.


### Steps to run:

 * Create local.properties and mention your android sdk path in it under android folder
 * react-native run-android

Here is the request url to The Next Web API:

```javascript
var REQUEST_URL = 'https://newsapi.org/v1/articles?source=the-next-web&sortBy=latest&apiKey='
```