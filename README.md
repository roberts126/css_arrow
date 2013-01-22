# General Description
SASS Mixin For CSS Arrows based on cssarrowplease.com.

## Usage
Copy the _css_arrow.scss file to your SASS project directory or to a subfolder.  Then add an import statement to the scss file(s) you want access to the CSS arrow block from:

## Defaults
You can change the defaults after the import statement.  The defaults are:

$dArrowDirection - default is up.
$dArrowBorderColor - default is #c2e1f5.
$dArrowBackground - default is #88b7d5.
$dArrowSize - default is 30px.
$dArrowBorderSize: - default is 4px.

## Example
@import "/path/to/css_arrow";

$dArrowDirection: right;
$dArrowBorderColor: #000;
$dArrowBackground: #fff;
$dArrowSize: 10px;
$dArrowBorderSize: 4px;

.element-class {
	@include arrow;
}

Since we changed the default direction to right this would create add a right facing, white arrow 10px in size, with a 4px black border.

.element-class.up {
	@include arrow(up);
}

Since we changed the default direction to right this would create add an upward facing, white arrow 10px in size, with a 4px black border.

## License
This mixin is Copyright © 2012 Chris Roberts. This mixin is free, and may be redistributed under the terms specified in the LICENSE file.