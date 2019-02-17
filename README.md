# Joomla Activation Email
A plugin meant to replace the Joomla activation email allowing for greater customization.

This comes after great frustration that the current Joomla registration email only allows customization via the modification of a language tag override.

## Installation
Installation is straigtforward: 
- Tthe plugin can be directly installed from .zip file.
- The plugin source files can also be added to your project directly and added via "discovery".

## Configuration
As of now, The only configurable thing is the email subject and body.

## Tags
Programmatic information is inserted into the email body in the form of tags, the available tags are as follows:
- [USER_NAME]: The new user's full name.
- [USER_EMAIL]: The new user's email address.
- [SITE_NAME]: The name of your site/application.
- [ACTIVATION_URL]: The URL to be used by the user in order to activate his account.
- [BASE_URL]: Your site's base URL.
- [USER_LOGIN]: The user's username.
- [USER_PASS]: The user's PLAINTEXT password, Please only include this if you are automatically generating a password for your users and requiring them to set their password afterwards, its is never a good idea to send passwords via unencrypted email!
