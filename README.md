## Visual Composer Templates Library

This plugin provides a framework for creating themes and plugins that utilize the built-in template function in Visual Composer (as of version 4.4)

<p align="center">
Video Demo:
</p>
<p align="center">
  <a href="https://www.youtube.com/watch?v=oIfizD9Qz3E" target="_blank"><img src="https://img.youtube.com/vi/oIfizD9Qz3E/0.jpg" alt="Visual Composer Templates Library"></a>
</p>

It works by loading templates from files in your theme (and optionally plugin) folders, making it possible to version control templates in a simple way.

### Building templates

Building a template is easy. Start out by creating a layout in Visual Composer. (For example, by creating a new page with the layout you want.)

When you are done, click the "Classic mode" button to return to the TinyMCE WYSISYG, and then click on the Text tab. Now you can copy the content of your layout into a template!

<p align="center">
Workflow:
</p>
<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=0B9LakaSozcQXcS1WS00xN25CeGs" alt="Visual workflow of text above">
</p>

### Using in a theme

To bundle templates with your theme, create the folder:

```
/your-theme/vc_templates
```

Then, create a file, for example:

```
/your-theme/vc_templates/my-template.php
```

The only requirement is that the file has a .php extension.

Paste the template you got from the "Building templates" section above, and you will see a new template called "My Template" after you click on Templates > Default Templates in Visual Composer. You're done!

<p align="center">
Workflow:
</p> 
<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=0B9LakaSozcQXd09BaTVKdXRlZmc" alt="Visual explanation of text above">
</p>
