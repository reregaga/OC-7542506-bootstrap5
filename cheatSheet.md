## Frameworks
[Bootstrap](https://getbootstrap.com/) is the most famous CSS framework, but there are many others that have a different design or design approach. Other notable examples of CSS frameworks include [Materialize CSS](https://materializecss.com/), [Foundation](https://get.foundation/), [Bulma](https://bulma.io/), and [Tailwind CSS](https://tailwindcss.com/).

### In sum:
- **Accessing websites via mobile phones is a growing trend** that you should consider as a web developer.
- It is **recommended to create responsive layouts for your websites** and web applications.
- External libraries such as **Bootstrap will help you build user interfaces** that provide a **responsive** user experience.

## Include Bootstrap to your project
All you need to get started with Bootstrap 5 is a link to a minified CSS file in `<head>` section:
```css
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
```
It must be added before other CSS files so that your styles override Bootstrap's default styles.

Many of Bootstrap components require the use of JavaScript to function. Specifically, they require our own JavaScript plugins and Popper. Add this line of code at the bottom of the page just before the closing `</body>` tag:
```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
```

Starter template:
```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <!-- Optional JavaScript; -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```

[Instructions](https://getbootstrap.com/docs/5.1/getting-started/introduction/)

[BootstrapCDN](https://www.bootstrapcdn.com/)
