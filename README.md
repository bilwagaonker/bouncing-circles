# Bouncing Circles with Mouse hover effect

Documenting the things learnt while making this mini-project

## HTML
- < canvas > tag<br/>

It is used to draw graphics via scripting (using JS). This tag is transperent and is only a container for graphics. Hence to draw anything on this canvas we need a script to draw. It supports global attributes in HTML as well as the event attributes :)

## CSS

Not much of new properties used to style the body element. Use the normal 'background-color', and 'margin'.

I was particularly intrigued by the 'overflow' used in the CSS. 
Apparently this property controls what happens to the content that is too big to fit into an area.

It hass following values:
- visible: Default setting and the overflow is not clipped. Hence if we draw a box and write content, it'll be typed post the box's boundaries too.

- hidden: the overflowed is clipped, the rest of content won't be visible as well as accessible.

- scroll: a scrollbar is added to the rest of the content to be visible.

- auto: Similar to scrollbar but it adds scrollbar when necessary.
