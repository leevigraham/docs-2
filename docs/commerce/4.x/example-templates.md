# Example Templates

Commerce includes example templates you can use for a reference or starting point building your store.

The examples include a robust set of templates that do pretty much everything with Commerce. This includes a full checkout flow, address handling, order management, subscription management, and cart management.

The [`commerce/example-templates` console command](console-commands.md#example-templates) offers a quick way to customize the templates and copy them into your project, but you can also browse the templates built with default options in `vendor/craftcms/commerce/example-templates/dist/`.

You can copy these built templates directly to your project’s top level `templates/` folder:

```bash
cp -r vendor/craftcms/commerce/example-templates/dist/* ./templates
```

If your system supports it, you could also symlink these folders into your project’s `templates/` folder so you always have up-to-date examples _while in development_:

```bash
ln -s vendor/craftcms/commerce/example-templates/dist/shop ./templates/shop
```

::: tip
You can also visit [craftcms.com/demo](https://craftcms.com/demo) to spin up the Spoke & Chain Craft Commerce demo. The source code is available at [github.com/craftcms/spoke-and-chain](https://github.com/craftcms/spoke-and-chain).
:::