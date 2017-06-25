Clear password field
====================

This [Backdrop](https://backdropcms.org/) module clears common password form fields.

The [Open Web Application Security Project](https://www.owasp.org/) has multiple documents which recommend disabling automatic password capture. In their [response to Draft NIST SP 800-118](https://www.owasp.org/index.php/Industry:Draft_NIST_SP_800-118), they recommend setting the `autocomplete` attribute for form fields to `off`.

> For a web application, the 'autocomplete' attribute should be implemented
> with the value 'off' in rendered HTML form fields, or whole HTML forms,
> where sensitive data such as passwords are entered...

This module sets the `autocomplete` attribute to `off` for the login, user profile, and registration forms. It also uses jQuery to clear password fields where passwords are already saved. This module _does not_ erase the password from client browsers' configuration - it just clears the field to improve security.

Current Maintainer
------------------

- None

Credits
-------

- Originally written for Drupal by Victor Kareh (https://github.com/vkareh)
- Ported to Backdrop by David Norman (https://github.com/deekayen)

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
