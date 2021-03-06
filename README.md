# Fresh WP Script

Task automator for new Wordpress installations, install all your Wordpress plugins and main theme with one single click.

**Main features**

- One single click to install all your plugins and main theme of your next project
- Require only 3 files
- You don't need download anything, get everything from the WP repository or your own server (for your premium plugins)

![](https://develus.com/share/fresh/fresh-preview.jpg)

### How to use

1. Install Wordpress on your server
2. Add the path to your theme on the file `fresh-theme.php`
![](https://develus.com/share/fresh/fresh-setup-theme.png)
3. Add the list of plugins that you want to install automatically on the file `fresh-plugins.php`
![](https://develus.com/share/fresh/fresh-setup-plugins.png)
4. Upload the 3 `fresh-*` files to your server where your WP installation is located usually on /public_html
5. Open your browser and navigate to your Wordpress installation like this `http://mydomain/fresh.php`
6. Customize the content of the textareas `wp-config` and `functions` this code will be added to your theme be sure that your theme have a functions.php file on your theme.

7. Press the button. **Fresh Now!** and let's the magic happen!

## Some important notes

You must wait for complete installation, once you click the button you must wait until all the tasks be finished.

**⭐ Installing Premium Plugins**

If you have premium plugins and you want to add it to the list just upload your zipped plugin to your own server and add the URL to `fresh-plugins.php` file.

![](https://develus.com/share/fresh/fresh-wait-installing.png)

### Successful installation

Once installed you should see this screen. Don't forget to delete all the fresh-* files from your server, that's all.

![](https://develus.com/share/fresh/fresh-finished.png)

### Do you want to contribute to this project?

Clone, modify and send your PR's to improve the power of Fresh!

### Do you find this script useful on your workflow?

🍺 [Support the development of Fresh WP Script with a donation](https://gumroad.com/l/freshwp)

### License:

This software is release under GNU General Public License v3.0