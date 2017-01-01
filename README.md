# goslowTag
A simple jQuery plugin for initializing hashtags on input fields and textareas

# integrating with your application
Include the following lines in your HTML

```html
<link rel="stylesheet" href="css/goslowTag.css">
<script src="js/jquery.js"></script>
<script src="js/goslowTag.js"></script>
```
# Intialization
intialize goslowTag in your javascript within the document.ready

```javascript
$(document).on('ready', function() {
    $('input').goslowTag();
});
```
