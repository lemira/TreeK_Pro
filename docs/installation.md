# Installation

TreeK Pro is installed as a Joomla package.

## Requirements

TreeK Pro has been tested and works on Joomla 6.0.x or 6.1.x and Kunena Forum
7.0.4 through 7.0.8. Installing TreeK Pro on other builds likely works, but it is not
officially announced, as extensive testing has not been performed on them. If
necessary, please contact the developer via the website:

https://treek.support

TreeK Pro requests may include up to two website URLs. These URLs are used to manage paid downloads, update access, and support records.

## Install TreeK Pro

1. Get the TreeK Pro package from the developer.
2. In Joomla Administrator, open **System -> Install -> Extensions**.
3. Upload and install the TreeK Pro package ZIP.
4. In **Extensions: Manage**, enable the **Treek - Add-on for Kunena Forum** plugin.
5. Open **Kunena -> Templates** and activate the TreeK template.

## After Installation

In Kunena's **Recent Topics** tab, the **Replies** number for topics with responses is clickable and highlighted in color. Clicking this number opens the topic's post tree.

If you have already entered a topic, you can access the post tree by clicking the tree icon located in the header of each post.

Use the settings button in the tree window to adjust the visible tree.

## Updating

Install the new package over the old one using Joomla extension installer. User
settings are preserved.

If Kunena is updated, install or update TreeK Pro again after the Kunena update.
Kunena updates can replace files that TreeK patches during installation.

## Troubleshooting

If the tree does not open:

- confirm that the TreeK AJAX plugin is enabled;
- confirm that Kunena is installed and working;
- clear Joomla and browser cache;
- check whether the current Kunena template is TreeK.
### AJAX Diagnostics

If the tree still does not open, enable **Debug AJAX log** in the **Treek -
Add-on for Kunena Forum** plugin settings. Then open a Kunena topic and click
the TreeK icon once to reproduce the problem.

TreeK writes AJAX diagnostics to:

```text
administrator/logs/treek_ajax.php
```

If your Joomla log folder has been changed, use the path shown in **System ->
Global Configuration -> System -> Path to Log Folder**.

The `treek_install.php` file is only the installation/update log. It is not the
AJAX diagnostic log.

After testing, disable **Debug AJAX log** again.
