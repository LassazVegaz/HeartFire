# Heart Fire ❤

## Fire in heart 🙂

\
~~No JS~~. &nbsp;&nbsp;&nbsp; **CSS & HTML only**

I see two special features in this web page

1. Reflection
2. Fire

   <br />
   <br />

### 1. REFLECTION

Reflection is made using CSS property `-webkit-box-reflect` Its format is like this

```
-webkit-box-reflect : [ above | below | right | left ]? <length>? <image>?;
```

First of all, this property is not standard 😐
MSDN link is [here](https://developer.mozilla.org/en-US/docs/Web/CSS/-webkit-box-reflect). This link gives all the possible values and their effects.  
Anyone who does not know what this Webkit is? Well I was one of them when I was using this feature.

> WebKit is a layout engine designed to allow web browsers to render web pages.

Well this engine allows browsers to display some fantastic UI features like our case REFLECTION. If a browser supports Webkit 😕 we can tell the browser to use Webkit features using `-webkit-property-name` in CSS. Check more details in this SO [link](https://stackoverflow.com/questions/3468154/what-is-webkit-and-how-is-it-related-to-css)

In my example I have used

```
-webkit-box-reflect: below -50px linear-gradient(transparent, #00000024);
```

Reflection is shown below the text element. It is uplifted by 50px otherwise there is a gap between reflection and the element. Image value is a gradient color. This gradient color blends black color to the bottom of the reflection making fade out scene.
<br />
<br />

### 2. Fire

Fire effect is made with a SVG filter added to the text 'I ❤ You'. Learn more about SVG Filters [here](https://www.w3schools.com/graphics/svg_filters_intro.asp). SVG code is living inside `body` tag. `style.css` prevents this SVG element from taking space in the page layout.

From several SVG filters, `feTurbulence` can make the effect of water and fire. There are some specific attributes related to this filter, if you went through physics class well, it won't be hard to understand. If you did not, try this [link](https://yoksel.github.io/svg-filters/#/) to play with feTurbulence and other filters to learn them and have an excitement. WOW SVG!

There is also a nice extension for SVG in VS Code. Extension ID is [jock.svg](https://marketplace.visualstudio.com/items?itemName=jock.svg)
