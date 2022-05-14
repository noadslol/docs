---
description: What libraries are and how to use them
---

# Libraries 101

{% hint style="danger" %}
**THE FIRST LINE OF THE CONFIG.PHP FILE SHOULD ALWAYS BE `<?PHP`**

This is **REQUIRED** otherwise this will break the entire program! This is already sat up out-of-the-box, but in case you accidentally remove that line, you will need to open your text editor of choice and manually fix it.
{% endhint %}

{% hint style="warning" %}
You need to install the library **BEFORE** you install a plugin that requires that library, otherwise PHP will think the library is not installed!

Valid Example (no error):

1. You installed the JavaScript Library **BEFORE**
2. You install a plugin that requires the JavaScript library **OR** you entered your own below the JavaScript library code in the `config.php`

Invalid example (no library error):

1. You install a plugin that requires the JavaScript library **OR** you entered your own below the JavaScript library code in the `config.php`
2. You installed the JavaScript Library **AFTER OR** you did not install the JavaScript library at all
{% endhint %}

Libraries are special plugin "helpers" that require you to use a specific OS or have specific compatibilities. These are available in the plugin dropdown menu and documentation for libraries are available in this category.
