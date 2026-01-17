# ProtoHax i18n Submodule

This repository contains the translation files for ProtoHax 2.

## Contributing

We welcome contributions to help translate ProtoHax 2! Whether you're adding a
new language or improving an existing one, your help is appreciated.

### Adding a New Language

1. **Fork the Repository**: Start by forking this repository to your GitHub
   account.
2. **Create a Directory**: Inside the `translated/` folder, create a new
   directory using your **2-letter ISO 639-1 language code** (e.g., `es` for
   Spanish, `fr` for French).
3. **Initialize the Translation**:
   - Copy the desired `.pot` files from the `template/` directory into your new
     directory.
   - Rename the copies to change the extension from `.pot` to `.po` (e.g.,
     `description.pot` -> `description.po`).
4. **Translate**: Open the `.po` files using a translation editor like
   [Poedit](https://poedit.net/) or any text editor, and translate the strings.
5. **Submit a Pull Request**: Commit your changes and open a Pull Request
   against this repository.

### Updating an Existing Language

1. **Fork the Repository**.
2. **Locate the Files**: Find the relevant `.po` files in the
   `translated/<lang>/` directory you wish to update.
3. **Update Translations**: Make your corrections or additions.
4. **Submit a Pull Request**.

### Tools

We recommend using **Poedit** for managing `.po` files, as it handles syntax and
encoding automatically.
