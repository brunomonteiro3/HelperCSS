HelperCSS
=========

Common classes to help you optimize your HTML

This CSS is designed to help you create your HTML faster, with no need to rewrite default rules on your file. 

Notice: the suggested names for the classes on this files are the shortest as possible, in some cases it can make your code unreadable in team works, so feel free to change the name of the class to suit the way you work.

Usage
-----

Using `helper.css`, your other CSS files will have the lines reduced because you'll avoid using default settings in different classes. For example:

Your **dirty** HTML without `helper.css`:

`
	<h1>Example title</h1>
`

And... your **dirty** CSS without `helper.css`:

`
h1{
	float: left;
	font-size: 20px;
	margin-bottom: 5px;
	font-weight: lighter;
	position: absolute;
	text-align: center;}
`

Now, your **awesome** HTML with `helper.css`:

`
	<h1 class="l f20 mb5 fl pos-abs center">Example title</h1>
`

And... you don't need to write a single line of CSS. Awesome, huh? :)