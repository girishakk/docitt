# docitt_admin_portal

## Requirements

For development, you will need Node.js and npm installation on your environment and you can use appropriate EditorConfig plugin for your editor(not mandatory).

### Installation

Node is really easy to install & now include npm should be able to run command after the installation procedure.

    $node --version
    v8.10.0

    $npm --version
    6.8.0

#### Node Installation on Linux

To install node you will need to run the following command

    $sudo apt-get update
    $sudo apt-get upgrade
    $sudo apt-get -y install nodejs

#### Finally update the version of npm

One last step that’s a good practice is to update npm. There’s a default version that came with the version of Node you just installed, but that version is commonly slightly behind the latest and greatest version of npm.

To get the most up-to-date npm, you can run the command:

    $sudo npm install npm --global

#### Node installation on Windows

 1. Open the official page for Node.js downloads and download Node.js for Windows by clicking the "Windows Installer" option.
 2. Run the downloaded Node.js .msi Installer - including accepting the license, selecting the destination, and authenticating for the install.
 3. To ensure Node.js has been installed, run node -v in your terminal - you should get something like v6.9.5.
 4. Update your version of npm with:

        $sudo npm install npm --global

#### Node installation on mac

Before you can install Node, you’ll need to install two other applications. Fortunately, once you’ve got these on your machine, installing Node takes just a few minutes.

1. XCode. Apple’s XCode development software is used to build Mac and iOS apps,but it also includes the tools you need to compile software for use on your Mac. XCode is free and you can find it in the Apple App Store.

2. Homebrew. Homebrew is a package manager for the Mac — it makes installing most open source sofware (like Node) as simple as writing brew install node. You can learn more about Homebrew at the Homebrew website. 

Installing Node.js and NPM is pretty straightforward using Homebrew. Homebrew handles downloading, unpacking and installing Node and NPM on your system. The whole process (after you have XCode and Homebrew installed) should only take you a few minutes.

    1. Open the Terminal app and type:

         $sudo apt-get update
    
    2. To check the version on Node and npm type the command:

         $node -v
         v0.10.31

         $npm -v
         1.4.27

## Installation

### Clone Repository
To Clone the Repository type the following command in terminal

    $git clone https://github.com/girishakk/docitt.git

Then change the Directory to docitt

    $cd docitt

### Install Project Dependancies
Before starting the project you need to install the dependencies. To install hit the following command in Terminal.

    $npm install

### Start the Development Environment
To start the Development Environment type the following command in Terminal

    $npm start

### Run in Browser
To run project in Browser visit to the following address

    http://localhost:3000


    




