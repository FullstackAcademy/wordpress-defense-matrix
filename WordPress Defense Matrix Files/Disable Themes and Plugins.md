# How to Disable Theme and Plugin Editors from WordPress Admin Panel
**Why Disable Theme and Plugin Editors in WordPress?**
>WordPress comes with a built-in code editor which allows you to edit WordPress theme
and plugin files directly from the admin area.
The theme editor is located at Appearance » Theme Editor page. By default, it will
show your currently active theme’s files.
The biggest problem with the built-in file editor is that it gives full access to add any kind
of code to your website.
If a hacker broke into your WordPress admin area, then they can use the built-in editor
to gain access to all your WordPress data.

>Hackers can also use it to distribute malware or launch DDOS attacks from your
WordPress website.
>To improve WordPress security, we recommend removing the built-in file editors
completely.
That being said, let’s see how to easily disable theme and plugin editors in WordPress.

**How to Disable Theme and Plugin Editors in WordPress**
>Disabling theme and plugin editors in WordPress is quite easy.

>Simply edit your wp-config.php file and paste the following code just before the line that
says ‘That’s all, stop editing! Happy publishing’ :

>**1 define( 'DISALLOW_FILE_EDIT', true );**

>You can now save your changes and upload the file back to your website.
That’s all, plugin and theme editors will now disappear from themes and plugins menus in the WordPress admin area.

>You can also add this line of code to your themes function.php file, a site specific plugin, or by using the code snippets plugin.
