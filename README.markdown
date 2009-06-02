Tinymce Filter
--------------

This extension provides a TinyMCE filter for the Radiant CMS. 
It allows you to edit the content of your pages in the TinyMCE editor.

Fork of MrGossett/radiant-tinymce_filter

Installation
------------

1. `cd vendor/extensions`
2. `git clone git://github.com/kmayer/radiant-tinymce_filter.git tinymce_filter`
3. `rake radiant:extensions:tinymce_filter:install`
4. restart your server

== Settings ==

If you want to change the settings of the editor, you can do this by editing the `app/views/admin/page/_edit_tiny_mce.html.erb` file. Here's a link to all of the many, many TinyMCE 
[configuration options](http://wiki.moxiecode.com/index.php/TinyMCE:Configuration)

The 'codeprotect' plugin is used to protect the Radiant tags from being edited within the editor.

- Ken Mayer

http://github.com/kmayer/radiant-tinymce_filter/