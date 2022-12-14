![Civil Services Logo](https://cdn.civil.services/common/github-logo.png "Civil Services Logo")

__Civil Services__ is a collection of tools that make it possible for citizens to be a part of what is happening in their Local, State & Federal Governments.


Instructions
===

This directory is for you to upload finished files that will be processed by running `npm run -s build`.


Update CSV File
---

This City Council Data is maintained in the `./source/us-senate.csv` Spreadsheet.  Any edits made to the CSV file in `./us-senate/data/us-senate.csv` will be lost. 


Update City Photo
---

This image is for web services that will display City Council Member listings on their website.  The background image is used for the website to display a custom image for that city.

#### Image Guidelines:

* Image should reflect a famous landmark of the city
* Image be licensed for NonCommercial use
* Edit the `./source/city.jpg` image with the photo you selected

#### Image Automation:

The `./source/city.jpg` image will be automatically converted to the following sizes:

* 640x360 ( stored in `./us-senate/images/backgrounds/640x360` )
* 960x540 ( stored in `./us-senate/images/backgrounds/960x540` )
* 1280x720 ( stored in `./us-senate/images/backgrounds/1280x720` )
* 1920x1080 ( stored in `./us-senate/images/backgrounds/1280x720` )


City Councilor Headshots
---

#### Image Guidelines:

1. Find and download a High Resolution Images for each City Councilor
2. Use a Photo Editor ( [https://pixlr.com/editor/](https://pixlr.com/editor/) if you do not already have one ) and export an image with a name like `firstname-lastname.jpg` ( using their actual first and last name, all lower case letters, using only letters a-z and replace all spaces with dashes ). Make sure the image is exactly 1024 pixels wide by 1024 pixels tall ( Download [./source/headshots/template.jpg](./headshots/template.jpg) if you need an image template )
3. Upload the file named something like `firstname-lastname.jpg` into this `./source/headshots/` directory

#### Image Automation:

The `./source/headshots/` images will be automatically converted to the following sizes:

* 64x64 ( stored in `./us-senate/images/headshots/64x64` )
* 128x128 ( stored in `./us-senate/images/headshots/128x128` )
* 256x256 ( stored in `./us-senate/images/headshots/256x256` )
* 512x512 ( stored in `./us-senate/images/headshots/512x512` )
* 1024x1024 ( stored in `./us-senate/images/headshots/1024x1024` )