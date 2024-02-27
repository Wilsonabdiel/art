# Artisan Shortcut

## Description

This is a simple shell script that provides a shortcut for running PHP Artisan commands. The script is named `art`, and it allows you to use commands like `art serve` instead of `php artisan serve`.

## Usage

To use this script, simply call it with the desired Artisan command as an argument. For example:

```bash
./art serve
```

This will run the `php artisan serve` command.

## Installation

To install this script, you can clone the repository and add execute permissions to the script:

```bash
git clone https://github.com/Wilsonabdiel/art.git
cd art
chmod +x art
```

Then, add the directory to your system's PATH. Now, you can use the `art` command from anywhere on your system.

## OR

To download and install a PHP package using Composer, you can use the `composer require` command followed by the package name. Here are the steps:

1. Open a terminal or command prompt.
2. Navigate to the directory where your `composer.json` file is located.
3. Run the following command:

```bash
composer require bytes/art
```

This command tells Composer to download the `bytes/art` package and any dependencies it requires. It also updates your `composer.json` and `composer.lock` files¹.

Please note that you need to have Composer installed on your machine to use this command. If you haven't installed Composer yet, you can download it from the https://getcomposer.org/download/.

## Requirements

- PHP
- Laravel
- Bash

Please ensure that you have PHP and Laravel installed on your machine, and that you're running a Unix-like operating system with a Bash shell.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open-source software licensed under the MIT license.
```
