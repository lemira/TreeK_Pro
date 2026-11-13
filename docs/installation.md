# Installation

TreeK Pro is installed as a Joomla package.

## Requirements

TreeK Free and Pro 3.1.0 support Kunena 7.0.11, 7.1.0, and 7.1.1 on Joomla 5.4, 6.0, 6.1, and 6.2. On the Joomla 5.4 branch, TreeK requires Joomla 5.4.7 or later with Kunena 7.0.11, and Joomla 5.4.10 or later with Kunena 7.1.0 or 7.1.1.

Kunena 7.1.0 and 7.1.1 require PHP 8.3 or later. An internet connection is required during TreeK installation so the installer can download the matching template files.

## Install TreeK Pro

TreeK Pro requests may include up to two website URLs. These URLs are used to manage paid downloads, update access, and support records.

1. Get the TreeK Pro package from the developer.
2. In Joomla Administrator, open **System -> Install -> Extensions**.
3. Upload and install the TreeK Pro package ZIP.
4. In **Extensions: Manage**, enable the **Treek - Add-on for Kunena Forum** plugin.
5. Open **Kunena -> Templates** and activate the TreeK template.

## After Installation

In Kunena's **Recent Topics** tab, the **Replies** number for topics with responses is clickable and highlighted in color. Clicking this number opens the topic's post tree.

If you have already entered a topic, you can access the post tree by clicking the tree icon located in the header of each post.

The settings window closes after 15 seconds of inactivity by default. Reopen it with **⚙ (Settings)**.

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
