<!--
- I'm assuming if you are looking at this, you must be thinking "Wow, that's pretty neat!"
and "I can't wait to finaggle together a totally sick and amazing README like this."

- I used this method to be able to use CSS inside of markdown (basically putting it inside a foreignObject inside an SVG)
https://github.com/sindresorhus/css-in-readme-like-wat

- And I used a text glitching animation by Isaac Doud
https://codepen.io/cipherbeta/pen/YLdVjw
except I made the skew animation less extreme, and removed the background, which had a background image using a url
which doesn't work inside the SVG foreignObject

- And I removed the Montserrat font import since that doesn't work inside SVG foreignObject
so basically you can use most CSS but some things do not work
and you have to make sure you are using plain CSS and not SASS

- Also worth noting that using links inside the html in the SVG foreignObject won't work
because when a user clicks on the SVG, it will take them to that SVG file's location in the repo
so you instead need to use your SVG as an image in the README.md file and wrap that img in a link
-->

<a href="https://thomasfoydel.com">
    <img src="header.svg" width="800" height="470">
</a>

<a href="https://github.com/ThomasFoydel/roshambo">
    <img src="projects/roshambo.svg" width="800" height="110" >
</a>

<a href="https://github.com/ThomasFoydel/fitra">
    <img src="projects/fitra.svg" width="800" height="110" >
</a>

<a href="https://github.com/ThomasFoydel/cleanbreak">
    <img src="projects/cleanbreak.svg" width="800" height="110" >
</a>

<a href="https://github.com/ThomasFoydel/fmsynth">
    <img src="projects/fmsynth.svg" width="800" height="110" >
</a>

<a href="https://github.com/ThomasFoydel/svelte_snake">
    <img src="projects/sveltesnake.svg" width="800" height="110" >
</a>

<a href="https://github.com/ThomasFoydel/pandatron">
    <img src="projects/pandatron.svg" width="800" height="110" >
</a>

<!-- <a href="https://github.com/ThomasFoydel/socketchat">
    <img src="projects/socketchat.svg" width="800" height="110" >
</a> -->
