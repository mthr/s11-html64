
html64
================================

This simple tool converts `<img src="..."/>` to `<img src="data:..."/>`
in an HTML file.

My use case: 

* Generate HTML from a reST file (or any other markup).
* Base64-encode images in the HTML file.
* Email it as a single attachment.

Dependencies
------------

* `sed`, `awk`, `file`, et. al.
* `base64`
* `xmlstarlet` (some distros call the executable `xml`) 


