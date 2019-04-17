# instagram-export-viewer
Instagram’s “Data Download” lets users export their photos, videos, archived Stories, profile, info, comments, and non-ephemeral messages as  bunch of JSON files. However, Instgram does not provide an `index.html` for simple viewing of the export. 

## Prototype
Yes, this repo is mostly here on popular request an SHOULD be seen for what it is, a quick sketch. 

## Usage
Place the `index.html` file in the root directory of your Instagram export and open it in a web browser. For standalone use, please use Firefox. Internet Explorer and Chrome need the JSON files to be served by a webserver, like `[http-server](https://www.npmjs.com/package/http-server)` (NodeJS) or `[http.server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server#Running_a_simple_local_HTTP_server)` (Python).

## Example
<img align="left" src="https://raw.githubusercontent.com/Segerberg/instagram-export-viewer/master/instaviewer.jpg" width="60%" height="60%"/>
