## selectlist

selectlist is a jQuery plugin of customizable, styleable replacement for native SELECT elements.

### Features

* Support standard HTML **select** tag
* Support keyborad options(UP,DOWN,ESC,ENTER)
* Support custom style
* Support IE7+,Firefox3+,Chrome and Oprea

## Usage

Link to the **jQuery.js** file:

```
<script src="http://code.jquery.com/jquery-1.11.2.min.js"></script>
```

Link to the **jquery.selectlist.js** file:

```
<script src="js/jquery.selectlist.js"></script>
```

Add the **CSS** file:

```
<link rel="stylesheet" type="text/css" href="css/jquery.selectlist.css">
```

To initialize:

```
$('select').selectlist();

$('#education').selectlist({
    zIndex:20,
    width:300,
    height:20,
    onChange:function(){
        //custom change callback
    }
})
```

## Notes
The selectlist plugin will according to match the native select on a page, the automatically generated simulation select, according to the native select the **name** and **id** attribute stored and added to the original list (it does not destroy the native defined properties).
native to the select is **the name and id attribute must be set and must be consistent** (for compatibility linkage select ).

## License

Copyright © 2015 YuChao Liu Licensed under the MIT license.