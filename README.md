# demoMaterialComponents
[android][demo] Demonstration of using and styling latest material components


## Button Styles

The included Styles show-case the different suggested material buttons following a defined accent color. Defining custom `selector` based colors allows correct looking disabled states.



### Primary Button Style

The primary style (filled & hovering button) comes with a hard-coded grey disabled color (Internally `color/mtrl_btn_bg_color_disabled` used in a selector). 
Note that especially in *Dark Mode* the default disabled colors are hardly readable.

Previous documentation / solutions on the internet stated that the disabled state was defined via `colorButtonNormal`. This is no longer true with the Material Components Button!

The button active and disabled color can instead be overwritten using `tint`. Ensure to provide a `selector color` for a visual different disabled look.


### Secondary Button Style

Using a button with just a colored outline is one of the new material component button styles. Customizing the button by setting the `strokeColor` is straight-forward.


### Action Links / Tertiary Button Style

Accent colored action text links can now also use a Material Button. This way it is very easy to switch between different button styles. As bonus the ripple effect highlight when pressing the text link works out of the box. 
When using with an icon the `iconTint` must be set too.
