# Ocr

Ocr Converts a scanned PDF or image file to a searchable PDF or a text file.

## Build

Run `npm run build` to build the project. The build artifacts will be stored in the `dist/` directory. package.json can be changed for custom build.

## Deploy 

Use [PM2](https://github.com/Unitech/pm2) to deploy server.js and set the server to point into the dist folder.

## External Dependencies
This project relies on [PyMuPDF](https://pypi.python.org/pypi/PyMuPDF/1.9.2) and [PyPDFOCR](https://pypi.python.org/pypi/pypdfocr) being installed and in the path.
