LayoutUnremove
==============

A Magento extension that adds an `<unremove/>` tag to Magento's Layout XML.

###Layout Unremove

The Layout Unremove module allows you to, via Layout Update XML scripts, undo the effects of a previously executed &lt;remove/&gt; tag.

Original Blog Post: http://alanstorm.com/magento_layout_unremove_in_local_xml

###Build Instructions

The `build_layout_unremove.bash` file is a bash script that will create a simple tar archive of the extension files. 

    $ ./build_layout_unremove.bash
    
This script assumes the existence of a `var` folder.    