
# Directory structure
Your project will contain the following directories by default:

## `/docs`
Contains the files .docx .pdf that you produce 

- `settings.php`: Contains master module configuration and any other configuration that will be common to all environments for the site. This file will be under version control so do not put sensitive or local environment information in it.
- `secret.settings.php`: Contains database settings for the environment and any other sensitive configuration settings. **Important**: Be sure to configure your database settings in this file before you build your project. This file will not be under version control for security reasons.
- `local.settings.php`: Contains local configuration overrides for the current environment. This file will not be under version control as it contains environment specific settings.

## `/figures`
Holds files .jpg that will be placed into the Drupal root directory in the build. By default it will contain the following files:


