# decked-out

*decked-out* provides an [html decking layer](https://github.com/bahrus/be-decked-with) that can surround and enhance general HTML elements and components.

It makes HTML elements and components [customizable](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Customizable_select), and adds styling and functionality to create rich, interactive experiences.

## Sample markup

```html
<script type=importmap >
{
    "imports": {
        "decked-out/": "node_modules/decked-out/"
    }
}
</script>
<script type=module>
    import 'be-decked-with/😶‍🌫️.js';
</script>

<div id=element
    data-label=Example
    😶‍🌫️-src="decked-out/template.html">
    <button>
        <content></content>
    </button>
</div>
```

## Recommended vscode extensions:

[json-in-html, custom link attributes, idref](https://marketplace.visualstudio.com/publishers/andersonbruceb)