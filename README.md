PHP_CodeSniffer_GIT_Hook
========================

A server-side git hook script for checking PHP, JavaScript and CSS code styling using PHP_CodeSniffer.

REQUIREMENTS
------------
- Bash Shell
- PHP_CodeSniffer : http://pear.php.net/manual/fr/package.php.php-codesniffer.php

INSTALLATION
------------

- Copy the pre-receive file into the hook directory of the remote GIT
repository.
-  Add the execution permission to copied file : 
```bash
chmod +x /REPOSITORY_PATH/hooks/pre-receive
``` 
