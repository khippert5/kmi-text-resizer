The following is a description of options and usage for KMi Text Resizer:


Dependencies for default:
The folder "font-awesome-4-6-3" should be included in the package. This should include everything you need.


Put in the head of your page as followed:
<link rel="stylesheet" type="text/css" href="<your-directory>/font-awesome-4-6-3/css/font-awesome.min.css">


To change default settings:
create an empty div on your page with the class attribute "kmitextresizeOptions". Best suited near the bottom. KMi Text Resizer will pick up the data attributes set on this div and overwritte the default settings.


Alternate change:
You can also go into the kmi-textresizer.js and change the defaults in here.  Just make sure to connect kmi-textresizer.js to your page instead of kmi-textresizer.min.js


Assumptions:
KMi Text Resizer assumes that CSS standards using "rem" or "em". 
	If attaching to a site that is unknown; use the kmitextsizes div to reset the elements and gain control over the page.


***NOTE: 
If you are also using KMi Page Arrows the default settings are set to match the page arrows



Default Settings:

	"data-font-start-size" -> Set the starting point for the text size
	
	"data-position":"fixed" -> Set the position of the textresize container
	
	"data-padding":"12px 15px" -> Set the padding of the textresize container
	
	"data-zindex":"50" -> Set the z index of the container. Set to 9999 to always be on top;
	
	"data-border-radius":"3px" -> Set the border radius on the textresize container
	
	"data-background-color":"transparent" -> Set the backgound color of the textresize container (Should not be changed but available)
	
	"data-position-vertical":"bottom" -> Set the vertical position of the textresize container
	
	"data-position-vertical-offset":"2px" -> Set the vertical offset of the textresize container (IE: bottom:2px)
	
	"data-position-horizontal":"left" -> Set the horizontal position of the textresize container 
	
	"data-position-horizontal-offset":"2px" -> Set the horizontal offset of the textresize container (IE: left:2px)
	
	"data-text-adjust":"on" -> This will allow the font attributes to over write. It will attach custom css to the head to target just font styles.
	
	"data-text":"Text resize" -> Initial display text
	
	"data-text-mobile":"Aa" -> Mobile display text (shows at 480px)
	
	"data-text-color":"FFF" -> Intial font color of display text
	
	"data-text-margin":"0" -> Set the margin around the display text
	
	"data-text-padding":"0" -> Set the padding aruond the display text
	
	"data-text-color-hover":"333" -> Changes the color of the font on hover
	
	"data-text-color-hover-background":"FFF" -> Changes the background color on hover
	
	"data-text-font-weight":"bold" -> Set the font weight of the display text
	
	"data-ul-margin":"0 0 15px" -> Set the margin around the entire list container
	
	"data-ul-border-radius":"3px" -> Set the border radius around the entire list container
	
	"data-li-padding":"5px" -> Set padding between each li element in the font increase list
	
	"data-li-border-radius":"3px" -> Set border radius around each li element in the font increase list
	
	"data-tog-border":"1px solid #FFF" -> Border around the toggle button
	
	"data-tog-padding":"15px 7px" -> Padding around the toggle button
	
	"data-tog-margin":"0 0 0 5px" -> Margins for the toggle button
	
	"data-tog-font-size":".75em" -> This is the font size of the toggle button
	
	"data-tog-range":"100,150"-> This is the range to show available increase.
	
	"data-tog-interval":"10" -> this is the visible percentage increase between each resize selection (100%, 110%...)
	
	"data-tog-font-interval":"2" -> this is the interval between each selected font to increase by. (2px, 4px...)
	
	"data-tog-icon":"fa" -> fa targets the font awesome. Change this to img to use image in the next two attributes
	
	"data-tog-icon-fa-attribute-show":"chevron-up" -> This is the icon to use for the toggle up element
	
	"data-tog-icon-fa-attribute-hide":"chevron-down" -> This is the icon to use for the toggle down element
	
	"data-tint-background-color":"#000" -> This is the color setting to set the color behind the entire elemnet
	
	"data-tint-background-opacity":".85" -> This is the opacity level of the color behind entire element
	
	"data-action-slide":"right" -> This is the direction of the slide. Right will start offscreen left and slide in right; vice versa
	
	"data-action-fade":"0" -> This is the delay timer on the fade in
	
	"data-text-takeover":"0" -> Default is assuming site is using "rem" or "em" font attributes.
		To take over css settings, change to 1 and use the below settings to change.

	"mobile-font-difference" -> Set the mobile difference if device is mobile this will take the default font size, subtract this difference before changing.



Default font sizes: 

To change the default values set a div with the class "kmitextsizes" and use the following attributes to change.  

"data-font-family":"Helvetica Neue, Helvetica, arial, sans-serif" -> Set the font family

"data-font-style":"normal" -> Set font style

"data-font-weight":"normal" -> Set font weight

"data-line-height":"1.4em" -> Set line height

"data-margins":"0 0 0 8px" -> set margin

"data-header-line-height":"1.25em" -> Set line height to all header tags

"data-header-padding":"0" -> Set padding to all header tags

"data-header-margins":"0 0 12px" -> Set margins to all header tags

"data-header-h1":"3em" -> Set font size to h1

"data-header-h2":"2.25em" -> Set font size to h2

"data-header-h3":"2em" -> Set font size to h3

"data-header-h4":"1.75em" -> Set font size to h4

"data-header-h5":"1.5em" -> Set cont size to h5

"data-header-h6":"1.25em" -> Set font size to h6

"data-text":"1em" -> Set font size to remaining p, li, td
