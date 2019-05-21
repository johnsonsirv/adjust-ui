# Adjust UI Documentation
Adjust UI is a free and open source Sass framework that empowers you to create flexible, clear, and semantic website layouts. A modular, front end framework to easily and quickly help you jumpstart your process in building complex interfaces for the web right out the box.

## Overview
You only need 1 CSS file to use Adjust UI
## Geting Started
Download from the Github repository
https://github.com/johnsonsirv/adjust-ui/master/tree/css
#### Code Requirements
* Use HTML 5 doctype
`<!DOCTYPE html>`
* Add a responsive viewport meta tag
`<meta name="viewport" content="width=device-width, initial-scale=1">`

## Starter Template
```sh
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Hello Adjust UI!</title>
    <link rel="stylesheet" href="path_to_downloaded_css_file">
  </head>
  <body>
  <section class="row">
    <div class="col-12">
      <h1 class="text-large">
        Hello World
      </h1>
      <p class="text-small">
        My first website with <strong>Bulma</strong>!
      </p>
    </div>
  </section>
  </body>
</html>
```

## Modularity
Adjust UI currently contains _13_ `.sass` files that you can import directly and use them as you like. 
The file is located at `adjust-ui/sass/partials` folder

## Layout
`Row` is a simple grid container position your content horizontally
The `.row` class can be used in any context and will contain direct children such as 
`.col-12` for a 12-span column. You can use modifiers to control the gaps/gutters between columns. 
### 12-column Grid
The 12-grid column gives you freedom to slice you page into 12 sections.

Columns `.col-` are direct children of the `.row` container

```sh
    <div class="row">
      <div class="col-4">
          <h1> I span 4 columns</h1>
      </div>
      <div class="col-8">
          <h1> I span 8 columns</h1>
      </div>
    </div>
```

## Typography


## Elements

### Buttons
The `button` is an essential element of any design. It's meant to look and behave as an interactive element of your page. The default button is creaed using the `.btn` class
* `btn-primary`
* `btn-primary`
* `btn-warning`

### Message / Alerts
`.alert` enables you to create a message display on the web page.
* `alert-error`
* `alert-danger`
* `alert-info`
* `alert-success`
* `alert-warning`
