This is a standalone, anonymous version of the downsampling web app.

The tool uses webassembly, which is currently supported on all major browsers. However, this requires that the page be served rather than simply opened in a web browser. An easy way to do this is to call the following command in the project directory (the webapp directory):

python3 -m http.server

Then, navigate to http://127.0.0.1:8000/ using a supported browser (Chrome, Safari, Edge, and most others)

## Using the App 

Obtain a (single-ended) fastq file, from the SRA, ENA, or other location. Note that the SRA encodes fastq files in their own special format, which must be converted to fastq using the SRA toolkit. Then, simply follow the onscreen instructions to downsample the file. The downsampling runs in the browser, so your runtime may vary.


