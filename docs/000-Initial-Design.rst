Initial Design
--------------

**Roles**

- End User
- Site Administrator
- Network Administrator (Multi Site Mode)

**End User Cases**

The use cases for end user.

Editing and updating

- file upload form be able to upload multiple files at one time.
- be able to setup categories
- be able search existing categories
- be able to create new folder/category

Browsing and Viewing

- file browser based on categories, in tag cloud format.
- file manager view, the tree view, 
  this will rely on proper category structure.

**Network Admin Cases**

The network admin will also be the super admin.

- set up the URL for Plupload_ AJAX request handler.

**Site Admin Cases**

The use cases for site administrator.

- set up default categories for each files.
- category management, it could be the folder management.
- be able to batch rename category.

**MediaWiki File Structure**

MediaWiki files will organized by categories,
which is different from tree structure.
If end users want a tree structure, 
they have to maintain the categories properly for each file.

Plan for Phase One
------------------

The first phase we will focus on the file upload function.

- easy to use upload form
- support multiple files upload
- support drag and drop

The initial upload form should have the following:

- Category: Name of Category separate by comma (,)
- Text?
- Comment?
- plupload file selection button
- File upload status prograss, check up

The MediaWiki_ extension MassEditRegex_ will give some ideas about
how to perform a single edit across multiple pages.

.. _Plupload: https://github.com/moxiecode/plupload
.. _MediaWiki: http://www.mediawiki.org
.. _MassEditRegex: http://www.mediawiki.org/wiki/Extension:MassEditRegex
