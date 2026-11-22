# Hamza Aqqaoui

I build small PHP tools for validating input and checking data before it reaches an application.

## Selected projects

| Project | What it does |
| --- | --- |
| [CSV Audit](https://github.com/Hamzaaqq/csv-audit) | A command-line tool that checks CSV exports for duplicate headers, inconsistent row widths, and missing required values. It supports JSON reports and runs automated tests on PHP 8.2–8.5. |
| [PHP Mini Validator](https://github.com/Hamzaaqq/php-mini-validator) | A dependency-free input validator for PHP. It uses simple rules to check required fields, email addresses, and minimum lengths. |

## Try CSV Audit

From the CSV Audit repository root, run the included sample with PHP 8.2 or later:

```sh
php bin/csv-audit examples/customers.csv --required=email
```

The sample reports a missing email and a row with too few columns.
