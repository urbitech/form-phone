# Form Phone control

[![Build Status](https://img.shields.io/travis/ipublikuj-ui/form-phone.svg?style=flat-square)](https://travis-ci.org/ipublikuj-ui/form-phone)
[![Scrutinizer Code Coverage](https://img.shields.io/scrutinizer/coverage/g/ipublikuj-ui/form-phone.svg?style=flat-square)](https://scrutinizer-ci.com/g/ipublikuj-ui/form-phone/?branch=master)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/ipublikuj-ui/form-phone.svg?style=flat-square)](https://scrutinizer-ci.com/g/ipublikuj-ui/form-phone/?branch=master)
[![Latest Stable Version](https://img.shields.io/packagist/v/ipub/form-phone.svg?style=flat-square)](https://packagist.org/packages/ipub/form-phone)
[![Composer Downloads](https://img.shields.io/packagist/dt/ipub/form-phone.svg?style=flat-square)](https://packagist.org/packages/ipub/form-phone)
[![License](https://img.shields.io/packagist/l/ipub/form-phone.svg?style=flat-square)](https://packagist.org/packages/ipub/form-phone)

Forms control for adding phone number filed for [Nette Framework](http://nette.org/)

## Installation

The best way to install ipub/form-phone is using [Composer](http://getcomposer.org/):

```sh
$ composer require urbitech/form-phone
```

After that you have to register extension in config.neon.

```neon
extensions:
	formPhone: IPub\FormPhone\DI\FormPhoneExtension
```

And you also need to include static files into your page:

```html
	<script src="{$basePath}/libs/ipub.formPhone.js"></script>
</body>
```

note: You have to upload static files from **client-site** folder to your project.

## Documentation

Learn how to extend your forms with phone field in [documentation](https://github.com/iPublikuj/form-phone/blob/master/docs/en/index.md).
For JavaScript part of this extension please checkout [JS documentation](https://github.com/iPublikuj/form-phone/blob/master/public/readme.md)

---

Homepage [http://www.ipublikuj.eu](http://www.ipublikuj.eu) and repository [http://github.com/iPublikuj/form-phone](http://github.com/iPublikuj/form-phone).
