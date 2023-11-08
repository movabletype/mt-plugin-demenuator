This plugin is no longer supported in Movable Type 8 and later.

# Demenuator, a plugin for Movable Type

Authors: Six Apart
Copyright: 2009 Six Apart Ltd.
License: [Artistic License 2.0](http://www.opensource.org/licenses/artistic-license-2.0.php)


## Overview

De-menu-ator removes specified menus and menu items from the MT UI.


## Requirements

* MT 4.x


## Features

* Ability to remove from the Movable Type UI:
    * menu items
    * full menus
* Ability to do not remove menu items for users with the System Administrator privilege.


## Documentation

Demenuator provides three configuration directives.

### PreserveSuperuserMenus

Value of "1" preserves all menus for users with System Administrator priviege. Value of "0" to diable.

    PreserveSuperuserMenus 1

### RemovedMenuItems

Specifies menu items to remove.

Create a comma-separated list of menu items. Specify each using the menu then a colon then the menu item.

    RemovedMenuItems tools:plugins, manage:user, prefs:trackback

### RemovedMenus

Specifies menus to remove.

Create a comma-separated list of menus:

    RemovedMenus design, system


## Installation

1. Move the Demenuator plugin directory to the MT `plugins` directory.
2. Add configuration directives

Should look like this when installed:

    $MT_HOME/
        plugins/
            Demenuator/

[More in-depth plugin installation instructions](http://tinyurl.com/easy-plugin-install).


## Desired Features

*none listed*


## Support

This plugin is not an official Six Apart release, and as such support from Six Apart for this plugin is not available.
