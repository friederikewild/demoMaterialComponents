# demoMaterialComponents
[android][demo] Demonstration of using and styling latest material components


## Button Styles

The included styles show case the different suggested material buttons following a base accent color. Defining custom selector based colors allows correct looking disabled states.


### Primary Button Style

The primary style (filled & hovering button) comes with a hard-coded grey disabled color (Internally `color/mtrl_btn_bg_color_disabled` used in a selector). 
In light themes the button active and disabled color can be set using `tint`.


### Secondary Button Style

Using a button with just a colored outline is one of the new material component button styles. Customizing the button by setting the `strokeColor` is straight-forward.


### Action Links / Tertiary Button Style

Accent colored action text links can now also use a Material Button. This way it is very easy to switch between different button styles. As bonus the ripple effect highlight when pressing the text link works out of the box. 
When using with an icon the `iconTint` must be set too.
