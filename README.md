# Levels Authentication System

**Security-Level Authentication System in PHP with SQL Database Integration.**

This is an authentication system with security-level based access control, developed in PHP. It allows for information release based on the user's authentication level, enhancing security without increasing the number of logins required for the user. This system is highly configurable and can be implemented simply by editing the configuration file, `/etc/conf.php`.

## Installation

To install the system:

1. Download or clone this repository into a separate folder.
2. Configure the file `/etc/conf.php` based on your preferences.

## How to Use the System

After installation, follow these steps to use the system effectively:

1. Ensure to include the file `/etc/conf.php` in all files where the system will be used.
2. To restrict access to a page only to logged-in users, add the variable `$access_level` with the required access level for the page. (If the variable is not defined, it defaults to 0).
3. For more detailed instructions on how to use the system, refer to the documentation available in `/docs/`.

## Contribution

Contributions are welcome! Feel free to propose improvements, report issues, or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
