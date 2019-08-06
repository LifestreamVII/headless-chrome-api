# HEADLESS CHROME HEADLESS

puppeteer as an independent nodejs app. forked from [mailtarget](https://github.com/mailtarget/headless-chrome-api)

### Usage

    docker run -p 3000:3000 wkwksama/headless-chrome-api

### example create pdf

    POST http://localhost:3000/pdf

    {
        "html": "<h1>my awesome dpf</h1>",
        "paperSize": "A5" // default A4
    }

It will response the pdf file generated from html
