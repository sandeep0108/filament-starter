# Filament Starter

Here lives a beautiful starting point to quickly bootstrap your next [TALL stack](https://tallstack.dev/) application utilizing [Filament](https://filamentphp.com/) for the admin panel.

![Screenshot](https://i.imgur.com/AxerbeO.png)

## Features

- 🚀 Quick, clean starting point with an example **Post** model and resource.
- 🧑‍💻 Fully pre-configured and [customized](#plugins-used) Filament panel with best practices in place.
- 🎨 Clean, minimally styled frontend powered by [Livewire](https://livewire.laravel.com/).
- 💄 [TailwindCSS](https://tailwindcss.com/) and [Vite](https://vitejs.dev/) ready for immediate use.
- 👷 Pre-bundled Livewire and [Alpine](https://alpinejs.dev/) for easy extendability.
- ⚡️ SPA-ready in both Filament and the frontend.
- 🔨 GitHub Actions workflows for [Pint](https://github.com/laravel/pint) with pre-configured Dependabot for dependencies.
- 🔍️ Easy programmatic SEO using [romanzipp/laravel-seo](https://github.com/romanzipp/Laravel-SEO).

## Requirements

Make sure all dependencies have been installed before moving on:

- [PHP](https://secure.php.net/manual/en/install.php) >= 8.1
- [Composer](https://getcomposer.org/download/)
- [Node.js](http://nodejs.org/) >= 18
- [Yarn](https://yarnpkg.com/en/docs/install)

## Getting Started

Start by clonning the project and composer install and configuring the `.env` file:

```sh
git clone https://github.com/sandeep0108/filament-starter.git
cd filament-starter
composer install
cp .env.example .env
```

After `.env` is configured, you can proceed to migrate & seed the database:

```sh
php artisan migrate:fresh --seed
```

Once the database is seeded, you can login at `/admin` using the default admin user:

```yaml
Username: admin
Password: admin
```


## Plugins Used

The following [Filament plugins](https://filamentphp.com/plugins) come fully implemented and configured out of the box:

| **Plugin**                                                          | **Description**                                    | **Author**                                      |
| :------------------------------------------------------------------ | :------------------------------------------------- | :---------------------------------------------- |
| [Curator](https://github.com/awcodes/filament-curator)              | A beautiful media library.                         | [awcodes](https://github.com/awcodes)           |
| [Gravatar](https://github.com/awcodes/filament-gravatar)            | Easy avatar integration powered by Gravatar.       | [awcodes](https://github.com/awcodes)           |
| [Exceptions](https://github.com/bezhansalleh/filament-exceptions)   | A simple but powerful Exception viewer.            | [bezhansalleh](https://github.com/bezhansalleh) |
| [Jobs Monitor](https://github.com/croustibat/filament-jobs-monitor) | Easily monitor background jobs and their progress. | [croustibat](https://github.com/croustibat)     |
| [Breezy](https://github.com/jeffgreco13/filament-breezy)            | Customizable user profile pages and 2FA support.   | [jeffgreco13](https://github.com/jeffgreco13)   |
| [Peek](https://github.com/pboivin/filament-peek)                    | Quick & efficient front-end previews of resources. | [pboivin](https://github.com/pboivin)           |
| [Logger](https://github.com/z3d0x/filament-logger)                  | Zero-config resource activity logging.             | [z3d0x](https://github.com/z3d0x)               |


## Contributing
Contributing whether it be through PRs, reporting an issue, or suggesting an idea is encouraged and appreciated.

## License

Filament Starter is provided under the [MIT License](LICENSE.md).
