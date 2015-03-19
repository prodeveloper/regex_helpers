Quickly generate form html

Input data format sample

  name="patient" title="Patient Names" type="text"

Regex

  name="([\s\S]*?)" title="([\s\S]*?)" type="([\s\S]*?)"

Substitution regex
```html
<label class="col-md-4 control-label">$2</label><div class="col-md-6"><input type="$3" class="form-control" name="$1" /></div>
```
