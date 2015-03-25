Generate list items that have titles

##The regex

```regex
\*title="([\s\S]*?)" value="([\s\S]*?)"\*
```

##The replacement string

```html
 <div class="list-group">            <a href="#" class="list-group-item">                <h4 class="list-group-item-heading">$1</h4>                <p class="list-group-item-text">$2</p>            </a>        </div>
```
