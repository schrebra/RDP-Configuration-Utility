# RDP Configuration Utility

A set of tools to simplify the creation and management of Remote Desktop Protocol (RDP) connection files with comprehensive configuration options.

## Overview

This project provides a JSON schema (`rdpoptions.json`) that documents all available RDP configuration settings and a web-based RDP file editor. It helps system administrators and users create properly configured RDP files without having to memorize or look up the numerous configuration options.

## Why Use This Tool?

- **Simplified Configuration**: Instead of manually editing RDP files or remembering complex settings, users can configure their remote desktop connections through a structured interface.
- **Comprehensive Settings**: Includes detailed configuration options for:
  - Connection settings (authentication, auto-reconnection, bandwidth)
  - Display settings (resolution, color depth, performance)
  - Gateway configuration
  - Hardware redirection (printers, drives, audio, USB devices)
- **Documentation Built-in**: Each setting includes detailed descriptions, valid values, and usage notes.
- **Enterprise Deployment**: Helps IT administrators create standardized RDP configurations across their organization.

## Features

- Complete documentation of all RDP settings and their valid values
- Settings organized into logical categories:
  - Connection
  - Display
  - Gateway
  - Hardware
- Support for various connection types from modem to high-speed LAN
- Comprehensive security settings
- Extensive device redirection options
- Modern authentication support including Microsoft Entra ID

## Use Cases

- Creating standardized remote desktop connections across an organization
- Configuring secure remote access with specific security requirements
- Setting up specialized remote sessions with specific hardware requirements
- Deploying remote desktop solutions with custom display and performance settings

## Configuration Categories

### Connection Settings
Configure core connection properties including:
- Authentication levels
- Auto-reconnection
- Bandwidth detection
- Network type optimization
- Security layer settings

### Display Settings
Customize the remote desktop experience with:
- Resolution control
- Multiple monitor support
- Performance optimizations
- Visual quality settings

### Gateway Settings
Configure Remote Desktop Gateway properties:
- Gateway server settings
- Authentication methods
- Connection routing

### Hardware Settings
Control device redirection including:
- Audio devices
- Printers
- Local drives
- USB devices
- Smart cards

## Getting Started

### If you're new to GitHub and web files:

#### Method 1: Using the Web Editor Directly
1. Click on the green Code button and at the bottom download zip
2. Unzip it to a folder
3. Double-click the `RDP.Configuration.Utility.html` file from your computer
4. When the webpage opens, you'll see a "Browse rdpoptions.json" button
5. Click this button and select the `rdpoptions.json` file from your computer
6. The editor will load with all available RDP settings
7. Fill out the settings you want to change
8. Click "Generate RDP File" to create your connection file
9. Save the `.rdp` file to your computer (usually downloads to your Downloads folder)


### Using Your New RDP File
1. Find your saved `.rdp` file
2. Double-click it to open
3. Windows will start Remote Desktop Connection
4. Enter your username and password when prompted
5. You'll connect to your remote computer!

### Common Questions for Beginners

#### "What is an RDP file?"
- It's like a shortcut that helps your computer connect to another computer remotely
- Think of it as a recipe that tells your computer exactly how to connect to another computer


#### "How do I know it worked?"
- After double-clicking your `.rdp` file, you should see a window asking for your password
- Then you'll see the screen of the remote computer you're connecting to

#### "What if I get an error?"
Common fixes:
- Make sure the remote computer is turned on
- Check that you have the correct computer name or IP address
- Verify your username and password are correct
- Ensure the remote computer allows remote connections


## Credits
- https://github.com/kimmknight/rdpfileeditor for the rdpoptions.json

