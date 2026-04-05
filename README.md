# Folder.View Custom CSS Files

------------

Custom CSS styles for use with the **[FolderView3](https://github.com/scolcipitato/folder.view/tree/main)** plugin for **unRAID**.

_Requires FolderView3 version **2026.03.23.3** or later._

These themes include full styling for **Dashboard**, **Docker page**, and **VM page**, with support for FolderView3's layout modes (classic, accordion, fullwidth, inset, embossed) and preview overflow modes (scroll, expand).

Folder.View plugin **[Support Page](https://forums.unraid.net/topic/142782-plugin-folderview/)** on the unRAID forum.

If you have issues or customization suggestions, contact me on the unRAID forum. **[@Mattaton](https://forums.unraid.net/profile/95289-mattaton/)**

## Installation Instructions:

- CSS rules in this repo are organized by theme folder. Download the entire repo or the specific folder for the theme you wish to use. Copy the folder or folders in the Folder.View plugin folder here: **/boot/config/plugins/folder.view/styles**
- More than one theme can be copied to the plugin's styles folder, but only one should be enabled. To disable unused themes, append _.disabled_ to the folder name.
- To disable individual files, append _.disabled_ to the file name.
- See individual theme README for explanation of the files included in the theme.

## Autostart Icon Customization

Among other basic theme styling, all themes customize the autostart icons on the Dashboard and Docker page. Special icons for autostart containers and the folders that hold autostart containers make it easy to see, at a glance, if all of your autostart containers are running as they should.
Icons are fully customizable (design, color, and size) via custom properties (variables) in the 06-icons.dashboard.css and 06-icons.docker-vm.css files.

_See the individual theme README files for more information on that theme._

![Dashboard](Dashboard.png?raw=true "Title")

![Docker Page](Docker.png?raw=true "Title")
