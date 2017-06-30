To create an navigation menu, you need to do the following:

Add the “menu” class to your <nav> tag (or div)
The “menu-header” class must then be added to the first child (or other block tag). This will be the hamburger menu for cellphone and tablets
The “main-menu” class needs to be attached to the first (parent) tag
All tags must also include the “list-unstyled” class If you have a submenu, add this code to the parent of the submenu:

class=“subMenu" data-trigger = "submenu”
data-trigger = "submenu” and the class "table-unstyled" must be added to each child of the submenu.
The custom caret for a dropdown menu is: . This is an optional icon and can be substituted with a standard caret. If the caret is wrapped in a tag, the formatting will still be applied, the “fa” class is for the icon only.
Classes:

menu
menu-header
fa (icon)
submenu
Data

data-trigger = "submenu"

Options

settings.backgroundColor - Background color of the menu plugin
settings.highlightColor - Highlight color for hover state on computer screens
settings.submenuColor - Color of submenu on mobile and tablets in profile mode
settings.toggleSpeed - Speed in milliseconds of how fast the menu slides. A “0” value will deactivate the slide animation and the submenu will just appear.
settings.menuNumber - The number of top menu links. This will ensure there is no wrapping on screens where the menu items are inline. THIS NUMBER MUST BE THE EXACT NUMBER OF ITEMS IN THE TOP MENU!
Code Example

    <pre class="codesnippet">  

      &lt;nav class="menu"&gt;

          &lt;div class="menu-header"&gt;

              &lt;span class="fa"&gt;&lt;/span&gt;Menu

         &lt;/div&gt;

          &lt;ul class="main-menu"&gt;

                  &lt;li&gt; &lt;a href="#"&gt;Item 1 &lt;/a&gt; &lt;/li&gt;

                  &lt;li&gt; &lt;a href="#"&gt;Item 2 &lt;/a&gt; &lt;/li&gt;

                  &lt;li class="subMenu" data-trigger="submenu"&gt;

                      &lt;a href="#"&gt;Item 3 &lt;span class="fa"&gt; &lt;/span&gt; &lt;/a&gt;

                          &lt;ul&gt;

                              &lt;li data-trigger="submenu"&gt; &lt;a href="#"&gt;SubItem 1 &lt;/a&gt; &lt;/li&gt;

                              &lt;li data-trigger="submenu"&gt; &lt;a href="#"&gt;SubItem 2 &lt;/a&gt; &lt;/li&gt;

                          &lt;/ul&gt;

                  &lt;/li&gt;

                  &lt;li&gt; &lt;a href="#"&gt;Item 4 &lt;/a&gt; &lt;/li&gt;

                  &lt;li class="subMenu" data-trigger="submenu"&gt; 

                      &lt;a href=""&gt;Item 5&lt;span class="fa"&gt; &lt;/span&gt; &lt;/a&gt;

                          &lt;ul&gt;

                              &lt;li data-trigger="submenu"&gt; &lt;a href="#"&gt;SubItem 1 &lt;/a&gt; &lt;/li&gt;

                              &lt;li data-trigger="submenu"&gt; &lt;a href="#"&gt;SubItem 2 &lt;/a&gt; &lt;/li&gt;

                          &lt;/ul&gt;

                  &lt;/li&gt;

          &lt;/ul&gt;

      &lt;/nav&gt;

    </pre>
