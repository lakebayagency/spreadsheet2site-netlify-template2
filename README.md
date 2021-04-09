# Netlify template for a spreadsheet2site website

## Setup

1. Make a copy of [this Google Sheet template](https://docs.google.com/spreadsheets/d/1iHXM2M6m2vksvQ8PpxZTg0ZsRyJL58f243do1I1c3IQ)
2. Authorization on the Google sheet:
   1. Hit the Share button and add user spreadsheet2site-cli@spreadsheet2site.iam.gserviceaccount.com , uncheck notify email and save.
   2. Alternatively, make the Sheet public to anyone knowing the link
3. <a href="https://app.netlify.com/start/deploy?repository=https://github.com/azarai/spreadsheet2site-netlify-template"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>
4. Insert the Spreadsheet id during setup
5. Insert your License key as environment variable SS2S_LICENSE or leave it empty for trial mode


## CLI

The binaries are in the _bin_ folder and support OSX, Linux and Windows.

```bash
spreadsheet2site-osx build -sheet <sheetId> templates/ -output <output file or dir>
```

## Templates

See [readme](templates/README.md)