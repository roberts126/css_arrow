# General Description
SASS Mixin For CSS Arrows based on cssarrowplease.com.

## Usage
Copy the _css_arrow.scss file to your SASS project directory or to a subfolder.  Then add an import statement to the scss file(s) you want access to the CSS arrow block from:

## Example
@import "/path/to/css_arrow";

.element-class {
	@include arrow(right, #fff, #000, 10px, 4px);
}

This would create add a right facing, white arrow 10px in size, with a 4px black border.

## License
This mixin is Copyright © 2012 Chris Roberts. This mixin is free, and may be redistributed under the terms specified in the LICENSE file.