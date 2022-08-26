<h1>I am learning about CSS in this course:</h1>

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
<br>
px are absolute values and should be used carefully. Fonts are usually handled by the browser and should therfore not be set for the root (the main {usually HTML tags} element), its more to do with borders and margins and other aesthetic features
<br>
 percentage are relative some other value, width for example has a value of 100% if a child element is to use a width 50%, :-> means it's using half of the parent elemts width relatively.
 <br>
rem : its also a relative unit, it applies a multiple of the root element (usually the HTML tag) to whatever it's defining (usually font size). So if the root element has a standard font size of 16px, applying a 2rem to h1 will make it 32px
<br>
viewport height and width: used to scale items according the size of the window current window. 100% scales content automatically to the full width the open window
