# Language Chooser for Sending Emails

The sample provided adds an action on the Part Item that will allow the user to send an email to the creator of the Part with details of the part. The action is a client action that takes user input, in the form of a "Language Chooser" so the user can determine what language to send the email in (Translated Emails must be provided by you).

## History

This project and the following release notes have been migrated from the old Aras Projects page.

Release | Notes
--------|--------
[v1](https://github.com/ArasLabs/email-language-chooser/releases/tag/v1) | LanguageChooserForEmail Sample Package
[v2](https://github.com/ArasLabs/email-language-chooser/releases/tag/v2) | Updated for Aras 11 SP9

#### Supported Aras Versions

Project | Aras
--------|------
[v1](https://github.com/ArasLabs/email-language-chooser/releases/tag/v1) | 9.3.0 SP5 - SP8
[v2](https://github.com/ArasLabs/email-language-chooser/releases/tag/v2) | 11.0 SP9

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Prerequisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **LanguageChooserForEmail** import package
4. The target Aras instance must have an SMTP server configured.
5. Users must have email addresses in the target Aras database.

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\LanguageChooserForEmail\Import\imports.mf` file in the Manifest File field.
6. Select all in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Created by Aras Corporation Support.

## License

Published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.
