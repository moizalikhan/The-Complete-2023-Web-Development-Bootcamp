### Css Notes:
* Style sheet is type of language and there are many-->CSS & Sass

* Three Ways to Add Css:
  * Inline Css --> for Single Element
    * Style attribute is available to all --> Global 
    * style= "background: Blue"
  * Internal --> for Single Page
    * <style>CssSelector{Css;}</style> -->
  * External --> for Multipage Websites
    * Separate file
    * <head><link rel="stylesheet" href = "location"/></head>

* Css Selectors:
  * Element Selector:
    * It Selects html on which css rules apply
    * Element Selector --> h1{}
  * Class Selector:
    * .red-heading{} --> Class name
    * Class is an attribute that we can add to html by which we can group certain elements and it's also case sensitive
  * Id Selector:
    * #main{} 
    * id is an attribute which can apply to only one element in an html file
    * select the element with the id is helpful to apply a a style to a particular element and in that there are many same elements are present we can differentiate them by this
  * Attribute Selector:
    * p[draggable attribute:]{} --> this means that select all the paragraphs that has the attribute dragabble
    * p[draggable attribute:"False"] --> this means that it selects the paragraphs that has the attribute draggable and also which has false value to apply css
  * Universal Selector:
    * *{} --> this means it selects all the elements in the html

* Css Properties:
  * Color property--> property:value--> background-color, color(text), color hexcode(total are 255)
    * We can also use https://colorhunt.co/ 
  * Font Property--> font-weight, font-size, font-family
    * Font-size:
      * 1 px = 1/ 96 inch
      * 1 pt = 1/72 inch
      * the above ones are static
      * 1 em (m) = 100 perc of parent size (Relative Size)
      * 1 Rem (relative m) = 100 perc pf root size (does not change)
      * the above ones are Relative
      * We should more use Rem
      * font-size : xx-large --> this can be
    * Font-weight:
      * bold, normal, normal bold, lighter and bolder(relative to parent), number(100-900)
    * Font-family:
      * font-family: h1{helvetica,"times new roman", sans-serif-->backup generic type}
      * https://fonts.google.com/
    * Text Align:
      * text-align: center,left, right, start(text start), end(text end)


