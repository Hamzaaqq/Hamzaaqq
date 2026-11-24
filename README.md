# Hamza Aqqaoui

Open-source projects for data quality, input validation and practical software testing.

## Projects

| Project | Purpose |
| --- | --- |
| [CSV Audit](https://github.com/Hamzaaqq/csv-audit) | Dependency-free PHP CLI for detecting malformed CSV records, duplicate headers and missing required values. Includes JSON output and automated tests. |
| [PHP Mini Validator](https://github.com/Hamzaaqq/php-mini-validator) | Small PHP input validation library with required, email and minimum-length rules. |

## Try CSV Audit

Requires PHP 8.2 or later. From the project directory:

```sh
php bin/csv-audit examples/customers.csv --required=email
php tests/run.php
```

The sample demonstrates a missing email and a row with too few columns.

## Current learning interests

- Manual software quality assurance and reproducible bug reports
- Accessible web experiences and defensive security checks
- Automated testing, documentation and maintainable developer tools

## Feedback and contributions

Bug reports, reproducible examples and suggestions are welcome through the relevant repository's issue tracker. Please avoid sharing private data or credentials in issues.
