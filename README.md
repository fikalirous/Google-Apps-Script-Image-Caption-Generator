# Image Captions Generator

This script is designed to work with Google Sheets and Google Docs to generate a document that includes images and captions. It's especially useful when you have a list of image URLs and their corresponding captions in a Google Sheet and you want to create a report with these images and captions.

## Features

- Downloads images from provided URLs.
- Resizes the images for a uniform appearance.
- Inserts the images and captions into a Google Doc.
- Handles errors gracefully when an image cannot be fetched.
- Automatically creates new pages in the Google Doc as needed.

## Usage

1. Open your Google Sheet with the image URLs and captions.
2. Click on "Extensions" in the menu and select "Apps Script."
3. Paste the provided code into the script editor.
4. Save the script and close the script editor.
5. Click on the "Generate Image" menu in your Google Sheet.
6. Select "Generate Image and Caption Report" from the dropdown.
7. The script will create a new Google Doc with images and captions.

## Configuration

You can adjust the desired image width and height in the code:

```javascript
image.setWidth(300); // Desired pixels width
image.setHeight(200); // Desired pixels height
