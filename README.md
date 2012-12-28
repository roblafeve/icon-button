# Use

## Button Colors
Add or adjust color subclasses by defining background-color.

## Icons
Create a new subclass for .icon (e.g. &.phone:before/after) and add the character as the content (e.g. content: 'x'). Depending on whether the icon is inserted before or after the button text, add a trailing or leading space (e.g. 'x 'for :before or ' x' for :after). Entypo (http://www.entypo.com) is the icon font used here, but can easily be replaced with one of your choice, or scrapped altogether if you prefer to link directly to an image (NOTE: content: url('...') would be an interesting way to add this with the current :before/:after element implementation)