# KaMe Customers

This package provides the customers module for the _KAME_, a simple cms made with laravel, livewire and tailwind.

### Requirements

    PHP >= 7.3|8.0
    Laravel >=7.X

### Installation

Install via composer:

```bash
composer require kamekun/kame-customers
```

### Publish

Publish config file.

```bash
php artisan vendor:publish --tag="Kamekun\\KameCustomers\\KameCustomersServiceProvider"
```

### Configure

You can change the options of this module from `config/kame-customers.php` file

### Database

Create the tabes for the Model

```bash
php artisan migrate
```


### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

### Contributing

I am open to contributions to this package, and will do the best I can to maintain it over time.
Pull requests are welcome, and in fact encouraged. Right now there are no specific guidelines for a PR.

### Road Map

Some considerations for future versions:

- 


### Credits and License

- [KaMekuN](https://github.com/kamekun)

- Taylor Otwell and co. for Laravel

- Caleb Porzio for livewire

- Adam Wathan for Tailwind labs

This project is licensed under the MIT License - see the [License File](LICENSE) for details
