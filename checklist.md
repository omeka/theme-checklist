# Omeka Theme Testing Checklist

## Global components

### Cross-browser

* Testing devices
    * Chrome
    * Firefox
    * IE10

### Responsive styles

* Testing devices
    * Safari (iOS)
    * Chrome (Android)

### Accessibility audits

* Browser extensions/plugins
    * Chrome - Accessibility Developer Tools extension
    * Firefox - WAVE Toolbar

### Admin Bar

Admin bar should always look the same across themes.

### Header

* Theme logo
* Theme header

### Navigation
* Nested navigation

### Footer

'Powered by Omeka' tagline should be present across CHNM themes.

### Site-wide search

* Simple search
* __Advanced search__ - There should be an obvious way to open a menu that allows the user to filter search results by records (item, collection, exhibit, etc.) and use boolean (and, or, etc.).    

### Other theme options

## Basic Views

### Home

* Featured item
* Featured collection
* Featured exhibit
* Recent items

### Items

* Browse
    * __Pagination__ - Form input works
    * __Sort links__ - Links for sorting by date created, author, name
* Show
    * If item navigation present (next item, previous item), the navigation is obvious and usable.
* Advanced Items Search
    * __Narrow by specific fields__ - The user should be able to add fields, and remove previously added fields via "Add a field" and "Remove field" or "-" buttons.
* Tags
* File view

### Collections

* Browse
    * __Pagination__ - Form input works
    * Collections do *not* have sorting links.
* Show

### Search

* Search filters appropriately styled (no bulleted lists).

### 404

## Plugins

* Exhibit Builder
* Geolocation
* Simple Pages
* Commenting