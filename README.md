<h1>CSS Course Notes:</h1>

<h2>Lesson 1</h2>
<p>In CSS the color: is the property and the aquamarine is the value. Both (the property and the value) together are classed as a Declaration, and the whole thing from p is defined as a ruleset/rule!</p>

<h2>Lesson 2</h2>
<p>CSS works an specifity index, the rules that apply to a peice of code is dependant on the level of specifity of that code, i.e  id -> class -> rule</p>
<p>Classes are create by adding.{classname}.
id's are created by adding#{idname}.</p>

<h2>Ch3: Colours in CSS</h2>

<p>RGB: allows to set specific colours aside from the ones that already given. 255 is max value for each place holder, i.e, rgb(255,0,0) is red.</p>
<p>RGB<u>A</u> scale: a (alpha channel) in this sets the trasnparency in the 4th placeholder. It goes from 0-1, 0 being fully transparent and 1 being fully opaque and 0.5 being 50% opacity.</p> 
<p> Hexadecimal color: using a scale of 0-9 and A-F, 0 being absence of colour and f being brightest value of that colour.</p>
<p>[coolors.coo](https://coolors.co) ==> a good website to get color palettes and check contrast between diferent colors</p>

<h2>Ch4: CSS Units</h2>

<p> Px : are absolute values and should be used carefully. Fonts are usually handled by the browser and should therfore not be set for the root (the main {usually HTML tags} element), its more to do with borders and margins and other aesthetic features.</p>

 <p>Percentage are relative some other value, width for example has a value of 100% if a child element is to use a width 50%, :-> means it's using half of the parent elemts width relatively.</p>
 
<p>Rem : its also a relative unit, it applies a multiple of the root element (usually the HTML tag) to whatever it's defining (usually font size). So if the root element has a standard font size of 16px, applying a 2rem to h1 will make it 32px.</p>

<p>Viewport height and width: used to scale items according the size of the window current window. 100% scales content automatically to the full width the open window.</p>

<h2>Ch5: CSS Box Model</h2>

<p>Border box includes content, padding and border when setting widths etc.</p>

<p>In the CSS box model, it content -> padding -> border -> margin.</p>
 
<p>margin, border, padding all of this can be set as value for all the sides or you can set specific value for each side in the code.</p>

<p>margin auto, wil center an element within its container horizontally.</p>

<h2>Ch6: CSS Typography</h2>

<p>Typography is the way that text is arranged and represented.</p>

<p>Form elements, such as the input and button, Don Not inherit the properties assigned to the body element. In order to make them inherit you have to state specificaly by adding this (input, button {font: inherit}) to the code.</p>
 
<p>New fonts can be imported from (https://fonts.google.com/) and by using the @import code given paste it at the top of the CSS file. and add the font family aswell.</p>

<h2>Ch7: CSS Styling Links</h2>

<p> the visited, hover and active are pseudo classes of the anchor element. Thus, they have more specifity and can ovrride the styling of the normal anchor tag.</p>

<p>If assigning different styling to the visited -> hover -> active, it's best to writed the code in this order, otherwise the styling may not function correctly.</p>
 
<p>a:focus allows user to tab throught th page with keyboard and see which link is being focused at. Increasing accesibility.</p>

<p>Using the HSL colours you can change the setting minutely to stick within the colour schem of anchor tags. Alternatively you can sue opacity to differetiate.</p>

<h2>Ch8: CSS List Styles</h2>

<p>List style type - changes the thing used to order lists. You can add attributes to HTML code (start = '3' reversed") this would start the bullet point from 3 and also reverse the order of the counting.</p>

<p>List tyle: attributes can be clustered, such as image, shape and position</p>
 
<p>Pseudoclass (n'th child()) is used to change the properties of a specific item on a list. so an nth-child(2) color:red would make the second item on the list red. This pseudo class only applies when styling li tag. Also in the you can add odd or even to the nth class so the property only effects the odd or even number items on the list.</p>

<h2>Ch9: CSS Styles</h2>

<p>Paragraphs and others are block level elements. They have by default 100% width available (i.e the width of their parents element). </p>
<p>In-line elements donlt stack. Margins, height and some other properties cannot be applied to iniline elements.</p>
<p>Display property: inline-block encompasses the in-line element within its parent block element, making it respect the boundaries of the parent element while letting you apply properties. </p>

<h2>Ch10: CSS Dsiplays</h2>

<p>Paragraphs and others are block level elements. They have by default 100% width available (i.e the width of their parents element). </p>
<p>In-line elements donlt stack. Margins, height and some other properties cannot be applied to iniline elements.</p>
<p>Display property: inline-block encompasses the in-line element within its parent block element, making it respect the boundaries of the parent element while letting you apply properties. </p>

<h2>Ch11: CSS Floats</h2>

<p>Floats allows text to wrap around an element.</p>
<p>Overflow:auto allows for the container like section to encompass the full-size of floats. However current way to do its is display: flow-roots </p>
<p>clear class with clear both is required if you dont want a float to affect another paragraph and stay within a container.</p>

<h2>Ch12: CSS Columns</h2>

<p>The column-rule funtions allows the add a line between columns to seperate them</p>
<p>Usually in the column setting, the first paragraph has top margin, to get rid of that you have to manually set margin-top to 0. Be specific to set this attrbute to only column paragraphs else, it will affect all other paragraphs as well. </p>
<p>The break-inside:avoid function allows for the text to not be split in the middle when using columns.</p>
<p>The column-span:all function allows for a paragraph to span multiple columns.</p>
<p>When the attribute white-space:nowrap is applied to class in the span element, it ensures that the content in the span element does not get split or broken when the window size is changed. </p>
