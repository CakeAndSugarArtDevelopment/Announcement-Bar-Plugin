== Installation ==

1. Place `<?php if (function_exists('mbj_notify_bar_display')) { mbj_notify_bar_display(); } ?>` 
   immediately after the BODY tag in the template files for all areas that you want to display the Notify Bar on your site.  
   Depending on your set up, this may involve only pasting this code in one place in header.php, or you may have multiple places where the BODY tag is used.
   
1. You will then be able to compose your message, adjust the settings, and deploy the Notify Bar to your website by hitting the *Notify Bar* link in the *Settings* sub-menu of the WordPress admin panel main menu.


The following tags can be used in the message field on the Notify Bar settings admin page:

* br
* strong
* em
* b
* i
* span
* a (with attributes of href, title, and alt)
