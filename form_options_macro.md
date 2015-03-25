Quickly generate form options

##Sample input data

*value=low title=Low Priority*
*value=neutral title=Neutral*
*value=high title=High Priority*

##Regex
```regex
\*value="([\s\S]*?)" title="([\s\S]*?)"\*
```
##Replacement

```html
<option value='$1'>$2</option>
```

##output

<option value=low>Low Priority</option>
<option value=neutral>Neutral</option>
<option value=high>High Priority</option>

