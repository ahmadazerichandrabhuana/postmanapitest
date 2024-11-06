# Postman API Test
Sample API Test using Postman Collection

## Website Test

API Collection retrieved from this Website : https://thinking-tester-contact-list.herokuapp.com/

## Requirements

Install [Postman CLI](https://learning.postman.com/docs/postman-cli/postman-cli-installation/) or [Newman](https://learning.postman.com/docs/collections/using-newman-cli/installing-running-newman/) and download my API Collection on this repository (file is on `.json` format).

## Run Test using Postman CLI

    postman collection run '[downloaded file name].json'

You can also just import my API Collection into Postman (either on Browser or using Postman Desktop App) and do 'Run collection'.

## Run Test using Newman

    newman run '[downloaded file name].json'

For a better test result, install [Newman Reporter HTMLExtra](https://www.npmjs.com/package/newman-reporter-htmlextra)(`npm install -g newman-reporter-htmlextra`) and run with this command : 

    newman run '[downloaded file name].json' -r cli,htmlextra


