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


 ## Before lanush any website
 > it is important to test it in more than one browser, because there
can be slight differences in how browsers display the pages.
>You do not need lots of computers to test your site, as there are online tools to show you what a page looks like in multiple browsers:

> *BrowserCam.com
BrowserLab.Adobe.com
BrowserShots.org
CrossBrowserTesting.com *

>If you come across a CSS bug, you can use your favorite search
engine to try and find a solution. Or you can check these sites:
*PositionIsEverything.net
QuirksMode.org*

>When a CSS property does not display as expected, it is generally referred to as a **browser quirk** or **CSS bug.**

# colors
1. **foreGround Colors**
2.**background Colors**
 ## colors Systems 
 1.**RGB values**
 2.**HEX Codee**
 3.**Color Names**



 

## Contrast
> When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.
>**A lack of contrast is particularly a problem for those with
visual impairments and color blindness**
>*It also affects those with poor monitors and sunlight on their
screens*
>For long spans of text, reducing the contrast a little bit improves
readability.
>You can reduce contrast by using **dark gray text on a white background** or an **off-white text on a dark background.**

## Css3 Opacity , rgba
** opacity value have to be between 1.0 and 0.0
> 0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).

> adds a fourth value to rgba to indicates opacity. This value is
known as an alpha value and is a number between 0.0 and 1.0

>The
rgba value will only affect the element on which it is applied
**(not child elements).**

## differenance between lightness and Brightness
>Please note that lightness is a different concept to brightness.
Graphic design software (such as Photoshop and GIMP) have
color pickers that use hue, saturation, and brightness —
but brightness only adds black, whereas lightness offers both
white and black.

## Css3 HSL , HSLA 
body {
background-color: #C8C8C8;
**background-color: hsl(0,0%,78%);**}
p {
background-color: #ffffff;
**background-color: hsla(0,100%,100%,0.5);**}
1.**Hue**:
> This is expressed as an angle
(between 0 and 360 degrees).

2.**saturation** :
>This is expressed as a percentage.

3.**lightness**:
>This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black. 
>*fourth value which represents transparency (just like the rgba property)*

4.**alpha**
>This is expressed as a number between 0 and 1.0.For example, 0.5 represents 50% transparency, and 0.75 represents 75% transparency.

>Because older browsers do not recognize HSL and HSLA values, it is a good idea to add an extra rule which specifies the color using a hex code, RGB value, or color name.


