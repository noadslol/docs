---
description: The No Ads Lol library that requires JavaScript.
---

# JavaScript Library

This library requires JavaScript to be available. With this library installed, you can...

* Inject JavaScript code (`jsi('alert("Hello World");');` to make a Hello World alert using JavaScript directly, it may be easier using the alert function though),
* Make a JavaScript popup alert (`alert("Hello World");`to make a Hello World alert), and
* Log stuff to the console (`conslog("Hello, source dweller");` to log "Hello, source dweller" to the browser console).

I am still working on things to add to this library.

To have your plugin check if the JavaScript library installed, use this code...

```
if(isset($jsLib) && $jsLib == true){
    //conslog("The JavaScript library is installed!");
    //Your PHP code here;
}else{
    echo '<script defer>alert("A plugin you installed requires the JavaScript library, which is not installed! Please install the JavaScript library from the admin panel or remove this plugin from the config.php.");</script>';
}
```
