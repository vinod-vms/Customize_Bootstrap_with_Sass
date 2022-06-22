## Customize_Bootstrap_with_Sass

How to customize Bootstrap with Sass

### How to install

Clone this repo and run: `npm install`.

The index.html file is already linked to the customized_bootstrap.css file in the `assets/css` folder.

After running `npm install`, node_modules directory containing Bootstrap and the Sass compiler will be installed.

The default Bootstrap .css file is `./node_modules/bootstrap/dist/css/bootstrap.min.css`

### How to compile

Run: `npm run compile:sass`

If you make any changes to the custom.scss file in the `custom_scss`  folder, the compiler will automatically compile to assets/css/customized_bootstrap.css upon saving. The `--watch` flag is enabled (see package.json)




