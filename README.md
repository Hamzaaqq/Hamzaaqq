# Hamza Aqqaoui

Open-source PHP projects for practical software quality assurance, data quality and input validation.

**[OpenQA documentation](https://hamzaaqq.github.io/openqa-toolkit/) · [Composer package](https://packagist.org/packages/hamzaaqq/openqa-toolkit) · [Source and issues](https://github.com/Hamzaaqq/openqa-toolkit)**

## Featured project: OpenQA Toolkit

[![PHP checks](https://github.com/Hamzaaqq/openqa-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/Hamzaaqq/openqa-toolkit/actions/workflows/ci.yml) [![Integration checks](https://github.com/Hamzaaqq/openqa-toolkit/actions/workflows/integrations.yml/badge.svg)](https://github.com/Hamzaaqq/openqa-toolkit/actions/workflows/integrations.yml) [![Website deployment](https://github.com/Hamzaaqq/openqa-toolkit/actions/workflows/pages.yml/badge.svg)](https://github.com/Hamzaaqq/openqa-toolkit/actions/workflows/pages.yml) [![Packagist](https://img.shields.io/packagist/v/hamzaaqq/openqa-toolkit)](https://packagist.org/packages/hamzaaqq/openqa-toolkit) [![MIT license](https://img.shields.io/badge/license-MIT-green)](https://github.com/Hamzaaqq/openqa-toolkit/blob/main/LICENSE)

[OpenQA Toolkit](https://github.com/Hamzaaqq/openqa-toolkit) is an early-stage MIT-licensed command-line tool for checking HTML quality, local anchors and HTTP security headers. It provides JSON output for automation, a sample HTML fixture, regression tests, optional Laravel Blade auditing and a reusable GitHub Action.

[Read the quick-start guide](https://hamzaaqq.github.io/openqa-toolkit/guide.html) or install with Composer:

```sh
composer require --dev hamzaaqq/openqa-toolkit:^0.1
```

Try the offline fixture from a Git checkout:

```sh
git clone https://github.com/Hamzaaqq/openqa-toolkit.git
cd openqa-toolkit
php bin/openqa html examples/sample.html --json
php tests/run.php
```

Requires PHP 8.2+ with DOM and cURL. The sample deliberately contains three findings. See the [current CI results](https://github.com/Hamzaaqq/openqa-toolkit/actions). The tool is not a complete accessibility or security audit.

## Other projects

| Project | Purpose |
| --- | --- |
| [CSV Audit](https://github.com/Hamzaaqq/csv-audit) | Dependency-free PHP CLI for checking CSV structure and required values, with JSON reports and automated tests. |
| [PHP Mini Validator](https://github.com/Hamzaaqq/php-mini-validator) | Small PHP input validation library with required, email and minimum-length rules. |

## Learning and development focus

- Manual software QA and reproducible bug reports
- Accessible web experiences and defensive security checks
- Automated tests and maintainable developer tools

## Contributing

Feedback and reproducible bug reports are welcome. See the [OpenQA contribution guide](https://github.com/Hamzaaqq/openqa-toolkit/blob/main/CONTRIBUTING.md) and [roadmap](https://github.com/Hamzaaqq/openqa-toolkit/blob/main/docs/roadmap.md). Please omit credentials and private data from issues.
