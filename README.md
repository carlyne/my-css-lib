# my css lib

Helper for quick layouting projects.
It uses Componant, Modificator and Variables for multy-lvl handling.

Every element is setting with `flex`, `wrap` and `direction-column`. It useful for footer and for adding responsive easily. You juste have to set `display--row` and use other display flex modificators if need to change axis.

For better lisibility on file, every class is prefixed by its category name, like :

```html
<section class="position--relative shape--rounded">
	<header class="padding--m-children">
		<h2 class="text--upper">Section title</h2>
		<p>hello beers</p>
	</header>
</section>
```

## Variables
Add you own values in `_colors` and ` _typeface` with your own visual identity. You can also set size of h-titles and update spacing as you need for comfort layouting.

## Modificators
Use modificators for adding specific style on a element like color, font transform, display, position etc... 
use `children` suffix on any modificator to apply style on every first lvl children of an element.

## Componants
It define structure for different element as lists, gallery, global structure, shape etc... you can add your own in `custom-componant` file, ìf you need specific design.


# State of project

This "lib" is FULLY WORK IN PROGRESS !! For testing it, download those files in you asset or src folder.
Its needs a scss compiler to works, what you can easily do with another `npm install` and node-sass by example.

## Available

- basics in variables, modificators, componants for understanding project

## Feature to implements

- responsive (yes I know, should be priority in Availabe section, oupsy)
- webkit and cross browsers stuff
- fully brain reflexion on design rules for variables spacings, typefaces etc... The final idea is to let you modify the minimum of configuration and mathematics of design do the rest for you !
- accessibility helpers
- html templates for help using lib
- lib available with cdn or npm install
- tools for minifying and deleting not used rules
