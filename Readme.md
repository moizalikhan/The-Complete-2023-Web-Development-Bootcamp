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
  *  
