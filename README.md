# CSS3 patterned buttons #

[red-team-design.com/css3-patterned-buttons](http://www.red-team-design.com/css3-patterned-buttons)

## Buttons ##

Basically, to create a button, the only thing you have to do is this:

	<a href="" class="button">Button</a>
	<button class="button">Button</button>
	
## Different buttons sizes ##

If you want to make a more prominent or a less prominent call-to-action button, you have options:

	<button class="small button">Button</button>
	<button class="large button">Button</button>
	
## Various buttons colors ##

You will need custom colors for successful actions or negative ones as delete:

	<button class="button">Button</button>
	<button class="color red button">Button</button>
	<button class="color green button">Button</button>
	<button class="color blue button">Button</button>
	
## Disabled states ##

In case you are using buttons or inputs, in some cases you will need them to be disabled until a certain task is triggered:

	<button class="button" disabled>Button</button>
	<button class="color red button" disabled>Button</button>
	<button class="color green button" disabled>Button</button>
	<button class="color blue button" disabled>Button</button>
	
## Grouped buttons ##

There will be cases when you will need to group similar call-to-action buttons:

	<ul class="button-group">
		<li><button class="button">Button</button></li>
		<li><button class="button">Button</button></li>
		<li><button class="button">Button</button></li>
		<li><button class="button">Button</button></li>
	</ul>
	
## Browser compatibility ##

CSS3 patterned buttons works in all major browsers. But of course CSS3 features used here do not work in oder browsers like IE8 and below.

## License ##

Public domain: [http://unlicense.org](http://unlicense.org)