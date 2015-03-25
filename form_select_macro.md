Creates select item provided the option items

##The regex

```regex
\*name="([\s\S]*?)" title="([\s\S]*?)" content="([\s\S]*?)"\*
```

##The substition

```html
<div class="form-group"><label class="col-md-4 control-label">$2</label><div class="col-md-6"><select name="$1">$3</select></div></div>
```
