# For for Laravel 11

# Country Codes

Validates 2 & 3 character country codes.

<p align="center">
  <a href="https://github.com/laravel-validation-rules/country-codes/actions">
    <img src="https://img.shields.io/github/workflow/status/laravel-validation-rules/country-codes/CI?style=flat-square">
  </a>
  <a href="https://github.com/laravel-validation-rules/country-codes/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/laravel-validation-rules/country-codes.svg?style=flat-square">
  </a>
</p>

## Installation

```bash
composer require laravel-validation-rules/country-codes
```

## Usage

Validate a 2 character country code.

```php
use LVR\CountryCode\Two;

$request->validate([
    'country' => ['required', new Two],
]);
```

Validate a 3 character country code.

```php
use LVR\CountryCode\Three;

$request->validate([
    'country' => ['required', new Three],
]);
```
