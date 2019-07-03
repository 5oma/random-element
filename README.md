# Random billingual quote from Tao te Ching. 

Visit in: http://www.casaxolotl.com/taoteching/

To create a random element appear, while all other arehidden, simply adapt the next script in javaScript: 

```javascript
var elems = $("p");
		if (elems.length) {
  			var keep = Math.floor(Math.random() * elems.length);
  		for (var i = 0; i < elems.length; ++i) {
    	if (i !== keep) {
      	$(elems[i]).hide();
    }
  }
}

```

