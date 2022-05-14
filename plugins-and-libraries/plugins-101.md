---
description: What a plugin is and how it works.
---

# Plugins 101

Plugins are PHP snippets that are injected to the `config.php` file which are included on every page. This can be used to...

* Execute shell commands,
* Fetch contents from an API,
* Change the CSS,
* Add, remove or edit content,
* Create and delete pages,
* ...the list goes on, if you can do it in PHP you can make it a plugin.

The plugins listed on the dropdown menu on the admin panel are developed by the No Ads Lol developer. These consist of...

* Libraries (special plugin "helpers" that require you to use a specific OS or have specific compatibilities),
* Library-Free Plugins (plugins that work regardless of your device), and
* Library Required Plugins (plugins that require a library to be installed).

Users can code and inject their own plugins, too! Just code a PHP snippet and paste it into the `config.php` file below the dropdown.
