## Navigation
- [Installation requirements](#installation-requirements)
- [Installation instructions](#installation-instructions)

-----

## Installation requirements

This plugin is developed and tested against WordPress 4.9.7+ and PHP 5.4.x+. {{Modify version numbers as needed!}}

While this plugin should work against any server running the [minimum requirements for WordPress installations](https://wordpress.org/about/requirements/), we cannot guarantee compatibility with, or provide support for, installations on non-LAMP stacks (e.g. Windows installations).

### Required Plugins
These plugins *must* be activated for {{My Project}} to function properly.

{{Bulleted list of required plugins + links to readmes/documentation here}}

### Supported Plugins
The plugins listed below are extended upon in this plugin--this may include custom layouts for feeds, additional functionality, etc.  These plugins are not technically required on sites running this plugin, and shouldn't be activated on sites that don't require their features.  A plugin does not have to be listed here to be compatible with {{My Project}}.

For more information on how these plugins are extended in {{My Project}}, please see our [[Plugin Extensions and Overrides docs|Plugin Extensions and Overrides]].

{{Bulleted list of supported plugins + links to readmes/documentation here}}

-----

## Installation instructions

Before getting started: make sure you've satisfied all the [installation requirements](#installation-requirements), and that any required plugins or recommended plugins that you wish to use are **installed and activated**.

1. Install the plugin:**

    - **via Github Updater**

      This plugin supports installation and updates via the [Github Updater plugin](https://github.com/afragen/github-updater).  See their documentation for more information on setup and usage.  (Requires PHP 5.6.0+)

    - **via standard (manual) installation**

      Download the plugin .zip file here: [https://github.com/UCF/{{My-Project}}/archive/master.zip](https://github.com/UCF/{{My-Project}}/archive/master.zip)

      Unzip and upload the plugin files to your WordPress instance's `wp-content/plugins/` directory.

      Alternatively, upload the .zip file using the WordPress plugins interface directly:
        - **On single sites:** navigate to Plugins > Add New.
        - **On multisite instances:** navigate to Network Admin > Plugins > Add New.

    - **via [WP-CLI](http://wp-cli.org/)**

      `$ wp plugin install https://github.com/UCF/{{My-Project}}/archive/master.zip`

      See the [WP-CLI docs](https://developer.wordpress.org/cli/commands/plugin/install/) for more information.

2. Activate the plugin: from your site's admin, click "Plugins" in the admin menu, find {{My Project}} in the list of plugins, and click "Activate".

3. Configure the plugin: Navigate to Settings > {{My Project}}{{Update this path as necessary!!}}, and update any default plugin settings as necessary for your site.  See the [[plugin settings docs|Plugin Settings]] for detailed information on available options.

That's it! Now you're ready to start using this plugin.

** Note that this plugin is not deployed to the WordPress plugin directory, and therefore will not notify you of plugin updates, unless you are using Github Updater.  You are responsible for keeping your copy of this plugin up-to-date with bugfixes and other new releases.

