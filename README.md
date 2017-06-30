<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
      <section class="frost">
    <h3>To create an navigation menu, you need to do the following:</h3>
    <ol>
       <li>Add the “menu” class to your &lt;nav&gt; tag (or div)</li>
       <li>The “menu-header” class must then be added to the first child
            (or other block tag). This will be the hamburger menu for cellphone and
            tablets
        </li>
        <li>The “main-menu” class needs to be attached to the first (parent) tag</li>
    </ol>
       <h3> All tags must also include the “list-unstyled” class If you have a submenu, add this code to the parent of the submenu:</h3>
                   <ol>
                        <li>class=“subMenu" data-trigger = "submenu”</li>
                         <li>data-trigger = "submenu” and the class "table-unstyled" must be added to each child of the submenu.</li>
                         <li>
                             The custom caret for a dropdown menu is: <span class="fa"></span>. This is an optional icon and can be substituted with a standard caret. If the caret is wrapped in a tag, the formatting will still be applied, the “fa” class is for the icon only.
                         </li>
                    </ol>
                     <h4>Classes:</h4>
                    <ul>
                         <li>menu</li>
                         <li>menu-header</li>
                         <li>fa (icon)</li>
                         <li>submenu</li>
                     </ul>
                     
                     <h4>Data</h4>
                     <p>data-trigger = "submenu"</p>
                     
                     <h4>Options</h4>
                     <ul>
                        <li>settings.backgroundColor - Background color of the menu plugin</li>
                        <li>settings.highlightColor - Highlight color for hover state on computer screens</li>
                        <li>settings.submenuColor - Color of submenu on mobile and tablets in profile mode</li>
                        <li>
                            settings.toggleSpeed - Speed in milliseconds of how fast the menu slides. A “0” value will deactivate the slide animation and the submenu will just appear.
                        </li>
                        <li>
                            settings.menuNumber - The number of top menu links. This will ensure there is no wrapping on screens where the menu items are inline. <strong>THIS NUMBER MUST BE THE EXACT NUMBER OF ITEMS IN THE TOP MENU!</strong>
                        </li>
                    </ul>
    
    <h3>Code Example</h3> 
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
</section>
</body>
</html>
 