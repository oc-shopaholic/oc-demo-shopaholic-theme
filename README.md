# Demo theme for Shopaholic plugin

# Installation guide

1. Install theme in your project (themes/shopaholic-demo folder)
2. Install plugins:
  * [Static Pages](http://octobercms.com/plugin/rainlab-pages) - required
  * [Twig Extensions](http://octobercms.com/plugin/vojtasvoboda-twigextensions) - required
  * [Toolbox](http://octobercms.com/plugin/lovata-toolbox) - required
  * [Shopaholic](http://octobercms.com/plugin/lovata-shopaholic) - required
  * [Orders for Shopaholic](http://octobercms.com/plugin/lovata-ordersshopaholic) - required
  * [Buddies](http://octobercms.com/plugin/lovata-buddies) - required
3. Install ["Fake data for Shopaholic"](https://github.com/lovata/oc-fake-data-shopaholic-plugin) plugin.
4. Fills catalog with fake data. Catalog will be cleared before filling.
```bash
php artisan shopaholic:generate.fake.data
```

> If you add new extensions of [Shopaholic](http://octobercms.com/plugin/lovata-shopaholic) plugin,
you need to run ```php artisan shopaholic:generate.fake.data``` command again.

## Get involved

If you're interested in the improvement of this project you can help in the following ways:
* bug reporting and new feature requesting by creating issues on plugin [GitHub page](https://github.com/lovata/oc-shopaholic-plugin/issues);
* contribution to a project following these [instructions](https://github.com/lovata/oc-shopaholic-plugin/blob/master/CONTRIBUTING.md);
* localization to your language using [Crowdin](https://crowdin.com/project/shopaholic-plugin-for-october) service.

## License

© 2019, [LOVATA Group, LLC](https://github.com/lovata) under [GNU GPL v3](https://opensource.org/licenses/GPL-3.0).

Developed by [Andrey Kharanenka](https://github.com/kharanenka).
