# jquery.typeProgress

**[1] Include plugin files:**
```html
<link rel="stylesheet" href="jquery.typeProgress.min.css">
<script src="jquery.typeProgress.min.js"></script>
```

**[2] Your input must contains "maxlength" attribute:**
```html
<div class="form-group">
  <input type="text" maxlength="100" class="form-control type-progress-example">
</div>
```
**[3] Initialize plugin like this example:**
```javascript
$('.type-progress-example').each(function() {
  $(this).typeProgress();
});
```
**[4] Enjoy.**
