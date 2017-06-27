# responsive-menu-jquery-plugin
jQuery Plugin for a fully responsive menu This menu has rollover functionality on computers and dropdowns for
mobile devices.

Use
To create an navigation menu, you need to do the following:
•	Add the “menu” class to your <nav> tag (or div)
•	The “menu-header” class must then be added to the first child <div>
(or other block tag). This will be the hamburger menu for cellphone and
tablets
•	The “main-menu” class needs to be attached to the first (parent)
<ul> tag
•	All <ul> tags must also include the “list-unstyled” class
•	If you have a submenu, add this code to the <li> parent of the
submenu:  class=“subMenu" data-trigger = "submenu”
•	data-trigger = "submenu” and the class "table-unstyled" must be
added to each child <li> of the submenu.
•	The custom caret for a dropdown menu is: <span
class="fa">&#xf150;</span>. This is an optional icon and can be
substituted with a standard caret. If the caret is wrapped in a <span>
tag, the formatting will still be applied, the “fa” class is for the
icon only.
Classes:
•	menu
•	menu-header
•	fa (icon)
•	submenu
•	list-unstyled
•	table-unstyled"

Data-
data-trigger = "submenu"

Options
•	settings.backgroundColor - Background color of the menu plugin
•	settings.highlightColor - Highlight color for hover state on
computer screens
•	settings.submenuColor - Color of submenu <li> on mobile and tablets
in profile mode
•	settings.toggleSpeed - Speed in milliseconds of how fast the menu
slides. A “0” value will deactivate the slide animation and the submenu
will just appear
•	settings.menuNumber - The number of top menu links. This will ensure
there is no wrapping on screens where the menu items are inline. THIS
NUMBER MUST BE THE EXACT NUMBER OF ITEMS IN THE TOP MENU.

<nav class="menu">
<div class="menu-header"><span
class="fa">&#xf0c9;</span>Menu</div>
<ul class="main-menu list-unstyled">
<li><a href="#style">Styles</a></li>
<li><a href="#grid">Grid</a></li>
<li class="subMenu" data-trigger = "submenu"><a
href="#">CSS Components<span class="fa">&#xf150;</span></a>
<ul class="list-unstyled">
<li class="table-unstyled" data-trigger =
"submenu"><a  href="#filters">Image Filters</a></li>
<li class="table-unstyled" data-trigger =
"submenu"><a href="#video">Responsive Video</a></li>
<li class="table-unstyled" data-trigger =
"submenu"><a href="#footer">Sticky Footer</a></li>
<li class="table-unstyled" data-trigger =
"submenu"><a href="#hero">Hero Image</a></li>
</ul>
</li>

<li class="subMenu" data-trigger = "submenu"><a
href="">jQuery Plugins<span class="fa">&#xf150;</span></a>
<ul class="list-unstyled">
<li class="table-unstyled" data-trigger =
"submenu"><a href="#">Menu</a></li>
<li class="table-unstyled" data-trigger =
"submenu"><a href="#">Tooltips</a></li>
<li class="table-unstyled" data-trigger =
"submenu"><a href="#sticky">Sticky Element</a></li>
<li class="table-unstyled" data-trigger =
"submenu"><a href="#height">Height Adjust</a></li>
</ul>
</li>
</ul>
</nav>
