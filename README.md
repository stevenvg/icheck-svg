# iCheck-SVG

Add SVG functionality to fronteed/iCheck for easy custom colors through LESS.


### General

This is a prototype to add SVG functionality to iCheck.js through LESS, although it is possible this could be achieved through any other "Language".

What it does is fairly simple, it reads an external SVG file and replaces a defined color with another one through regex, which in turn spits the result out as an inline background data/uri. Because Firefox was giving output problems due to not being encoded, this is also done in the process.

more to come


### Requirements

coming soon


### Setting up

coming soon


### Limitations

As data-uri's are not safe/secure (and this makes heavy use of it), it is advised to compile your files locally.


### To-do

- [ ] Add dynamic theming and more "skins".
- [ ] Better calculations for dimensional properties.
- [ ] Add dynamic sizing (at his point it doesn't scale to a given size).
- [ ] Add custom variables for the disabled states, or make them black with an opac.
- [ ] Remove the background property when composing the data-uri.
- [ ] Add a version for SASS and php.
