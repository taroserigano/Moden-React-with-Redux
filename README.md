# Modern React with Redux

A collection of ReactJS sample exercises based on tutorial videos of Udemy's Modern React with Redux course

### Video Browser App:
- video sections "An Intro to React" and "AJAX Requests with React"
    - uses [Youtube API](https://developers.google.com/youtube/v3/)

### Book List App

### Weather App
  - uses openweathermap.org's free API to get weather data
  - also uses google maps
  
### Blog App
  - uses API Stephen Grider wrote for this tutorial: http://reduxblog.herokuapp.com/
  - uses [axios](https://www.npmjs.com/package/axios), which is a "Promise based HTTP client for the browser and node.js"
  - video section "Exploring the Posts API"
    - uses Postman, a free application for API Development: https://www.getpostman.com/

---------------------------------------------------------------------------------------------------
- if you accidentally push node_modules to a repo by not putting them in the .gitignore
    file and need to remove them, run:
    - `git rm -r --cached node_modules`
    - `git commit -m "remove the ignored node_modules directory"`
    - `git push origin master`
