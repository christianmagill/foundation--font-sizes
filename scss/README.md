# Foundation Font Sizes
This project creates responsive font sizes, similar to Foundation's responsive headings.

----------

Usage
-----
Before importing package, create a **$font-sizes** map using the following format.

    $font-sizes: (
	    small: ( // breakpoint
		    size1: 10, // unitless pixel font size
		    size2: 14
	    ),
	    medium: (
		    size1: 12,
		    size2: 16
	    )
	}

To use within your project 

    .selector{
    	@include font-size(size1);
    }
