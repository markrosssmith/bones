# Bones

Bones is a super light-weight SASS Grid System that makes use of **data attributes** to keep your element classes squeaky clean.
Bones offers a number of variables to provide tailoring out of the box, and should be extended as required in your project.

## Markup

Bones proscribes as little as possible, defining only **wrappers**, **rows** and **columns**. You specify the number of columns in a row, the maximum width of a row and the padding of a wrapper. 

### Basic Grid

Markup : 
	
	<div data-wrapper>
		<div data-row>
			<div data-column="12-6-3">
				// Content
			</div><!-- data-column -->
		</div><!-- data-row -->
	</div><!-- data-wrapper -->

## Options

Available markup options

Markup 		  | Description
------------- | -------------
data-wrapper  | No parameters. Defines a wrapper to hold rows
data-row  | No parameters. Defines a row to hold columns
data-column	|	Defines responsive behaviour of a row, mobile first (See responsive table below)
data-hide | Defines show/hide behaviour of an element, mobile first (See responsive table below)


Responsive configuration for data-column / data-hide. *Example considers a grid of 12 columns*

Example	|	Description
--------|	------------
12 		|	100% width column from mobile up
12-6 	|	100% width column for mobile. 50% width column for tablet up
12-6-4  | 	100% width column for mobile. 50% width column for tablet up. 33.33% width column for desktop
hide 	| 	Hide from mobile up
show-hide | Show mobile, hide tablet up
show-show-hide | Show mobile, show tablet and hide from desktop



## Installation

Simply include in your stylebase and compile.


## Contributors

Created by <a href="http://hellomark.co.uk" target="_blank">Mark Smith</a>.


## License

Apache License, Version 2.0
