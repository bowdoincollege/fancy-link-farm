# Fancy Link Farm Table

## About
Template to display list of links in a searchable, filterable, pretty HTML table. 
Done in 100% JavaScript so no awkward server code is needed.

Originally forked from [derekeder/csv-to-html-table](https://github.com/derekeder/csv-to-html-table), but later
converted to just using YAML data and jQuery DataTables.

## Adapt to your stuff and using this template

To set this up for your links, you will need to edit `index.html`:

* Change the page title in the `&lt;head&gt;` section
* Change the `&lt;header&gt;` text to match your project's description
* Change the table row headings text to match your project's data fields
* Change the `columns` in the JavaScript code to match your YAML data fields
* Change the `&lt;footer&gt;` text to match your project's description (like the header)

Then for all your data:

* Update the `links.yaml` file with your data

In daily usage, after being installed, the `links.yaml` is updated with new links and descriptive fields.
Then, viola, the site is magically and deliciously updated.

## About the Code

Originally adapted from [derekeder/csv-to-html-table](https://github.com/derekeder/csv-to-html-table). Which would convert CSV files for use by jQuery DataTables. I no longer use any of Derek's code, but have an appreciation and give thanks for his work.

This version uses:
* [jQuery](https://jquery.com), and the [jQuery DataTables](https://datatables.net) plugin.
* [jeremyfa/yaml.js](https://github.com/jeremyfa/yaml.js) to convert [YAML](http://www.yaml.org) to [JSON](http://www.json.org) for [jQuery DataTables](https://datatables.net).
* [Bootstrap Table](http://bootstrap-table.wenzhixin.net.cn) for the pretty table display.

## Copyright

Copyright (c) 2018 Stephen Houser. Released under the [MIT License]().