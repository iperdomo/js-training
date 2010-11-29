!SLIDE bullets incremental transition=scrollUp
# JavaScript Object Notation #
## JSON ##

!SLIDE bullets incremental transition=scrollUp

* Es un formato de intercambio de información
* Sencillo de leer
* RFC 4627 application/json

!SLIDE bulllets incremental

# JSON object #

    @@@ javaScript
		var jsObject = JSON.parse('[1, 2, 3]');


		var foo = {};  
		foo.bar = "new property";  
		foo.baz = 3;
		var jsonString = JSON.stringify(foo);

    // {"bar":"new property","baz":3}
