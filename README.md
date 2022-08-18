Views Role Based Global Text
============================

This module provides the feature to show the content of Global:Text area field
in views to selected roles.

For example when a user uses the Global:Text area
field in header / footer in views, and wants to show this message to only
selected users, then he can select the roles to which this message is to show.

Installation
------------
- Install and enable the **views_role_based_global_text** module using the official [Backdrop CMS modules installation instructions](https://docs.backdropcms.org/documentation/extend-with-modules).

How to Use
----------

1. Enable this module.
2. Create a new view or edit existing view.
3. In View's add "Global: Text area" field (for example in header / footer /
no result found).
4. In "Global: Text area field", there is "Role" section.
5. Click on "Roles" and select the roles to which you want to display this
content.
6. If no role is selected, this content will be available to all users as view
does.

Dependencies
------------
Views

Documentation
-------------
Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/views_role_based_global_text/wiki/Documentation

Issues
------
Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/views_role_based_global_text/issues

Current Maintainers
-------------------
- Ryan Ositis (https://github.com/rositis)

Credits
-------
- Ported to Backdrop CMS by [Ryan Ositis](https://github.com/rositis).
- Maintained for Drupal by [Rohit Joshi](https://www.drupal.org/u/joshirohit100) and
  [Amit Goyal](https://www.drupal.org/u/amitgoyal).

License
-------
This project is GPL v2.0 software.
See the LICENSE.txt file in this directory for complete text.
