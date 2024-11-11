# Laravel Installer

<a href="https://github.com/digiton-ma/installer/actions"><img src="https://github.com/digiton-ma/installer/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/digiton-ma/installer"><img src="https://img.shields.io/packagist/dt/digiton-ma/installer" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/digiton-ma/installer"><img src="https://img.shields.io/packagist/v/digiton-ma/installer" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/digiton-ma/installer"><img src="https://img.shields.io/packagist/l/digiton-ma/installer" alt="License"></a>

## Documentation

### Installation

You can install the package via composer:

```bash
composer global require digiton-ma/installer
```

### Usage

You can create a new Laravel project by running:

```bash
digitoncli new project-name
```

Use flags to customize the installation:

`--git`: Initialize a git repository
```bash
digitoncli new project-name --git
```

`--git --github`: Initialize a git repository and create a new repository on GitHub
```bash
digitoncli new project-name --git --github
```

`--git --github --org=digiton-ma`: Initialize a git repository and create a new repository on GitHub under the digiton-ma organization
```bash
digitoncli new project-name --git --github --org=digiton-ma
```

`--migrate --seed`: Run the migrations and seed the database
```bash
digitoncli new project-name --migrate --seed 
```

`--migrate --db-use=root --db-password=pass`: Run the migrations and seed the database using the specified database user and password 
```bash
digitoncli new project-name --migrate --db-use=root --db-password=pass
```
Most used command:
```bash
digitoncli new project-name --git --github --org=digiton-ma --migrate --seed
```

## Contributing

Thank you for considering contributing to the Installer! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

Please review [our security policy](https://github.com/digiton-ma/installer/security/policy) on how to report security vulnerabilities.

## License

Laravel Installer is open-sourced software licensed under the [MIT license](LICENSE.md).
