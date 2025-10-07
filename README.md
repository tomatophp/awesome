Hello, Laravel and PHP enthusiasts!

We are excited to announce that we are enhancing our contributions to the Laravel & PHP community. Our team is developing a series of powerful packages and plugins for FilamentPHP, bringing the robust features of the TomatoPHP framework directly to your Filament applications. Stay tuned for more updates and take your Filament apps to the next level with TomatoPHP!

## Use Plugin as a Module

before use this feature please make sure that you are publish the config file of `modules.php` using this command

```bash
 php artisan vendor:publish --provider="Nwidart\Modules\LaravelModulesServiceProvider" --tag="config"
```

on the config file edit this `'enabled' => true,`

```php
<?php

return [
    /*
    |--------------------------------------------------------------------------
    | Scan Path
    |--------------------------------------------------------------------------
    |
    | Here you define which folder will be scanned. By default will scan vendor
    | directory. This is useful if you host the package in packagist website.
    |
    */
    'scan' => [
        'enabled' => true,
        'paths' => [
            base_path('vendor/*/*'),
        ],
    ],
]
```

all of this plugin can work as a module inside your app using our `filament-plugins` package and use this command

```bash
php artisan filament-plugins:publish
```

and type the name of the plugin you went to publish, if you don't know the plugin name you can use the list of all plugins using this command

```bash
php artisan module:list
```

## Plugins List

here is the plugins list you can use.

#### Filament Users

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-users/version.svg)](https://packagist.org/packages/tomatophp/filament-users)
[![License](https://poser.pugx.org/tomatophp/filament-users/license.svg)](https://packagist.org/packages/tomatophp/filament-users)
[![Downloads](https://poser.pugx.org/tomatophp/filament-users/d/total.svg)](https://packagist.org/packages/tomatophp/filament-users)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-users?style=flat)](https://packagist.org/packages/tomatophp/filament-users)

![Filament Users](https://raw.githubusercontent.com/tomatophp/filament-users/master/arts/fadymondy-tomato-users.jpg)

User Table Resource with a lot of package integrations

[Filament Users V2](https://www.github.com/tomatophp/filament-users)
[Filament Users V1](https://www.github.com/3x1io/filament-user)

### Filament Translations

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-translations/version.svg)](https://packagist.org/packages/tomatophp/filament-translations)
[![License](https://poser.pugx.org/tomatophp/filament-translations/license.svg)](https://packagist.org/packages/tomatophp/filament-translations)
[![Downloads](https://poser.pugx.org/tomatophp/filament-translations/d/total.svg)](https://packagist.org/packages/tomatophp/filament-translations)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-translations?style=flat)](https://packagist.org/packages/tomatophp/filament-translations)


![Filament Translations](https://raw.githubusercontent.com/tomatophp/filament-translations/master/arts/fadymondy-tomato-translations.jpg)

Manage your translation with DB and cache, you can scan your language tags like trans(), __(), and get the string inside and translate them using UI.

[Filament Translations V2](https://www.github.com/tomatophp/filament-translations)
[Filament Translations V1](https://www.github.com/3x1io/filament-translations)

### Filament Plugins

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-plugins/version.svg)](https://packagist.org/packages/tomatophp/filament-plugins)
[![License](https://poser.pugx.org/tomatophp/filament-plugins/license.svg)](https://packagist.org/packages/tomatophp/filament-plugins)
[![Downloads](https://poser.pugx.org/tomatophp/filament-plugins/d/total.svg)](https://packagist.org/packages/tomatophp/filament-plugins)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-plugins?style=flat)](https://packagist.org/packages/tomatophp/filament-plugins)

![Filament Plugins](https://raw.githubusercontent.com/tomatophp/filament-plugins/master/arts/3x1io-tomato-plugins.jpg)

Manage your modules as a plugin system with a plugin generator

[Filament Plugins](https://www.github.com/tomatophp/filament-plugins)

### Filament Media Manager

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-media-manager/version.svg)](https://packagist.org/packages/tomatophp/filament-media-manager)
[![License](https://poser.pugx.org/tomatophp/filament-media-manager/license.svg)](https://packagist.org/packages/tomatophp/filament-media-manager)
[![Downloads](https://poser.pugx.org/tomatophp/filament-media-manager/d/total.svg)](https://packagist.org/packages/tomatophp/filament-media-manager)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-media-manager?style=flat)](https://packagist.org/packages/tomatophp/filament-media-manager)

![Filament Media Manager](https://raw.githubusercontent.com/tomatophp/filament-media-manager/master/arts/fadymondy-tomato-media-manager.jpg)


Manage your media files using spatie media library with easy to use GUI for FilamentPHP

[Filament Media Manager](https://www.github.com/tomatophp/filament-media-manager)


### Filament Developer Gate

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-developer-gate/version.svg)](https://packagist.org/packages/tomatophp/filament-developer-gate)
[![License](https://poser.pugx.org/tomatophp/filament-developer-gate/license.svg)](https://packagist.org/packages/tomatophp/filament-developer-gate)
[![Downloads](https://poser.pugx.org/tomatophp/filament-developer-gate/d/total.svg)](https://packagist.org/packages/tomatophp/filament-developer-gate)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-developer-gate?style=flat)](https://packagist.org/packages/tomatophp/filament-developer-gate)

![Filament Developer Gate](https://raw.githubusercontent.com/tomatophp/filament-developer-gate/master/arts/fadymondy-tomato-developer-gate.jpg)

Secure your selected route by using a middleware with a static password for developers only

[Filament Developer Gate](https://www.github.com/tomatophp/filament-developer-gate)

### Filament Accounts

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-accounts/version.svg)](https://packagist.org/packages/tomatophp/filament-accounts)
[![License](https://poser.pugx.org/tomatophp/filament-accounts/license.svg)](https://packagist.org/packages/tomatophp/filament-accounts)
[![Downloads](https://poser.pugx.org/tomatophp/filament-accounts/d/total.svg)](https://packagist.org/packages/tomatophp/filament-accounts)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-accounts?style=flat)](https://packagist.org/packages/tomatophp/filament-accounts)


![Filament Accounts](https://raw.githubusercontent.com/tomatophp/filament-accounts/master/arts/3x1io-tomato-accounts.jpg)

full accounts manager with API/Notifications/Contacts to manage your contacts and accounts

[Filament Accounts](https://www.github.com/tomatophp/filament-accounts)

### Filament Wallet

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-wallet/version.svg)](https://packagist.org/packages/tomatophp/filament-wallet)
[![License](https://poser.pugx.org/tomatophp/filament-wallet/license.svg)](https://packagist.org/packages/tomatophp/filament-wallet)
[![Downloads](https://poser.pugx.org/tomatophp/filament-wallet/d/total.svg)](https://packagist.org/packages/tomatophp/filament-wallet)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-wallet?style=flat)](https://packagist.org/packages/tomatophp/filament-wallet)


![Filament Wallet](https://raw.githubusercontent.com/tomatophp/filament-wallet/master/arts/3x1io-tomato-wallet.jpg)

Account Balance / Wallets Manager For FilamentPHP and Filament Account Builder

[Filament Wallet](https://www.github.com/tomatophp/filament-wallet)

### Filament Alerts

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-alerts/version.svg)](https://packagist.org/packages/tomatophp/filament-alerts)
[![License](https://poser.pugx.org/tomatophp/filament-alerts/license.svg)](https://packagist.org/packages/tomatophp/filament-alerts)
[![Downloads](https://poser.pugx.org/tomatophp/filament-alerts/d/total.svg)](https://packagist.org/packages/tomatophp/filament-alerts)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-alerts?style=flat)](https://packagist.org/packages/tomatophp/filament-alerts)

![Image description](https://raw.githubusercontent.com/tomatophp/filament-alerts/master/arts/fadymondy-tomato-alerts.jpg)

Send notifications to users using notification templates and multi-notification channels

[Filament Alerts](https://www.github.com/tomatophp/filament-alerts)

### Filament FCM

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-fcm/version.svg)](https://packagist.org/packages/tomatophp/filament-fcm)
[![License](https://poser.pugx.org/tomatophp/filament-fcm/license.svg)](https://packagist.org/packages/tomatophp/filament-fcm)
[![Downloads](https://poser.pugx.org/tomatophp/filament-fcm/d/total.svg)](https://packagist.org/packages/tomatophp/filament-fcm)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-fcm?style=flat)](https://packagist.org/packages/tomatophp/filament-fcm)

![Filament FCM](https://raw.githubusercontent.com/tomatophp/filament-fcm/master/arts/3x1io-tomato-fcm.jpg)

Firebase Cloud Messaging integration to Native FilamentPHP Notification Package

[Filament FCM](https://www.github.com/tomatophp/filament-fcm)

### Filament Helpers

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-helpers/version.svg)](https://packagist.org/packages/tomatophp/filament-helpers)
[![License](https://poser.pugx.org/tomatophp/filament-helpers/license.svg)](https://packagist.org/packages/tomatophp/filament-helpers)
[![Downloads](https://poser.pugx.org/tomatophp/filament-helpers/d/total.svg)](https://packagist.org/packages/tomatophp/filament-helpers)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-helpers?style=flat)](https://packagist.org/packages/tomatophp/filament-helpers)

![Filament Helpers](https://raw.githubusercontent.com/tomatophp/filament-helpers/master/arts/3x1io-tomato-helpers.jpg)

Helper Class Generator to manage your forms and table inside your filament app

[Filament Helpers](https://www.github.com/tomatophp/filament-helpers)

### Filament Icons

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-icons/version.svg)](https://packagist.org/packages/tomatophp/filament-icons)
[![License](https://poser.pugx.org/tomatophp/filament-icons/license.svg)](https://packagist.org/packages/tomatophp/filament-icons)
[![Downloads](https://poser.pugx.org/tomatophp/filament-icons/d/total.svg)](https://packagist.org/packages/tomatophp/filament-icons)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-icons?style=flat)](https://packagist.org/packages/tomatophp/filament-icons)

![Filament Icons](https://raw.githubusercontent.com/tomatophp/filament-icons/master/arts/fadymondy-tomato-icons.jpg)

Picker & Table Column & Icons Provider for FilamentPHP

[Filament Icons](https://www.github.com/tomatophp/filament-icons)

### Filament CMS

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-cms/version.svg)](https://packagist.org/packages/tomatophp/filament-cms)
[![License](https://poser.pugx.org/tomatophp/filament-cms/license.svg)](https://packagist.org/packages/tomatophp/filament-cms)
[![Downloads](https://poser.pugx.org/tomatophp/filament-cms/d/total.svg)](https://packagist.org/packages/tomatophp/filament-cms)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-cms?style=flat)](https://packagist.org/packages/tomatophp/filament-cms)

![Filament CMS](https://raw.githubusercontent.com/tomatophp/filament-cms/master/arts/3x1io-tomato-cms.jpg)

Full CMS System with easy-to-use page builder & theme manager for FilamentPHP

[Filament CMS](https://www.github.com/tomatophp/filament-cms)

### Filament Types

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-types/version.svg)](https://packagist.org/packages/tomatophp/filament-types)
[![License](https://poser.pugx.org/tomatophp/filament-types/license.svg)](https://packagist.org/packages/tomatophp/filament-types)
[![Downloads](https://poser.pugx.org/tomatophp/filament-types/d/total.svg)](https://packagist.org/packages/tomatophp/filament-types)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-types?style=flat)](https://packagist.org/packages/tomatophp/filament-types)

![Filament Types](https://raw.githubusercontent.com/tomatophp/filament-types/master/arts/fadymondy-tomato-types.jpg)

Manage any type on your app in the Database with easy Resources for FilamentPHP

[Filament Types](https://www.github.com/tomatophp/filament-types)

### Filament Menus

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-menus/version.svg)](https://packagist.org/packages/tomatophp/filament-menus)
[![License](https://poser.pugx.org/tomatophp/filament-menus/license.svg)](https://packagist.org/packages/tomatophp/filament-menus)
[![Downloads](https://poser.pugx.org/tomatophp/filament-menus/d/total.svg)](https://packagist.org/packages/tomatophp/filament-menus)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-menus?style=flat)](https://packagist.org/packages/tomatophp/filament-menus)

![Filament Menus](https://raw.githubusercontent.com/tomatophp/filament-menus/master/arts/3x1io-tomato-menus.jpg)

Menu Database builder to use as a navigation on Filament Panel or as a Livewire Component

[Filament Menus](https://www.github.com/tomatophp/filament-menus)

### Filament Browser

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-browser/version.svg)](https://packagist.org/packages/tomatophp/filament-browser)
[![License](https://poser.pugx.org/tomatophp/filament-browser/license.svg)](https://packagist.org/packages/tomatophp/filament-browser)
[![Downloads](https://poser.pugx.org/tomatophp/filament-browser/d/total.svg)](https://packagist.org/packages/tomatophp/filament-browser)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-browser?style=flat)](https://packagist.org/packages/tomatophp/filament-browser)

![Filament Browser](https://raw.githubusercontent.com/tomatophp/filament-browser/master/arts/3x1io-tomato-browser.jpg)

File & Folders & Media Browser With Code Editor

[Filament Browser](https://www.github.com/tomatophp/filament-browser)

### Filament Artisan

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-artisan/version.svg)](https://packagist.org/packages/tomatophp/filament-artisan)
[![License](https://poser.pugx.org/tomatophp/filament-artisan/license.svg)](https://packagist.org/packages/tomatophp/filament-artisan)
[![Downloads](https://poser.pugx.org/tomatophp/filament-artisan/d/total.svg)](https://packagist.org/packages/tomatophp/filament-artisan)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-artisan?style=flat)](https://packagist.org/packages/tomatophp/filament-artisan)

![Filament Artisan](https://raw.githubusercontent.com/tomatophp/filament-artisan/master/arts/3x1io-tomato-artisan.jpg)

Simple yet powerful library for running some artisan commands. this package is a fork of artisan-gui with some custom for filament UI

[Filament Artisan](https://www.github.com/tomatophp/filament-artisan)

### Filament Settings Hub

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-settings-hub/version.svg)](https://packagist.org/packages/tomatophp/filament-settings-hub)
[![License](https://poser.pugx.org/tomatophp/filament-settings-hub/license.svg)](https://packagist.org/packages/tomatophp/filament-settings-hub)
[![Downloads](https://poser.pugx.org/tomatophp/filament-settings-hub/d/total.svg)](https://packagist.org/packages/tomatophp/filament-settings-hub)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-settings-hub?style=flat)](https://packagist.org/packages/tomatophp/filament-settings-hub)

![Filament Settings Hub](https://raw.githubusercontent.com/tomatophp/filament-settings-hub/master/arts/fadymondy-tomato-settings-hub.jpg)

Manage your app settings with GUI and helpers

[Filament Settings Hub](https://www.github.com/tomatophp/filament-settings-hub)

### Filament Locations

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-locations/version.svg)](https://packagist.org/packages/tomatophp/filament-locations)
[![License](https://poser.pugx.org/tomatophp/filament-locations/license.svg)](https://packagist.org/packages/tomatophp/filament-locations)
[![Downloads](https://poser.pugx.org/tomatophp/filament-locations/d/total.svg)](https://packagist.org/packages/tomatophp/filament-locations)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-locations?style=flat)](https://packagist.org/packages/tomatophp/filament-locations)

![Filament Locations](https://raw.githubusercontent.com/tomatophp/filament-locations/master/arts/3x1io-tomato-locations.jpg)

Database Seeds for Locations for FilamentPHP

[Filament Locations](https://www.github.com/tomatophp/filament-locations)

### Filament API

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-api/version.svg)](https://packagist.org/packages/tomatophp/filament-api)
[![License](https://poser.pugx.org/tomatophp/filament-api/license.svg)](https://packagist.org/packages/tomatophp/filament-api)
[![Downloads](https://poser.pugx.org/tomatophp/filament-api/d/total.svg)](https://packagist.org/packages/tomatophp/filament-api)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-api?style=flat)](https://packagist.org/packages/tomatophp/filament-api)

![Filament API](https://raw.githubusercontent.com/tomatophp/filament-api/master/arts/3x1io-tomato-api.jpg)

Generate APIs from your filament resource using a single line of code

[Filament API](https://www.github.com/tomatophp/filament-api)

### Filament E-commerce

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-ecommerce/version.svg)](https://packagist.org/packages/tomatophp/filament-ecommerce)
[![License](https://poser.pugx.org/tomatophp/filament-ecommerce/license.svg)](https://packagist.org/packages/tomatophp/filament-ecommerce)
[![Downloads](https://poser.pugx.org/tomatophp/filament-ecommerce/d/total.svg)](https://packagist.org/packages/tomatophp/filament-ecommerce)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-ecommerce?style=flat)](https://packagist.org/packages/tomatophp/filament-ecommerce)

![Filament Ecommerce](https://raw.githubusercontent.com/tomatophp/filament-ecommerce/master/arts/3x1io-tomato-ecommerce.jpg)

Build your own e-commerce store with FilamentPHP with the Power of Tomato CMS Builder

[Filament E-commerce](https://www.github.com/tomatophp/filament-ecommerce)

### Filament Twilio

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-twilio/version.svg)](https://packagist.org/packages/tomatophp/filament-twilio)
[![License](https://poser.pugx.org/tomatophp/filament-twilio/license.svg)](https://packagist.org/packages/tomatophp/filament-twilio)
[![Downloads](https://poser.pugx.org/tomatophp/filament-twilio/d/total.svg)](https://packagist.org/packages/tomatophp/filament-twilio)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-twilio?style=flat)](https://packagist.org/packages/tomatophp/filament-twilio)


![Filament Twilio](https://raw.githubusercontent.com/tomatophp/filament-twilio/master/arts/3x1io-tomato-twilio.jpg)

Send Whatsapp messages using Twilio and native filament Notification Facade class

[Filament Twilio](https://www.github.com/tomatophp/filament-twilio)


### Filament Discord

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-discord/version.svg)](https://packagist.org/packages/tomatophp/filament-discord)
[![License](https://poser.pugx.org/tomatophp/filament-discord/license.svg)](https://packagist.org/packages/tomatophp/filament-discord)
[![Downloads](https://poser.pugx.org/tomatophp/filament-discord/d/total.svg)](https://packagist.org/packages/tomatophp/filament-discord)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-discord?style=flat)](https://packagist.org/packages/tomatophp/filament-discord)

![Filament Discord](https://raw.githubusercontent.com/tomatophp/filament-discord/master/arts/3x1io-tomato-discord.jpg)

Send Notification to discord channel Webhook using native FilamentPHP Notification Facade class

[Filament Discord](https://www.github.com/tomatophp/filament-discord)

### Filament Translation Component

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-translation-component/version.svg)](https://packagist.org/packages/tomatophp/filament-translation-component)
[![License](https://poser.pugx.org/tomatophp/filament-translation-component/license.svg)](https://packagist.org/packages/tomatophp/filament-translation-component)
[![Downloads](https://poser.pugx.org/tomatophp/filament-translation-component/d/total.svg)](https://packagist.org/packages/tomatophp/filament-translation-component)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-translation-component?style=flat)](https://packagist.org/packages/tomatophp/filament-translation-component)


![Filament Translation Component](https://raw.githubusercontent.com/tomatophp/filament-translation-component/master/arts/fadymondy-tomato-translation-component.jpg)


Translation Component as a key/value to use it with Spatie Translatable FilamentPHP Plugin

[Filament Translation Component](https://www.github.com/tomatophp/filament-translation-component)


### Filament Sticky Notes

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-notes/version.svg)](https://packagist.org/packages/tomatophp/filament-notes)
[![License](https://poser.pugx.org/tomatophp/filament-notes/license.svg)](https://packagist.org/packages/tomatophp/filament-notes)
[![Downloads](https://poser.pugx.org/tomatophp/filament-notes/d/total.svg)](https://packagist.org/packages/tomatophp/filament-notes)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-notes?style=flat)](https://packagist.org/packages/tomatophp/filament-notes)

![Filament Sticky Notes](https://raw.githubusercontent.com/tomatophp/filament-notes/master/arts/3x1io-tomato-notes.jpg)

Add Sticky Notes to your FilamentPHP dashboard with tons of options and style

[Filament Sticky Notes](https://www.github.com/tomatophp/filament-notes)

# Filament Invoices Manager

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-invoices/version.svg)](https://packagist.org/packages/tomatophp/filament-invoices)
[![License](https://poser.pugx.org/tomatophp/filament-invoices/license.svg)](https://packagist.org/packages/tomatophp/filament-invoices)
[![Downloads](https://poser.pugx.org/tomatophp/filament-invoices/d/total.svg)](https://packagist.org/packages/tomatophp/filament-invoices)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-invoices?style=flat)](https://packagist.org/packages/tomatophp/filament-invoices)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-invoices/master/arts/3x1io-tomato-invoices.jpg)

Generate and manage your invoices / payments using multi currencies and multi types in FilamentPHP

[Filament Invoices Manager](https://www.github.com/tomatophp/filament-invoices)


# Filament PWA

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-pwa/version.svg)](https://packagist.org/packages/tomatophp/filament-pwa)
[![License](https://poser.pugx.org/tomatophp/filament-pwa/license.svg)](https://packagist.org/packages/tomatophp/filament-pwa)
[![Downloads](https://poser.pugx.org/tomatophp/filament-pwa/d/total.svg)](https://packagist.org/packages/tomatophp/filament-pwa)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-pwa?style=flat)](https://packagist.org/packages/tomatophp/filament-pwa)

![Screenshot](https://raw.githubusercontent.com//tomatophp/filament-pwa/master/arts/3x1io-tomato-pwa.jpg)

get a PWA feature on your FilamentPHP app with settings from panel

[Filament PWA](https://www.github.com/tomatophp/filament-pwa)


# Filament Simple Theme

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-simple-theme/version.svg)](https://packagist.org/packages/tomatophp/filament-simple-theme)
[![License](https://poser.pugx.org/tomatophp/filament-simple-theme/license.svg)](https://packagist.org/packages/tomatophp/filament-simple-theme)
[![Downloads](https://poser.pugx.org/tomatophp/filament-simple-theme/d/total.svg)](https://packagist.org/packages/tomatophp/filament-simple-theme)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-simple-theme?style=flat)](https://packagist.org/packages/tomatophp/filament-simple-theme)


![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-simple-theme/master/arts/3x1io-tomato-simple-theme.jpg)

A simple theme for FilamentPHP with custom user menu in sidebar


[Filament Simple Theme](https://www.github.com/tomatophp/filament-simple-theme)

# Filament Subscriptions

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-subscriptions/version.svg)](https://packagist.org/packages/tomatophp/filament-subscriptions)
[![License](https://poser.pugx.org/tomatophp/filament-subscriptions/license.svg)](https://packagist.org/packages/tomatophp/filament-subscriptions)
[![Downloads](https://poser.pugx.org/tomatophp/filament-subscriptions/d/total.svg)](https://packagist.org/packages/tomatophp/filament-subscriptions)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-subscriptions?style=flat)](https://packagist.org/packages/tomatophp/filament-subscriptions)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-subscriptions/master/arts/megoxv-tomato-subscriptions.jpg)

Manage subscriptions and feature access with customizable plans in FilamentPHP

thanks for [Laravel Subscriptions](https://github.com/laravelcm/laravel-subscriptions) you can review it before use this package.

[Filament Subscriptions](https://www.github.com/tomatophp/filament-subscriptions)

# Filament POS

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-pos/version.svg)](https://packagist.org/packages/tomatophp/filament-pos)
[![License](https://poser.pugx.org/tomatophp/filament-pos/license.svg)](https://packagist.org/packages/tomatophp/filament-pos)
[![Downloads](https://poser.pugx.org/tomatophp/filament-pos/d/total.svg)](https://packagist.org/packages/tomatophp/filament-pos)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-pos?style=flat)](https://packagist.org/packages/tomatophp/filament-pos)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-pos/master/arts/3x1io-tomato-pos.jpg)

POS System for FilamentPHP with a lot of features and integration with Ecommerce Builder

[Filament POS](https://www.github.com/tomatophp/filament-pos)


# Filament Tenancy

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-tenancy/version.svg)](https://packagist.org/packages/tomatophp/filament-tenancy)
[![License](https://poser.pugx.org/tomatophp/filament-tenancy/license.svg)](https://packagist.org/packages/tomatophp/filament-tenancy)
[![Downloads](https://poser.pugx.org/tomatophp/filament-tenancy/d/total.svg)](https://packagist.org/packages/tomatophp/filament-tenancy)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-tenancy?style=flat)](https://packagist.org/packages/tomatophp/filament-tenancy)


![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-tenancy/master/arts/3x1io-tomato-tenancy.jpg)

Tenancy multi-database integration for FilamentPHP

[Filament Tenancy](https://www.github.com/tomatophp/filament-tenancy)


# Filament Withdrawals

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-withdrawals/version.svg)](https://packagist.org/packages/tomatophp/filament-withdrawals)
[![License](https://poser.pugx.org/tomatophp/filament-withdrawals/license.svg)](https://packagist.org/packages/tomatophp/filament-withdrawals)
[![Downloads](https://poser.pugx.org/tomatophp/filament-withdrawals/d/total.svg)](https://packagist.org/packages/tomatophp/filament-withdrawals)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-withdrawals?style=flat)](https://packagist.org/packages/tomatophp/filament-withdrawals)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-withdrawals/master/arts/megoxv-tomato-withdrawals.jpg)

Manage your withdrawals in Filament

[Filament Withdrawals](https://www.github.com/tomatophp/filament-withdrawals)


# Filament Payment Manager

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-payments/version.svg)](https://packagist.org/packages/tomatophp/filament-payments)
[![License](https://poser.pugx.org/tomatophp/filament-payments/license.svg)](https://packagist.org/packages/tomatophp/filament-payments)
[![Downloads](https://poser.pugx.org/tomatophp/filament-payments/d/total.svg)](https://packagist.org/packages/tomatophp/filament-payments)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-payments?style=flat)](https://packagist.org/packages/tomatophp/filament-payments)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-payments/master/arts/3x1io-tomato-payments.jpg)


Manage your payments inside FilamentPHP app with multi payment gateway integration

[Filament Payment Manager](https://www.github.com/tomatophp/filament-payments)

# Filament User Logger

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-logger/version.svg)](https://packagist.org/packages/tomatophp/filament-logger)
[![License](https://poser.pugx.org/tomatophp/filament-logger/license.svg)](https://packagist.org/packages/tomatophp/filament-logger)
[![Downloads](https://poser.pugx.org/tomatophp/filament-logger/d/total.svg)](https://packagist.org/packages/tomatophp/filament-logger)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-logger?style=flat)](https://packagist.org/packages/tomatophp/filament-logger)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-logger/master/arts/3x1io-tomato-logger.jpg)


Log all user activity to file or log driver and preview it on your FilamentPHP panel

[Filament User Logger](https://www.github.com/tomatophp/filament-logger)

# Filament SEO Manager

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-seo/version.svg)](https://packagist.org/packages/tomatophp/filament-seo)
[![License](https://poser.pugx.org/tomatophp/filament-seo/license.svg)](https://packagist.org/packages/tomatophp/filament-seo)
[![Downloads](https://poser.pugx.org/tomatophp/filament-seo/d/total.svg)](https://packagist.org/packages/tomatophp/filament-seo)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-seo?style=flat)](https://packagist.org/packages/tomatophp/filament-seo)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-seo/master/arts/3x1io-tomato-seo.jpg)


Manage and generate SEO tags and integrate your website with Google SEO services

[Filament SEO Manager](https://www.github.com/tomatophp/filament-seo)

# Filament Documents Editor

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-docs/version.svg)](https://packagist.org/packages/tomatophp/filament-docs)
[![License](https://poser.pugx.org/tomatophp/filament-docs/license.svg)](https://packagist.org/packages/tomatophp/filament-docs)
[![Downloads](https://poser.pugx.org/tomatophp/filament-docs/d/total.svg)](https://packagist.org/packages/tomatophp/filament-docs)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-docs?style=flat)](https://packagist.org/packages/tomatophp/filament-docs)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-docs/master/arts/3x1io-tomato-docs.jpg)


Manage your documents and contracts all in one place with template builder

[Filament Documents Editor](https://www.github.com/tomatophp/filament-docs)

# Filament Social Media Manager

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-social/version.svg)](https://packagist.org/packages/tomatophp/filament-social)
[![License](https://poser.pugx.org/tomatophp/filament-social/license.svg)](https://packagist.org/packages/tomatophp/filament-social)
[![Downloads](https://poser.pugx.org/tomatophp/filament-social/d/total.svg)](https://packagist.org/packages/tomatophp/filament-social)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-social?style=flat)](https://packagist.org/packages/tomatophp/filament-social)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-social/master/arts/3x1io-tomato-social.jpg)


Integration of social media platform actions and auth to your FilamentPHP panel

[Filament Social Media Manager](https://www.github.com/tomatophp/filament-social)

# Filament Blog Template

[![Latest Stable Version](https://poser.pugx.org/tomatophp/filament-blog/version.svg)](https://packagist.org/packages/tomatophp/filament-blog)
[![License](https://poser.pugx.org/tomatophp/filament-blog/license.svg)](https://packagist.org/packages/tomatophp/filament-blog)
[![Downloads](https://poser.pugx.org/tomatophp/filament-blog/d/total.svg)](https://packagist.org/packages/tomatophp/filament-blog)
[![GitHub Repo stars](https://img.shields.io/github/stars/tomatophp/filament-blog?style=flat)](https://packagist.org/packages/tomatophp/filament-blog)

![Screenshot](https://raw.githubusercontent.com/tomatophp/filament-blog/master/arts/3x1io-tomato-blog.jpg)


Frontend for CMS Builder to build a blog and personal websites

[Filament Blog Template](https://www.github.com/tomatophp/filament-blog)



### Support

you can join our discord server to get support [TomatoPHP](https://discord.gg/Xqmt35Uh)

### Docs

you can check docs of all packages on [Docs](https://docs.tomatophp.com)

### Credits

- [Fady Mondy](https://wa.me/+201207860084)
- [Abdelmjid](https://wa.me/201091523908)

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

### License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
