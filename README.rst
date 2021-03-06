.. contents::

======================
jQuery Graphviz plugin
======================

With this plugin you can move (click and drag and drop) and remove (double click on a node or on a edge) the nodes and the edges of a graph created with `graphviz <http://www.graphviz.org/>`_

Dependences
===========

* `jquery <http://jquery.com/>`_
* `jquery-ui <http://jqueryui.com/>`_:
 * jquery.ui.core.js
 * jquery.ui.widget.js
 * jquery.ui.mouse.js
 * jquery.ui.draggable.js

Usage
=====

* Add CSS

::

    <link rel="stylesheet" href="jquery.graphviz.0.0.1.css" />

* Add JS

::

    <script type="text/javascript" src="jquery.graphviz.0.0.1.js"></script>

* Initialize

::

    <script type="text/javascript">
        (function($){
            $(document).ready(function () {
                $("svg").graphviz();
            });
        })(jQuery);
    </script>

Testing
=======

This jquery plugin has been tested on the browsers: Latest versions of Firefox, Safari and Google Chrome, and even IE9. You can see in `jsfiddle <http://jsfiddle.net/UdysN/>`_

Releases
========

0.0.1  (2012-07-25)
-------------------

 * Move node and edges (drag and drop)
 * Remove node and edges (dobleclick)
 * Works, at least, Firefox, Safari, Google Chrome and IE9

