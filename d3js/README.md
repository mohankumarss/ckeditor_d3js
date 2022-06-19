CKEditor Chart Plugin
=====================

This is a proof-of-concept plugin that adds support for injecting charts into CKEditor.

This is wogressk in progress, plugin is used to create a chart in ckeditor using d3js open source library. Right now plugin creates a static chart using d3js
## Installation

1. Put the plugin into the CKEditor "plugins" folder.
2. Enable the plugin with `config.extraPlugins`.
3. Add the `d3js` button to the toolbar if it will not appear automatically.

<pre>
CKEDITOR.replace( 'editor1', {
    extraPlugins: 'd3js'
} );
</pre>
