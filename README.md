sfPropelORMPlugin v. pandabear
=================

This fork was born due to the existing sfPropelORMPlugin was not suitable for projects done on PHP 5.4. 
The issue arises during model creation. The issue that PHP 5.4 brought up was fixed in Phing 2.4.12, but
current sfPropelORMPlugin was not compatible with Phing 2.4.12.

## Installation

Please refer to propelorm / sfPropelORMPlugin at https://github.com/propelorm/sfPropelORMPlugin for installation.
This section contains guidance to get Phing 2.4.12 working with sfPropelORMPlugin

### The SVN way v. pandabear

Install the plugin via the subversion repository:

    svn checkout http://svn.github.com/propelorm/sfPropelORMPlugin.git plugins/sfPropelORMPlugin

Install `Propel`:

    svn checkout http://svn.github.com/propelorm/Propel.git lib/vendor/propel

Install `Phing`:
    Download Phing 2.4.12 from http://www.phing.info. 
    Extract `classes` contents to lib/vendor/phing.
    Also extract `etc` contents to lib/vendor/phing/etc.
