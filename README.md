# Running the discogs export executable

1. Download, extract, and move to preferred folder location
2. Run
3. Enter your [Discogs API key](https://www.discogs.com/settings/developers) when prompted
   * This is free with your Discogs account
4. Enter as many Discogs release IDs as you want, delimited with commas, and hit Enter
   * These numeric IDs appear in the Discogs website URL when viewing a release
     - e.g. 3433792 in https://www.discogs.com/release/3433792-Junior-Kimbrough-You-Better-Run-The-Essential-Junior-Kimbrough
5. Files will be output in the same folder the app is in and will be overwritten by subsequent runs if not renamed

## Viewing JSON files
The JSON files serve as a full dump of all available data from Discogs for the specified releases. Use the JSON compare the CSV
against or just use the JSON by itself.

### Recommended JSON viewers
* Online: https://jsonformatter.org/json-viewer
* Chrome/Edge browser extension: https://chromewebstore.google.com/detail/json-viewer-pro/eifflpmocdbdmepbjaopkkhbfmdgijcc
