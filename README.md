Node access node reference
==========================

Gives content access permissions to users if they have access to content that is
referenced with Node reference or Entity reference. Checks view, update, and delete grant
operations, and can pass those on to the referencing content, or trigger a
different grant configuration according to settings.

Requirements
------------

This module requires a field module that can reference users.  Currently there
are two modules supported:

- Entity Reference <https://backdropcms.org/project/entityreference>
- References <https://backdropcms.org/project/references>

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  <https://backdropcms.org/guide/modules>
- Add a field of type 'node reference' or 'entity reference' to your content type.

Usage
-----

Create a field to reference content in a content type using the Field UI. The
field's configuration page will contain the settings for Node access node
reference.

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Current Maintainers
-------------------

- Herb v/d Dool <https://github.com/herbdool>

Credits
-------

This module is ported from Drupal 7.

Drupal Maintainers:

- danielb <https://www.drupal.org/u/danielb>
- galooph <https://www.drupal.org/u/galooph>
