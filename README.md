# Plugin CI workflows

## Continuous integration workflow

This workflow will execute the following actions as long as they are available on the checked repository.

| Action | Required package | Required config file |
| -------- | -------- | -------- |
| PHP Parallel Lint | [php-parallel-lint/php-parallel-lint](https://packagist.org/packages/php-parallel-lint/php-parallel-lint) | |
| PHP CodeSniffer | [squizlabs/php_codesniffer](https://packagist.org/packages/squizlabs/php_codesniffer) | `.phpcs.xml` |
| PHPStan | [phpstan/phpstan](https://packagist.org/packages/phpstan/phpstan) | `phpstan.neon` |
| ESLint | [eslint](https://www.npmjs.com/package/eslint) | `.eslintrc.js` |
| Stylelint | [stylelint](https://www.npmjs.com/package/stylelint) | `.stylelintrc.js` |
| Licence headers check | [glpi-project/tools](https://packagist.org/packages/glpi-project/tools) | `tools/HEADER` |
| PHPUnit | [phpunit/phpunit](https://packagist.org/packages/phpunit/phpunit) | `phpunit.xml` |
