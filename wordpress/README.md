# WordPress Code Standards

There are several pieces that go into the WordPress bucket. First, there are the official WordPress code style standards that we utlize. Secondly, there is a nfity wiki called WordPress: The Right Way that we pay attention to. This offers best practices as well as handy tips and techniques.

[Official WordPress Code Style](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/)
[WordPress: The Right Way](https://www.wptherightway.org/en/)

## Theming 

When writing a theme from scratch, it is important to ensure the theme is robust and handles anything WordPress will throw at it. For this we can use the [Theme Check](https://wordpress.org/plugins/theme-check/) plugin.

## Linting

Fortunately there is a [WordPress configuration ruleset](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards) that is used in conjuction with [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer).

### Configuring IDE Code Style/Completion

PHPStorm:
  1. Go to `Project Settings > Code Style > PHP`
  2. Select Set `From... (top right of window) > Predefined Style > WordPress`
