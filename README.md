# WP Plugin Boilerplate

A standardized, organized, object-oriented foundation for building high-quality WordPress Plugins.

## Installation

The Boilerplate can be installed directly into your plugins folder "as-is". You will want to rename it and the classes inside of it to fit your needs. For example, if your plugin is named 'example-me' then:

* rename files from `plugin-name` to `example-me`
* change `plugin_name` to `example_me`
* change `plugin-name` to `example-me`
* change `Plugin_Name` to `Example_Me`
* change `PLUGIN_NAME_` to `EXAMPLE_ME_`

It's safe to activate the plugin at this point. Because the Boilerplate has no real functionality there will be no menu items, meta boxes, or custom post types added until you write the code.

## How use

Just add to `composer.php`:
```
{
  "repositories": [
    {
      "type": "vcs",
      "url": "git@bitbucket.org:simple-solution/wp-plugin-boilerplate.git"
    }
  ],
  "require": {
    "simple-solution/wp-plugin-boilerplate": ">=1.0",
  }
}

```
