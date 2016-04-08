# Tasty Backend Page

The Tasty Backend Basic Page content type.

This module adds a "Tasty Backend" Basic Page if one does not already exist. It checks for the content type machine name **page**if it is found it does not create a "Tasty Backend" vesion of the Basic Page.

#### Options for using this module on a Drupal installation that already has a content type with the machine name **page**.

If you are using this module without the Tasty Backend Installation Profile you will find that it does not change the current Basic Page into a Tasty Backend one. Here are a few options on how to remedy this.

* Change the machine name of the current content type to something other than **page** then install.
* Delete the content type with the machine name **page** then install.
* Change the machine name of the content type to be created to something other than **page**. To do this fork this project and replace the four instances of **'page'** with you new machine name, maybe **'tasty_page'**. You may also want to change the name of the content type to something other than **'Basic page'**. Just replace the one instance of **'Basic page'** with something else, maybe **'Tasty Backend page'**

## RDF module
If the RDF module is not a dependency but if it is installed RDF mappings will be create during the installation.
