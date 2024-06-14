# RESTFUL_Newman_Report

Newman Report with html and htmlextra

# Package Requirements:
> Node.js (preferred LTS Version)

https://nodejs.org/en/download/prebuilt-installer

> Newman package

https://www.npmjs.com/package/newman

> Newman html extra package

https://www.npmjs.com/package/newman-reporter-htmlextra

> JSON Export of Collections and Environment from Postman

https://learning.postman.com/docs/getting-started/importing-and-exporting/exporting-data/

# cmd to run

`newman run {collection_name}.json -e {environment_name}.json --reporters html --reporter-html-export {file_name}.html`

`newman run {collection_name}.json -e {environment_name}.json --reporters htmlextra --reporter-htmlextra-export {file_name}.html`
