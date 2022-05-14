---
description: The No Ads Lol library that requires Windows (OS 10 or higher).
---

# Windows Library

This library requires Windows (10+) to be available. With this library installed, you can...

* Shutdown, restart or logout of the device (`shutdown('-r -t 1'); to restart`, `shutdown('-l -t 1');` to part shutdown (log out only, power still on and `shutdown('-s -t 1');` to full shutdown (log out and power off)),
* Ping a website or IP Address (`ping('www.github.com');` to ping Github, returns full ping response), and
* Download stuff to a directory via BitsAdmin (`dlBits('http://localhost/favicon.ico', 'C:\Users\%USERNAME%\Downloads\favicon.ico');` to copy the No Ads Lol favicon to your Downloads folder via BitsAdmin. You can also use this to download stuff from the Internet. Response should contain `Transfer complete.` if the transfer was done successfully.).

I am still working on things to add to this library.

To have your plugin check if the Windows library installed, use this code...

```
if(isset($winLib) && $winLib == true){
    //Your PHP code here;
}else{
    echo '<script defer>alert("A plugin you installed requires the Windows library, which is not installed! Please install the Windows library from the admin panel or remove this plugin from the config.php.");</script>';
}
```
