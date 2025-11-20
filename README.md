# Shapr3D Export to STL for free!

This is a Google Chrome & Firefox extension that allows the download of high-resolution models out of the web preview. Huge thanks to three.js for being awesome.

Forked from [mmahler2/Shapr3DSTL](https://github.com/mmahler2/Shapr3DSTL) and updated to support `firefox`

## Extension Installation
**Chrome** <img src="https://camo.githubusercontent.com/b1ded997835f13be4afaccfc2cc5941b7c899e6cb00a4d2ff589aa4ecb9eeda1/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f6368726f6d652e737667" alt="Chrome Icon" width="16" height="16">
1. Download the [~/chrome/](/chrome/) files to your local machine
2. Open `chrome://extensions/` in Chrome
3. Toggle on "**developer mode**"
4. Click "**Load unpacked**"
5. Select the folder you just downloaded

**Firefox** <img src="https://camo.githubusercontent.com/b75ea9652ae14231e213b8588ce717c948f69ec399e8032bb3f68fc89ff03379/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f66697265666f782e737667" alt="Chrome Icon" width="16" height="16">
1. Download the [~/firefox/](/firefox/) files to your local machine
2. Open `about:debugging#/runtime/this-firefox` in Firefox
3. Click "**Load Temporary Add-on...**"
4. Select the **manifest.json** file from the folder you just downloaded

## Usage
With the extension active in your browser, visit any Shapr3D preview link. An "Export STL" button should appear in the bottom right corner.

Note: Generating a Preview / Review Link
1. From the Menu bar in the modeling space, go to the File menu (Windows/macOS) or the More menu (iPadOS), then select Export To > Export…  to open the Export modal.
2. Under All Formats, select Review Link.
3. To generate your Review Link, select Publish.
Note: Select beside Publish Review Link to manage privacy and access settings before generating the link.
Optional: If Sync is disabled, you’ll be prompted to enable it before continuing. Enable Sync to continue.
