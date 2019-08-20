# Introduction



CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow, the other elements around them, their parent container, or the main viewport/window. 

·        Normal flow

·        The [display](https://developer.mozilla.org/en-US/docs/Web/CSS/display) property

* Flexbox
* Grid
* Floats
* Positioning
* Table Layout
* Multiply-column Layout



·    

1. Technique it uses
2. Advantages
3. Limits and Frustrates
4. Connect to other methods

\# Starting with a well-structured HTML document is so important, as you can then work with the way things are laid out by default rather than fighting against it.

The methods that can change how elements are laid out in CSS are as follows:

·        **The** [**display**](https://developer.mozilla.org/en-US/docs/Web/CSS/display) **property** — Standard values such as block, inline or inline-block can change how elements behave in normal flow \(see [Types of CSS boxes](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model#Types_of_CSS_boxes) for more information\). We then have entire layout methods that are switched on via a value of display, for example [CSS Grid](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids) and [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox).

·        **Floats** — Applying a [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float) value such as left can cause block level elements to wrap alongside one side of an element, like the way images sometimes have text floating around them in magazine layouts.

·        **The** [**position**](https://developer.mozilla.org/en-US/docs/Web/CSS/position) **property** — Allows you to precisely control the placement of boxes inside other boxes. static positioning is the default in normal flow, but you can cause elements to be laid out differently using other values, for example always fixed to the top left of the browser viewport.

·        **Table layout** — features designed for styling the parts of an HTML table can be used on non-table elements using display: table and associated properties..

·        **Multi-column layout** — The [Multi-column layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Columns) properties can cause the content of a block to layout in columns, as you might see in a newspaper.

