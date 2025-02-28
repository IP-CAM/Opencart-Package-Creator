# OpenCart Package Creator
An OpenCart extension to create and install complete site packages (files + database).

## Extention Link in Opencart.com
https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=47078&filter_category_id=5&filter_license=0

## Features
- Creates a ZIP package of your OpenCart site (files + database).
- Installs the package with a multilingual (English/Farsi) interface.
- Dynamic path detection for any server.
- HTTP/HTTPS support.
- Permission checks with automatic directory creation.

## Installation
1. Upload `package_creator_v2_1.php` to `admin/controller/extension/module/`.
2. Go to **Extensions > Modules > OpenCart Package Creator** in your OpenCart admin panel.
3. Click "Create Package" to generate a ZIP file (saved in `system/packages/` and downloaded).

## Usage
- Extract the ZIP file to your target server.
- Open `http://your-site/install_package.php` in your browser.
- Fill in the form (site URL, database details, admin credentials) and click "Install".
- Delete `install_package.php` and `database.sql` after installation.

## Requirements
- OpenCart 3.x or higher
- PHP 7.0+
- Write permissions for `system`, `system/storage`, and `system/storage/logs`

## Notes
- This is an open-source version (v2.1). Future premium versions with additional features are planned.
- Feedback and contributions are welcome!

## License
Licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Fork this repository, submit pull requests, or report issues on GitHub: [https://github.com/caspiancms/OpenCart-Package-Creator](https://github.com/caspiancms/OpenCart-Package-Creator).

## Author
Developed by **Caspiancms.ir** - Visit [www.caspiancms.ir](https://www.caspiancms.ir) for more info and support.

## Support
Join the discussion on the [OpenCart Forum Thread](#) or open an issue on GitHub: [https://github.com/caspiancms/OpenCart-Package-Creator/issues](https://github.com/caspiancms/OpenCart-Package-Creator/issues).
