# plymouth    

[![build result](https://build.opensuse.org/projects/home:guideos:trixie/packages/plymouth-theme-guideos/badge.svg?type=default)](https://build.opensuse.org/package/show/home:guideos:trixie/plymouth-theme-guideos)

Plymouth is a software component that displays a graphical boot animation and status messages during system startup. It is commonly used in Linux distributions to make the boot process visually appealing and to provide feedback to the user about the progress. Plymouth runs very early in the boot process and replaces traditional text-based messages with a modern, configurable interface.

## Features

- Displays boot animations
- Supports various themes
- Shows status messages during system startup
- Customizable and extensible

## Usage

Plymouth is automatically executed when the system starts and usually requires no manual interaction. Themes and settings can be adjusted via configuration files.

## Changing Themes

To change the Plymouth theme, use the following commands:

List available themes:
```sh
sudo plymouth-set-default-theme --list
```

Set a new theme (replace `theme-name` with your chosen theme):
```sh
sudo plymouth-set-default-theme -R theme-name
```

Reboot your system to see the new theme.

## More Information

Further details about configuration and customization can be found in the official documentation or in the respective theme files.

