# Hamza Aqqaoui

Open-source PHP projects for data quality, input validation and practical software testing.

## Featured project: OpenQA Toolkit

[![PHP checks](https://github.com/Hamzaaqq/openqa-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/Hamzaaqq/openqa-toolkit/actions/workflows/ci.yml)

[OpenQA Toolkit](https://github.com/Hamzaaqq/openqa-toolkit) is an early-stage MIT-licensed command-line tool for checking HTML quality, local anchors and HTTP security headers. It provides JSON output for automation, a sample HTML fixture and regression tests.

```sh
git clone https://github.com/Hamzaaqq/openqa-toolkit.git
cd openqa-toolkit
php bin/openqa html examples/sample.html --json
php tests/run.php
```

Requires PHP 8.2+ with DOM and cURL. The sample deliberately contains three findings. The [initial CI run](https://github.com/Hamzaaqq/openqa-toolkit/actions/runs/45481651163) passed; the tool is not a complete accessibility or security audit.

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
