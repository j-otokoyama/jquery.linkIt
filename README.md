# LinkIt jQuery Plugin #

**LinkIt** is a simple jQuery plugin to attach links to elements

## Version ##
0.1.0

## Usage ##
    $(document).ready(function() { 						// 1).
                $("span").linkIt( { 					// 2).
                    href: "http://www.yourUrlHere.com",	// 3).
                    text: "Some new text", 				// 4).
                    target: "_blank" 					// 5).
                });
            });
1. Add the above script to your index.html document header
1. Define your html, element or css class / id etc ("`_here_`")
1. Add your URL in quotes here
1. Add "Some new text" or null, unquoted to set exising element
1. Define href window target, i.e. _parent, _blank, _self, _top

## Vendors ##
jQuery - [http://jquery.com](http://jquery.com)

## License ##
MIT License
