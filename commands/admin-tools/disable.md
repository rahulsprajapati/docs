# ee admin-tools disable

Disables admin-tools on given site.

### OPTIONS

[&lt;site-name&gt;]
: Name of website to disable admin-tools on.

[\--force]
: Force disabling of admin-tools for a site.

### EXAMPLES

    # Disable admin tools on site
    $ ee admin-tools disable example.com

    # Force disable admin tools on site
    $ ee admin-tools disable example.com --force

### GLOBAL PARAMETERS

| **Argument**    | **Description**              |
|:----------------|:-----------------------------|
| `--sites_path=<path>` | Absolute path to where all sites will be stored. |
| `--locale=<locale>` | Locale for WordPress. |
| `--le-mail=<le-mail>` | Mail-id to be used for letsencrypt. |
| `--[no-]color` | Whether to colorize the output. |
| `--debug[=<group>]` | Show all PHP errors; add verbosity to EE bootstrap. |
| `--prompt[=<assoc>]` | Prompt the user to enter values for all command arguments, or a subset specified as comma-separated values. |
| `--quiet` | Suppress informational messages. |
