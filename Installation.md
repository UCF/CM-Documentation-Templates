Before getting started: make sure you've satisfied all the [installation requirements](https://github.com/UCF/{{My-Theme}}/#installation-requirements) for this theme, and that any required plugins or recommended plugins that you wish to use are **installed and activated**.


## Installation Instructions

1. Install the theme:**

    - **via Jenkins (for SWP users)**

      If you are using UCF's Shared WordPress service (SWP), we recommend working with CMIT to set up continuous deployment of this theme via Jenkins.  TODO do we want this to be our "official" recommendation? If so, how should folks contact CMIT to get started?

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
3. Configure the theme: create and set menus, and [make any other configuration updates noted in the theme readme](https://github.com/UCF/{{My-Theme}}/#theme-configuration).

That's it! Now you're ready to start adding content.

-----

** Note that this theme is not deployed to the WordPress theme directory, and therefore will not notify you of theme updates, unless you are using Github Updater.  You are responsible for keeping your copy of this theme up-to-date with bugfixes and other new releases.
