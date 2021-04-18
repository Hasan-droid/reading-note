# introduction to css
> CSS allows you to create rules that specify how the content of
an element should appear.

>* *The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.*

>* CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed.

## creating a css rule 
** p {
   font-family:arial;
}**
1. *p* : selector 
>Selectors indicate which element the rule applies to.
> **The same rule can apply to more than one element if you separate the element names with commas.** 

** p , a {
  font-family:arial;
}**

## css properties 
** h1 , h2 , h3 {
  font-family : arial;
}**
font-family:*propertiy*
>indicate the aspects of the element you want to change. 
arial:*value*
>specify the settings you want to use for the chosen properties

## using css
 ### using extrenal css
  #### <link href="css/styles.css" type="text/css"  rel="stylesheet" />
  1. **<link/>**:
  >The <link> element can be used in an HTML document to tell the
browser where to find the CSS file used to style the page

 2.**href**
 >This specifies the path to the CSS file (which is often placed in
a folder called css or styles).

 3.**type**
 >This attribute specifies the type of document being linked to. The
value should be **text/css.**

 4.**rel**
 >This specifies the relationship between the HTML page and
the file it is linked to.
### using internal css
** *<style type="text/css">*
 body {
 font-family: arial;
 background-color: rgb(185,179,175);}
 h1 {
 color: rgb(255,255,255);}
 *</style>***
 > a <style> element, which usually sits inside the <head> element of the page.
The <style> element should use the type attribute to indicate that the styles are specified in CSS. The value should be** text/ css.**

**When building a site with more than one page, you should use
an external CSS style sheet*
### css selector 
> CSS selectors are case sensitive, so they must match element names and attribute values exactly.
![css selector](https://cf.ppt-online.org/files/slide/k/Kbp3XcismqFREgGuz9OBIWY1vDx6MwHVeZQjC5/slide-8.jpg)

## Css Rules Cascade
1. last Rule 
2. specifiy 
3. important 
> Understanding how CSS rules cascade means you can write simpler style sheets because you can create generic rules that apply to most elements and then override the properties on individual elements that need to appear differently

## Inheritance
> or color properties on the <body> element, they will apply to most child elements. This is because the value of the font-family property is inherited by child elements. It saves you from having to apply
these properties to as many elements (and results in simpler style sheets).

>You can compare this with **the background-color or border properties;** they are **not inherited** by child elements

# colors
1. **foreGround Colors**
2.**background Colors**
 ## colors Systems 
 1.**RGB values**
 2.**HEX Codee**
 3.**Color Names**
 4.**Hue **
 5.** Saturation**
 6.** Brightness**
