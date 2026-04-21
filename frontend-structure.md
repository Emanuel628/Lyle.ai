# Lyle.ai Frontend Structure

## Frontend Root
The frontend lives under:
- public

## HTML Location
HTML files live under:
- public/html

Examples:
- public/html/index.html
- public/html/chat.html

## CSS Location
CSS files live under:
- public/css

Expected CSS files:
- global.css
- landing.css
- chat.css

## JavaScript Location
JavaScript files live under:
- public/js

Expected JavaScript files:
- global.js
- chat.js

## Assets Location
Assets live under:
- public/assets

Possible asset folders:
- public/assets/images
- public/assets/icons

## Frontend File Responsibilities

### index.html
Landing page for product introduction and trust building.

### chat.html
Main chat interface for interacting with Lyle.

### global.css
Shared styles across the site.

### landing.css
Landing-page-only styling.

### chat.css
Chat-page-only styling.

### global.js
Shared site interactions if needed.

### chat.js
Chat behavior and later product interaction logic.

## Frontend Rule
Keep structure organized and easy to scan.

## Build Order
1. HTML structure
2. CSS styling
3. JavaScript behavior
4. backend integration after the frontend base is stable