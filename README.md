# Installation wizard for brightly.in

The wizard installation is simple way to install brightly.in and doesn't require any special skills.

1. Prepare a directory on your server that is empty. It can be a sub-directory, domain root or a sub-domain.
2. [Download the installer archive file](https://github.com/brightly-in/install/archive/master.zip).
3. Unpack the installer archive to the prepared directory.
4. Grant writing permissions on the installation directory and all its subdirectories and files.
5. Navigate to the install.php script in your web browser.
6. Follow the installation instructions.

## Minimum System Requirements

brightly.in has a few system requirements:

* PHP version 7.0.8 or higher
* PDO PHP Extension
* cURL PHP Extension
* OpenSSL PHP Extension
* Mbstring PHP Library
* ZipArchive PHP Library
* GD PHP Library

As of PHP 5.5, some OS distributions may require you to manually install the PHP JSON extension.
When using Ubuntu, this can be done via ``apt-get install php5-json``.
