Project nr. 9 / 21 - made during the Technigo Bootcamp
___

# Music Releases
This project assignment was to use React components to build a page which shows new album and single releases, using a downloaded response from the Spotify API.

This was our first project coding with React and we used .map() to iterate data from Spotify API that was already stored in a file . 

We started by doing a component called Album where we used props to pass the correct data from the data.json file.
To be able to .map through all the artists and display all of them (if there were more than one on an album) and have them in separate links, we also did an Artist component. In the App.js file we looped both the album info and the artist info separately.

We structured our components by using JSX. To position the albums and have the site responsive we used flexbox, and also added code that fills up the row evenly with the albums, and if there aren't enough to fill a row they are placed to the left. The task was also to apply different hovering effects on the links and icons.

## Techs used:
* HTML, JSX
* CSS, Flexbox
* React
* Pair programming
* Implementation of design

## View it live
https://project-new-releases.netlify.app/
