## Navigation
- [Installation requirements](#installation-requirements)
- [Installation instructions](#installation-instructions)
- [Theme configuration](#theme-configuration)

-----

## Installation requirements

This theme is developed and tested against WordPress 4.9.7+ and PHP 5.4.x+. {{Modify version numbers as needed!}}

While this theme should work against any server running the [minimum requirements for WordPress installations](https://wordpress.org/about/requirements/), we cannot guarantee compatibility with, or provide support for, installations on non-LAMP stacks (e.g. Windows installations).

### Required Plugins
These plugins *must* be activated for the theme to function properly.

{{Bulleted list of required themes + links to readmes/documentation here}}

### Supported Plugins
The plugins listed below are extended upon in this theme--this may include custom layouts for feeds, style modifications, etc.  These plugins are not technically required on sites running this theme, and shouldn't be activated on sites that don't require their features.  A plugin does not have to be listed here to be compatible with this theme.

{{Bulleted list of supported themes + links to readmes/documentation here}}

-----

## Installation instructions

Before getting started: make sure you've satisfied all the [installation requirements](#installation-requirements) for this theme, and that any required plugins or recommended plugins that you wish to use are **installed and activated**.

1. Install the theme:**

    - **via Github Updater**

      This theme supports installation and updates via the [Github Updater plugin](https://github.com/afragen/github-updater).  See their documentation for more information on setup and usage.  (Requires PHP 5.6.0+)

    - **via standard (manual) installation**

      Download the theme .zip file here: [https://github.com/UCF/{{My-Theme}}/archive/master.zip](https://github.com/UCF/{{My-Theme}}/archive/master.zip)

      This theme can be installed via traditional installation methods if desired.  After downloading the latest theme .zip file onto your computer, [follow the steps on this page](https://codex.wordpress.org/Using_Themes#Adding_New_Themes).

      Alternatively, if you're running a WordPress Multisite instance, you can install the theme by navigating to the network admin, go to Themes > Add New, then click the "Upload Theme" button to upload the .zip file.  After uploading and installing the theme, you can choose to either network activate it, or activate the theme for a specific site (navigate to All Sites, click on a site in the list, then click the Themes tab and enable the theme in the list.)

    - **via [WP-CLI](http://wp-cli.org/)**

      `$ wp theme install https://github.com/UCF/{{My-Theme}}/archive/master.zip`

      See the [WP-CLI docs](https://developer.wordpress.org/cli/commands/theme/install/) for more information.
2. Activate the theme: from your site's admin, navigate to Appearance > Themes, hover over the theme's thumbnail, and click the "Activate" button that appears.
3. Configure the theme: create and set menus, and [make any other configuration updates noted in the theme configuration steps](#theme-configuration).

That's it! Now you're ready to start adding content.

** Note that this theme is not deployed to the WordPress theme directory, and therefore will not notify you of theme updates, unless you are using Github Updater.  You are responsible for keeping your copy of this theme up-to-date with bugfixes and other new releases.

-----

## Theme configuration

After [installing this theme](#installation-instructions), you should perform the following configuration steps:

* {{IF ACF IS REQUIRED:}} [Download this theme's ACF config file](https://github.com/UCF/{{My-Project}}/blob/master/dev/acf-export.json), and import field groups using the ACF importer under Custom Fields > Tools.
* {{IF A STATIC FRONT PAGE IS REQUIRED/EXPECTED:}} Create and set a static front page under Settings > Reading.
* {{Include instructions on assigning header/footer menus here, as needed}}
* {{IF THEME UTILIZES PREMIUM WEBFONTS:}}If you plan on using [premium webfonts using Cloud.Typography](https://ucf.github.io/Athena-Framework/getting-started/install/#cloudtypography-premium-font-configuration), ensure that webfonts have been properly configured to a Cloud.Typography CSS Key that [allows access to your environment](https://dashboard.typography.com/user-guide/managing-domains). A Cloud.Typography CSS Key URL can be added via the WordPress Customizer (Appearance > Customize > Web Fonts).

{{Add any additional bullet points as necessary}}
