This is a standalone, anonymous version of the downsampling web app.

The tool uses webassembly, which is currently supported on all major browsers. However, this requires that the page be served rather than simply opened in a web browser. An easy way to do this is to call the following command in the project directory (the webapp directory):

python3 -m http.server

Then, navigate to http://127.0.0.1:8000/ using a supported browser (Chrome, Safari, Edge, and most others)

