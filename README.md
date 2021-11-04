# Stream feature extractor

A QGIS plugin to extract stream features (wells, sinks, confluences etc.)
from a stream network. The easiest way to install this plugin is to use
the QGIS plugin manager to install it (just search for 'stream' in the
plugin manager).


Visit our [home page](https://github.com/kartoza/stream_feature_extractor) for more details.

This plugin is Free and Open Source Software and is released under the GPL V2.
See the LICENSE file included with the plugin (and in this repository) for
more information about this license.

# Feature definitions
There are 11 types of features which can be extracted from a stream network:

1. Crossing: When two lines cross each other

![crossing](https://github.com/kartoza/stream_feature_extractor/blob/develop/help/source/static/crossing.png)

2. Pseudo node: A node that has one upstream and one downstream node. The node is superfluous as it can be represented by one line instead of two.

![pseudo_node](https://github.com/kartoza/stream_feature_extractor/blob/develop/help/source/static/pseudo_node.png)

3. 

# Contributing

If you would like to contribute an enhancement, bug fix, translation etc. to
this plugin, please make a fork of the repository on github at:

https://github.com/kartoza/stream_feature_extractor

Then make your improvements and make a github pull request. Please follow
the existing coding conventions if you want us to include your changes.

## This plugin was implemented by:

**Kartoza (Pty) Ltd.**
https://kartoza.com/

**Tim Sutton**
tim@kartoza.com

## Under subcontract to:

**Terrestris**
http://www.terrestris.de/

## This plugin was sponsored by:

**Landesbetrieb fuer Hochwasserschutz und Wasserwirtschaft Sachsen-Anhalt,**
Otto-von-Guericke-Strasse 5,
39104
Magdeburg, Germany.
