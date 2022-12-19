# Google Search in English, Always

Search engine for Firefox to search Google in English with the country set to
America. Also sets your homepage to Google in English, Firefox will ask if you
want to keep your current homepage or replace it with the suggested by this
extension.

This shouldn't be needed but Google insists that because you are in another
country you surely must speak their language and want their local results
despite your browser telling Google that your language is English.

## Limitations

The extension also provides search suggestions but I haven't found a way to
make Google return them in English, they are always in the local language as
detected by your IP address.

## Build the extension

```bash
npx web-ext build
```

Needless to say you need Node.js installed for this to work. This command
creates a .zip file inside a web-ext-artifacts folder. If you want an .xpi you
can either rename the .zip or run this other command instead:

```bash
npx web-ext build -n google_search.xpi
```
