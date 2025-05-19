# Custom Wordpress Theme Starter Files

Use custom wordpress theme starter files to speedup early development process.

## Features
- Vite Integration + hot reloads on save
- Bootstrap Integration + theme starter setup
- Jquery Integration

Integrated with Vite + hot reloads. On a dev server, changes on PHP files will perform hot reloads on website.
Integrated with Bootstrap + theme overriding styles and setup guide.
Integrated Jquery on functions.php

## How to use on Laragon
- ### Clone to Wordpress files, under `/themes` folder
- ### Root directory
Your folder name should match the wp_options table on DB
```
folder name -> sample-project
wp_options siteurl -> http://localhost/sample-project
wp_options home -> http://localhost/sample-project
```
- ### Development
Open Laragon Terminal
Navigate to localhost http://localhost/sample-project
Open Code Editor, go to your themes directory `/themes/my-custom-vite`
Open Code Editor Terminal, run `npm run dev`

- ### Production
Run `npm run build`
Upload the generated `/dist` folder into your themes directory `/themes/my-custom-vite/dist`