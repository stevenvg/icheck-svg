## iCheck-SVG

Add SVG functionality to fronteed/iCheck for easy custom colors through LESS.


#### General

This is a prototype to add SVG functionality to iCheck.js through LESS, although it is possible this could be achieved through any other "Language".

What it does is fairly simple, it reads an external SVG file and replaces a defined color with another one, which in turn spits the result out as an inline background data-uri. Because Firefox was giving output problems due to not being encoded, this is also done in the process.

more to come


#### Requirements

- iCheck base JS file & its dependencies.
- A LESS compiler, any really, as long as you can compile locally. I didn't test remote.
- An SVG editor if you want to adjust the shapes.


#### Setting up

coming soon


#### To-do

- [ ] Add dynamic theming and more example "skins".
- [ ] Better calculations for dimensional properties.
- [ ] Add dynamic sizing (at his point it doesn't scale to a given size).
- [ ] Add custom variables for the disabled states, or make them black with an opac.
- [ ] Remove the background property when composing the data-uri.
- [ ] Add a version for SASS and php.
- [ ] Put up an example.
- [ ] Look into regular css Fill instead of reading > search/replace > output.
