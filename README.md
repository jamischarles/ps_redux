# ps_redux
Status updates for Redux Fundamentals course https://www.pluralsight.com/courses/redux-fundamentals will be posted here 

## Course code examples
The code for the course can be found at https://app.pluralsight.com/library/courses/redux-fundamentals/exercise-files

## Updates
No recent updates.

## Questions / Comments / Concerns
I you like the course, please rate it, and consider dropping me a note in the `discussion` section on the course page or on twitter.

If you have problems with the code, please let me know.

Thanks for watching the course.

## FAQ

Q: In the React Crash course section, where do you get the `js/lib/react.min.js` and `js/lib/react-dom.min.js` files from?  
A: For all of the files in this example, I pulled the source from [https://unpkg.com](https://unpkg.com). It's essentially a CDN that allows you to easily load any file from any npm package. While node.js uses the commonJS format to load files / modules and webpack now supports commonJS as well, before webpack and browserify it was common to use the UMD / AMD format. In a nutshell it basically means there is a production-ready version of the library that is bundled as 1 file. You can read [more on commonJS vs AMD vs UMD here](https://www.davidbcalhoun.com/2014/what-is-amd-commonjs-and-umd/). So for most npm packages that can be loaded in a browser, you can use [https://unpkg.com](https://unpkg.com) to get a standalone file that you can manually copy in (if you aren't using webpack etc) by typically looking in the the `umd` or `dist` folder.

Examples:
```
https://unpkg.com/react@16.0.0/umd/react.production.min.js
https://unpkg.com/react-dom@16.0.0/umd/react-dom.production.min.js
https://unpkg.com/redux@3.7.2/dist/redux.min.js
```
