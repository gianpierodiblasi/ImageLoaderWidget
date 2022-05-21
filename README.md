# ImageLoaderWidget
An extension to manage client side image upload.

## Description
This extension provides a widget to manage client side image upload (the image is not sent to the server). The image loading can be started in three ways:
- by clicking in an area
- by dragging images into an area
- by triggering a service

## Properties
- debugMode - BOOLEAN (default = false): if set to true it sends to the browser's JS console a set of information useful for debugging the widget
- image - IMAGE (no default value): the uploaded image

## Services
- Open: service to trigger the file open dialog
- Clear: service to reset the image

## Events
- FilesNotCompatible: event thrown when an incompatible file is selected
- LoadStarted: event thrown when the loading starts
- LoadComplete: event thrown when the loading completes
- OnDragEnter: event thrown when entering in a drop zone
- OnDragLeave: event thrown when leaving a drop zone
- OnDrop: event thrown when a drop is executed

## LocalizationTables
This extension adds the following localization token (Default, it and de languages):
- ImageLoaderWidget.imageloader.dragorclick (default = 'Drag your image here or click in this area')

## Donate
If you would like to support the development of this and/or other extensions, consider making a [donation](https://www.paypal.com/donate/?business=HCDX9BAEYDF4C&no_recurring=0&currency_code=EUR).
